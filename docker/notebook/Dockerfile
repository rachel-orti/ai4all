# start from the jupyter image with R, Python, and Scala (Apache Toree) kernels pre-installed
FROM jupyter/all-spark-notebook

# Install AI Fairness 360
RUN pip install aif360

# Install What-If Tool
RUN pip install witwidget && \
	jupyter nbextension install --py --symlink --sys-prefix witwidget && \
	jupyter nbextension enable --py --sys-prefix witwidget

# Install LIME (Local Interpretable Model-agnostic Explanations)
## 1 - Install missing packages for LIME
USER root
RUN sudo apt-get update && apt-get install -y pkg-config
## 2 - Install LIME 
USER jovyan
RUN pip install lime

# Additional installation to run the sample notebooks
## Install xgboost (required for the sample notebook for LIME)
#RUN pip install xgboost

# Optional: Install hide_code (to be able to hide cells in Jupyter notebooks)
USER root
## 1 - Install wkhtmltopdf (dependency of hide_code ; required to make PDF Export (HTML) work for Hide Code)
### 1.1 - Install missing packages for wkhtmltopdf
RUN sudo apt-get update && apt-get install -y xfonts-75dpi xfonts-base
### 1.2 - Install wkhtmltopdf
RUN	mkdir -p wkhtmltopdf_download && cd wkhtmltopdf_download && \
	wget https://downloads.wkhtmltopdf.org/0.12/0.12.5/wkhtmltox_0.12.5-1.bionic_amd64.deb && \
	dpkg -i ./wkhtmltox_0.12.5-1.bionic_amd64.deb && \
	cd .. && \
	rm -rf wkhtmltopdf_download/

USER jovyan
## 2 - Install hide_code and enable it
RUN pip install --no-cache-dir hide_code && \
	jupyter nbextension install hide_code --user --py && \
	jupyter nbextension enable hide_code --user --py && \
	jupyter serverextension enable hide_code --py
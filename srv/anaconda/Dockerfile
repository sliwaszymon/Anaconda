FROM continuumio/anaconda3

ADD ./srv/anaconda/conf/requirements.txt /

RUN apt-get upgrade
RUN pip install --upgrade setuptools 
RUN pip install -r requirements.txt
RUN mkdir -p /root/.jupyter
COPY ./srv/anaconda/conf/jupyter_notebook_config.json /root/.jupyter/jupyter_notebook_config.json

EXPOSE 8888
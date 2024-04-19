FROM tensorflow/tensorflow:latest-gpu

RUN apt update && apt upgrade -y
RUN apt install \
    sudo -y \
    supervisor -y
RUN pip install notebook \
    scikit-learn \
    pandas \
    matplotlib
RUN mkdir /opt/JupyterNotebooks
COPY supervisord.conf /etc/supervisor/conf.d/supervisord.conf
EXPOSE 8888
CMD ["/usr/bin/supervisord"]
FROM tensorflow/tensorflow:latest-gpu-py3
LABEL maintainer="Eduardo P de Sousa <edupsousa@gmail.com>"
RUN pip --no-cache-dir install \
    seaborn \
    nltk \
    gensim
CMD ["/run_jupyter.sh", "--allow-root"]
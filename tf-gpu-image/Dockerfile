FROM tensorflow/tensorflow:latest-gpu-py3
LABEL maintainer="Eduardo P de Sousa <edupsousa@gmail.com>"
RUN apt update
RUN apt install -y git
RUN pip --no-cache-dir install \
    seaborn \
    nltk \
    gensim \
    gitpython \
    javalang
CMD ["/run_jupyter.sh", "--allow-root"]
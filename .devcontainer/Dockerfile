FROM pytorch/pytorch:1.13.0-cuda11.6-cudnn8-runtime

RUN conda install -c anaconda \
    ipykernel                 \
    scikit-learn              \
    pandas                    \
    matplotlib                \
    autopep8


RUN conda install -c conda-forge \
    gxx_linux-64                 \
    tensorboard                  \
    pyright
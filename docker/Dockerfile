FROM nvcr.io/nvidia/pytorch:24.06-py3
RUN pip install --upgrade pip
RUN pip install -U xformers --index-url https://download.pytorch.org/whl/cu121
RUN pip install diffusers["torch"] transformers
RUN pip install optuna optuna-dashboard jupyterlab ipython accelerate scipy safetensors omegaconf ipywidgets matplotlib
RUN pip uninstall transformer-engine -y
RUN pip install -U torchvision
RUN pip install -U flash-attn --no-build-isolation
# RUN pip install -U compel
RUN pip install git+https://github.com/damian0815/compel.git

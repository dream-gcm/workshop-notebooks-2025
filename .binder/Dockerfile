FROM ghcr.io/dream-gcm/dreamgcm-env:latest

# Copy all notebooks from repo root into /home/jovyan/work inside the image
COPY *.ipynb /home/jovyan/work/
COPY *.md /home/jovyan/work/
COPY *.py /home/jovyan/work/

# Expose JupyterLab port
EXPOSE 8888

# Start JupyterLab pointing at the notebooks folder
CMD ["jupyter", "lab", "--ip=0.0.0.0", "--no-browser", "--allow-root", "--notebook-dir=/home/jovyan/work"]

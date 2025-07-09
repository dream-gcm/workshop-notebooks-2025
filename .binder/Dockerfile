FROM ghcr.io/dream-gcm/dreamgcm-env:latest

# Expose the JupyterLab port
EXPOSE 8888

# Set the default command to start JupyterLab
CMD ["jupyter", "lab", "--ip=0.0.0.0", "--no-browser", "--allow-root", "--notebook-dir=/home/jovyan"]


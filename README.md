# pytorch-jupyter

Docker image build on top of ghcr.io/walkerlab/pytorch-docker images

Currently Avaliable Tags:
```
pytorch-docker-cpu:pytorch-2.0.0-torchvision-0.15.1-torchaudio-2.0.1
```

Important Notes:
- By default it written to use jupyter lab
- The default password is walkerlab, and the configuration is listed in jupyter_server_config.py (If you wish to modify, mount your own jupyter_server_config.py in /root/.jupyter/)
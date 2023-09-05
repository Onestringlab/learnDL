# There are links for learn DL on Youtube

## Patrick Loeber
PyTorch Tutorials - Complete Beginner Course
- https://www.youtube.com/playlist?list=PLqnslRFeH2UrcDBWF5mfPGpqQDSta6VK4

Machine Learning from Scratch - Python Tutorials
- https://www.youtube.com/playlist?list=PLqnslRFeH2Upcrywf-u2etjdxxkL8nl7E

## JCOp Untuk Indonesia
Transisi ke Deep Learning - Belajar Machine Learning
- https://www.youtube.com/playlist?list=PLGn1wRmlR3Mtz5i4k4qyd5qQjOtm9JSC6

## Anak AI
Belajar AI lebih detail
- https://www.youtube.com/playlist?list=PLLm0Ro1RXWC7tZoYWG30wTHIrV3mnJVHH

## CTC
- https://www.youtube.com/watch?v=RLWuzLLSIgw
- https://www.youtube.com/watch?v=_i3aqgKVNQI&list=PLkDaE6sCZn6F6wUI9tvS_Gw1vaFAx6rd6

# GitHub

## SL Paper
- https://github.com/binbinjiang/SL_Papers#text-gloss-translation

## RWTH
- https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX-2014-T/

## git hub CSLR
- https://github.com/ycmin95/VAC_CSLR
- https://github.com/binbinjiang/CVT-SLR

## Carnegie Mellon University Deep Learning
- https://www.youtube.com/playlist?list=PLp-0K3kfddPyH44FP0dl0CbYprvTcfgOI
- https://github.com/cmudeeplearning11785/Fall2018-tutorials.git

## CTC Spiky Problem
- https://github.com/hzli-ucas/caffe/tree/ctc
- https://distill.pub/2017/ctc/
- https://caffe.berkeleyvision.org/installation.html
- https://github.com/parlance/ctcdecode

## Udemy
- https://www.udemy.com/course/python-data-science-machine-learning-bootcamp/learn/lecture/14844176?start=0#overview

## Deep Learning
- Jeff Heaton | https://github.com/jeffheaton/app_deep_learning/tree/main | https://www.youtube.com/playlist?list=PLjy4p-07OYzuy_lHcRW8lPTLPTTOmUpmi

# Conda
- conda remove -n ENV_NAME --all
- conda create -n "myenv" python=3.3.0
## Linux Install
- mkdir -p ~/miniconda3
- wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
- bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
- rm -rf ~/miniconda3/miniconda.sh
- docker exec -it 52b513163c352cea58e9d47586881434d08961f78edc21a95b4b10b383b73636 bash
- ~/miniconda3/bin/conda init bash
- ~/miniconda3/bin/conda init zsh
- https://linuxhint.com/install-cuda-on-ubuntu-22-04-lts/

# Pythorch
- pip3 install torch torchvision torchaudio
- pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
- pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
- pip install torch==1.11.0+cu113 torchvision==0.12.0+cu113 torchaudio==0.11.0 --extra-index-url https://download.pytorch.org/whl/cu113
- import torch
- torch.cuda.is_available()
- !pip install matplotlib
- !pip install pandas
- !pip install tqdm
- !pip install opencv-python

# CUDA Install
- https://developer.nvidia.com/cuda-11-8-0-download-archive?target_os=Linux
- wget https://developer.download.nvidia.com/compute/cuda/repos/wsl-ubuntu/x86_64/cuda-wsl-ubuntu.pin
- sudo mv cuda-wsl-ubuntu.pin /etc/apt/preferences.d/cuda-repository-pin-600
- wget https://developer.download.nvidia.com/compute/cuda/11.8.0/local_installers/cuda-repo-wsl-ubuntu-11-8-local_11.8.0-1_amd64.deb
- sudo dpkg -i cuda-repo-wsl-ubuntu-11-8-local_11.8.0-1_amd64.deb
- sudo cp /var/cuda-repo-wsl-ubuntu-11-8-local/cuda-*-keyring.gpg /usr/share/keyrings/
- sudo apt-get update
- sudo apt-get -y install cuda
- nvidia-smi

# DDPM
DDPM from scratch on a custom dataset

Implementation of the paper "Denoising Diffusion Probabilistic Models" in PyTorch

## For the training pipeline
    # Create the environment
    python3 -m venv env
    source env/bin/activate
    pip install -r requirements.txt

    # Start training
    python3 train.py

- Training details:
    - GPUs: 1x RTX 2000 Ada (16 GB VRAM), 31 GB RAM • 6 vCPU
    - Vendor: <a href="https://www.runpod.io">Runpod</a>

## Infernce results
After training of the CIFAR10 dataset, here is a visualization for 1000 denoising steps.

<img src="assets/pred.gif" width="500" height="500"/>


## Reference
Thank you for the initial implementation!

<a href="https://github.com/hkproj/pytorch-ddpm">Link</a>

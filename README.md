# unCLIP

## Task
- [x] Install unCLIP
- [] Try unCLIP
- [] Find results on cityscape dataset
- [] Try DDIB
- [] Integrate DDIB to unCLIP

## Installation

1. Install [diffusers](https://github.com/huggingface/diffusers?tab=readme-ov-file)

```bash
    pip install --upgrade diffusers[torch]
    pip install transformers
    pip install accelerate
```
2. Install PyTorch

```
    conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
```

> Optional: To use Notebooks, install `ipykernel`: 
```bash
    pip install ipykernel
```
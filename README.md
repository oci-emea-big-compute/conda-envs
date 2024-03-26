# conda-envs
A collection of ready to use conda environments

The templates are divided per OS version, so they should be applied to the same OS.

To create an environment

```conda env create -f  environment.yml```




### Pytorch ###

You can check that pytorch works with GPUs with the command

```run_cifar```

which will run a test training:

```Using pytorch version: 2.2.1+cu121
Using: NVIDIA A10
Downloading https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz to ./data/cifar-10-python.tar.gz
100%|███████████████████████████████████████████████████████████████████████████████████████| 170498071/170498071 [00:05<00:00, 33540043.06it/s]
Extracting ./data/cifar-10-python.tar.gz to ./data
/home/opc/anaconda3/envs/pytorch/lib/python3.9/site-packages/torchvision/models/_utils.py:208: UserWarning: The parameter 'pretrained' is deprecated since 0.13 and may be removed in the future, please use 'weights' instead.
  warnings.warn(
/home/opc/anaconda3/envs/pytorch/lib/python3.9/site-packages/torchvision/models/_utils.py:223: UserWarning: Arguments other than a weight enum or `None` for 'weights' are deprecated since 0.13 and may be removed in the future. The current behavior is equivalent to passing `weights=ResNet50_Weights.IMAGENET1K_V1`. You can also use `weights=ResNet50_Weights.DEFAULT` to get the most up-to-date weights.
  warnings.warn(msg)
26-03-2024-10-13
[1,    20] loss: 1.745
[1,    40] loss: 0.989
[1,    60] loss: 0.765
[1,    80] loss: 0.671
[2,    20] loss: 0.424
... ```


### vLLM

WIP

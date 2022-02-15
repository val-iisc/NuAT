# NuAT: CIFAR-10

Run the following command to train a ResNet-18 network using Nuclear Norm Adversarial Training (NuAT):

`CUDA_VISIBLE_DEVICES=0 python NuAT_cifar10.py -EXP_NAME 'CIFAR10_ResNet18_NuAT' `


Run the following command to train a ResNet-18 network using Nuclear Norm Adversarial Training with Weight Averaging (NuAT-WA):

`CUDA_VISIBLE_DEVICES=0 python NuAT_WA_cifar10.py -EXP_NAME 'CIFAR10_ResNet18_NuAT-WA' `


Run the following command to train a WideResNet-34-10 network using 2-step Nuclear Norm Adversarial Training (NuAT2):

`CUDA_VISIBLE_DEVICES=0 python NuAT2_WRN_cifar10.py -EXP_NAME 'CIFAR10_WideResNet34_NuAT' `


Run the following command to train a WideResNet-34-10 network using 2-step Nuclear Norm Adversarial Training with supervision incorporated from the exponentially weight-averaged models  (NuAT2-WA):

`CUDA_VISIBLE_DEVICES=0 python NuAT2-WA_WRN_cifar10.py -EXP_NAME 'CIFAR10_WideResNet34_NuAT2-WA' `

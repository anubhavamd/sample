```mermaid
flowchart LR
    Pytorch-->Install-Pytorch
    Pytorch-->Test-Pytorch
    Pytorch-->Run-Pytorch
    Install-Pytorch-->Use-Docker 
    Install-Pytorch-->Use-wheels-package
    Install-Pytorch-->Use-Pytorch-Rocm-base-Docker-Image
    Install-Pytorch-->Use-Pytorch-upstream-Docker-file
```

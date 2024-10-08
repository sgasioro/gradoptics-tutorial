# GradOptics tutorial
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sgasioro/gradoptics-tutorial/blob/main/GradOptics%20Tutorial.ipynb)

## Environment setup
Colab should (hopefully) work. For local install, almost everything is version agnostic (latest should be ok, PyTorch just needs to be >=1.11). 

GradOptics rendering will run much faster on a GPU (CUDA), but will run on CPU if needed. PyTorch installs can be a bit tricky, feel free to use the latest PyTorch 
and follow: [https://pytorch.org/get-started/locally/](https://pytorch.org/get-started/locally/)

Requires:
```
torch
numpy
gradoptics
numpy
matplotlib
tqdm
notebook
```

## Extra links
[Intro slides](https://docs.google.com/presentation/d/1syT_ISaqWS3ucwZNixK7Gy12SunZBHi_UC_LE8hNL3s/edit?usp=sharing)

**Neural fields tutorial:** contains some useful snippets for mulitple camera imaging, demos 3D reconstruction:
[https://github.com/sgasioro/neural-fields-tutorial](https://github.com/sgasioro/neural-fields-tutorial)

**Tutorial on differentiable programming:** Given at LBNL. Targeted at HEP, but gives an overview/runs some simple demos of fitting parameters with PyTorch:

Indico with recordings: [https://indico.physics.lbl.gov/event/2850/timetable/?view=standard#13-differentiable-programming](https://indico.physics.lbl.gov/event/2850/timetable/?view=standard#13-differentiable-programming)

GitHub with Demo: [https://github.com/ml4fp/2024-lbnl/tree/main/diffprog](https://github.com/ml4fp/2024-lbnl/tree/main/diffprog)

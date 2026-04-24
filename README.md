# Reactive Pluto Notebook from article "A Kernelizable Primal-Dual Formulation of the Multilinear Singular Value Decomposition" 

This reactive [Pluto.jl](https://github.com/fonsp/Pluto.jl) notebooks is the numerical experiments of the article "[A Kernelizable Primal-Dual Formulation of the Multilinear Singular Value Decomposition](https://arxiv.org/abs/2410.10504)" by Frederiek Wesel, Kim Batselier.

There are basically two ways to run this notebook:

## 1. Run .jl files on your own computer

The recommended way to run this notebooks is on your own computer. This, however, requires that you install Julia first. Here are instructions on how to get this notebook running on your machine. Note that steps 1 up to 2 only need to be done once :). 

1. Download and install [Julia](https://julialang.org/).

2. In Julia press the "]" key to open the package manager and then run the command "add Pluto".

3. Once Pluto is installed press backspace to return to the prompt and run the command 
    
    Using Pluto

    Pluto.run()


4. Pluto will start in your browser, open the notebook you want to run and then click on "Run notebook code" in the upper right corner.

## 2. Run .jl files in the cloud via Binder

If installing Julia is not possible then this notebook can be run in 
the cloud via [Binder](https://mybinder.org/) instead. Please note that 
this option might be quite slow so please be patient. Simply click on 
the hyperlinks below to run the notebooks. Once the notebook has 
opened, click on "Run notebook code" in the upper right corner and then 
on the Binder button.

[Kernel TensorFaces](https://kbatseli.github.io/KMLSVD/KernelTensorFaces.html)

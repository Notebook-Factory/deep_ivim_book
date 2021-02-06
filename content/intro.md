
<img src="images/vol83_1.jpg" style="width:190px;height:auto;"  align="right">

Welcome to an interactive Jupyter Book for the Magnetic Resonance in Medicine paper by Sebastiano Barbieri et al. entitled 
"[*Deep learning how to fit an intravoxel incoherent motion model to diffusion weighted MRI*](https://onlinelibrary.wiley.com/doi/abs/10.1002/mrm.27910)".
It reports a prospective clinical study assesses the feasibility of training a deep neural network (DNN) for intravoxel incoherent motion (IVIM) model 
fitting to diffusion‐weighted MRI (DW‐MRI) data and evaluates its performance.

This Jupyter Book lets you interact with a [demo of their code](https://github.com/sebbarb/deep_ivim) to test their phase unwrapping method. You can change the code by inline on the pages or launch a MyBinder session to run your code in a Jupyter Notebook in another tab. The figures are made interactive using [Plotly](https://plotly.com). 

All of the analyssis code is contained inside one Jupyter notebook that recomputes eatch of the 3 considered algorithms and the average of each algorithm is recorded. 
The algorithms in the example are implemented using Python 3.6 and the library Pytorch 0.4.1 (without CUDA drivers). 
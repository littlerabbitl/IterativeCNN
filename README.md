# Iterative PET Image Reconstruction Using CNN Representation
### Prerequisites
Matlab, Python 2.7, Tensorflow 1.4
### Instructions
## Step 1. Download the data folder 'data' from https://www.dropbox.com/sh/2s93bp45wwwbxqq/AAC4ei5646jWZaCFUFGdD0xva?dl=0
## Step 2. Dowload the system matrix folder 'sys_ge690_smat' from https://www.dropbox.com/sh/x4wfuz1fq3okxg9/AADE7UXYi4X-uXPwh9IPWsmva?dl=0
## Step 3. Run demo_iterativeCNN.m to get the iterative reconstruction results. 
## Note: The CNN model is trained and the trained model is stored in pretraining_process. If you want to re-train the model based on your own data sets, you can use initialize_residual_cnnoutput.py, by changing it from interface to training mode. 

## Reference:
Gong, K., Guan, J., Kim, K., Zhang, X., Fakhri, G.E., Qi, J. and Li, Q., 2017. Iterative PET image reconstruction using convolutional neural network representation. arXiv preprint arXiv:1710.03344.
## License
This project is licensed under the 3-Clause BSD License - see the [LICENSE](LICENSE) file for details.

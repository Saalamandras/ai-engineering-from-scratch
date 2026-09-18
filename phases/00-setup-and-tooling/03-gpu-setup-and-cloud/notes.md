#Concepts 

- GPU (Graphics Processing Unit)
- CPU (Central Porcess Unit)
- CUDA CUDA is a platform for parallel computing. It allows developers to use NVIDIA GPUs for general-purpose processing (GPGPU) to accelerate computationally intensive tasks like:

AI and deep learning
Scientific simulations
Data analytics
Graphics rendering
Machine learning

 I config the Coolab, see the Python code inside. 


# Questions

Why is a GPU faster than a CPU for training neural networks?

B. GPUs can perform thousands of parallel matrix operations simultaneously

What does VRAM refer to?

C. Video RAM on the GPU, separate from system RAM

Post-lesson checks:

What command verifies that your NVIDIA GPU is detected and shows its current status?
B. nvidia-smi but it must inclhde the ! mark to run as a system command 

When benchmarking GPU vs CPU matmul, why must you call torch.cuda.synchronize() before measuring GPU time?
B. To ensure all GPU operations have completed before stopping the timer



Using the fp16 rule of thumb, approximately how many parameters fit in 24 GB of VRAM?
A. 6B · B. 24B · C. 12B · D. 48B
 


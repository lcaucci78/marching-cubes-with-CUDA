# marching-cubes-with-CUDA
Simple CUDA implementation of the marching cubes algorithm.  The code is adapted from [https://graphics.stanford.edu/~mdfisher/Code/MarchingCubes/MarchingCubes.cpp](https://graphics.stanford.edu/~mdfisher/Code/MarchingCubes/MarchingCubes.cpp).

I do not claim this is the most efficient and numerically accurate implementation out there, but it does the job for me.  Let me know how to make my code better :grinning:

To compile with NVCC, just run:

```
nvcc gpu_marching_cubes.cu
```

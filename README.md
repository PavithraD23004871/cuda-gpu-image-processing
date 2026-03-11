CUDA Image Processing Project

``` Project Overview```

This project implements GPU-accelerated image processing using CUDA. The application
processes large grayscale images using CUDA kernels and CUDA streams. The goal is to
demonstrate parallel image processing and performance comparison between CPU and GPU.

```Implementation Details```

• Implemented CUDA kernel for image processing.

• Used CUDA streams for asynchronous execution.

• Measured CPU time, GPU time, and stream execution time.

• Processed 200 images on GPU

```Performance Results```

CPU Time: 0.0274350643157959
GPU Time: 0.0040264129638671875
Speedup GPU vs CPU: 6.813773093320701
Processed 500 images on GPU
Total GPU Time: 0.21869349479675293 seconds

```Screenshots```

GPU vs CPU Time

<img width="385" height="92" alt="image" src="https://github.com/user-attachments/assets/34709f32-487b-4a8d-87d9-3f53b54677da" />

GPU Time

<img width="435" height="57" alt="image" src="https://github.com/user-attachments/assets/173bd85e-6c6b-4d83-b051-0471214909de" />
 
processed_images.png

<img width="737" height="571" alt="image" src="https://github.com/user-attachments/assets/e7ee8e95-76f8-44de-9aaf-7e5169d13d3e" />

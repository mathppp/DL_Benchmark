# DL_Benchmark
This project is for NCHC AI Taskforce to tuning the performance of Deep Learning facility.

+++++  Tensorflow whell  +++++
the version of install tensorflow package created by Fang-An Kuo from NCHC.
    
the first upload is the tensorflow wheel for installing tensorflow 1.4.1 with python 2.7 and cudnn 7.1.1.5.
the version is only for NCHC AI server and includes some optimizations in the following list:
1. GPU supports, only for V100 with CUDA 9.1 (sm_70).
2. The new feature of intel CPU supports, e.g. AVX512F et.al.
3. python version: 2.7
4. MKL 16.0 with AVX512 optimization.
5. GPU-Direct RDMA (GDR) and InfiniBand with MPI2 support.


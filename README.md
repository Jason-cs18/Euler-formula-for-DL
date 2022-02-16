# A Euler's Formula for Deep Learning Code
As Euler's Formula in mathematics, I hope to build a simple but effective optimization framework for existing deep learning (DL) code, which contains general and specific optimization techniques for different DL accelerators (GPU/NPU). The goal of this project is threefold: (1) introduce/understand how DL accelerators run/execute DL code; (2) understand how existing AI compilers optimize DL code and why popular DL frameworks are inefficient (specifically, understand why they write CUDA kernel for a single operation in this way and why they need to fuse kernel operations); (3) compare different optimization techniques on GPU/NPU and understand the differences between general and specific optimization techniques. In the end, I am diving into popular open-source DL optimization frameworks (TensorRT, DeepSpeed and FasterTransformer).

- Outline
  - [DL review](xxx) 
    - [Dive into deep learning, Mu Li (Amazon AI)](https://d2l.ai/chapter_introduction/index.html)
  - [C++ review](xxx)
    - [菜鸟教程](https://www.runoob.com/cplusplus/cpp-tutorial.html)
    - [C++ Primer](https://zhuanlan.zhihu.com/p/234146477)
    - [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
    - Advanced references:
      - [Effective C++](https://blog.csdn.net/fengbingchun/article/details/102761542)
      - [Effective Modern C++](https://blog.csdn.net/fengbingchun/article/details/102990753)
      - [STL源码分析](http://221.235.153.107:90/resource/book/C++%E8%BF%9B%E9%98%B6/C++%20STL%E6%BA%90%E7%A0%81%E5%89%96%E6%9E%90.pdf)
  - [CUDA review](xxx)
    - [Computer architecture review](xxx)
      - Computer Architecture - A Quantitative Approach (6th edition, 2019)
      - [Great Ideas in Computer Architecture](https://cs61c.org/fa21/)
      - [Coursea: Nand2Tetris](https://www.coursera.org/learn/build-a-computer/home/week/1)
      - [CMU CS15213 Computer Systems: A Programmers' Perspective, 3/E](http://csapp.cs.cmu.edu/)
    - [Parallel computing review](xxx)
      - [CMU CS15-418: Parallel Computing Architecture and Programming](http://www.cs.cmu.edu/~418/schedule.html)
      - [Stanford CS149: Parallel Computing](http://35.227.169.186/cs149/fall21/lecture/)
    - [Blog and documentation](xxx)
      - [NVIDIA official documentation](https://docs.nvidia.com/cuda/cuda-c-programming-guide/index.html)
      - [xxx]
  - [AI frameworks and compilers](xxx)
      - [Pytorch, FAIR](https://pytorch.org/tutorials/)
      - [TVM, Apache](https://tvm.apache.org/docs/)
      - [NPU, todo](xxx)
  - [Open source DL optimization frameworks](xxx)
    - [TensorRT, Nvidia](https://github.com/NVIDIA/TensorRT)
    - [DeepSpeed, Microsoft](https://github.com/microsoft/DeepSpeed)
    - [FasterTransformer, Nvidia](https://github.com/NVIDIA/FasterTransformer)  

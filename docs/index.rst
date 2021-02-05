C/C++ Tutorial for Astronomers
==========================================================

Goal 
----------

Although there are many existing materials for C/C++, I still decide to write this tutorial. 
The reason is 

- C++ itself is difficult. C++ has lots of features for general purpose OOP programming and 
  generic programming. However, most of them are not frequently used in real development, 
  especially when writing a scientific library or application.

- The compiling system is complex. C++ is widely used in system-level programming. 
  Hardware systems, operating systems and compilers have much difference, which are hard 
  to master.
  However, in scientific computation, the usage of C++ is somehow limited. Therefore, 
  a short and specific tutorial may be helpful to the astronomy community.

- Tricks in C++ programming help a lot in scientific computation. With modern C++ 
  features, it is easy to write efficient code in a very simple way, which ease your 
  life of scientific computation using C++.
  
In this tutorial, we will cover

- How to write a **minimal C++ pplication**. We will decribe the full pipeline of writing the code, 
  compiling it, and running the executable.

- How to use an **external library**.

- The C++ programming. 
  
   - Basic C++ programming.

   - More tricks in C++ programming which help simplify the codes.

   - Hints on how to improve the performance.

- How to write the compiling system using **Makefile** and **CMake**.

- How to organize your codes and how to build a library.

- How to cooperate with Python, i.e., call C++ subroutines in Python or call Python subroutines in C++.

Contributors
--------------

- Yangyao Chen (Tsinghua, DOA, `yangyaochen.astro@foxmail.com <mailto:yangyaochen.astro@foxmail.com>`_)


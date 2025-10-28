---
layout: post
title: "Python vs C++ OR Python and C++"
---

Python and C++ are one of the most popular programming languages. There has been debate on which is the best for a decade. But ever wondered what the combination can do. Being both a Python programmer and C++ programmer was something that propelled my career(along with computer vision and deep learning). Starting out being a jack of multiple languages, C#, Java, Golang, JS, Python, C++ etc was exciting; now learning new languages is still part of the process but the focus has shifted to Python and C++. 

Python and C++ is a great combo. Use Python for prototyping and public interfacing, C++ for all the optimized and core algorithms. Python is simple and the data manipulation techniques it provides is way above most languages. It is great for prototyping and production system due to its vast amount of optimized libraries(most are in C++) enabling anyone starting with Python to create a system with minimal effort. C++ is great because of it's speed and support of creating new algos with no toll on the performance(although performance depends on the programmer). One of my major project on compiler development is a combo of this, Python for interface and high-level preprocessing and post processing, C++ for the deep learning algorithms. For a motivation here is the list of 3 famous deep learning projects using this combo.

1. TensorFlow
    * Python interface: tensorflow high-level API (Keras integrated)
    * C++ core: TensorFlow runtime, XLA compiler, and ops kernel implementations
    * Core language mix: Python (frontend) + C++ (core runtime) + CUDA (GPU ops)

2. Pytorch
    * Python interface: torch, torch.nn, torch.autograd
    * C++ core: ATen (tensor library), Caffe2, and TorchScript runtime
    * Core language mix: Python (frontend) + C++/CUDA (backend)

3. ONNX runtime
    * Python interface: onnxruntime
    * C++ core: Optimized graph execution engine
    * Core language mix: Python (API) + C++ (runtime)
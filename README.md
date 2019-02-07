# MCU-Neural-Networks
----------------------
Tinn (Tiny Neural Network) is a 200 line dependency free neural network library written in C99.

这个神经网络使用全c编写 无依赖化

##特性

* Portable - Runs where a C99 or C++98 compiler is present.
* Sigmoidal activation.
* One hidden layer.

    0: 1 0 0 0 0 0 0 0 0 0
    1: 0 1 0 0 0 0 0 0 0 0
    2: 0 0 1 0 0 0 0 0 0 0
    3: 0 0 0 1 0 0 0 0 0 0
    4: 0 0 0 0 1 0 0 0 0 0
    ...
    9: 0 0 0 0 0 0 0 0 0 1
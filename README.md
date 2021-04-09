# 现代CMake的介绍

人们喜欢讨厌构建系统。只需观看CppCon17的演讲，就可以看到开发人员使构建系统状态首当其冲的示例。这就提出了一个问题：为什么？当然，构建时不乏问题。但我认为，到2020年，我们将为其中许多问题提供一个很好的解决方案。是CMake。虽然不是CMake 2.8；在C ++ 11甚至不存在之前就发布了！也没有关于CMake的可怕示例（甚至是那些发布在KitWare自己的教程列表中的示例）。我说的是Modern CMake。 CMake 3.4+，甚至CMake 3.20+！它干净，强大且优雅，因此您可以将大部分时间花在编码上，而不必在无法读取，无法维护的Make（或CMake 2）文件中添加行。而且CMake 3.11+应该也要快得多！！

> 这本书是活的文件。您可以在[GitLab](https://gitlab.com/CLIUtils/modern-cmake)上提出问题或提出合并请求。您也可以将副本[下载为PDF](https://cliutils.gitlab.io/modern-cmake/modern-cmake.pdf)。同样，请务必检查[HSF CMake培训](https://hsf-training.github.io/hsf-training-cmake-webpage/)！

## 为什么我需要一个好的构建系统？

以下任何一项对您适用吗？




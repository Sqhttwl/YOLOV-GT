# PaddlePaddle


[![Build Status](https://travis-ci.org/PaddlePaddle/Paddle.svg?branch=develop)](https://travis-ci.org/PaddlePaddle/Paddle)
[![Documentation Status](https://img.shields.io/badge/docs-latest-brightgreen.svg?style=flat)](http://www.paddlepaddle.org/docs/develop/documentation/en/getstarted/index_en.html)
[![Documentation Status](https://img.shields.io/badge/中文文档-最新-brightgreen.svg)](http://www.paddlepaddle.org/docs/develop/documentation/zh/getstarted/index_cn.html)
[![Release](https://img.shields.io/github/release/PaddlePaddle/Paddle.svg)](https://github.com/PaddlePaddle/Paddle/releases)
[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](LICENSE)


Welcome to the PaddlePaddle GitHub.

PaddlePaddle (PArallel Distributed Deep LEarning) is an easy-to-use,
efficient, flexible and scalable deep learning platform, which is originally
developed by Baidu scientists and engineers for the purpose of applying deep
learning to many products at Baidu.

Our vision is to enable deep learning for everyone via PaddlePaddle.
Please refer to our [release announcement](https://github.com/PaddlePaddle/Paddle/releases) to track the latest feature of PaddlePaddle.

## Features

- **Flexibility**

    PaddlePaddle supports a wide range of neural network architectures and
    optimization algorithms. It is easy to configure complex models such as
    neural machine translation model with attention mechanism or complex memory
    connection.

-  **Efficiency**

    In order to unleash the power of heterogeneous computing resource,
    optimization occurs at different levels of PaddlePaddle, including
    computing, memory, architecture and communication. The following are some
    examples:

      - Optimized math operations through SSE/AVX intrinsics, BLAS libraries
      (e.g. MKL, OpenBLAS, cuBLAS) or customized CPU/GPU kernels.
      - Optimized CNN networks through MKL-DNN library.
      - Highly optimized recurrent networks which can handle **variable-length**
      sequence without padding.
      - Optimized local and distributed training for models with high dimensional
      sparse data.

- **Scalability**

    With PaddlePaddle, it is easy to use many CPUs/GPUs and machines to speed
    up your training. PaddlePaddle can achieve high throughput and performance
    via optimized communication.

- **Connected to Products**

    In addition, PaddlePaddle is also designed to be easily deployable. At Baidu,
    PaddlePaddle has been deployed into products and services with a vast number
    of users, including ad click-through rate (CTR) prediction, large-scale image
    classification, optical character recognition(OCR), search ranking, computer
    virus detection, recommendation, etc. It is widely utilized in products at
    Baidu and it has achieved a significant impact. We hope you can also explore
    the capability of PaddlePaddle to make an impact on your product.

## Installation

It is recommended to check out the
[Installation guide](http://paddlepaddle.org/documentation/docs/zh/0.14.0/new_docs/beginners_guide/install/install_doc.html#permalink-1--paddlepaddle)
before looking into the
[build from source guide](http://paddlepaddle.org/documentation/docs/zh/0.14.0/new_docs/beginners_guide/install/install_doc.html#permalink-6--paddlepaddle).

## Documentation

We provide [English](http://www.paddlepaddle.org/docs/develop/documentation/en/getstarted/index_en.html) and
[Chinese](http://www.paddlepaddle.org/docs/develop/documentation/zh/getstarted/index_cn.html) documentation.

- [Deep Learning 101](http://www.paddlepaddle.org/docs/develop/book/01.fit_a_line/index.html)

  You might want to start from this online interactive book that can run in a Jupyter Notebook.

- [Distributed Training](http://www.paddlepaddle.org/docs/develop/documentation/en/howto/cluster/index_en.html)

  You can run distributed training jobs on MPI clusters.

- [Distributed Training on Kubernetes](http://www.paddlepaddle.org/docs/develop/documentation/en/howto/cluster/multi_cluster/k8s_en.html)

   You can also run distributed training jobs on Kubernetes clusters.

- [Python API](http://www.paddlepaddle.org/docs/develop/api/en/overview.html)

   Our new API enables much shorter programs.

- [How to Contribute](http://www.paddlepaddle.org/docs/develop/documentation/fluid/en/dev/contribute_to_paddle_en.html)

   We appreciate your contributions!


## Ask Questions

You are welcome to submit questions and bug reports as [Github Issues](https://github.com/PaddlePaddle/Paddle/issues).

## Copyright and License
PaddlePaddle is provided under the [Apache-2.0 license](LICENSE).

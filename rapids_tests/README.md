# Rapids tests

The [RAPIDS](https://www.rapids.ai) suite of open source software libraries and APIs gives you the ability to execute end-to-end data science and analytics pipelines entirely on GPUs. 

Licensed under Apache 2.0, RAPIDS is incubated by NVIDIA® based on extensive hardware and data science science experience. RAPIDS utilizes NVIDIA CUDA® primitives for low-level compute optimization, and exposes GPU parallelism and high-bandwidth memory speed through user-friendly Python interfaces.


```
docker pull rapidsai/rapidsai:cuda10.1-runtime-ubuntu16.04-py3.7
```

```
docker run -v /home/username/rapids_tests:/rapids/notebooks/host --gpus all --rm -it -p 8888:8888 -p 8787:8787 -p 8786:8786     rapidsai/rapidsai:cuda10.1-runtime-ubuntu16.04-py3.7
```


FROM opencl:runtime
MAINTAINER NVIDIA CORPORATION <digits@nvidia.com>

RUN apt-get update && apt-get install -y --no-install-recommends \
        clinfo \
        ocl-icd-opencl-dev && \
    rm -rf /var/lib/apt/lists/*

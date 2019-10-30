Bootstrap: docker
From: ubuntu:19.10

%post
    echo "Installing required packages..."

    apt-get update && apt-get install -y \
    libhdf5-openmpi-dev \
    python3-mpi4py \
    python3-h5py

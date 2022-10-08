# docker-cuda-sshd-supervisord

nvidia/cuda:11.3.1-cudnn8-devel-ubuntu20.04

nvidia/cuda:11.3.1-cudnn8-devel-ubuntu18.04

nvidia/cuda:11.3.1-cudnn8-devel-ubuntu16.04

nvidia/cuda:11.3.1-cudnn8-devel-ubi8

nvidia/cuda:11.3.1-cudnn8-devel-ubi7

nvidia/cuda:11.3.1-cudnn8-devel-centos8

nvidia/cuda:11.3.1-cudnn8-devel-centos7

pytorch/pytorch:1.10.0-cuda11.3-cudnn8-devel

docker run -it --rm --name abc --gpus "device=0,1,3-6" --cpuset-cpus="0,3-24" --cpus=8 --cpu-shares=1024 --memory=16g --storage-opt size=500G nvidia/cuda:11.3.1-cudnn8-devel-ubuntu20.04 /bin/bash

--storage-opt must xfs


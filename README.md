# PhysicsNeMo Training

This Bootcamp will provide researchers hands-on approaches on how to use NVIDIA PhysicsNeMo, a framework that combines physics and partial differential equations (PDEs) with artificial intelligence (AI) to build robust models. Participants will also learn about the differences between Physics-driven and Data-driven approaches to AI. This bootcamp consist of one training lab and one mini challenge.:

<p align="center">
  <img width="600" height="400" src="https://github.com/openhackathons-org/End-to-End-AI-for-Science/blob/d403086ce59c49b26be430bbea0056c37bd4d5f6/workspace/python/jupyter_notebook/omniverse/images/tcwv.gif">
</p>


## Bootcamp contents:

The content is structured in multiple modules covering the following: 

- Module 1: Training Labs
  - Lab 1: Solving ODEs with PhysicsNeMo
- Module 2: Mini Challenges
  - Challenge 1: 1D Wave Equation 
## Tools and frameworks:

The tools and frameworks used in the bootcamp are as follows:
- [NVIDIA® PhysicsNeMo](https://developer.nvidia.com/PhysicsNeMo)

## Bootcamp duration:

The overall bootcamp will take approximately 1 hours. 

## Bootcamp prerequisites:

Mathematical background in Differential equations, Python proficiency, and familiarity with deep learning fundamentals and frameworks are required.

#### Docker Container

The recommended PhysicsNeMo Docker image can be pulled from the NVIDIA Container Registry
`sudo pull nvcr.io/nvidia/physicsnemo/physicsnemo:25.06`

and to run the container, run:
`sudo docker run --gpus all --ipc=host --ulimit memlock=-1 --ulimit stack=67108864  -p 8888:8888 -it --rm nvcr.io/nvidia/physicsnemo/physicsnemo:25.06 bash`

The container launches jupyter lab and runs on port 8888
`jupyter-lab --ip 0.0.0.0 --port 8888 --no-browser --allow-root`

Then, open the jupyter lab in browser: http://localhost:8888

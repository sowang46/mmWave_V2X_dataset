# M3 mmWave V2X dataset

This is the 3D ray-tracing dataset repository for [*M3 mmWave V2X*](http://m3.ucsd.edu/mmwave-v2x-testbed/) project

## Data Organization

The data are organized as follow:

+-- data
|	+-- scenario_*
|	|	+-- sim_*
|	|	|    +-- x3d
|	|   |    |   +-- '*'.x3d.sqlite
|	|	+ sim_*
|	|	+ ...
|	+ scenario_*
|	+ ...

Each "scenario" directory folder corresponds to a specific experiment setup. Each "sim" directory corresponds to a specific timestamp under this setup. The 3D ray-tracing output is stored in the *sqlite* files. Here is a list of detail experiment setups for each "scenario" directory:

 - scenario_1: 

## Data format



## Citing the dataset
``
@inproceedings{10.1145/3372224.3419208,
    author = {Wang, Song and Huang, Jingqi and Zhang, Xinyu},
    title = {{Demystifying Millimeter-Wave V2X: Towards Robust and Efficient Directional  Connectivity Under High Mobility}},
    year = {2020},
    doi = {10.1145/3372224.3419208},
    booktitle = {Proceedings of the 26th ACM Annual International Conference on Mobile Computing and Networking (MobiCom)},
}
``

## Contact
 - [Song Wang](https://s0ngwang.github.io), PhD student @ UC San Diego, email: sowang@ucsd.edu
 - [Jingqi Huang](https://jingqihuang.github.io), MS student @ UCSD (Now PhD student @ Purdue University), email:huan1504@purdue.edu
 - [Xinyu Zhang](http://xyzhang.ucsd.edu), Associate Professor @ UC San Diego, email: xyzhang@ucsd.edu
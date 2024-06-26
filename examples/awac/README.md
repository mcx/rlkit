# AWAC

This directory contains examples to run the implementation of advantage
weighted actor critic (AWAC, pronounced "awake"). The paper with more details
is available [here](https://arxiv.org/abs/2006.09359).

## Usage Instructions

Running the dexterous manipulation experiments requires setting up the
environments in this repository:
[https://github.com/aravindr93/hand_dapg](https://github.com/aravindr93/hand_dapg).
You can also use the follwing docker image, which has the required dependencies
set up: anair17/railrl-hand-v3

For the mj_envs repository, please use:
https://github.com/anair13/mj_envs

## Data

Data can be downloaded from the following links:

MuJoCo benchmark tasks - https://drive.google.com/file/d/1IMUqUShv7tVqBvowvPkORe50KJ9gqPgR/view?usp=sharing

Dexterous manipulation - https://drive.google.com/file/d/1yUdJnGgYit94X_AvV6JJP5Y3Lx2JF30Y/view?usp=sharing

You will then have to update the paths in rlkit/launchers/experiments/awac/awac_rl.py

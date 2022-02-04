# Introduction to Reinforcement Learning

Presented by: Damian Dailisan

Reinforcement learning notebooks for AIM's MSDS ML3 Course Special Topics 1: Introduction to Reinforcement Learning. This repository contains two notebooks:

 - [01_Q-Learning.ipynb](./01_Q-Learning.ipynb)
 - [02_Deep_Q-Learning.ipynb](./02_Deep_Q-Learning.ipynb)
 
 In Part I of this lecture, we discuss Q-Learning using the [`Taxi-v3`](https://gym.openai.com/envs/Taxi-v3/) problem. Afterwards in Part II, we use a fully-connected neural network as our Deep-Q-Network using the [`LunarLander-v2`](https://gym.openai.com/envs/LunarLander-v2/) environment.

## Environment setup

To ensure that we can run the notebooks without any dependency error, create an environment using the following command:

```
conda env create -f environment.yml
```

This creates an environment named `msds-ml3-rl` and installs the required packages with specific versions specified in the `environment.yml` file. Afterwards, use the created conda environment kernel if you're using super jojie to run the codes or activate the environment if you're using your local machine.

### On super jojie

Use the environment as kernel when running the notebooks. Select `Kernel` > `Change Kernel` > `Python [conda env:.conda-msds-ml3-rl]`.

### On local

Activate the environment using the command:

```
conda activate msds-ml3-rl
```

Launch the jupyter notebook in your machine:

```
jupyter notebook
```

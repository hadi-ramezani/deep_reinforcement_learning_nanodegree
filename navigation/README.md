[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction

In this project, we train an agent to navigate a large, square world and collect bananas. 

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  
As such, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's 
forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:

- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.
For more details about the algorithms and the implementation, please see the files "Navigation.ipynb" and "Report.ipynb".   

### Getting Started

In this project, we use [Unity](https://unity.com/products/machine-learning-agents) environment to design, train, and 
evaluate our deep reinforcement learning algorithms. For more information, please see the Github repo 
[here](https://github.com/Unity-Technologies/ml-agents). To run the notebooks and reproduce the results, you do not need to 
build an environment. If you are using a Linux machine, the environment is already included in the folder "Banana_Linux". 
For other operating systems, follow the instructions below:

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the DRLND GitHub repository, in the `p1_navigation/` folder, and unzip (or decompress) the file. 
  
Please note that the content of this README file mainly comes from [here](https://github.com/udacity/deep-reinforcement-learning/blob/master/p1_navigation/README.md) 
with some minor modifications.

### Instructions
1. To set up your python environment, it's best to follow the instructions [here](https://github.com/udacity/deep-reinforcement-learning#dependencies)
2. Clone this repository.
3. Follow the instructions in `Navigation.ipynb` to get started with training the agent and reproducing the results!  
4. Read the Report.ipynb files for more details about the algorithms.

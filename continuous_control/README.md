[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"

# Project 2: Continuous Control

### Introduction

In this project, we train a double-jointed arm agent to track a target location.  

![Trained Agent][image1]

A reward of +0.1 is provided for each step that the agents hand is in the target location. As such, the goal of the agent 
is to maintain its position (the hand) at the target location for as many steps as possible.   

The state space has 33 dimensions and contains the position, rotation, velocity, and angular velocities of the arm. 
Each action is a vector with 4 numbers, corresponding to the torque that should be applied to each of the two joints. 
Every entry in the action vector should be a number between -1 and +1. 

The task is episodic, and in order to solve the environment, the agent must get an average score of +30 over 100 consecutive episodes.
For more details about the algorithms and the implementation, please see the files "Continuous_Control.ipynb" and "Report.ipynb".

Note: We are provided with two versions of the environment: i) a single agent, ii) 20 identical agent each with their 
own copy of the environment. In this project, we will focus on the first option.      

### Getting Started

In this project, we use [Unity](https://unity.com/products/machine-learning-agents) environment to design, train, and 
evaluate our deep reinforcement learning algorithms. For more information, please see the Github repo 
[here](https://github.com/Unity-Technologies/ml-agents). To run the notebooks and reproduce the results, you do not need to 
build an environment. If you are using a Linux machine, the environment is already included in the folder "Reacher_Linux". 
For other operating systems, follow the instructions below:

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the DRLND GitHub repository, in the `p2_continuous-control/` folder, and unzip (or decompress) the file. 
  
Please note that the content of this README file mainly comes from [here](https://github.com/udacity/deep-reinforcement-learning/blob/master/p2_continuous-control/README.md) 
with some minor modifications.

### Instructions
1. To set up your python environment, it's best to follow the instructions [here](https://github.com/udacity/deep-reinforcement-learning#dependencies)
2. Clone this repository.
3. Follow the instructions in `Continuous_Control.ipynb` to get started with training the agent and reproducing the results!  
4. Read the Report.ipynb files for more details about the algorithms.

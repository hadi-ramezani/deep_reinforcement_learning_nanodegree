[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135623-e770e354-7d12-11e8-998d-29fc74429ca2.gif "Trained Agent"

# Project 3: Collaboration and Competition

### Introduction

In this project, we train two agents to play tennis by bouncing a ball over a net.   

![Trained Agent][image1]

If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits 
the ball out of bounds, it receives a reward of -0.01. As such, the goal of each agent is to keep the ball in play.   

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. 
Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward 
(or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, the agent must get an average score of +30 over 100 consecutive episodes.
For more details about the algorithms and the implementation, please see the files "Continuous_Control.ipynb" and "Report.ipynb".

The task is episodic, and in order to solve the environment, our agents must get an average score of +0.5 
(over 100 consecutive episodes, after taking the maximum over both agents). Specifically, after each episode, we add up 
the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially 
different) scores. We then take the maximum of these 2 scores. This yields a single score for each episode.    

The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

### Getting Started

In this project, we use [Unity](https://unity.com/products/machine-learning-agents) environment to design, train, and 
evaluate our deep reinforcement learning algorithms. For more information, please see the Github repo 
[here](https://github.com/Unity-Technologies/ml-agents). To run the notebooks and reproduce the results, you do not need to 
build an environment. If you are using a Linux machine, the environment is already included in the folder "Tennis_Linux". 
For other operating systems, follow the instructions below:

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the DRLND GitHub repository, in the `tennis_collab_compet/` folder, and unzip (or decompress) the file. 
  
Please note that the content of this README file mainly comes from [here](https://github.com/udacity/deep-reinforcement-learning/blob/master/p3_collab-compet/README.md) 
with some minor modifications.

### Instructions
1. To set up your python environment, it's best to follow the instructions [here](https://github.com/udacity/deep-reinforcement-learning#dependencies)
2. Clone this repository.
3. Follow the instructions in `Tennis.ipynb` to get started with training the agent and reproducing the results!  
4. Read the Report.ipynb files for more details about the algorithms.

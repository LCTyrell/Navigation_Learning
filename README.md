[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Udacity DRL Nanodegree - Project 1: Navigation

### Environment description (Unity ML-Agents "Food collector")

The project consists of training an agent to navigate and collect as many yellow banana as possible while avoiding blue ones in a square world.  

![Trained Agent][image1]

A **reward of +1** is provided for collecting a yellow banana, and a **reward of -1** is provided for collecting a blue banana.

**The state space has 37 dimensions** and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.    
  
**Four discrete actions** are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

### Installation

1. Download or clone this Github repository.

2. Create a python environment and install required library: `pip install -r requirements.txt`

3. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    

4. Place the file in the repository and unzip (or decompress) the file. 

### Instructions

Follow the instructions in `Navigation_DQN.ipynb` to train and test the agent.

The model weights of the successful agent is saved in :`checkpoint_nav_solved.pth`   



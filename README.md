#### DDPG Continuous Control
Project using Reinforced learning and  DDQN network with Unity ML-Agents Reacher Environment.
Implementation was made as part of Udacity Deep Reinforcement Learning Nanodegree.
For this project, you will work with the Reacher environment.

##### *There are two versions of environment:*
* The first version contains a single agent.
* The second version contains 20 identical agents, each with its own copy of the environment.

##### *I decided to use first environment*
* In this environment, a double-jointed arm can move to target locations
* A reward of +0.1 is provided for each step that the agent's hand is in the goal location.
* Goal of your agent is to maintain its position at the target location for as many time steps as possible.
* The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm.
* Each action is a vector with four numbers, corresponding to torque applicable to two joints.
* Every entry in the action vector should be a number between -1 and 1.
* Task is ending after achieving average score of +30 during at least 100 episodes



#### Setup
1. Clone [DRLND Github repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) 
2. Download the environment that matches your operating system:
    * *Linux*: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
    * *Mac OSX*: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
    * *Windows (32-bit)*: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
    * *Windows (64-bit)*: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)
3. Place the file in the DRLND GitHub repository, in the p2_continuous-control/ folder, and unzip (or decompress) the file.

#### Instructions
* Follow the instructions in Continuous_Control.ipynb to get started.


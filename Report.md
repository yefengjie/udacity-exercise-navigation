# Udacity Exercise Navigation Report
The navigation project is using Deep Q-learing to train an agent to collect yellow bananas in an unity environment.
## The Environment Description
In this project, you will train an agent to navigate (and collect bananas!) in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- 0 - move forward.
- 1 - move backward.
- 2 - turn left.
- 3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.
## The Deep Q-learing Network
    QNetwork(
      (fc1): Linear(in_features=37, out_features=64, bias=True)
      (fc2): Linear(in_features=64, out_features=64, bias=True)
      (fc3): Linear(in_features=64, out_features=64, bias=True)
      (fc4): Linear(in_features=64, out_features=4, bias=True)
    ) 
## Train The Network
    Episode 100	Average Score: 0.33
    Episode 200	Average Score: 2.68
    Episode 300	Average Score: 7.26
    Episode 400	Average Score: 10.07
    Episode 500	Average Score: 11.49
    Episode 600	Average Score: 12.94
    Episode 700	Average Score: 14.08
    Episode 800	Average Score: 14.39
    Episode 851	Average Score: 15.01
    Environment solved in 751 episodes!	Average Score: 15.01  
![train_network](https://raw.githubusercontent.com/yefengjie/udacity-exercise-navigation/master/train_network.png)
## More Detail Info
Please see: [Navigation.ipynb](https://github.com/yefengjie/udacity-exercise-navigation/blob/master/Navigation.ipynb)
    

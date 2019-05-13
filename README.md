# BlackJack-with-RL-Agent
**Building a Reinforcement Learning Agent Using Q-Learning for the famous Casino Game "BlackJack"**

Reinforcement learning is considered as one of three machine learning paradigms, alongside supervised learning and unsupervised learning. Reinforcement Learning(RL) is a type of machine learning technique that enables an agent to learn in an interactive environment by trial and error using feedback from its own actions and experiences. A basic Reinforcement Learning model comprises of below :


- Reward: **R<sub>t</sub>** is a scaler feedback signal to the agent to indicate how good or bad is the agent performing at any time $t$ .

- State: **S<sub>t</sub>** represents current and future states. 

- Action: **A<sub>t</sub>** is how an agent affects to the environment that can change the state. 

- Observation: **O<sub>t</sub>** is what an agent recognizes the world for the state $S_t$. 

- Policy: This defines a statergy for chosing an action given a state to maximize the rewards earned by the agent 

<img src="https://i.stack.imgur.com/eoeSq.png" width=800 />

I will review the two main Temporal Difference(TD) approaches : **SARSA** and **Q-Learning** and finalise which approch is better out of the two approaches for training a RL Agent. I will build a RL Agent for the famous casino game **BlackJack** using the selected appraoch. Blackjack also known as twenty-one, is the most widely played casino banking game in the world. It is a comparing card game between a player and dealer, meaning players compete against the dealer but not against other players. 

I will also run some experiments to figure out the best parameters like alpha, gamma and epsilon for my model. In the last section, I will draw plots for these experiments and explain my results for the parameters that I pick for my model.

# Deep Learning Q-Learning Notes:

**Findings**:

29 Jan:
- Having high epsilon (10%) is usually better than having no epsilon
- Epsilon_min is the probability an agent takes a random action during training
- There exists a sweet spot between the two. The agent must have an exploration incentive.

26 Jan:

- Discount rate refers to how highly the AI values future reward
- Higher discount rate is better
- More layers increase training time 
- More layers makes the network more complex
- Increasing input layer is helpful in providing the forward information the agents need
- Increasing number of cars usually yields higher MPH, but makes the road more cluttered
- Decreasing temporal window maeks training faster, and in our case keeping it at 0 is good since the machines are markovian, they keep driving and are not interested in past memories
- Haven't found momentum to be all that useful

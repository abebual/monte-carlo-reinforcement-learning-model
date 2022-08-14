# Solving the UNO Card Game using Monte-Carlo Reinforcement Learning Model
**Abebual Zerihun Demilew and Rachel Fisher**

***
<p align="center">

![UNO Card Game](https://github.com/abebual/monte-carlo-reinforcement-learning-model/blob/main/uno.jpg) 
    </p>
`Image from Kohls.com`

***

In this project we developed a Monte-Carlo Reinforcment Learning Agent to play an optimal strategy to win a simplified scope of UNO Card Game. The project is stractured as follows:
1. Game Environment 
2. Monte-Carlo Reinforcment Learning Agent 
3. Model Training and Performance 
4. Experments 


### 1. Game Environment 
In environment.py class objects for <i>card, deck, player, turn</i> and <i>game</i> are defined. In main.ipynb, the classes are imported as module, to run simulations. The state_action_reward.py includes the <i>state, action, </i> and <i>reward</i> class objects. 

### 2. Monte-Carlo Reinforcment Learning Agent 
The monte-carlo method reinforcment learning algorithm is defined in agents.py module. 

### 3. Model Training and Performance 
Results from model training included in the project dataset folder - [Rachel Fisher]-[Abebual Demilew]--dataset.zip. Monte-carlo RL model outputs such as q-tables, q-values coverage, win-rates, turns, state-action pairs and visits are included in the dataset folder. 

Model performance results from best performing monte-carlo RL Agent:

![Model Performance](https://github.com/abebual/monte-carlo-reinforcement-learning-model/blob/main/model%20performance.png)

Frequency of playable cards available: 

![Playable Cards](https://github.com/abebual/monte-carlo-reinforcement-learning-model/blob/main/playable_cards.png)

### 4. Experments 

Additional experments were conducted to:
 
Understand if there is a first player advantage.

![Starting Advantage](https://github.com/abebual/monte-carlo-reinforcement-learning-model/blob/main/starting%20advantage.png)

Understand the exploration vs exploitation tradeoff.

![Q-Values Coverage](https://github.com/abebual/monte-carlo-reinforcement-learning-model/blob/main/qvalues.png)

Understand if any card has a playable advantage.

![Played Cards](https://github.com/abebual/monte-carlo-reinforcement-learning-model/blob/main/playableCards.png)


**Python Version:** 3.7  
**Packages:** pandas, numpy, random, itertools, time, tqdm, sys, os, matplotlib, seaborn, ipywidgets

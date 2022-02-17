# Training-Agent-for-First-Person-shooter-FPS-game
![image](https://user-images.githubusercontent.com/80639629/148648791-0da958bf-08a8-4209-a5ab-07e012638b70.png)
![image](https://user-images.githubusercontent.com/80639629/148648802-89aa9696-0282-44ac-91a6-33d55eb6fa19.png)


---
# 1.Title :
```
 Training agent for first-person shooter (FPS) game with Actor-critic Curriculum learning. 
```

2.Objective of the proposal :
we propose a new framework for training vision-based agent for First-Person Shooter (FPS) Game, in particular Doom.  Our model is simple in design and only uses game states from the AI side, rather than using opponents information.

# 3.Paper statement :

Doom is a 1993 First-Person Shooter (FPS) game in which a player fights against other computer controlled agents or human players in an adversarial 3D environment. Previous works on FPS AI focused on using hand-tuned state machines and privileged information, the geometry of the map, the precise location of all players, to design playable agents.
In this paper, we train an AI agent in Doom with a framework that based on A3C with convolutional neural networks (CNN). This model uses only the recent 4 frames and game variables from the AI side, to predict the next action of the agent and the value of the current situation. The goal of  Reinforcement Learning (RL) is to train an agent so that its behavior maximizes/minimizes expected future rewards/penalties it receives from a given environment. If we use Doom as a reinforcement learning platform, In Doom, the player controls the agent to fight against enemies in a 3D environment. The agent can only see the environment from his viewpoint and thus receives partial information upon which it makes decisions. On modern computers, the original Doom runs in thousands of frames per second, making it suitable as a platform for training AI agent. If we use Doom as a reinforcement learning platform for an AI agent in Doom, the player controls the agent to fight against enemies in a 3D environment. The agent can only see the environment from his viewpoint and thus receives partial information upon which it makes decisions. On modern computers, the original Doom runs in thousands of frames per second, making it suitable as a platform for training AI agent.


4.Methodology :
This paper is completely based on a number of quality journal paper. So most of the information will be collected from various paper.


# 5.Outline :
```
	Introduction covers starting points.
	Adaptability will cover basic function of FPS game.
	Challenges and requirements will be discussed.
	Outcome will provide complete review of work.
	Smartly playing concept, Complex performance requirements.
	Spectrum impact, Virtualized architecture of FPS and A3C.
	Conclusion contains recapitulation and possible future Version.
```

# 6.References :
```
https://www.semanticscholar.org/paper/Training-an-Agent-for-FPS-Doom-Game-using-Visual-Adil-Jiang/74c35bb13e71cdd8b5a553a7e65d9ed125ce958e
https://openreview.net/pdf?id=Hk3mPK5gg
https://proceedings.neurips.cc/paper/1999/file/6449f44a102fde848669bdd9eb6b76fa-Paper.pdf
https://www.semanticscholar.org/paper/Playing-FPS-Games-With-Environment-Aware-Learning-Song-Weng/5678aa198b35b672d5829e48c1d1bb0dec2ac4ad
https://www.semanticscholar.org/paper/Playing-First-Person-Shooter-Games-with-Network-Sun-Khan/01baab1073b81025972e35024a9af20ac7efde61
```


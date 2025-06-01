# AI_team_31
## Installation
Set up the project locally

1. **Clone the Repository**

```bash
git clone https://github.com/kongfusmallside/AI_team_31.git

cd /Active-object/
or cd /Hierarchical-Object-Detection/
```

2. **Create Virtual Environment and Install Required Packages**

```bash
virtualenv -p python3.9.0 .venv
.\.venv\Scripts\activate
pip install requirement.txt
```

## Goal
The objective of this final project is to reproduce and compare the advantages of object detection as presented in two papers, addressing their respective limitations, and proposing adjustments to enhance their methodologies. The reward function design in Hierarchical Object Detection is deemed too simplistic, potentially limiting its effectiveness in guiding the learning process. By adopting more sophisticated reward functions or improving the DQN model, we aim to improve the effectiveness and efficiency of object detection algorithms.

## Reference
1. *Picture:
● https://encord.com/blog/object-detection/
● https://medium.com/@sthanikamsanthosh1994/reinforcement-learning-part-3-dueling
-dqn-using-tensorflow-45b024c5b7d9
Paper and code:
● Hierarchical Object Detection with Deep Reinforcement Learning
○ https://github.com/XL2013/Pytorch_Deep_RL_1
● Active Object Localization with Deep Reinforcement Learning
○ https://github.com/rayanramoul/Active-Object-Localization-Deep-Reinforceme
nt-Learning/tree/master
● MULTI-STAGE REINFORCEMENT LEARNING FOR OBJECT DETECTION
● Deep Reinforcement Learning in Computer Vision: A Comprehensive Survey

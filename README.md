# lunar-lander-continuous-action-space
A continuous action space implementation of the Lunar Lander environment using Deep Deterministic Policy Gradient (DDPG) with multiple uncertainties. The agent learns to control the lander with smooth, continuous movements to safely land on the lunar surface. This project demonstrates reinforcement learning with continuous control.

To run the provided script, you need to have the following packages installed:

numpy (version 1.21.0)
torch (version 1.9.0)
gym (version 0.21.0)
matplotlib (version 3.4.2)
You can install these packages using the following pip commands:
pip install numpy==1.21.0
pip install torch==1.9.0
pip install gym==0.21.0
pip install matplotlib==3.4.2
!sudo apt-get install -y swig
!pip install box2d-py
!pip install gym[box2d]


## Installation

To set up the environment, install the following dependencies:

pip install numpy==1.21.0
pip install torch==1.9.0
pip install gym==0.21.0
pip install matplotlib==3.4.2

python trainedmodel.py

To run the dppg_implementation.py use python dppg_implemeentation.py   # keep in mind this will reset the weights of the current actor.pth file!

The finished model is in the actor.pth and is called into the trainedmodel.py file for demonstration 

# rl_basket
agent play basketball with guards
---------------------------------
1. need to run the code on Ubuntu
（export LD_LIBRARY_PATH=/home/jimmy/anaconda3/envs/rlgpu/lib）
 (export QT_QPA_PLATFORM=offscreen)
2. run the python policy_gradient_training.py
---------------------------------
it will show the basketball enviroment and the training figure
---------------------------------
I add some features when training using policy gradient:
1. The agent will not perform the same action as the previous step
2. The agent have the probabilty to perform the shoot command only after it gets ball
3. I designed the reward function to let agent faster reach the basket after it gets ball

# OpenAI_Gym_Projects
Small reinforcement learning projects in OpenAI Gym

# Question 1
Succeeded for 10 trials. The policy behind this question was going back on hill to gain momentum and going forward. However, one time was not enough, so the car goes back up again and tries it again and catches the flag!

# Question 2
Succeeded for 10 trials and the pole stayed in the air. The policy behind this question was the different movements and positions of the pole. If the pole is on the right and is going right, the cart needs to go right to stop it from falling. If it is on the left going left, the cart needs to go left to stop it. If it is on the right going left, the cart needs to go right to assist it. If it is on the left going right, the cart needs to go left to assist it. However this was not enough, if the pole had an angle that was two steep, a policy was put in place to reverse it immediatly, stopping the cart from going out of the frame.

# Question 3
The objective of all question were met except for question 3. In this question the cross entropy approach from cartpole question was taken, and I matched the steps in the algorithms, merging the codes, and used the modified rewards. While learning seemed to take place, and height went up every once in a while, I never reached the flag in question 3. I ran the test for 18 trials and used different hyperparameters.

# Question 4
Completed.

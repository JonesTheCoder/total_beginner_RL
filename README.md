This information is related to the learning resources below and meant to be a practical aid in understanding Reinforcement Learning.

Source 1: Video Lecture series and slides:
https://www.youtube.com/watch?v=lfHX2hHRMVQ&index=2&list=PL7-jPKtc4r78-wCZcQn5IqyuWhBZ8fOxT

Source 2: Move_37 RL Course with Siraj Rival:
https://www.theschool.ai/courses/

Source 3: Denny Britz's Reinforcement Learning repository with problems and solutions.
(All of the initial code from here)
https://github.com/dennybritz/reinforcement-learning

Source 4: Reinforcement Learning: An Introduction by Sutton and Barto
http://incompleteideas.net/book/bookdraft2018jan1.pdf


Policy_copy_1.py is meant to be for the absolute beginner. I've added a bunch of
print statements and code annotations, as well as manipulated the code so that a user can
run this script in terminal using python 3.

To clarify, this is running a policy evaluation algorithm. It is the first problem, titled 'Policy Evaluation' in Denny Britz's repository here: https://github.com/dennybritz/reinforcement-learning/tree/master/DP/

To run from terminal, first make sure you have cloned my repository so you have a copy of the "lib" file from Denny Britz's Github repository, and that you have Policy_copy_1 saved in the same directory.

It's important to have the lib file from Denny Britz because this has the code that
creates the GridWorld environment, a 4 x 4 grid which our agent is acting, "learning", in. Also his repository has links to most of the information/tutorials above and
is definitely the most valuable complimentary code for practicing RL.

Okay so with your files in order, use your terminal shell to CD into the folder with the
python script in it and then type/paste:
    python policy_copy_1.py

Also, I recommend drawing out a 4x4 square grid so you can follow along with the algorithm
and see how it's moving between states.


The program will run and segment each step so that you can see all of the data involved in the process of the
policy evaluation algorithm. This will help in exploring the data to better understand
what exactly is going on iteratively throughout the whole evaluation.

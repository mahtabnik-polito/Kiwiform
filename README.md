# Kiwiform
This repository contains the task for the Kiwiform selection process.
I developed a solution for the minimum possible knight moves in the chess board to reach the target cell. I used the Geektogeek website's code to write the algorithm for the minimum steps then I added the Graphviz library to draw the related graphs for the possible moves. 
Unfortunately, I could not dockerize the code because of the incompatibility of the docker files with Windows 10 and I decided to upload the .py file.
Part B)
I believe that one of the possible solutions for using AI to solve this problem is to produce all the possible movements in our input data and label the minimum path equal to 1. In this case, we can use a classification model like KNN, SVM, and Neural Networks to train a model on our dataset. Another solution to involve Machine learning for solving this problem is to use reinforcement learning. In this approach, we need an agent to take an action and based on the action the model rewards the agent, Finally, the agent will take the actions that have the most probable reward and we can use this model to solve this problem.

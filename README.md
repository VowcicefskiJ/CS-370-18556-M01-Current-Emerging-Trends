# CS-370-18556-M01-Current-Emerging-Trends

Pirate Intelligent Agent Project

Overview of the Project

In this project, I created a pirate intelligent agent using reinforcement learning, specifically deep Q-learning, to navigate a maze and find a treasure. The maze is an 8x8 grid with free and blocked cells, and the treasure is always in the bottom-right corner. The agent learns the best path to the treasure by training through repeated experiences.

Work on the Project 

Code Provided

The project came with a framework for the maze environment, including the TreasureMaze and GameExperience classes. These handled setting up the maze and saving the agent’s experiences for training.

The basic structure for the neural network and training process was also provided.

Code I Created

I implemented the deep Q-learning algorithm, defining how the agent learns the best path to the treasure.

I adjusted neural network parameters and training techniques to make the learning process more efficient.

I improved the GameExperience class to make training smoother by sampling past experiences better.

How This Relates to Computer Science

What Do Computer Scientists Do, and Why Does It Matter?

Computer scientists solve problems by creating algorithms and systems that can improve how things work in the real world. For example, reinforcement learning, like in this project, can be used in robotics, gaming, and even self-driving cars to make better decisions automatically.

My Approach to Problem-Solving

Understand the Problem: I started by understanding the maze setup, the agent’s goal, and how reinforcement learning works.

Build a Solution: I applied the Q-learning algorithm and used experience replay to help the agent learn from past attempts.

Test and Improve: I experimented with different settings, like how much the agent explores new paths versus using what it has already learned, to get better results.

Ethical Responsibilities

To Users: Reinforcement learning can have real-world impacts, so it’s important to ensure that systems are unbiased and fair. For example, in other contexts, like navigation, it’s crucial to prioritize safety and avoid discrimination.

To Organizations: It’s also important to make sure algorithms are reliable and follow ethical guidelines while meeting the organization’s goals.

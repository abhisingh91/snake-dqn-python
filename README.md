# snake-dqn-python 🕹

🤖 This snake AI project focuses on creating a optimizing the classic snake game and making it learn to play using DQN and reinforcement learning

#### 🔍 Description of modules used in the project:

1. **game_env.py:**
    - Environment class for grid-based Snake game dynamics.
    - Manages movement, collisions, and state representation.
    - I have used a total of 21 state parameters with 3 possible actions 🤯

2. **dqn_model.py:**
    - Implements DQNAgent class for Deep Q Learning.
    - Simple neural network with 2 hidden layers, experience replay buffer, and epsilon-greedy exploration.

3. **model_eval.py:**
    - ModelEval class for efficient training and testing.
    - Tracks rewards, saves models and calculates scores.

4. **main.ipynb:**
    - Main Jupyter Notebook orchestrating the project.
    - Disables interactive logging for a cleaner workflow.

☑ I have also provided some trained models in the **trained_model** directory. 
#### Replace the last cell of **main.ipynb** to use trained_model models:
  ```python
  # Test the model
  from keras.models import load_model 

  agent.model = load_model('./trained_models/{NAME_OF_THE_MODEL}')
  model_evaluator.test_model(num_episodes=50)
  ```

🚀 Explore and evolve the Snake Game RL project 

✨ Feel free to suggest any changes or contribute to this project 

#### Thank You!

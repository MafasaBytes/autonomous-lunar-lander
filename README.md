# Lunar Lander Reinforcement Learning Agent

## Description
This project implements a Reinforcement Learning (RL) agent to solve the Lunar Lander environment from OpenAI Gym. The agent uses a Deep Q-Network (DQN) to learn how to land the lunar module safely on the moon's surface. The agent is trained using a reward-based system to take actions (thrust, fire, etc.) in a simulated environment, ultimately learning to land the module successfully.

The goal is to develop an agent that can navigate the lunar lander environment, use the available controls, and successfully land on the moon’s surface while avoiding obstacles and maintaining a safe descent. The training process involves exploration and exploitation, where the agent tries various actions to maximize the reward signal.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/MafasaBytes/Lunar-Lander.git
   cd lunar-lander

## Install required dependencies
- pip install -r requirements.txt

## Usage
To train the RL agent, open the Jupyter Notebook lunar-lander_agent.ipynb and run the cells. The notebook will guide you through the training process and display the agent's performance as it learns to land the lunar module.

To start training in a Jupyter environment:
--jupyter notebook lunar-lander_agent.ipynb

## Rendering and Saving Video
To render the Lunar Lander environment while training, ensure that you have the appropriate dependencies installed and the necessary rendering functionality set up. The training process can display a real-time view of the environment as the agent trains.

Additionally, the notebook saves the video of the agent's training session as an MP4 file, in the outputs directory.

## Dependencies
  - Python ~= 3.9.x
  - TensorFlow ~= 2.19.x
  - OpenAI Gym ~= 0.24.0
  - NumPy ~= 2.0.2
  - Matplotlib (for plotting training results)
  - Jupyter (for running the notebook)
  - opencv-python (for video recording, if necessary)



  ## Acknowledgments
  - OpenAI Gym for providing the Lunar Lander environment.
  - TensorFlow for the deep learning framework.
  - Git LFS for managing large files in the project.
  - Matplotlib for visualizing the training results.
  - OpenCV for handling video recording.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
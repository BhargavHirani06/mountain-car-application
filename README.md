# Mountain Car DQN - Energy-Aware Reinforcement Learning

This project implements a Deep Q-Network (DQN) to solve the classic Mountain Car problem using the OpenAI Gym environment. 
The goal is to train an agent to reach the top of a hill by building momentum, despite limited engine power. 
Our implementation introduces an energy-efficiency constraint by penalizing unnecessary actions, simulating 
resource-aware behavior in autonomous systems.

## Features

- Deep Q-Network with fully connected layers
- Experience replay and target network synchronization
- Epsilon-greedy exploration with decay
- Energy penalty for pushing actions to simulate real-world constraints
- Visualization of training performance (reward curves, histograms, etc.)
- Final agent behavior recorded as video

## Installation

Clone the repository and install required packages:

```bash
git clone https://github.com/BhargavHirani06/mountain-car-application.git
cd mountain-car-application
pip install -r requirements.txt
```

## Running the Code

Train the agent using:

```bash
python train_mountaincar.py
```

To visualize rewards and plots:

```bash
python plot_results.py
```

To record a video of the trained agent:

```bash
python record_video.py
```

## Results

- Smoothed reward curve
- Histogram of episode rewards
- Block-wise average reward
- Final run demonstration

## Acknowledgment

Original baseline:  
https://github.com/rlcode/reinforcement-learning/tree/master/4-gym/1-mountaincar

## License

MIT License

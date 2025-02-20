# Music Recommendation System with Reinforcement Learning

[![Python 3.11.9](https://img.shields.io/badge/Python-3.11.9-blue.svg)](https://www.python.org/downloads/release/python-3119/) [![TensorFlow 2.18](https://img.shields.io/badge/TensorFlow-2.18-%23FF6F00.svg)](https://www.tensorflow.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains a reinforcement learning-based music recommendation system for a music application. The system aims to learn user preferences and provide personalized song recommendations.

## Table of Contents

-   [Project Overview](#project-overview)
-   [Getting Started](#getting-started)
    -   [Prerequisites](#prerequisites)
    -   [Installation](#installation)
-   [Reinforcement Learning Approach](#reinforcement-learning-approach)
-   [Project Status](#project-status)
-   [Issues](#known-issues)
-   [Contributing](#contributing)
-   [License](#license)
-   [Libraries](#libraries-used)

## Project Overview

This project explores the application of reinforcement learning to build a music recommendation system. The goal is to develop an agent that can learn user preferences and provide relevant song recommendations, enhancing the user experience.

## Getting Started

### Prerequisites

-   Python 3.11.9
-   pip
-   VS Code (or your preferred editor)

### Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/samuelsurr/music-recommendation-rl.git
    cd music-recommendation-rl
    ```

2.  Create a virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate  # On Windows
    ```

3.  Install the required packages:

    ```bash
    pip install tensorflow tf-agents gym numpy pandas matplotlib librosa
    ```


## Reinforcement Learning Approach

-   **Environment:** Custom Gym environment representing the music recommendation scenario.
-   **Agent:** Using TensorFlow Agents, potentially using DQN, DDPG, or other suitable algorithms.
-   **Reward Function:** Designed to incentivize relevant song recommendations based on user interactions.
-   **State Representation:** User profile, recent listening history, and song metadata.


## Project Status

-   [ ] Data ingestion and preprocessing.
-   [ ] Gym environment setup.
-   [ ] Initial RL agent implementation.
-   [ ] Offline training with static dataset.
-   [ ] Online training with real-time user data.
-   [ ] Evaluation and performance analysis.


## Known Issues


## Contributing

Contributions are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes.
4.  Commit your changes and push to your fork.
5.  Submit a pull request.

## License

This project is licensed under the MIT License.

## Libraries Used

-   TensorFlow Agents
-   Gym
-   NumPy
-   Pandas
-   Matplotlib
-   Librosa

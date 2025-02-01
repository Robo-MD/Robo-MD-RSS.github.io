# RoboFail: Analyzing Failures in Robot Learning Policies

RoboFail is a deep reinforcement learning-based framework designed to identify failure modes in robotic manipulation policies. By simulating diverse conditions and quantifying failure probabilities, RoboFail provides insights into model robustness and adaptability.

## Installation

### Prerequisites
Ensure you have the following dependencies installed:
- Python 3.8+
- CUDA (if using GPU)
- Conda (recommended for managing environments)


### Setting Up the Environment
1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/Robo-MD/Robo-MD-RSS.github.io.git
   cd Robo-MD-RSS.github.io
   \`\`\`

2. Create a Conda environment:
   \`\`\`bash
   conda create --name robomd python=3.8 -y
   conda activate robomd
   \`\`\`

### Installing Dependencies
#### 1. **Install robosuite**
   \`\`\`bash
   pip install robosuite
   \`\`\`
   If you need MuJoCo for simulation:
   \`\`\`bash
   pip install mujoco
   \`\`\`

#### 2. **Install robomimic**
   \`\`\`bash
   git clone https://github.com/ARISE-Initiative/robomimic.git
   cd robomimic
   pip install -e .
   \`\`\`

#### 3. **Additional Dependencies**
   Install required Python packages:
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`


## Usage







## License
MIT License © 2024 RoboMD Team

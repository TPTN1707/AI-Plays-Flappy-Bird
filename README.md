# 🧠 AI Plays Flappy Bird using NEAT

This project is an implementation of an AI that learns to play Flappy Bird using the [NEAT (NeuroEvolution of Augmenting Topologies)](https://neat-python.readthedocs.io/en/latest/) algorithm. The AI is trained through evolution and reinforcement-style feedback, learning to survive and score higher over generations.

---

## 🚀 How to Run

### 📁 1. Clone the Repository

```bash
git clone https://github.com/TPTN1707/AI-Plays-Flappy-Bird.git
cd AI-Plays-Flappy-Bird/
```
### 🛠️ 2. Create and Activate Conda Environment
```bash
conda create -n fbbot python=3.10 -y
conda activate fbbot
```
### 📦 3. Install Dependencies
```bash
pip install -r requirements.txt
```
### ▶️ 4. Run the Game with NEAT AI
```bash
python flapp_bird.py
```
The AI will start learning and evolving over generations. After a few iterations, you should see significant improvement in gameplay!

# 🧠 AI Training Summary
AI is trained using the neat-python library.

The bird is controlled by a feedforward neural network evolved by NEAT.

The fitness function rewards surviving longer and passing pipes.

# 📜 License
This project is open source and free to use under the MIT License.

# 🙌 Credits
Built with ❤️ by TPTN1707 - Tran Pham Trong Nhan
# Flappy Bird with NEAT Algorithm

This project simulates a Flappy Bird game where an AI agent learns to master the game using the **NEAT** genetic algorithm. Built with Python and Pygame, it demonstrates AI training through neuroevolution.

---

## Features
- Flappy Bird gameplay using Pygame.
- AI learning with the NEAT algorithm.
- Real-time visualization of the training process.

---

## Requirements
- Python 3.8+
- Pygame
- NEAT-Python

Install dependencies:
```bash
pip install pygame neat-python
```

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/habash2125/flappy_bird_NEAT.git
   ```
2. Navigate to the folder:
   ```bash
   cd flappy_bird_NEAT
   ```
3. Run the simulation:
   ```bash
   python main.py
   ```

---

## How It Works
- The AI controls birds using neural networks.
- NEAT evolves these networks to optimize performance.
- Fitness is based on how far birds travel without collisions.

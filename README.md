# Asteroids Game 🚀

A recreation of the classic arcade game Asteroids, built using Python and Pygame. This project demonstrates Object-Oriented Programming (OOP) principles, vector mathematics, and game loop management.

## Features

* **Physics-based Movement:** Smooth acceleration and rotation using vector arithmetic.
* **Collision System:** Custom circular collision detection logic.
* **Asteroid Mechanics:** Large asteroids split into smaller, faster pieces with random trajectories when destroyed.
* **Shooting System:** Weapon mechanics with rate-limited cooldowns.
* **Sprite Management:** Efficient handling of game objects using Pygame sprite groups.

## How to Run

Prerequisites: Ensure you have **Python** and **uv** installed.

1.  Clone the repository:
    ```bash
    git clone [https://github.com/your-username/asteroids.git](https://github.com/your-username/asteroids.git)
    cd asteroids
    ```

2.  Run the game:
    ```bash
    uv run main.py
    ```

## Controls

* **W / S:** Move forward / backward
* **A / D:** Rotate left / right
* **Space:** Shoot
# 🚗 DRIVE MAD - Voxel Physics Challenge

Welcome to the GitHub repository for **DRIVE MAD**, a fun and frustratingly addictive HTML5 voxel arcade game focused on balance and physics!

## 🕹️ About the Game

DRIVE MAD is a minimalist driving simulator where the primary goal is not speed, but precision and control. Players must navigate a high-wheeled, compact monster truck across a series of abstract, blocky platforms without flipping the vehicle or falling into the abyss.

The game features:

* **Voxel Aesthetic:** A clean, colorful, low-poly design inspired by modern mobile arcade games.
* **Realistic Physics:** Challenging vehicle physics that require constant adjustment of speed and momentum to maintain balance.
* **Simple Controls:** Easy-to-learn controls (usually gas and brake) that are difficult to master.
* **Level-Based Progression:** Increasingly difficult levels with unique platform designs and obstacles.

## ✨ How to Play

The controls are simple, but the terrain is not.

| Action | Control (Desktop) |
| :--- | :--- |
| **Accelerate** | `W` or `Up Arrow` |
| **Brake/Reverse** | `S` or `Down Arrow` |
| **Tilt Forward/Backward** | (Often linked to Gas/Brake, or use `A`/`D` or `Left`/`Right` if implemented) |

Your task is to drive your yellow truck from the start to the finish line of each platform sequence while keeping all four wheels (or just two!) on the ground enough to maintain movement.

## 💻 Technical Stack

This project is built using standard web technologies, making it highly accessible and easy to deploy:

* **HTML5:** Structure and initial game launch.
* **CSS3:** Styling and visual presentation.
* **JavaScript:** Core game logic and physics engine implementation.
* **Yandex Games SDK (Integration):** Used for platform deployment, advertising, and leaderboard support.

## 🚀 Deployment

This game is designed to be easily deployed on any static web host.

### GitHub Pages

You can instantly view and play the game using GitHub Pages:

1.  Navigate to your repository's **Settings > Pages**.
2.  Set the **Source** to the `main` branch and the **Folder** to `/(root)`.
3.  The game will be available at `https://[Your-Username].github.io/[Repository-Name]/`

### Yandex Games

This project includes the necessary boilerplate for integrating with the Yandex Games platform:

* The `index.html` file includes the **Yandex Games SDK** to handle loading screens, full-screen ads, and rewards (if implemented).

## 🛠️ Contribution

If you have suggestions for new levels, bug fixes, or physics improvements, feel free to open an issue or submit a Pull Request!

## 📜 License

This project is licensed under the MIT License - see the `LICENSE` file for details. (Agar litsenziya fayli bo'lsa, aks holda bu qismni o'chirishingiz mumkin).

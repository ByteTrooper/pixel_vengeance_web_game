# Pixel Vengeance Web Game

![Gameplay Screenshot](link_to_your_gameplay_screenshot.gif) 
<!-- TODO: Replace this with a link to a cool GIF of your game! -->

**Play the game live here:** [https://your-username.github.io/pixel-vengeance/](https://your-username.github.io/pixel-vengeance/)
<!-- TODO: Replace this with your actual live game URL! -->

---

## About The Game

**Pixel Vengeance** is a classic, high-energy arcade shoot-'em-up built from the ground up with Python and Pygame. It's designed to run directly in your web browser using WebAssembly, thanks to the `pygbag` packaging tool.

The mission is simple: survive the onslaught, obliterate the enemy forces, and defeat the final boss.

## Features

-   **Classic Arcade Action:** Fast-paced, top-down space shooter gameplay.
-   **Choose Your Ship:** Select from four distinct jets, each with its own stats for speed, firepower, armor, and special weapons.
    -   **Interceptor:** A balanced, all-around fighter.
    -   **Striker:** A heavy-hitter with double cannons.
    -   **Tank:** A durable ship that can withstand more damage.
    -   **Wraith:** A nimble and extremely fast scout.
-   **Epic Boss Battle:** Face a challenging, multi-stage boss with a variety of attack patterns, including bullet storms, homing missiles, and devastating laser beams.
-   **Power-Ups:** Collect power-ups to enhance your ship's firepower and speed.
-   **Procedurally Generated Assets:** All sounds in the game are generated from scratch using code, creating a unique and lightweight audio experience.

## How to Play

-   **Arrow Keys:** Move your ship
-   **Spacebar:** Fire primary weapon
-   **Left Shift:** Fire the Super Laser (when fully charged)
-   **C Key:** Use a screen-clearing Bomb

## Built With

This project was built using the following technologies:

-   [Python](https://www.python.org/)
-   [Pygame](https://www.pygame.org/) - The core game development library.
-   [pygbag](https://pypi.org/project/pygbag/) - A tool to package Pygame applications for the web.

## How It Works

The Python and Pygame code is cross-compiled into WebAssembly (WASM), allowing it to run efficiently and securely within a web browser. The `pygbag` tool handles the complex process of creating the necessary HTML, JavaScript, and WASM loaders, turning a desktop application into a web-hosted game.

## Local Development

If you wish to run the game locally on your desktop:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/pixel-vengeance.git
    cd pixel-vengeance
    ```
    <!-- TODO: Replace "your-username" and "pixel-vengeance" with your details -->

2.  **Install dependencies:**
    ```bash
    pip install pygame
    ```

3.  **Run the game:**
    ```bash
    python main.py
    ```
    *(Note: The main game file is named `main.py` for web compatibility)*

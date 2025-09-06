# Peggle Ultimate Deluxe Mega Ultra HD Edition

A web-based Peggle-like game built with JavaScript and the Matter.js physics engine.

## Features

*   **Multiple Game Modes:** Choose between Versus, Endless, and Story modes.
*   **Physics-Based Gameplay:** Uses the Matter.js physics engine for realistic ball dynamics.
*   **Scoring System:** Rack up points and watch your multiplier grow.
*   **Sound Effects:** Immersive audio for various in-game events.
*   **Easter Egg:** A hidden surprise for curious players.

## How to Run

To play the game, you need to run it on a local web server. This is because modern browsers have security restrictions that prevent loading game assets directly from the local file system.

Here's how to set it up:

### Using Python

1.  Make sure you have Python installed. You can download it from [python.org](https://www.python.org/).
2.  Open a terminal or command prompt in the root directory of the project (the `Peggle-Javascript-main` folder).
3.  Run one of the following commands, depending on your Python version:

    *   **Python 3:**
        ```bash
        python -m http.server
        ```

    *   **Python 2:**
        ```bash
        python -m SimpleHTTPServer
        ```
4.  Open your web browser and go to `http://localhost:8000`.

### Using Node.js

1.  Make sure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).
2.  Open a terminal or command prompt.
3.  Install the `http-server` package globally by running:
    ```bash
    npm install -g http-server
    ```
4.  Navigate to the root directory of the project (`Peggle-Javascript-main`) in your terminal.
5.  Start the server:
    ```bash
    http-server
    ```
6.  Open your web browser and go to the address shown in the terminal (usually `http://127.0.0.1:8080`).

## Controls

*   **Aim:** Move your mouse to aim the shooter.
*   **Shoot:** Click the left mouse button to launch a ball.

## Project Structure

```
.
├── index.html              # Main game file with HTML structure and game logic.
├── jsconfig.json           # Configuration for JavaScript language services.
├── libraries/
│   ├── matter.js           # The Matter.js physics engine library.
│   └── matter.min.js       # Minified version of Matter.js.
├── media/
│   └── ...                 # Image assets for the game.
├── Sounds/
│   └── ...                 # Sound effect files.
└── StyleSheet/
    └── style.css           # Styles for the game's UI and layout.
```

## Credits

A Bastian and Nicolaj production™©

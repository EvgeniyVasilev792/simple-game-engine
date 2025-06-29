# Simple Game Engine: Craft Your Own Interactive Adventures 🎮✨

![Game Engine](https://img.shields.io/badge/Game%20Engine-Simple%20Game%20Engine-brightgreen)

Welcome to the **Simple Game Engine** repository! This handcrafted game engine is designed for creating point-and-click adventures, puzzle games, and narrative experiments. Built from scratch using Python, PyGame, and YAML, it emphasizes deep modularity, allowing you to customize your projects with ease.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Modules](#modules)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## Features

- **Handcrafted Design**: Each component of the engine is carefully designed to meet the needs of game developers.
- **Modular System**: Easily add or remove features as needed.
- **Point-and-Click Mechanics**: Perfect for creating engaging adventure games.
- **Puzzle Integration**: Built-in support for puzzles and challenges.
- **Narrative Focus**: Tools for crafting rich stories and dialogues.
- **Open Source**: Freely available for anyone to use and modify.

## Installation

To get started with the Simple Game Engine, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/EvgeniyVasilev792/simple-game-engine.git
   ```

2. **Navigate to the Directory**:

   ```bash
   cd simple-game-engine
   ```

3. **Install Dependencies**:

   Make sure you have Python and pip installed. Then run:

   ```bash
   pip install -r requirements.txt
   ```

## Getting Started

After installation, you can start creating your game. Here’s a basic outline of how to begin:

1. **Create a New Project**: 
   Set up a new directory for your game.

2. **Initialize the Game**: 
   Use the provided templates to set up your game structure.

3. **Develop Your Game**: 
   Add your assets, scripts, and dialogue.

4. **Run Your Game**: 
   Execute the main script to see your game in action.

## Usage

The Simple Game Engine offers a straightforward API for game development. Here are some key components:

### Game Loop

The main game loop handles events, updates, and rendering:

```python
while running:
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            running = False

    # Update game state
    update()

    # Render
    render()
```

### Dialogue System

Creating dialogues is simple with YAML support:

```yaml
- character: "Hero"
  text: "Welcome to the adventure!"
  
- character: "Villain"
  text: "You will never escape!"
```

### Puzzle Mechanics

Implement puzzles with custom logic:

```python
def check_puzzle_solution(user_input):
    if user_input == "correct_answer":
        unlock_next_area()
    else:
        show_hint()
```

## Modules

The engine is modular, allowing you to extend functionality easily. Here are some core modules:

- **Core Module**: Handles the game loop and event management.
- **Dialogue Module**: Manages character dialogues and branching conversations.
- **Puzzle Module**: Implements logic for puzzles and challenges.
- **Asset Manager**: Loads and manages game assets like images and sounds.

## Examples

To illustrate the engine's capabilities, here are some example projects:

1. **Mystery Adventure**: A classic point-and-click game with intricate puzzles and a gripping story.
2. **Surreal Quest**: An experimental game that challenges players with abstract puzzles and narratives.
3. **Interactive Fiction**: A narrative-driven experience where choices affect the outcome.

Each example can be found in the `examples` directory of the repository.

## Contributing

We welcome contributions to the Simple Game Engine! If you’d like to help, please follow these steps:

1. **Fork the Repository**: Click the "Fork" button at the top right of this page.
2. **Create a New Branch**: 

   ```bash
   git checkout -b feature-branch
   ```

3. **Make Your Changes**: Add your features or fixes.
4. **Commit Your Changes**: 

   ```bash
   git commit -m "Add feature"
   ```

5. **Push to Your Fork**: 

   ```bash
   git push origin feature-branch
   ```

6. **Create a Pull Request**: Go to the original repository and click "New Pull Request."

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or suggestions, feel free to reach out:

- **Email**: evgeniy@example.com
- **GitHub**: [EvgeniyVasilev792](https://github.com/EvgeniyVasilev792)

## Releases

You can find the latest releases of the Simple Game Engine [here](https://github.com/EvgeniyVasilev792/simple-game-engine/releases). Download and execute the latest version to get started with your game development.

For more updates, check the "Releases" section in this repository.
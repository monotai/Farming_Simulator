## Requirements

Before running the Farming Simulator game, make sure the following requirements are met.

---

### Software Requirements

- **Python** 3.8 or higher  
- **Pygame** – for game rendering, input handling, and game loop  
- **Pymixer** – for sound and music management  

📘 **Reference Documentation**  
- Pygame Official Docs: https://www.pygame.org/docs/index.html

---

### Required Python Libraries

The project uses the following libraries:

- `pygame` – game engine and graphics  
- `os` – file and path management  
- `json` – configuration and game data storage  

---

### Installation

Install required libraries using pip:

```bash
pip install pygame pymixer

## Requirements & Dependencies

This project is a **Python-based game simulation** developed using **Pygame** and follows **Object-Oriented Programming (OOP)** principles.  
To run the project correctly, all requirements listed below must be installed and properly configured.

---

## System Requirements

### Operating System
- Windows 10 / 11  
- Linux (Ubuntu, Debian, Arch)  
- macOS  

### Python Version
- **Python 3.8 or higher**
- Python must be added to system PATH

Check Python version:
```bash
python --version
Core Dependencies
1. Pygame
Purpose:
Pygame is the main game development library used for:

Window creation and screen rendering

Keyboard and mouse input handling

Game loop and frame updates

Sprite management and collision detection

Installation:

bash
Copy code
pip install pygame
Documentation:

Official Pygame Documentation
https://www.pygame.org/docs/index.html

2. Pymixer
Purpose:
Pymixer is used for:

Background music playback

Sound effects (SFX)

Audio channel management

Volume and loop control

Installation:

bash
Copy code
pip install pymixer
Notes:

Requires a working audio device

Audio drivers must be installed and enabled

Standard Python Libraries Used
The following libraries are part of Python’s standard library and do not require installation:

os
Usage:

Handle file paths across different operating systems

Load assets (images, sounds) dynamically

Manage directories and resources safely

Example:

python
Copy code
os.path.join("assets", "images", "player.png")
json
Usage:

Store and load game configurations

Save player progress or settings

Read structured game data (levels, stats)

Example:

python
Copy code
with open("config.json") as f:
    config = json.load(f)
Optional Development Tools
These tools are recommended but not required:

VS Code / PyCharm – code editor

Git – version control

Virtual Environment (venv) – dependency isolation

Create virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows
Installation Guide (Step-by-Step)
Clone the repository:

bash
Copy code
git clone <repository-url>
cd Farming_Simulator
(Optional) Activate virtual environment

Install required dependencies:

bash
Copy code
pip install pygame pymixer
Run the project:

bash
Copy code
python main.py
Verification
To verify that Pygame is installed correctly:

bash
Copy code
python -m pygame.examples.aliens
If the demo runs, Pygame is configured correctly.

Common Issues & Solutions
❌ Game window does not open
Check Python version

Verify Pygame installation

Run script from project root directory

❌ No sound or music
Check system audio output

Ensure Pymixer is installed

Confirm sound files exist in assets directory

Project Scope
Single-player simulation game

Object-Oriented Programming design

Educational purpose

No external network or database dependency

Reference
Pygame Documentation:
https://www.pygame.org/docs/index.html
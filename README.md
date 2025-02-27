# IDAI207-2305396-YuvrajSoni-2205893-AaravNair-2011143-DarshPatel-2305402-AzmahTheba

# **Ripcord Game Repository Structure**

## **Directory Structure:**
```
Ripcord-Game/
│-- assets/
│   │-- images/
│   │   │-- characters/
│   │   │   │-- alpha_idle.png
│   │   │   │-- alpha_run.png
│   │   │   │-- alpha_jump.png
│   │   │   │-- enemies/
│   │   │   │   │-- enemy1.png
│   │   │   │   │-- enemy2.png
│   │   │-- environment/
│   │   │   │-- background.png
│   │   │   │-- platforms.png
│   │-- audio/
│   │   │-- music/
│   │   │   │-- background_theme.mp3
│   │   │   │-- level_complete.mp3
│   │   │-- sfx/
│   │   │   │-- jump.wav
│   │   │   │-- collect.wav
│   │   │   │-- hit.wav
│-- src/
│   │-- main.py
│   │-- settings.py
│   │-- game.py
│   │-- player.py
│   │-- enemy.py
│   │-- level.py
│   │-- ui.py
│   │-- particles.py
│   │-- foliage.py
│   │-- anim_loader.py
│   │-- spritesheet_loader.py
│   │-- text.py
│   │-- grass.py
│-- levels/
│   │-- level1.json
│   │-- level2.json
│   │-- level3.json
│-- docs/
│   │-- README.md
│   │-- CONTRIBUTING.md
│   │-- LICENSE
│-- tests/
│   │-- test_player.py
│   │-- test_enemy.py
│   │-- test_level.py
│-- requirements.txt
│-- .gitignore
│-- setup.py
```

## **Detailed Description of Each Directory and File:**

### **1. assets/**
Contains all game assets, including images, audio, and animations.

#### **- images/**
Stores visual assets for the game, categorized into:
- **characters/**: Player character (Alpha) and enemies.
- **environment/**: Background, platforms, and other visual elements.

#### **- audio/**
Contains sound files for:
- **music/**: Background themes and level completion sounds.
- **sfx/**: Sound effects for jumps, attacks, enemy hits, and collectibles.

---

### **2. src/**
Main game logic and Python scripts.

#### **- main.py**
- Entry point of the game.
- Initializes the game engine and loads assets.

#### **- settings.py**
- Stores game settings such as screen resolution, frame rate, and sound levels.

#### **- game.py**
- Handles game loops, physics, and main logic.

#### **- player.py**
- Defines the player character, including movement, animations, and interactions.

#### **- enemy.py**
- Manages enemy AI, movement, and attack behavior.

#### **- level.py**
- Handles level loading, obstacles, and platform generation.

#### **- ui.py**
- Manages in-game user interface elements, such as the anger bar and score display.

#### **- particles.py**
- Handles particle effects, including sparks, explosions, and environmental animations.

#### **- foliage.py**
- Manages animated foliage elements.

#### **- anim_loader.py**
- Loads and manages animations for characters and environment objects.

#### **- spritesheet_loader.py**
- Handles spritesheet loading and parsing for rendering.

#### **- text.py**
- Renders in-game text and UI elements.

#### **- grass.py**
- Manages procedural grass movement and rendering.

---

### **3. levels/**
- JSON files that define level layouts, including:
  - Platform positions.
  - Enemy spawn points.
  - Collectible placements.
  - Level objectives.

---

### **4. docs/**
Contains documentation for the project.

#### **- README.md**
- Overview of the project.
- Installation and usage instructions.

#### **- CONTRIBUTING.md**
- Guidelines for contributors, including coding standards and issue reporting.

#### **- LICENSE**
- Specifies the game’s licensing terms.

---

### **5. tests/**
Unit tests to ensure game stability and performance.

#### **- test_player.py**
- Tests player movement, jumping, and interactions.

#### **- test_enemy.py**
- Tests enemy AI, behavior, and attack patterns.

#### **- test_level.py**
- Tests level loading and environment interactions.

---

### **6. requirements.txt**
Lists all dependencies required to run the game, such as:
```
pygame==2.1.2
arcade==2.6.10
pyglet==1.5.21
```
---

### **7. .gitignore**
Specifies files and directories to exclude from version control (e.g., temporary files, logs, and compiled binaries).

---

### **8. setup.py**
- Script to package the game for installation and distribution.
- Defines dependencies and entry points.

---

## **Version Control & Collaboration**
- The repository follows **GitHub Flow** for collaboration.
- Branch structure:
  - **main**: Stable release versions.
  - **dev**: Active development branch.
  - **feature/**: Branches for new features.
  - **bugfix/**: Branches for fixing reported issues.
- **Pull Requests (PRs)** required for merging changes into the main branch.

---

## **Contribution Guidelines**
- Code should follow **PEP 8** standards.
- Commits should be structured as:
  ```
  feat: Added new enemy AI behavior
  fix: Resolved collision detection issue
  refactor: Optimized level loading function
  ```
- Issues should be reported in GitHub’s **Issues** section with labels like **bug**, **enhancement**, **documentation**.

---

## **Deployment & Running Instructions**

### **1. Clone the repository:**
```sh
git clone https://github.com/yourusername/Ripcord-Game.git
cd Ripcord-Game
```

### **2. Create a virtual environment and install dependencies:**
```sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### **3. Run the game:**
```sh
python src/main.py
```



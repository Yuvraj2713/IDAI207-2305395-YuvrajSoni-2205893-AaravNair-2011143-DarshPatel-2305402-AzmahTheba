# IDAI207-2305396-YuvrajSoni-2205893-AaravNair-2011143-DarshPatel-2305402-AzmahTheba

# **Ripcord Game Repository**

## **Project Title and Description**
### **Ripcord - A 2D Platformer with an Anger Bar Mechanic**

*Ripcord* is an engaging and challenging 2D platformer game where players must navigate levels, collect items, and battle enemies while managing an "anger bar." This unique mechanic introduces a sense of urgency, making every decision crucial. Inspired by classic platformers like *Cut the Rope*, *Ripcord* combines fast-paced gameplay with strategic resource management to create an immersive gaming experience.

### **Objectives**
- Develop a fun and strategic 2D platformer.
- Implement an innovative anger bar mechanic to drive player decisions.
- Provide an engaging, well-balanced difficulty curve.
- Optimize performance for smooth gameplay.
- Design visually appealing environments with interactive elements.

---

## **Features**
- **Anger Bar Mechanic**: The player’s anger meter continuously depletes unless lollipops are collected.
- **Dynamic Level Progression**: Increasingly complex level designs encourage skill growth.
- **Enemy AI & Combat**: Enemies dynamically interact with the player and respond to actions.
- **Physics-Based Movements**: Gravity, jump physics, and smooth acceleration.
- **Collectibles & Power-ups**: Lollipops replenish the anger bar, while other collectibles enhance gameplay.
- **Animated Environments**: Trees, grass, and clouds react to player interactions.
- **Smooth Player Controls**: Optimized key bindings for fluid movement and combat.
- **Audio-Visual Enhancements**: High-quality sound effects, music, and animations for immersive gameplay.

---

## **Technologies Used**

### **Programming Languages & Libraries**
- **Python**: Core programming language.
- **Pygame**: Primary game engine for rendering and logic.
- **Arcade**: Simplifies 2D game development.
- **Pyglet**: Handles multimedia (images, animations, and sound).

### **Graphics & Animations**
- **Custom Spritesheets**: Created using Photoshop and Aseprite.
- **Spritesheet Loader**: Efficiently loads and manages animations.
- **Procedural Grass & Foliage Animation**: Dynamic environmental interactions.

### **Sound & Music**
- **Pygame Mixer**: Manages background music and in-game sound effects.
- **Custom Sound Design**: Recorded and mixed using Audacity.

### **Level Design & Storage**
- **Tile-Based Level Maps**: Stored in JSON format for easy modifications.
- **Procedural Object Placement**: Grass, trees, and background elements adapt dynamically.

---

## **Installation Instructions**
### **Step 1: Clone the Repository**
```sh
git clone https://github.com/yourusername/Ripcord-Game.git
cd Ripcord-Game
```

### **Step 2: Set Up a Virtual Environment & Install Dependencies**
```sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### **Step 3: Run the Game**
```sh
python src/main.py
```

---

## **Usage Instructions**

### **Gameplay Controls**
- **Move Left:** `A` or `Left Arrow`
- **Move Right:** `D` or `Right Arrow`
- **Jump:** `Space` or `Up Arrow`
- **Attack:** `X`
- **Pause:** `Esc`

### **How to Play**
1. **Start the Game:** The player controls Alpha, the main character.
2. **Monitor the Anger Bar:** Keep it from depleting by collecting lollipops.
3. **Navigate Levels:** Jump across platforms, dodge obstacles, and fight enemies.
4. **Defeat Enemies:** Use attacks strategically while maintaining movement.
5. **Complete Levels:** Reach the designated goal with a balanced anger meter.

---

## **Contribution Guidelines**
We encourage contributions from the community! Follow these steps to contribute:

### **Step 1: Fork the Repository**
Create a fork on GitHub to make your modifications without affecting the main branch.

### **Step 2: Create a Feature Branch**
```sh
git checkout -b feature-new-enhancement
```

### **Step 3: Make Changes & Commit**
Follow best practices when committing code:
```sh
git commit -m "feat: Added new enemy AI behavior"
```

### **Step 4: Push Changes & Create a Pull Request**
```sh
git push origin feature-new-enhancement
```
Submit a **Pull Request (PR)** for review, ensuring you provide a clear description of changes.

### **Code Standards**
- Follow **PEP 8** for Python code formatting.
- Use meaningful commit messages.
- Submit well-documented code with comments where necessary.

---

## **Acknowledgments**
- **Pygame & Arcade**: Powerful libraries that made development smoother.
- **Open-Source Community**: Contributions from various forums helped troubleshoot issues.
- **Game Testers & Developers**: Everyone who contributed to testing and refining *Ripcord*.
- **Sound Designers & Artists**: For creating immersive audio-visual elements.

---

## **Screenshots/Demos**
### **Main Menu**
![Main Menu](screenshots/main_menu.png)


![Gameplay](screenshots/gameplay.png)

### **Level Completion Screen**
![Level Complete](screenshots/level_complete.png)

### **Enemy Encounter**
![Enemy Encounter](screenshots/enemy_encounter.png)

---



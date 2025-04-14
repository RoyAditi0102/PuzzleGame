# Sliding Puzzle Game 

A fun and interactive **Sliding Puzzle Game** built with **Python**, **Pygame**, and **OpenCV**, where users rearrange shuffled tiles to recreate the original image. This project demonstrates proficiency in image processing, game development, and GUI design.

## 🛠 Tech Stack
- **Python**
- **Pygame** – for game interface and logic
- **OpenCV** – for image slicing and manipulation

## 📸 Features
- Load and slice any image into a grid of tiles
- Drag or use arrow keys to move tiles (sliding mechanism)
- Timer to track how fast you solve the puzzle
- Intuitive UI with instructions and start/exit screen
- Solvable puzzle configuration ensured after each shuffle
- Supports keyboard interaction and smooth tile movement

## 🎮 How to Play
1. Clone this repository.
2. Install the required packages:
   ```bash
   pip install pygame opencv-python
   ```
3. Run the game using:
   ```bash
   python main.py
   ```
4. Use **arrow keys** to move tiles and solve the puzzle.
5. Arrange the tiles in order to match the original image.
6. Timer tracks your completion time – challenge yourself!

## 📂 File Structure
```
.
├── assets/               # Images
├── src.py              # Game entry point        
└── README.md
```

## 🔧 Customization
- You can change the puzzle image by replacing the default image inside the `/assets` folder.
- Adjust grid size (e.g., 3x3, 4x4) by modifying the `GRID_SIZE` variable in `main.py`.

## 💡 Solvability
To ensure fairness and challenge, the game generates only **solvable** configurations using inversion count logic.

## 📌 License
This project is open-source and available under the [MIT License](LICENSE).

## 👤 Author
**Aditi Roy**  

📧 [LinkedIn](https://www.linkedin.com/in/royaditi0102/)  
📁 [GitHub](https://github.com/RoyAditi0102/)

**Anindita Goswami**

📧 [LinkedIn](https://www.linkedin.com/in/anindita-goswami-baa239238/)  
📁 [GitHub](https://github.com/Code-Ani2/)

**Ayushi Gupta**

📧 [LinkedIn](https://www.linkedin.com/in/ayushi-gupta-03a713242/)  
📁 [GitHub](https://github.com/Ayushi-gupta-025/)

## 🌟 Show Your Support
If you like this project, please ⭐ the repo! Contributions, feedback, and ideas are always welcome.

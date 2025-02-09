# Simon Says Game 🎮

This is a web-based version of the classic Simon Says memory game. The goal of the game is to follow and repeat the randomly generated color sequence. As the game progresses, the sequence gets longer and more challenging.

![image_alt](https://github.com/Darshan0244/Simon_Says_Game/blob/55f220895d359ccf22f60c75eab62196fa6a4e35/Screenshot%202025-02-09%20154358.png)
![image alt](https://github.com/Darshan0244/Simon_Says_Game/blob/9784d2dda74ef2079ecf20e8c29e1d6b3767786f/Screenshot%202025-02-09%20153133.png)
![image alt](https://github.com/Darshan0244/Simon_Says_Game/blob/9784d2dda74ef2079ecf20e8c29e1d6b3767786f/Screenshot%202025-02-09%20153133.png)

## Table of Contents
- [How to Play](#how-to-play)
- [Features](#features)
- [Installation](#installation)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [License](#license)

---

## How to Play 😉

1. **Start the Game**:
    - Open the game in a web browser and press any key on your keyboard to start the game.
    
2. **Observe the Pattern**:
    - Watch carefully as one of the four colored buttons will flash. This is the first color in the sequence.
    
3. **Repeat the Sequence**:
    - Click the button that matches the color that just flashed. If you're correct, the game will add another color to the sequence.
    
4. **Increase the Sequence**:
    - Each time you correctly match the sequence, a new color will be added to the sequence, and you will need to repeat the entire sequence in order.

5. **Game Over**:
    - If you click the wrong button or fail to match the sequence, the game will play a "wrong" sound, the screen will flash red, and the game will display "Game Over." You can press any key to restart and try again.

6. **Goal**:
    - The goal is to see how long you can keep up with the increasing length of the sequence.

---

## Features 🔻
- **Dynamic Game Sequence**: Each level generates a random sequence of colors that the player must repeat.
- **Keyboard Start**: The game starts when any key is pressed.
- **Visual and Audio Feedback**: Buttons flash with color, and each button has a unique sound associated with it. There is also feedback for incorrect answers (sound and screen flash).
- **Responsive Design**: Works on both desktop and mobile devices.

---

3. **Open `index.html` in your browser**:
    You can open the game by simply double-clicking on the `index.html` file in the project folder, or by using a live server extension if you’re using VSCode or a similar editor.

---

## ⚙️Technologies Used
- **HTML**: For the game structure and layout.
- **CSS**: For styling the game elements, including colors and animations.
- **JavaScript (jQuery)**: For handling the game logic, sequence generation, button clicks, and user interactions.
- **jQuery**: For simplifying DOM manipulation and event handling.

---

## 📁File Structure

```
Simon-Game/
│
├── sounds/                     # Folder for sound files
│   ├── blue.mp3
│   ├── green.mp3
│   ├── red.mp3
│   └── yellow.mp3
│
├── index.html                  # Main HTML file
├── styles.css                  # CSS file for styling the game
└── index.js                    # JavaScript file with game logic
```

---

## License 🪪

This project is licensed under the MIT License. Feel free to modify and distribute as needed.

---

### Enjoy the Game! 🫡

If you have any feedback or suggestions, feel free to reach out or submit a pull request.

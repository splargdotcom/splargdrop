# Splarg Drop

> *“You can drop a mouse down a thousand-yard mine shaft; and on arriving at the bottom, it gets a slight shock and walks away. A rat is killed, a man is broken, a horse splashes.”*
>
> — **J.B.S. Haldane**, *On Being the Right Size*

<img width="1919" height="1079" alt="Screenshot 2025-12-12 202305" src="https://github.com/user-attachments/assets/e2dc1821-34f8-42e0-a4cb-940cd6c57fa7" />
<img width="1918" height="1079" alt="Screenshot 2025-12-12 202245" src="https://github.com/user-attachments/assets/3897d1f1-21c2-42fa-b2a8-190efb69cc94" />

**Splarg Drop** is a customizable, retro-terminal styled falling block puzzle game built with vanilla JavaScript.

Unlike traditional games in this genre, **Splarg Drop** features a constant game loop—the speed does not increase as you level up. Instead, the challenge lies in endurance, grid management, and optimizing your playstyle to achieve the ultimate status of "Horse Splashed."

## ✨ Features

* **Constant Flow:** The drop speed remains constant throughout the game. You set the pace in the config menu.
* **Dynamic Board Sizing:** Want a narrow 4-wide challenge? Or a massive 50-wide marathon? The game engine automatically scales the blocks to fit your screen based on your custom width and height inputs.
* **Retro Terminal Aesthetic:** Featuring a "hollow-block" CRT visual style with a single-pixel border.
* **Theme Engine:** Includes a retro color picker to tint your monitor (Green, Amber, Cyan, Magenta, White).
* **Full Gamepad Support:** Plug and play with standard Xbox/PlayStation controllers. You can navigate menus and play the game entirely without a keyboard.
* **Zero Dependencies:** Written entirely in a single HTML file using the HTML5 Canvas API. No build steps, no libraries.

## 🕹️ Controls

The game automatically detects connected gamepads.

| Action | Keyboard | Gamepad |
| :--- | :--- | :--- |
| **Start Game** | (Click Button) | Start / A |
| **Move Left/Right** | Arrow Left / Right | D-Pad / Left Stick |
| **Soft Drop** | Arrow Down | D-Pad Down |
| **Hard Drop** | Arrow Up | D-Pad Up |
| **Rotate** | Q, W | Face Buttons (A, B, X, Y) |
| **Pause Game** | Esc | Start |
| **Quit to Menu** | - | Select / Back |

*> **Note:** When paused, you can use the D-Pad or Arrow keys to adjust the game speed on the fly.*

## 🏆 Scoring System

The game ranks your performance based on the J.B.S. Haldane quote found on the title screen. Your "Game Over" title changes based on your final score:

1.  **MOUSE SHOCKED** (Low Score) - You walked away unharmed.
2.  **RAT KILLED** (Medium Score)
3.  **MAN BROKEN** (High Score)
4.  **HORSE SPLASHED** (Ultimate Score)

## 🚀 How to Run

Because **Splarg Drop** uses zero external dependencies, running it is incredibly simple:

1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/your-username/splarg-drop.git](https://github.com/your-username/splarg-drop.git)
    ```
2.  **Open the file:**
    Double-click `index.html` to open it in any modern web browser (Chrome, Firefox, Edge, Safari).

## ⚙️ Customization

On the start screen, you can configure:
* **Width:** The number of blocks horizontally (Min: 4, Max: 50).
* **Height:** The number of blocks vertically (Min: 10, Max: 100).
* **Speed:** The drop interval in milliseconds (Standard is 1000ms).
* **Tint:** Click the colored squares to change the CRT phosphor color.

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---

*Concept and code by splargdotcom*

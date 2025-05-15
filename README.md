# 🧩 Jigsaw Puzzle – Image-Based Drag & Snap Game

An interactive browser-based **Jigsaw Puzzle** game where you can upload your own image, choose difficulty (rows/columns), and solve the puzzle by dragging, rotating, and snapping pieces into place.

---

## 📸 Features

- 📤 Upload any image to generate a jigsaw puzzle
- 🎚 Adjustable puzzle difficulty (choose rows and columns)
- ✋ Drag & drop pieces from a scattered canvas to the board
- 🔄 Double-click to **rotate** pieces
- ✅ Automatic snap when pieces are correctly placed
- 🎉 Confetti celebration when the puzzle is solved
- 💡 Visual outline templates on the board to guide placement

---

## 🎮 How to Play

1. Click **"Pick Image"** and choose a local image (JPG/PNG).
2. Set the number of **Rows** and **Columns** (e.g., 4x4).
3. Click **"Start Puzzle"** to begin.
4. Drag pieces from the left pane to the board on the right.
5. **Double-click** pieces to rotate.
6. When a piece is placed correctly and oriented properly, it will snap into position.
7. Solve the full puzzle to trigger a fun **confetti celebration**!

---

## 🧩 Puzzle Logic

- **Knobs and holes** are randomly generated for each edge.
- Edges are mirrored between adjacent pieces (e.g., one’s "bump" becomes the other’s "hole").
- Only pieces with **0° rotation** and enough overlap **(≥90%)** will snap into place.

---

## 📦 Tech Stack

| Technology | Purpose                               |
|------------|----------------------------------------|
| HTML5      | Layout structure                       |
| CSS3       | Styling, transitions, and animations   |
| JavaScript | Core game logic and interactions       |
| Canvas     | Dynamically rendering jigsaw pieces    |

---

## 🗂️ Project Structure

| Section              | Description                                        |
|----------------------|----------------------------------------------------|
| `#upload`            | Image file input                                   |
| `#rows`, `#cols`     | Puzzle difficulty controls                         |
| `#scatter-container` | Left-side piece bin (pieces placed randomly)       |
| `#board-container`   | Right-side puzzle board with guides                |
| `makePiece()`        | Cuts image and draws jigsaw shapes on canvas       |
| `makeDraggable()`    | Adds drag/drop and snapping logic                  |
| `rotate()`           | Handles piece rotation on double-click             |
| `launchConfetti()`   | Triggers when all pieces are placed                |

---

## 🖥️ How to Use Locally

1. Download or clone the repository.
2. Open `index.html` in any modern browser (Chrome recommended).
3. Enjoy solving your own personalized jigsaw puzzles!

---

## 🎯 Ideas for Future Enhancements

- 🧠 Timer and scoring system
- 🕹️ Touch support for mobile devices
- 🔄 Undo/Reset puzzle buttons
- 🧠 Puzzle preview or hint toggle
- 💾 Save/load puzzle state

---

## 👩‍💻 Author

Developed with 💚 and logic by **Vinayak Rai**  
Perfect blend of creativity, canvas, and interactivity

---

## 📜 License

Free to use and modify under the [MIT License](LICENSE)

---

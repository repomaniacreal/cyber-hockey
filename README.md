# ⚡ Neon Cyberpunk Air Hockey

A fast-paced, lightweight, web-based 2D Air Hockey game featuring a retro-futuristic Cyberpunk/Neon aesthetic, particle explosion goal effects, and a smart CPU opponent with anti-stuck AI mechanics. Built using pure HTML5 Canvas and Vanilla JavaScript with zero external build dependencies required.

---

## 🚀 Features

* **Cyberpunk Neon Aesthetic:** Vibrant glowing visual effects, dark grid background, and custom neon mallets (*Cyan vs. Magenta*).
* **Particle Goal Explosions:** Explosive particle effects trigger whenever a goal is scored, matched with color-coded sparks for each player.
* **Smart CPU AI:** Responsive computer opponent that defends, attacks, and recovers pucks even from tricky corners.
* **Anti-Stuck Physics:** Automatic puck nudge mechanism to prevent the puck from freezing in corner dead zones.
* **Smooth Physics Engine:** Circle-to-circle collision detection with velocity transfers, wall bounces, and friction simulation.
* **Touch & Mouse Support:** Fully responsive touch and mouse controls designed for desktop and mobile browsers.
* **Single-File Execution:** Runs directly in any modern browser without needing Node.js or build steps.

---

## 📦 Installation & Running

Since the game is packaged as a standalone web application, no installation or package manager is required.

### Option 1: Direct Launch (Easiest)
1. Download or clone this repository to your local machine.
2. Locate the `index.html` file.
3. Double-click the file to open it directly in your web browser (Chrome, Firefox, Safari, Edge).

### Option 2: Local Development Server
If you prefer running it through a local HTTP server:

Using **VS Code Live Server**:
1. Open the project folder in VS Code.
2. Right-click `index.html` and select **Open with Live Server**.

Using **Python HTTP Server**:
```bash
# Navigate to project directory
cd /path/to/project

# Run local Python server
python3 -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

---

## 🎮 How to Play

### Controls
* **Desktop:** Move your mouse over the right side of the arena to move your Magenta mallet.
* **Mobile / Touchscreen:** Tap and drag your finger on the right side of the screen to maneuver your mallet.

### Rules
* **Objective:** Hit the puck into the CPU's left goal while defending your right goal.
* **Winning Condition:** First player to reach **7 points** wins the match.
* **Boundaries:** Your mallet is restricted to your side of the table (the right half).

---

## 🛠️ Project Structure

```text
cyber-hockey/
├── index.html        # Complete single-file application (HTML, CSS, & JS)
└── README.md         # Project documentation
```

---

## 💻 Tech Stack

* **HTML5 Canvas (2D Context):** Game rendering and particle effects.
* **Vanilla JavaScript (ES6+):** Game loop, AI logic, and collision physics.
* **CSS3:** Neon glow filters, CSS variables, and layout styling.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE). Feel free to modify and adapt it for your own projects!

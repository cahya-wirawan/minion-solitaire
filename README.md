# Minion Solitaire 3D

A 3D animated visualization of the classic Peg Solitaire game, featuring Minion-inspired characters. This project solves the English Peg Solitaire board and animates the solution with kicks and sound effects.

## Features

- **3D Visualization**: Built with [Three.js](https://threejs.org/) for rendering the board and characters.
- **Automated Solver**: Includes a backtracking algorithm to solve the puzzle.
- **Animations**: Characters walk, kick, and fly off the board using [GSAP](https://greensock.com/gsap/).
- **Sound Effects**: Procedural audio for kicks and screams generated via the Web Audio API (no external assets required).
- **Controls**:
  - **Auto Play**: Watch the full solution unfold automatically.
  - **Step**: Advance one move at a time.
  - **Reset**: Restart the simulation.
  - **Camera**: Orbit, zoom, and pan around the board (standard Three.js OrbitControls).

## Technologies

- **HTML5 & CSS3**
- **JavaScript (ES6+)**
- **Three.js** (3D Rendering)
- **GSAP** (Animations)
- **Web Audio API** (Sound)

## How to Run

1. Simply open the demo in Github: [cahya-wirawan/minion-solitaire](https://cahya-wirawan.github.io/minion-solitaire)

Or:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/cahya-wirawan/minion-solitaire.git
   cd minion-solitaire
   ```

2. **Open `index.html`:**
   Simply open the `index.html` file in any modern web browser. No build process or backend server is required.
   
   *Note: Some browsers might restrict local file access for certain resources. If you encounter issues, consider running a simple local server:*

   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (http-server)
   npx http-server .
   ```
   Then navigate to `http://localhost:8000`.

## Credits

- Based on the classic [English Peg Solitaire puzzle](https://en.wikipedia.org/wiki/Peg_solitaire).
- Character design inspired by the *Despicable Me* franchise.

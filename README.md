<svg width="100" height="100" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
  <rect width="100" height="100" rx="15" fill="#6366f1" />
  
  <line x1="33" y1="10" x2="33" y2="90" stroke="white" stroke-width="2" opacity="0.3"/>
  <line x1="66" y1="10" x2="66" y2="90" stroke="white" stroke-width="2" opacity="0.3"/>
  <line x1="10" y1="33" x2="90" y2="33" stroke="white" stroke-width="2" opacity="0.3"/>
  <line x1="10" y1="66" x2="90" y2="66" stroke="white" stroke-width="2" opacity="0.3"/>

  <text x="18" y="25" fill="white" font-family="sans-serif" font-weight="bold" font-size="16">
    5
    <animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite" />
  </text>
  <text x="50" y="58" fill="white" font-family="sans-serif" font-weight="bold" font-size="16" text-anchor="middle">
    9
    <animate attributeName="opacity" values="0;1;0" dur="2s" begin="0.5s" repeatCount="indefinite" />
  </text>
  <text x="75" y="85" fill="white" font-family="sans-serif" font-weight="bold" font-size="16">
    2
    <animate attributeName="opacity" values="0;1;0" dur="2s" begin="1s" repeatCount="indefinite" />
  </text>
</svg>


# 🧩 Sudoku Pro - Mobile Web Edition

A sleek, lightweight, and high-performance Sudoku game optimized specifically for mobile browsers. Featuring a dual-thumb navigation system, instant feedback, and local record tracking.

## 🚀 Features

* **Mobile-First Design:** Custom layout optimized for portrait mode and thumb accessibility.
* **Dual Number Pads:** Symmetrical input controls allow for comfortable play with either hand.
* **Intelligent Highlighting:** Automatically highlights rows, columns, and selected cells for better focus.
* **Real-time Validation:** Instant visual feedback (shake animation and color cues) when a wrong number is entered.
* **Adaptive Difficulty:** Choose between **Easy**, **Medium**, and **Hard** modes.
* **Record Tracking:** Locally saves your top 10 fastest times and difficulty levels.
* **Audio Feedback:** Retro-style synthesized sound effects for taps, errors, and victories.

## 🛠️ Built With

* **HTML5 & CSS3:** Semantic structure and modern CSS variables for easy theming.
* **Vanilla JavaScript:** Lightweight game logic with no external dependencies or frameworks.
* **Web Audio API:** Real-time sound synthesis for a tactile gaming feel.
* **Google Fonts:** Utilizes 'Poppins' for a clean, modern aesthetic.

## 📱 How to Play

1. **Select a Difficulty:** Use the dropdown at the top to set your challenge level.
2. **Start Game:** Tap "New" to generate a unique, solvable Sudoku grid.
3. **Select a Cell:** Tap any empty square on the 9x9 grid.
4. **Input Numbers:** Use the number pads at the bottom.
* **Left/Right Pads:** Numbers 1–9.
* **Erase:** Use the "ERASE" button to clear a mistake.


5. **Win:** Fill the entire grid correctly to stop the timer and save your record!

## 🔧 Technical Setup

To run this project locally, you don't need a server.

1. Copy the code into a file named `index.html`.
2. Open `index.html` in any modern web browser (Chrome, Safari, or Firefox).
3. For the best experience, open it on a mobile device or use the "Inspect Element" mobile emulator in your desktop browser.

## 📜 License

This project is open-source. Feel free to modify the colors, logic, or layout to suit your own style!

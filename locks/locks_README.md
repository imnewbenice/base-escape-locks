
# 🔐 Escape Room Locks – Instruction Guide

Welcome to the `/locks/` folder! This is where all your individual escape room puzzles live. Each `.html` file is a separate lock page. You can customize each one with your own logic, visuals, clues, or answers.

This guide explains what each file does and where to make edits.

---

## ✅ How to Use These Files

1. Open any `.html` file inside the `/locks/` folder.
2. Edit the placeholder text, puzzle logic, or answer key.
3. Save and preview in a browser to test the lock.
4. Upload your changes to GitHub or your hosting environment.

---

## 🔢 keypad-lock.html

- A number pad for entering a 4-digit code.
- Change the answer in the JavaScript:
  ```js
  const CORRECT_CODE = "1234";
  ```
- Replace clue image or instructions in the body area.

---

## 🧭 directional-lock.html

- Students click arrow buttons to enter a directional sequence.
- Change the pattern here:
  ```js
  const CORRECT_SEQUENCE = "↑→↓←";
  ```

---

## 🎨 color-sequence-lock.html

- Students click colored shapes to enter a color code.
- Each color is tied to a specific shape (e.g. star = orange).
- Update the correct answer:
  ```js
  const CORRECT_PATTERN = [
    { color: 'red', shape: 'circle' },
    { color: 'blue', shape: 'square' },
    { color: 'yellow', shape: 'triangle' },
    { color: 'orange', shape: 'star' }
  ];
  ```

---

## 🔠 anagram-lock.html

- Drag-and-drop letter tiles to unscramble a word.
- Change the word here:
  ```js
  const CORRECT_WORD = "LEMON";
  ```

---

## 🧩 drag-to-slot-lock.html

- Drag symbols into the correct order.
- Change the sequence here:
  ```js
  const CORRECT_ORDER = ["🌞", "🌳", "🏠", "🚗"];
  ```

---

## 🧮 logic-grid-lock.html

- Toggle a row of switches to match a logic pattern.
- Edit the correct toggle pattern here:
  ```js
  const CORRECT_PATTERN = [1, 0, 1, 1, 0, 0];
  ```

---

## 🧷 multi-lock-panel.html

- Checks whether all other locks have been solved.
- No puzzle on this page — just reads saved values like:
  ```js
  localStorage.getItem("keypadSolved") === "true"
  ```

---

## 🔍 hidden-object-lock.html

- A hidden clickable area on an image.
- Use `<div class="hotspot">` to create hidden or decoy zones.

---

## 🎉 room-escaped.html

- Final celebration page.
- You can add confetti, victory sounds, or redirect options here.

---

## 🎨 How to Change the Look or Sound

If you're trying to change how something looks, and you don't see it in the lock file, here's where to go:

### 🖼️ `/assets/` folder

- Contains shared images and sounds.
- Replace these to customize:
  - `placeholder-image.png`
  - `correct-answer-sound.mp3`
  - `incorrect-answer-sound.mp3`

### 🎨 `theme.css`

This file controls:
- Font sizes and button styles
- Colors and spacing
- Mobile responsiveness
- Shared styles like `.unlocked`, `.lockedout`

---

## 📄 Final Tips

- Sound effects are included with every lock. To replace them, go to `/assets/`.
- Most answer keys are in JavaScript — search for `const CORRECT_...`
- Preview by double-clicking a file or using Live Server in VS Code.

Happy escaping! 🧩

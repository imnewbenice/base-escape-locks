
# 🚪 start.html – Escape Room Launch Page

This is your public-facing **starting page** for students to enter the escape room experience.

---

## ✅ What It Does

- Presents a simple intro message
- Includes a “Begin Escape Room” button that links to the first puzzle
- Hides all lock links so students only begin when they’re ready
- Keeps the editing/test page (`index.html`) separate for teachers or coders

---

## 🎯 How to Customize It

### Edit the intro message:
Find the paragraph in `start.html`:
```html
<p class="directions">
  You and your team are locked in. Solve the puzzles to escape...
</p>
```
Change the story, tone, or add group/team instructions.

---

### Change the starting lock:
```html
<a href="locks/keypad-lock.html"><button>Begin Escape Room</button></a>
```
If you want students to start with a different lock, just change the `href` to another file in the `/locks/` folder.

---

### Use this for immersive flow:
- This page is meant to be the **only thing students see at first**
- You can hide all other links (or protect them using logic later)
- Use `start.html` as your GitHub Pages default start page if you don’t want to show `index.html`

---

## 🧱 Placeholder Hooks Included (but hidden)

The HTML includes hidden comment blocks so you can expand this later with:

- 🎵 Intro music
- 👤 Group name input
- 🖼️ Background image or animation
- 🧠 Logic to unlock puzzles one-by-one

You’ll see these lines in the code:
```html
<!-- <audio src="assets/intro-theme.mp3" autoplay loop style="display: none;"></audio> -->
<!-- <img src="assets/escape-background.png" style="display: none;"> -->
```

---

## 🔗 Publishing

To make this your default homepage:
1. Rename `start.html` to `index.html`
2. Or in GitHub Pages, manually set `/start.html` as your launch link

---

This file is meant to give structure without limitations. Use it your way!

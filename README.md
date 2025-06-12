
# 🔐 Escape Room Base Template

This is a minimal, beginner-friendly starter kit for building your own web-based escape room using HTML, CSS, and JavaScript.

---

## 📁 Project Structure

| Folder/File       | Purpose                                  |
|-------------------|-------------------------------------------|
| `/locks/`         | Each lock/puzzle page lives here         |
| `/assets/`        | Shared images and sound effects          |
| `index.html`      | Homepage linking to all locks            |
| `theme.css`       | Shared layout and styling                |
| `README.md`       | This instruction guide                   |

---

## 🚀 How to Deploy on GitHub Pages

1. **Create a GitHub repo**  
   Name it something like `escape-room` or `my-escape`.

2. **Upload all files to the repo root**  
   Make sure `index.html` is at the top level (not inside a folder).

3. **Enable GitHub Pages:**
   - Go to **Settings → Pages**
   - Under "Source", choose:
     - Branch: `main`
     - Folder: `/ (root)`
   - Click **Save**

4. **Your site will be live at:**  
   ```
   https://your-username.github.io/your-repo-name/
   ```

   Example:
   ```
   https://jturnbull.github.io/escape-room/
   ```

---

## ✏️ How to Customize

1. **Edit locks** in `/locks/` to change puzzles, logic, and clues.
2. **Replace images/sounds** in `/assets/`
3. **Adjust layout/colors/fonts** in `theme.css`

Each lock has clear comments to help you find and update:

- Puzzle instructions
- Correct answers
- Feedback text
- Sounds and visuals

---

## 🛠 Tips

- Try editing with [VS Code](https://code.visualstudio.com/)
- Preview locally using Live Server or by dragging `index.html` into a browser
- Fork the repo to experiment freely

---

Happy escaping! 🧩

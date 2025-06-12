
# 📍 index.html – Escape Room Starting Page

This is the homepage students see when they visit your GitHub Pages site.

---

## ✅ What It Does
- Introduces the escape room
- Displays instructions
- Links to all puzzle pages in the `/locks/` folder

---

## 🔗 Want a Sequential Lock Flow?

You can guide students through the puzzles one-by-one like a real escape room.

### How To:

1. Remove some lock links from `index.html`
2. Instead, place a "Next Puzzle" link at the bottom of each lock page:
   ```html
   <a href="directional-lock.html">Next Lock</a>
   ```

3. On the last page (`room-escaped.html`), celebrate their escape!

---

## 🔐 Optional Gatekeeping Ideas:
- Require group name before starting
- Hide links until previous puzzle is solved (via localStorage or teacher unlock)

---

This file can be edited freely to match your escape room theme and flow.

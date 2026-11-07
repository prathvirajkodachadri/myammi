# For Ammi ❤️ | Anniversary Treasure Hunt

A romantic interactive anniversary scavenger hunt web application created with love by **Prathviraj** for **Ammi**.

Designed and optimized to run smoothly on Android mobile phones (including the **OnePlus Nord CE 3**), this experience guides Ammi through 6 real-life gifts with interactive clues, audio chimes, animated SVG artwork, and a suspenseful final reveal.

---

## ✨ Features & Storyline

1. **Crafted for Mobile (OnePlus Nord CE 3 & Android)**:
   - Screen-fit responsive layout (`max-width: 440px`) designed for 20:9 tall aspect ratio viewports (~392×872px).
   - High-contrast velvet wine (`#1a080d`) and champagne gold typography.
   - Touch-optimized buttons, full Kannada Unicode font fallback, and clean mobile keyboard interaction.

2. **The 6 Gifts Treasure Hunt**:
   - **Welcome Screen**: Anniversary celebration date (*November 18*), screen recording reminder, beating heart artwork, and journey start button.
   - **Stage 1 (Call Arpitha)**: Ringing phone illustration & clue to call Arpitha for password `LOVE01` to unlock the journey.
   - **Stage 2 (Gift 01 • Studio Room)**: Studio room vanity mirror illustration & clue for password `LOVE02`.
   - **Stage 3 (Gift 02 • Hair Clips)**: Blooming floral hair accessory illustration & clue for password `LOVE03`.
   - **Stage 4 (Gift 03 • Diwan Cot)**: Silk scrunchie illustration & clue for password `LOVE04`.
   - **Stage 5 (Gift 04 • Shoe Rack)**: Shoe rack clue & password `LOVE05`.
   - **Stage 6 (Gift 05 • Pooja Room)**: Pooja room clue & password `LOVE06`.
   - **Final Screen (Gift 06 • The Grand Mystery)**: Directs Ammi to the **Musical Keyboard Backside Room** where a special mystery box awaits. When she physically opens the box in that room, she discovers the grand anniversary surprise!

3. **Stage-by-Stage Animated Gift Box Unboxing**:
   - Every unlocked stage pops open a 3D animated gift box with flying confetti hearts, congratulatory message, and sound chime.

4. **100% Offline & Zero External Dependencies**:
   - Pure inline HTML, CSS, bespoke inline SVG illustrations, and Web Audio API synthesizer for romantic background music box and chimes. No external mp3 files or CDN font files that could fail on slow mobile networks.

---

## 🛠️ Customization

All passwords, locations, and celebration messages can be customized easily in `index.html` inside the `CONFIG` object:

```javascript
const CONFIG = {
  // Passwords for Stages 1 to 6 (case-insensitive)
  passwords: {
    1: "LOVE01", // Spoken by Arpitha
    2: "LOVE02", // Studio room mirror
    3: "LOVE03", // Hair clips
    4: "LOVE04", // Diwan cot
    5: "LOVE05", // Shoe rack
    6: "LOVE06"  // Pooja room
  }
};
```

---

## 🚀 Running Locally & Testing

You can run any local static file server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js npx
npx serve .
```

Open `http://localhost:8000` in your mobile or desktop browser.

---

## 🌐 Deploying to GitHub Pages

1. Push this repository to GitHub: `https://github.com/prathvirajkodachadri/myammi`
2. Go to **Settings** > **Pages**.
3. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
4. Choose the `main` branch (or your preferred branch) and `/ (root)` folder, then click **Save**.
5. Your website will be live at `https://prathvirajkodachadri.github.io/myammi/` ❤️

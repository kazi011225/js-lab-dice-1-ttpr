<p align="center">
  <img src="https://hhassan1230.github.io/CodePenImgs/images/dicebackdropmini.png?auto=format&fit=crop&w=1200&q=80" alt="Colorful dice tumbling" width="600">
</p>

# js-lab-dice-1-ttpr · Dice Roller

Welcome to your first JavaScript lab for the **Tech Talent Pipeline Residency**!  
You’ll wire up a _virtual die_: every time the user clicks **Roll**, a random value between **1** and **6** should appear on-screen.

---

## Learning goals

1. Generate integers in any range with **`Math.random()`** + **`Math.floor()`**
2. Work with a simple JavaScript **object** (`dice`) that contains both data and behavior
3. Attach a **click handler** and update the DOM with JavaScript

---

## Starter files

```markdown
# js-lab-dice-1-ttpr · Dice Roller

Welcome to your first JavaScript lab for the **Tech Talent Pipeline Residency**!  
You’ll wire up a _virtual die_: every time the user clicks **Roll**, a random value between **1** and **6** should appear on-screen.

---

## Learning goals

1. Generate integers in any range with **`Math.random()`** + **`Math.floor()`**
2. Work with a simple JavaScript **object** (`dice`) that contains both data and behavior
3. Attach a **click handler** and update the DOM with JavaScript

---

## Starter files
```

.
├── index.html # markup for the button & placeholder
└── main.js # dice object and event logic (edit this)

````

Open **`index.html`** in a browser and **`main.js`** in your editor.
Look for the **“Write Code Here”** comment inside the `roll` method.

---

## Your task

Inside `dice.roll`:

1. Generate a random integer **≥ 1** and **≤ this.sides**.
2. Assign it to the existing `randomNumber` variable.

> Pattern: `Math.floor(Math.random() * max) + min`

Clicking the button should now show a different number (1-6) each time.

---

## Steps

1. **Fork** this repo to your GitHub account.
2. **Clone** your fork and `cd` into it.
3. Complete **`main.js`**.
4. Commit & push:
   ```bash
   git add main.js
   git commit -m "Implement random dice roll"
   git push
````

5. Open a **Pull Request** to submit your solution.

---

## Running the lab locally

### 1. With VS Code (recommended)

1. Open the repo folder in VS Code
   ```bash
   code path/to/js-lab-dice-1-ttpr
   ```
2. Install the **Live Server** extension if you don’t already have it.
3. Right-click **index.html** → **“Open with Live Server.”**  
   A browser tab will launch at something like `http://127.0.0.1:5500/index.html`.
4. Edit **main.js** and save—Live Server auto-refreshes the page so you can see changes instantly.

### 2. From the terminal only

1. `cd` into the repo:
   ```bash
   cd path/to/js-lab-dice-1-ttpr
   ```
2. Spin up a quick local server (pick one):

   - **Node users:**
     ```bash
     npx http-server .
     # → defaults to http://127.0.0.1:8080
     ```
   - **Python 3:**
     ```bash
     python -m http.server 8080
     # omit the port to use the default 8000
     ```

3. Open your browser to the printed URL (e.g. `http://localhost:8080`).
4. Click **Roll** and watch the dice values update.

> **Why not just double-click `index.html`?**  
> Modern browsers sometimes restrict JavaScript modules or fetch calls when a page is opened via the `file://` protocol. Serving the files over HTTP avoids those issues and mirrors real-world hosting.

---

## Stretch goals (optional)

- Use the images in the img folder to represent a face side.

---

## Resources

- [MDN — `Math.random()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)
- [MDN — `onclick`](https://developer.mozilla.org/en-US/docs/Web/API/GlobalEventHandlers/onclick)

Happy rolling—commit early & often!


## 🌟 Goal

Each teammate will:

* Create a **personal page** (e.g., `harsh.html`, `alice.html`, etc.)
* Add a link to their page inside the shared file **`main.html`**
* Create a **Pull Request (PR)** to merge their branch into `main`
* Practice resolving **merge conflicts** together

---

## 🪼 Steps to Follow

### 1️⃣ Make sure you’re on the latest `main` branch

```bash
git checkout main
git pull origin main
```

---

### 2️⃣ Create a new branch for your personal page

```bash
git checkout -b yourname-personal-page
```

Example:

```bash
git checkout -b harsh-personal-page
```

---

### 3️⃣ Create your personal page

```bash
touch yourname.html
```

Then open it and add simple content:

```html
<h1>Hi, I’m [Your Name]!</h1>
<p>This is my personal page.</p>
```

---

### 4️⃣ Edit the shared `main.html`

Add a link to your personal page:

```html
<a href="yourname.html">[Your Name]’s Page</a><br>
```

---

### 5️⃣ Save, stage, and commit your changes

```bash
git add .
git commit -m "Added my personal page and linked it in main.html"
```

---

### 6️⃣ Pull the latest version before pushing

```bash
git pull origin main
```

If you see merge conflicts:

1. Open the conflicted file(s)
2. Keep your section and your teammates’ changes
3. After fixing, run:

   ```bash
   git add .
   git commit -m "Resolved merge conflicts"
   ```

---

### 7️⃣ Push your branch to GitHub

```bash
git push origin yourname-personal-page
```

---

### 8️⃣ Create a Pull Request (PR)

1. Go to your GitHub repository in your browser.
2. You’ll see a banner:

   > “yourname-personal-page had recent pushes — Compare & Pull Request”
3. Click **Compare & Pull Request**.
4. Add a short description (e.g.):

   ```
   Added my personal page and linked it in main.html
   ```
5. Click **Create Pull Request**.

---

### 9️⃣ Review and Merge

* Have a teammate review your PR and merge it into `main`.
* If conflicts appear, resolve them together in GitHub’s web editor or locally.

---

### 🔠 Sync your local repository

After your PR is merged:

```bash
git checkout main
git pull origin main
```

Now you’ll see your page and your teammates’ pages linked in **`main.html`** 🎉

---

## 🗁 Example Project Structure

```
team-project/
│
├── main.html
├── harsh.html
├── alice.html
├── bob.html
└── README.md
```

---

## 💡 Notes

* Don’t edit directly on the `main` branch — always use your own branch.
* Always **pull before you push** to reduce merge conflicts.
* The goal is to **practice collaboration** and **get comfortable resolving conflicts**.

---

👩‍💻 **End Goal:**
By the end of this task, your repository will include everyone’s personal pages, merged together cleanly via Pull Requests!

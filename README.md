# 🌟 Student Contributor Showcase

Welcome to our first collaborative GitHub project! In this activity, every student will contribute their own profile card to this webpage using Git branches and GitHub Pull Requests.

---

## 🎯 Goal
Learn the standard industry workflow for contributing to open-source and team projects:
1. **Branching** (working safely in your own copy)
2. **Committing** (saving your work)
3. **Pushing** (uploading to GitHub)
4. **Pull Request (PR)** (requesting to merge your work into the main project)

---

## 🛠️ Step-by-Step Instructions

### Step 1: Clone the Repository
Open your terminal (or Git Bash) and run:
```bash
git clone https://github.com/chathuka-official/Github-Practicle.git
cd Github-Practicle
```

---

### Step 2: Create Your Own Branch
Never work directly on the `main` branch. Create a new branch named after yourself:
```bash
git checkout -b student-yourname
```
*(Example: `git checkout -b student-kasun`)*

---

### Step 3: Add Your Profile Card
1. Open [index.html](file:///Users/lahiru/Desktop/Github-Practicle/index.html) in your editor (VS Code, etc.).
2. Find the comment:
   ```html
   <!-- STUDENTS: ADD YOUR CARD BELOW THIS LINE -->
   ```
3. Copy and paste the snippet below, then fill in your details:

```html
<div class="card">
    <div class="card-avatar">🚀</div> <!-- Pick any emoji -->
    <h3 class="card-name">Your Full Name</h3>
    <span class="card-role">Student / Developer</span>
    <p class="card-bio">One sentence about your interests or goals.</p>
    <div class="card-tags">
        <span class="tag">HTML</span>
        <span class="tag">CSS</span>
        <span class="tag">Python</span>
    </div>
    <a href="https://github.com/your-username" target="_blank" class="card-link">View GitHub &rarr;</a>
</div>
```

*(Optional: open [styls.css](file:///Users/lahiru/Desktop/Github-Practicle/styls.css) to customize your card color if you want!)*

---

### Step 4: Save, Commit, and Push

Run the following commands in your terminal:

```bash
# 1. Check your changes
git status

# 2. Stage the changes
git add index.html

# 3. Commit with a meaningful message
git commit -m "Add profile card for [Your Name]"

# 4. Push your branch to GitHub
git push -u origin student-yourname
```

---

### Step 5: Open a Pull Request (PR) on GitHub
1. Go to the repository page on GitHub: [https://github.com/chathuka-official/Github-Practicle](https://github.com/chathuka-official/Github-Practicle)
2. You will see a yellow banner: **"student-yourname had recent pushes — Compare & pull request"**.
3. Click **"Compare & pull request"**.
4. Add a short description (e.g., *"Added my profile card to index.html"*).
5. Click **"Create pull request"**.

---

### Step 6: Watch the Magic Happen!
Once the instructor reviews and merges your pull request, pull the updated code back to your computer to see everyone's cards merged together!

```bash
git checkout main
git pull origin main
```
Double-click `index.html` in your file browser to see the entire class wall! 🎉

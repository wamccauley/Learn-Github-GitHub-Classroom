# 🎓 Learn GitHub & GitHub Classroom

> **Assignment:** Sample Intro Assignment — Getting Started with GitHub Classroom  
> **Course:** Computer Science / CTE  
> **Points:** 10 pts

---

## 📋 Overview

Welcome to your first GitHub Classroom assignment! In this activity, you will:

1. **Accept** the assignment through GitHub Classroom
2. **Clone** your personal assignment repository to your computer using VS Code
3. **Edit** a file to complete the assignment
4. **Commit** your changes with a meaningful message
5. **Push** your work back to GitHub to turn it in

This assignment is worth **10 points** and is designed to make sure you know how to use GitHub as your digital "turn-in box" for the rest of this course.

---

## 🛠️ Step 1 — Accept the Assignment

1. Click the **GitHub Classroom assignment link** provided by your teacher.
2. Sign in to GitHub with your school Google account.
3. Click **Accept this assignment**.
4. GitHub will create a **personal copy** of this repository just for you. Wait for the green checkmark ✅, then click the link to open your repo.

> 💡 **Your repo URL will look like:**  
> `https://github.com/[org]/learn-github-github-classroom-[your-username]`

---

## 🖥️ Step 2 — Set Up Your Folder Structure on the V: Drive

Before you clone, you need to create the correct folder on **your personal network drive (V: Drive)**. This keeps all your work organized across all your CTE courses.

### 📂 Finding Your V: Drive

1. Open **File Explorer** (the folder icon on your taskbar).
2. Click **This PC** in the left panel.
3. Look for a drive labeled **`firstinitiallastname`** — this is your **V: Drive** (e.g., `jsmith` for John Smith).
4. Double-click it to open your personal network drive.

> ⚠️ If you do not see your V: Drive, raise your hand and let your teacher know.

---

### 📁 Build Your Folder Structure

You will organize your repos inside your V: Drive by **course**, then by **unit/lesson/activity**. This way you always know exactly where your work is.

#### 📅 Your Course Lineup by Year

| School Year | Courses |
|-------------|--------|
| **This Year (2025–26)** | CSE · CSP · Cyber |
| **Next Year (2026–27)** | IT Fundamentals · CSA · Cyber |
| **2027–28** | IT Fundamentals · C# · Cyber |
| **2028–29** | IT Fundamentals · CSP · Cyber |

---

#### 📁 Folder Structure Options

Choose the structure that matches how your teacher has organized the course. Use **one consistent structure per class** — don’t mix them.

**Option A — Unit → Lesson → Activity** *(most organized, recommended for larger courses)*
```
V:\
└── CSE\
    └── Unit1-Programming-Basics\
        └── Lesson1-Variables\
            └── Activity1-HelloWorld\   ← clone repo here
```

**Option B — Lesson → Activity** *(good for shorter courses)*
```
V:\
└── CSP\
    └── Lesson3-Data\
        └── Activity2-Spreadsheets\   ← clone repo here
```

**Option C — Activity Only** *(use only if your teacher directs you to)*
```
V:\
└── Cyber\
    └── Activity5-Phishing-Lab\   ← clone repo here
```

> 💡 **Naming Tips:**
> - Use the **course abbreviation** as the top-level folder (e.g., `CSE`, `CSP`, `Cyber`, `CSA`, `IT-Fundamentals`, `CSharp`)
> - No spaces in folder names — use a **dash `-`** instead (e.g., `Unit1-Intro` not `Unit 1 Intro`)
> - Be **consistent** — use the same naming style every time so you can find your work fast

---

#### 📅 Full Example — This Year’s Courses (2025–26)

```
V:\
├── CSE\
│   ├── Unit1-Intro\
│   │   ├── Lesson1-What-Is-CS\
│   │   │   └── Activity1-GitHub-Setup\   ← THIS assignment goes here
│   │   └── Lesson2-Algorithms\
│   │       └── Activity1-Flowcharts\
│   └── Unit2-Programming\
│       └── Lesson1-Variables\
│           └── Activity1-HelloWorld\
├── CSP\
│   ├── Unit1-Digital-Information\
│   │   └── Lesson1-Binary\
│   │       └── Activity1-Number-Systems\
│   └── Unit2-The-Internet\
│       └── Lesson1-How-Internet-Works\
│           └── Activity1-Network-Diagram\
└── Cyber\
    ├── Unit1-Cybersecurity-Basics\
    │   └── Lesson1-Threats\
    │       └── Activity1-Threat-Identification\
    └── Unit2-Defense\
        └── Lesson1-Firewalls\
            └── Activity1-Firewall-Lab\
```

---

## 🖥️ Step 3 — Clone the Repository in VS Code

Now that your folder is created, you’ll clone the repo **directly into it**.

1. Open **VS Code**.
2. Open the **Command Palette** with `Ctrl+Shift+P` (Windows) or `Cmd+Shift+P` (Mac).
3. Type `Git: Clone` and press **Enter**.
4. Paste your repository URL (from Step 1) and press **Enter**.
5. When asked where to save, **navigate to your V: Drive** and select the correct activity folder you just created.
6. Click **Select as Repository Destination**.
7. Click **Open** when VS Code asks if you want to open the cloned repository.

> ✅ Your repo is now saved in the right place on your V: Drive and will be there every time you log in at school.

You should now see the project files in the **Explorer panel** on the left side of VS Code.

---

## ✏️ Step 4 — Complete the Assignment

1. In VS Code, open the file called **`my_intro.md`** (found in the Explorer panel).
2. Follow the instructions inside that file to fill in your answers.
3. Save the file when you are done (`Ctrl+S` or `Cmd+S`).

---

## 💾 Step 5 — Commit Your Changes

A **commit** is like saving a snapshot of your work with a note describing what you did.

1. Click the **Source Control** icon in the left sidebar (it looks like a branch `⑂`).
2. You should see `my_intro.md` listed under **Changes**.
3. Click the **`+`** icon next to the file to **stage** it.
4. In the **Message** box at the top, type a commit message like:  
   `Complete intro assignment - [Your Name]`
5. Click the **✔ Commit** button (checkmark).

---

## 🚀 Step 6 — Push to GitHub (Turn It In!)

Pushing sends your committed changes back to GitHub — this is how you **turn in your assignment**.

1. After committing, click the **Sync Changes** button (🔄) that appears, OR
2. Open the Command Palette (`Ctrl+Shift+P`) → type `Git: Push` → press **Enter**.
3. Go back to your GitHub repository in the browser and refresh — you should see your updated `my_intro.md` file. 🎉

> ✅ **Your assignment is submitted when your changes appear on GitHub.**  
> Your teacher can see your submission directly in GitHub Classroom.

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `README.md` | This instruction file |
| `my_intro.md` | ⬅️ **The file you need to edit and submit** |

---

## ❓ Troubleshooting

| Problem | Solution |
|---------|----------|
| VS Code doesn’t show "Git: Clone" | Make sure Git is installed: [git-scm.com](https://git-scm.com) |
| Asked for GitHub login in VS Code | Sign in with your GitHub username and password or token |
| Push is rejected | Make sure you accepted the assignment first so you own the repo |
| Can’t find your repo | Check GitHub Classroom dashboard or ask your teacher for the link |
| V: Drive not showing in This PC | Raise your hand — your teacher will reconnect your network drive |
| Cloned to the wrong folder | Right-click the folder in File Explorer, delete it, and re-clone to the correct location |

---

## 🏆 Grading Rubric

| Criteria | Points |
|----------|--------|
| `my_intro.md` file is present and edited | 4 pts |
| All questions answered completely | 4 pts |
| Commit message is descriptive (not "update" or "asdf") | 2 pts |
| **Total** | **10 pts** |

---

*Questions? Raise your hand or email your teacher!*

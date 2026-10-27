# FOSS-101 Contribution Guide

Welcome to the **FOSS-101** repository! Follow the step-by-step instructions below to make your contribution.

---

## Instructions

### 1. Fork the Repository
1. Navigate to the top-right corner of this repository on GitHub.
2. Click the **Fork** button to create a copy of this repository under your personal GitHub account.
3. Clone your forked repository to your local system:
   ```bash
   git clone https://github.com/<your-username>/FOSS-101.git
   cd FOSS-101
   ```

---

### 2. Create and Switch to a New Branch
> [!IMPORTANT]
> **Do not make changes directly on the `main` branch.** Always create and switch to a new branch for your work.

Create and check out a new branch (use your roll number as the branch name):
```bash
git checkout -b <your-roll-no>
```

---

### 3. Create a File with Your Roll Number
1. Identify the folder corresponding to your branch/department:
   - `CS/` - Computer Science
   - `CSAI/` - Computer Science & Artificial Intelligence
   - `CSB/` - Computer Science & Business Systems
   - `CSIT/` - Computer Science & Information Technology
2. Navigate to your department directory and create a new file named with your roll number (e.g., `<roll_no>.txt` or `<roll_no>.md`):
   ```bash
   # Example for CS branch with roll number LCS20260XX:
   touch CS/LCS20260XX.txt
   ```
3. Add your details (such as your Name, Roll Number, and Department) inside the file. You can refer to `example.txt` in your branch directory for the reference format:
   ```text
   Name: Jane Doe
   Roll Number: LCS2026001
   Branch: Computer Science (CS)
   GitHub Username: janedoe
   ```

---

### 4. Commit the Changes
1. Check the status and stage your new file:
   ```bash
   git status
   git add <branch-dir>/<roll_no>.txt
   ```
2. Commit the changes with a clear commit message:
   ```bash
   git commit -m "Add roll number <roll_no>"
   ```

---

### 5. Push Changes to GitHub
Push your local branch and committed changes to your forked repository on GitHub:
```bash
git push -u origin <your-roll-no>
```

---

### 6. Send a Pull Request (PR)
1. Go to the original **FOSS-101** repository on GitHub.
2. You will see a banner prompt: **"Compare & pull request"**. Click on it.
   *(Alternatively, go to the **Pull requests** tab and click **New pull request**)*.
3. Verify that:
   - **Base repository:** Original repository (`main` branch)
   - **Head repository:** Your fork (`<your-roll-no>` branch)
4. Provide a title (e.g., `Add roll number <roll_no>`) and a brief description.
5. Click **Create pull request** to submit your contribution for review.


Lookin forwarward to your PR.

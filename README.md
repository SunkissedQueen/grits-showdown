# 🥣 The Great Grits Showdown 🧂 🍯 🚫

**Welcome to the Git Kitchen Collaboration Challenge!**

This project helps us practice using Git and GitHub together while having a little fun. Each participant will choose their side in the Great Grits Debate and explain why.

---

## 🍳 Instructions

0. Get to the right folder
   ```bash
   pwd            # print where you are
   ls             # see files/folders here
   git clone https://github.com/SunkissedQueen/grits-showdown.git   # copy the remote project onto your local machine
   cd grits-showdown  # open the project locally
   ```
1. Make sure main is up to date.
   ```bash
   git checkout main
   git pull origin main
   ```
2. Create a feature branch (so you don’t touch main)
   ```bash
   git checkout -b feature-yourname
   ```
3. Open the project in vs code
   ```bash
   code .
   ```
4. Select the applicable file (grits.md)
5. Add your entry within the correct category using this format:

   ```bash
   - [Your Name] — [Savory, Sweet, or No Grits] — [One-sentence reason]
   ```

   `Example: - Charlean — Savory — Because my tastebuds only guide me to deliciousness!`

6. Complete work → check status → stage → commit

   ```bash
   git status
   git add README.md
   git commit -m "Add [Your Name]'s grits entry"
   git push origin feature-yourname
   ```

7. Create a Pull Request on GitHub to merge your entry.

   ```bash
   a. Go to your repository on GitHub.

   b. Click “Compare & pull request.”

   c. Add a title and short description.

   d. Click “Create pull request.”

   e. Review changes under “Files changed.”

   f. Click “Merge pull request.”

   g. Click “Confirm merge.”

   h. Click “Delete branch.”
   ```

8. Delete stale branch on local machine

   ```bash
   git checkout main
   git pull origin main
   git branch -d feature-yourname
   ```

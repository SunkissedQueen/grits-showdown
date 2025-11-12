# 🥣  The Great Grits Showdown 🧂 🍯 🚫
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
3. Select the applicable file (README.md)
4. Add your entry below in the correct category using this format:

    ```bash
    - `[Your Name] — [Savory, Sweet, or No Grits] — [One-sentence reason]`
    ```
    `Example: - Charlean — Savory — Because my tastebuds only guide me to deliciousness!`
4. Complete work → check status → stage → commit

    ```bash
    git status
    git add README.md
    git commit -m "Add [Your Name]'s grits entry"
    git push origin feature-yourname
    ```
5. Create a Pull Request on GitHub to merge your entry.

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
---

## 🍳 Great Grits Debate

***(Add your name and reason below the appropriate category)***

### 🧂 Team Savory  
_Because butter, cheese, and salt make everything better._

- Charlean — Savory — Because my tastebuds only guide me to deliciousness!
- Yali — Savory — Savory is just the best

### 🍯 Team Sweet  
_Because sugar, syrup, and cream belong on grits too._


### 🚫 Team No Grits  
_Because texture is everything and this one isn't for everyone._

---
## 🤔 Reflection

Once everyone has merged their entry, answer this question:

>What made it easier (or harder) to work together compared to the Google Doc chaos?

### 🎗️ Remember

_Pull before you push, taste before you season._

_Keep the kitchen clean and commit with confidence!_

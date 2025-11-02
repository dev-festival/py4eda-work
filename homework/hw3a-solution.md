# HW3A Solution - Git and Version Control 

## Part 1: Repository Cloning

I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to `~/insy6500/class_repo`.

### Key Commands Used 

- `git clone <url>` - Create local copy of remote repository
- `git log` - View commit history
- `git remote -v` - Check remotre repository connections

## Part 2 Porfolio Repository Creation

I created my personal course repository with:

- Professional README.md describing the project
- Proper .gitignore to exclude unnecessary files
- Organized directory structure for homework, projects, and notes

### Understanding Git Workflow

The three-stage workflow:

1. Working Directory: Where I edit files
2. Staging Area: Where I prepare commits with `git add`
3. Repository: Where commits are permanently stored with `git commit`

## Part 3: GitHub Publishing

Successfully published repository to GitHub:

- Used `git remote add origin` to connect local repo to Github
- Used `git push -u origin main` to upload commits
- Verified all files and commits are visible on GitHub

### The Remote Connection

My local repository is now connected to GitHub:

- `git remote -v` shows the remote URL
- `git push` will send my commits to github
- `git pull` will get updates from GitHub (if changes are made on Github)

### Details 

Complete this section with details from your setup: 

- Repository URL: https://github.com/dev-festival/py4eda-work
- Output of `git remote -v`:

```bash
origin  https://github.com/dev-festival/py4eda-work.git (fetch)
origin  https://github.com/dev-festival/py4eda-work.git (push)
(insy6500)
```

- Output of `git log --oneline`:

```bash
a188ef4 (HEAD -> main, origin/main) Correction to README.md
2bf05cc Add hw3a solution document
33f6e9c Initial commit: add README and .gitignore
(insy6500)
```

## Questions

### Reflections

1. 
 - a) Before this assignment I normally versioned my work with a revision table and markers. File names like v1-1 and v1-2 for minor changes and then v1 and v2 for major changes. Something along those lines. Files that I felt were important enough for such versioning usually have a table at the bottom with version numbers, dates, and modified content as well. Git provides the benefit of version history without having a mess of file names. Another advantage of 

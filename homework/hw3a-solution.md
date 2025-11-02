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
a) Before this assignment I normally versioned my work with a revision table and markers. File names like v1-1 and v1-2 for minor changes and then v1 and v2 for major changes. Something along those lines. Files that I felt were important enough for such versioning usually have a table at the bottom with version numbers, dates, and modified content as well. One Benefit of Git is that the notes for revisioning are packed inline with the revision history with the `git commit -m "message"` making it easy to track all changes. Another benefit is that the older versions are always available in the version history and git provides an easy way to access that version history without too much digging throught files. 

b) I currently work off of a lot of SQL files that sprawl in quantity and scope. Sometimes I update existing queries but lose track of whether or not I used that one in an excel or powerbi tool. Git version control, I believe, could help me organize this sprawl a lot better with the verion control and commit messaging. Besides version control, it seems to provide intentionality and structure as well which would help me maintain some better records and documentation for these queries. 

2.
a) It is important to have seperated reference and working directories with seperate security levels so that the files in the reference directory remain intact. If we tried to have a my_repo folder for each student in the class_repo then everyone would be constantly overwriting. If we tried to have seperate folders, then we could also see each others' work which would compromise the integrity. The standalone working repo, sequesters the trials of learning from the class directory at large keeping the class files safe and protecting personal learning environments from other students. 

b) 
For future coursework, I would organize my repositories based on their purpose:
- Group projects: If I'm the group lead, I would create a central repository for the project that all team members can contribute to. If I'm not the lead, I would clone the group's repository to my local machine in a separate location from my individual work to keep things organized.
- Individual assignments: I would keep these in their own separate repository (or repositories) so my personal work stays independent from group projects and doesn't get mixed up.
- Reference materials: I would maintain a separate repository for references, similar to how class_repo works in this class. This keeps important reference materials safe and organized, and I can update them intentionally when needed without accidentally changing them while working on assignments.
This organization helps me keep different types of work separate, makes it easier to find things, and prevents accidental changes to important materials.


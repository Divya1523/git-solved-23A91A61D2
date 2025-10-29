
## Student Information
- Name: Divya Alluri
- Student ID: [YOUR ID]
- Repository: [YOUR REPO URL]
- Date Started: 25 Oct 2025
- Date Completed: 29 Oct 2025

---

## Task Summary
Cloned the instructor’s repository, explored multiple branches, resolved all merge conflicts, performed rebases, cherry-picks, and applied advanced Git workflows to synchronize code across environments.

---

## Commands Used

| Command | Times Used | Purpose |
|----------|-------------|----------|
| git clone | 1 | Clone instructor's repository |
| git checkout | 25+ | Switch between branches |
| git branch | 10+ | View and manage branches |
| git merge | 2 | Merge `dev` and `conflict-simulator` into `main` |
| git add | 30+ | Stage resolved conflicts |
| git commit | 15+ | Commit resolved changes |
| git push | 10+ | Push commits to my repository |
| git fetch | 3 | Fetch updates from remote |
| git pull | 2 | Pull latest changes |
| git stash | 2 | Save temporary work |
| git cherry-pick | 1 | Recover a lost commit |
| git rebase | 1 | Rebase feature branch |
| git reset | 3 | Undo commits (soft/mixed/hard) |
| git revert | 1 | Safely undo a commit |
| git tag | 2 | Create release tags |
| git status | 50+ | Check repo state |
| git log | 30+ | View commit history |
| git diff | 20+ | Compare branch/file differences |
| git reflog | 5 | Recover lost commits |

---

## Conflicts Resolved

### 🔹 Merge 1: main + dev (6 files)

#### Conflict 1: config/app-config.yaml
- **Issue**: Port mismatch — production (8080) vs dev (3000)
- **Resolution**: Unified config with environment-based logic
- **Strategy**: Kept production default, added dev override
- **Difficulty**: Medium
- **Time**: 15 minutes

#### Conflict 2: config/database-config.json
- **Issue**: Database host and SSL differences
- **Resolution**: Added JSON structure for both environments
- **Strategy**: Supported multiple DB profiles
- **Difficulty**: Medium
- **Time**: 10 minutes

#### Conflict 3: scripts/deploy.sh
- **Issue**: Conflicting deployment methods
- **Resolution**: Added `DEPLOY_ENV` condition
- **Strategy**: Dynamic deployment flow
- **Difficulty**: Hard
- **Time**: 20 minutes

#### Conflict 4: scripts/monitor.js
- **Issue**: Different log formats and intervals
- **Resolution**: Used `process.env.NODE_ENV` for control
- **Difficulty**: Medium
- **Time**: 15 minutes

#### Conflict 5: docs/architecture.md
- **Issue**: Separate architecture descriptions
- **Resolution**: Combined both into one document
- **Difficulty**: Easy
- **Time**: 10 minutes

#### Conflict 6: README.md
- **Issue**: Different versions and features
- **Resolution**: Combined both with clear environment labeling
- **Difficulty**: Easy
- **Time**: 10 minutes

---

### 🔹 Merge 2: main + conflict-simulator (6 files)

#### Conflict 1: config/app-config.yaml
- **Issue**: Experimental configuration missing in main
- **Resolution**: Added “experimental” profile with AI scaling logic
- **Strategy**: Extended config to handle `production`, `dev`, and `experimental`
- **Difficulty**: Medium
- **Time**: 15 minutes

#### Conflict 2: config/database-config.json
- **Issue**: Conflicting DB authentication methods
- **Resolution**: Added `authMethod` parameter and unified structure
- **Strategy**: Merged both connection logics safely
- **Difficulty**: Medium
- **Time**: 10 minutes

#### Conflict 3: scripts/deploy.sh
- **Issue**: Different pipelines (production vs simulator)
- **Resolution**: Created hybrid deployment script with simulation mode
- **Strategy**: Used conditional branching to select pipeline
- **Difficulty**: Hard
- **Time**: 20 minutes

#### Conflict 4: scripts/monitor.js
- **Issue**: Different alert and metric thresholds
- **Resolution**: Created modular configuration
- **Strategy**: Used JSON-based threshold configuration
- **Difficulty**: Medium
- **Time**: 15 minutes

#### Conflict 5: docs/architecture.md
- **Issue**: Overlapping sections
- **Resolution**: Combined both and clarified simulator section
- **Difficulty**: Easy
- **Time**: 10 minutes

#### Conflict 6: README.md
- **Issue**: Outdated simulator features
- **Resolution**: Merged new simulator documentation
- **Difficulty**: Easy
- **Time**: 10 minutes

---

## 🧠 Most Challenging Parts

1. **Understanding Conflict Markers** — Learning how `<<<<<<<`, `=======`, and `>>>>>>>` represent conflicting branches.  
2. **Choosing Correct Code** — Needed to carefully merge logic instead of overwriting it.  
3. **deploy.sh Merge** — Contained complex scripts; required testing to confirm both pipelines worked.  
4. **git reflog Recovery** — Helped restore a lost commit after accidental reset.  
5. **Rebase vs Merge Confusion** — Learned when to rebase vs when to merge for history clarity.

---

## 📘 Key Learnings

### Technical Skills
- Resolved complex merge conflicts  
- Used rebase, cherry-pick, and reflog effectively  
- Learned soft/mixed/hard reset differences  
- Understood branch workflows deeply  

### Best Practices
- Commit small, logical changes  
- Always run tests after merging  
- Use `git status` and `git diff` before every commit  
- Maintain clear, meaningful commit messages  

### Workflow Insights
- Conflicts are normal and manageable  
- Reading both sides of the diff is crucial  
- Reflog is a lifesaver for recovery  
- Document every resolution decision  

---

## 💬 Reflection

This Git Mastery Challenge was a deep dive into real-world version control scenarios.  
I learned how to manage conflicting branches, recover lost commits, and cleanly merge codebases.  
The exercise transformed my understanding of Git from basic usage to professional-level problem-solving.  
Now, I feel confident resolving conflicts and managing branches in large collaborative projects.

---

### ✅ End of Report


# CHANGELOG

This changelog records all major Git operations performed in Phase 4 of the Git Mastery Challenge.

### Step 4.1: Git Fetch & Pull
- ✅ Used `git fetch instructor` **1 time** to check for remote updates.
- ✅ Compared differences using `git diff main instructor/main`.
- ✅ Used `git pull instructor main` **1 time** to sync updates.
---

### Step 4.2: Git Stash
- ✅ Created a new branch: `feature/new-feature`.
- ✅ Used `git stash push -m "WIP: New feature development"` **1 time** to temporarily save work.
- ✅ Restored stashed work with `git stash pop`.

---

### Step 4.3: Git Cherry-Pick
- ✅ Used `git cherry-pick <commit-hash>` **1 time** to apply a specific commit from another branch.
- ✅ Verified successful cherry-pick and pushed changes to main.

---

### Step 4.4: Git Rebase
- ✅ Created `feature/another-feature` branch.
- ✅ Used `git rebase main` **1 time** to align feature branch with updated main.
- ✅ Resolved any conflicts and force-pushed changes.

---

### Step 4.5: Git Reset & Revert
- ✅ Made a bad commit (`"BUG"` in `scripts/deploy.sh`).
- ✅ Used `git revert HEAD` **1 time** to undo it safely.
- ✅ Practiced 3 reset types:
  - `git reset --soft HEAD~1`
  - `git reset --mixed HEAD~1`
  - `git reset --hard HEAD~1`
- ✅ Recovered lost commit using `git reflog` and `git cherry-pick`.

---

### Step 4.6: Git Tag
- ✅ Created annotated tags:
  - `v1.0.0` → "Resolved all conflicts"
  - `v1.1.0` → "Added all features"
- ✅ Pushed all tags with `git push origin --tags`.

---


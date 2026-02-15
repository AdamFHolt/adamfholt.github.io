# Notes

## 1) Set up this repo on another machine

If the other machine has an old local copy, do this in that folder.

```bash
cd /path/to/adamfholt.github.io

# confirm what remote it points to
git remote -v

# point to the current canonical repo
git remote set-url origin git@github.com:AdamFHolt/adamfholt.github.io.git

# fetch latest refs
git fetch origin --prune

# switch/create local gh-pages from remote
git checkout -B gh-pages origin/gh-pages

# verify
git branch -vv
git status
```

If there is no local copy on that machine, clone fresh:

```bash
git clone git@github.com:AdamFHolt/adamfholt.github.io.git
cd adamfholt.github.io
git checkout gh-pages
```

## 2) Normal edit/commit/push flow

```bash
cd /path/to/adamfholt.github.io
git checkout gh-pages
git pull --ff-only

# make edits

git add -A
git commit -m "Describe update"
git push
```

Quick checks:

```bash
git status
git branch -vv
git remote -v
```

Live site:

- https://adamfholt.github.io/

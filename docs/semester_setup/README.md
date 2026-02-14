# Semester GitHub system

This system uses:

1. One GitHub repo per class
2. One dashboard repo for navigation, templates, and small shared scripts
3. Notion as the dashboard for notes, with links in both directions

## Folder structure on your computer

Semester root
Class folder
repo folder, this is the Git repository
local folder, never tracked

Example
/your_path/spring_2026
6.8300_Computer_Vision
repo
local

## Standard structure inside each class repo

repo
README.md
notes/
homework/
labs/
project/
assets/
submission/
tools/

## What goes where

Repo
Code, writeups, small figures used in writeups, cleaned notebooks, final submission copies

Local
Large datasets, raw exports, caches, intermediate renders, anything private or huge

## One time per class repo setup

1. Enter the class repo folder
2. Initialize git
3. Create standard folders
4. Add .gitignore
5. Add README
6. First commit
7. Create GitHub repo, connect remote, push

Commands

```bash
pwd
ls

git init
mkdir -p notes homework labs project assets submission tools

git add .
git commit
```

# QA Study Tracker

Personal progress tracker for the 12-week QA automation study plan.

## Features
- Full 7-phase, 12-week checklist covering everything on the CV
- Subtask-level checkboxes inside each skill
- Notes field per section — auto-saves as you type
- Progress persists in browser localStorage (survives page refresh/close)
- Udemy course links for every topic
- Phase progress bars and sidebar navigation

## How to use locally
Just open `index.html` in any browser. No server needed.

## Hosting on GitHub Pages (free, permanent URL)

### Step 1 — Create a GitHub repo
1. Go to https://github.com/new
2. Name it `qa-study-tracker` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Push this file
```bash
cd qa-tracker
git init
git add .
git commit -m "initial: QA study tracker"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/qa-study-tracker.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: `main`, Folder: `/ (root)`
5. Click **Save**

### Step 4 — Get your URL
After ~60 seconds your app is live at:
```
https://YOUR_USERNAME.github.io/qa-study-tracker/
```

Bookmark it. Open it on any device. Progress saves in that browser's localStorage.

## Notes on persistence
Progress is saved in your browser's `localStorage` under the key `qa_tracker_v2`.  
This means:
- Works on any device you open the URL on
- Each browser/device has its own progress (not synced across devices)
- Clearing browser data will clear progress — export notes manually if needed
- Incognito/private windows do NOT persist

## Resetting
Click **Reset all** in the top-right corner to clear all progress and notes.

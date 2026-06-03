# Josh Yule — Style Guide & Leadership Diary

Live site: https://curious-dango-f4ca9b.netlify.app

## What this is

Two connected tools built as single HTML files:

**Style Guide (`index.html`)** — A personal design reference for Josh Yule's visual identity. Typography, color, and component patterns.

**Leadership Diary (`leadership-diary.html`)** — A private journaling tool for tracking leadership growth over time. Entries are stored locally in the browser and can be backed up and restored using the Export / Import buttons.

## How to deploy

Changes are deployed to Netlify automatically when pushed to GitHub:

```
git add .
git commit -m "description of change"
git push
```

## How the diary works

- Entries live in your browser's localStorage — they don't get sent anywhere
- Use **Export ↓** to download a backup JSON file
- Use **Import ↑** to restore from a backup (duplicates are skipped automatically)
- A reminder banner appears after each saved entry prompting you to back up

## Built with

- Plain HTML, CSS, and JavaScript — no frameworks, no build step
- Hosted on Netlify
- Source on GitHub at https://github.com/yulebesorry/style-guide

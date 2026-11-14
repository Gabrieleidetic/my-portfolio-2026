# How to Work on Your Portfolio

## 1. See your changes live on your computer

Open a terminal in the project folder and run:

```bash
yarn dev
```

Then open the link shown in the terminal (usually http://localhost:3000) in your browser. Leave this running while you edit. Every time you save a file, the page updates on its own so you can see your changes right away.

To stop the local server, press `Ctrl + C` in the terminal.

## 2. Publish your changes to the live site

When you're happy with your changes, run these three commands one after the other:

```bash
git add .
git commit -m "feat: updates"
git push
```

What each one does:

- `git add .` gets all your changed files ready to be saved.
- `git commit -m "feat: updates"` saves them with a short note describing the change.
- `git push` sends them online, and the live site updates.

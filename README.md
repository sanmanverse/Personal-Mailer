# Personal Mailer

A simple mail-merge web app. Add names and emails to the built-in sheet (or import .xlsx/.csv, or paste rows), write one mail with `{name}` as a placeholder, and send a personalised mail to everyone.

## Features
- Built-in editable sheet (name + email), saved in your browser
- Import Excel/CSV or paste rows
- `{name}` placeholder in subject and body
- Opens each personalised mail in your mail app or Gmail
- Auto-clears the sheet after the last mail (with Undo)
- Optional Google Apps Script generator for fully automatic sending

## Run
Open `index.html` in any browser. No install or build needed.

## Host on GitHub Pages
1. Upload `index.html` and `README.md` to a new repository.
2. Go to Settings → Pages.
3. Under Source choose "Deploy from a branch", pick `main` and `/ (root)`, then Save.
4. Your app will be live at `https://<your-username>.github.io/<repo-name>/` in a minute or two.

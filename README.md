# GitHub-only setup

Upload ONE file, `index.html`, to a GitHub repo and turn on Pages.

Loadstring:
    loadstring(game:HttpGet("https://YOUR_USERNAME.github.io/YOUR_REPO/"))()

- Executors download the file and run it. Line 1 is a Lua comment, so it is ignored.
- Browsers render the file as a web page. Line 1 hides the page, shows "Nice try skidder" and redirects to Google.

To update the script: edit index.html on GitHub, keep line 1 exactly as it is, and replace everything below it.

🟢 How to Use (Mac) – v1.1 (Universal)

Place all Classicube files in the same folder
Example folder structure:

Classicube-Pack/
├── Classicube-Launcher.sh
├── y.html
└── static/


Make the launcher executable (one-time setup)
Open Terminal, navigate to the folder, and run:

chmod +x Classicube-Launcher.sh


Launch Classicube
Double-click Classicube-Launcher.sh (or rename it to Classicube.command for macOS convenience).
Terminal will open, start a local server on localhost:8080, and your browser will automatically open y.html. Classicube is ready to play.

Stop the server
When finished, simply close the Terminal window to stop the local server.



🔄 Reloading Classicube Without Caching

If the browser shows a stale version of Classicube after closing or reopening the launcher:

Do not use keyboard shortcuts like Cmd+R / Ctrl+R or the small reload button.

Right-click on the browser tab and select Reload from the context menu.

This forces the browser to bypass cached files and load the latest version from the server.

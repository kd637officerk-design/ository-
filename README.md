# Symphony 6th

Windows 11 desktop app (Electron) built on GitHub Actions.

## Get the installer
1. Upload this folder's contents to a new GitHub repo (keep the `.github` folder).
2. Open the **Actions** tab -> "Build Symphony 6th (Windows)" -> wait for green.
3. Open the finished run -> **Artifacts** -> `Symphony-6th-Windows`.
   Inside: `Symphony-6th-Setup-1.0.0.exe` (installer, adds Desktop + Start menu shortcuts) and a portable .exe.

Windows may show SmartScreen ("More info" -> "Run anyway") since the app is unsigned.

Run locally: `npm install` then `npm start`.

# CMO Executive Academy — E-Learning

Static, Thai-language E-Learning Web App for a 24-week CMO development curriculum.

## Run locally
Open `index.html` in a browser. No build or API keys needed.

## Deploy to Vercel
1. Create a new GitHub repository named `cmo-executive-academy`.
2. Upload all files in this folder to the repository root (`index.html`, `course.json`, `vercel.json`, `README.md`).
3. In Vercel select **Add New > Project > Import Git Repository**.
4. Select `cmo-executive-academy`, select Framework Preset `Other`, Root Directory `./`, no build command, Output Directory `.`.
5. Click Deploy. On future pushes to the production branch, Vercel will deploy automatically.

## Data persistence
Learning progress and assignment notes are currently stored in browser localStorage; they are not synced across devices and may be lost if browser data is cleared. Public deployment does not add an account/login system.

## Security note
Do not commit personal student information, access tokens, or business confidential files to the public repository. Sample business figures are hypothetical.

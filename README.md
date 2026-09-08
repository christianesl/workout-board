# Workout Board

Drop a workout infographic once. Open the same page on your phone. The image stays until you replace or remove it.

**Live page:** [https://christianesl.github.io/workout-board/](https://christianesl.github.io/workout-board/)

## How to use

1. Open the live page on your computer.
2. One-time setup: **Settings** → paste a GitHub token so uploads are saved in this repo (required for your phone to see the image).
3. Drag and drop, tap to choose, or paste (`Ctrl/Cmd+V`) the infographic or HTML file.
4. On your phone, open the same URL (or add it to the home screen). The image is already there.

Replace by dropping another image or HTML file. HTML files are displayed in a sandboxed preview. Remove with the **Remove** button.

## One-time token (uploads only)

Viewing does not need a token. Saving an image to GitHub does.

Easiest classic token (public repos only):

1. Open [github.com/settings/tokens/new](https://github.com/settings/tokens/new?description=workout-board&scopes=public_repo)
2. Note: `workout-board`
3. Scope: **`public_repo`** only
4. Generate and paste it in Settings on the board. It stays in this browser, never in the repo.

Safer fine-grained token:

- Resource owner: `christianesl`
- Only repository: `workout-board`
- Permissions → Repository → **Contents: Read and write**

## Notes

- This repository is public, so the current infographic is public.
- The page keeps a single image. A new drop replaces the previous file.
- After the first deploy, GitHub Pages can take a minute to go live. Image updates themselves show up right away (the page reads the file from GitHub, not a cached Pages build).

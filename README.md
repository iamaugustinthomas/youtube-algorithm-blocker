# YouTube Distraction & Algorithm Blocker

A lightweight custom filter list for **AdGuard** and **uBlock Origin** designed to strip away YouTube's algorithmic hooks, endless feeds, and distractions, helping you stay focused.

## What It Blocks
* 🚫 **Home Feed:** Disables the algorithmic homepage loop (loads a clean, blank screen).
* 🚫 **Sidebar Recommendations:** Removes the "Up Next" column next to the video player.
* 🚫 **YouTube Shorts:** Hides Shorts shelves from appearing in searches.
* 🚫 **End Screen Suggestions:** Blocks grid popups when a video finishes.

## How to Install

### Method 1: One-Click Subscribe (Recommended)
1. Go to your GitHub repository and click on the `youtube-filter.txt` file.
2. Click the **Raw** button in the top right of the file view to get the raw URL.
3. Open **AdGuard Settings** > **Filters** > **Custom** > **Add Custom Filter**.
4. Paste the Raw URL and give it a name. AdGuard will now automatically update your filter when you push changes to GitHub!

### Method 2: Manual Copy-Paste
1. Copy the content inside `youtube-filter.txt`.
2. Open **AdGuard** > **Settings** > **User Rules**.
3. Paste the snippets directly into the editor text field and save.

## Contribution
Feel free to open an issue or submit a pull request if YouTube changes their element selectors and updates are needed.

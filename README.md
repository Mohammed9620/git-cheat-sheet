# Git Cheat Sheet

A single-page, bilingual (English / Arabic) Git cheat sheet. Every command you need, in the order you need it. Tap any command to copy it.

## Features

- **Bilingual with RTL support.** Switch between English and Arabic at any time. The layout flips automatically.
- **Interactive journey.** Follow one file through the working directory, staging area, local repository, and GitHub, with the exact command for each step (and the command to go back).
- **Copy on tap.** Click any command to copy it to your clipboard.
- **Search.** Find a command fast with the built-in search overlay.
- **Favorites.** Star the commands you use most, then export them as `~/.gitconfig` aliases.
- **Essentials / Full view.** Start with the daily essentials, switch to the full sheet when you need more.
- **Risk badges.** Every undo command is labeled safe, local-only, or dangerous, so you know what you are about to do.
- **Practice drills.** A checklist of exercises to run in a throwaway repo. Progress is saved in your browser.
- **Light and dark themes.** Follows your system setting.

## What's covered

| Section | Topics |
| --- | --- |
| First-time setup | Name, email, default branch, editor |
| Start a repository | `init`, `clone` |
| The daily loop | `status`, `add`, `commit`, `diff` |
| Look around | `log`, `show`, `blame` |
| Branches and merging | `switch`, `merge`, resolving conflicts |
| Undo | `restore`, `revert`, `reset`, with risk badges |
| Stash | Save and restore work in progress |
| Working with GitHub | `remote`, `push`, `pull`, `fetch` |
| `.gitignore` | Patterns and common examples |
| Rules worth keeping | Habits and commit message conventions |
| Practice drills | Hands-on exercises |

## Usage

No build step, no dependencies. Just open the file.

```bash
git clone https://github.com/Mohammed9620/git-cheat-sheet.git
cd git-cheat-sheet
open index.html   # macOS. On Windows: start index.html, on Linux: xdg-open index.html
```

Fonts (Readex Pro and JetBrains Mono) load from Google Fonts. Offline, the page falls back to your system fonts and everything still works.

## Host it on GitHub Pages

1. Rename `git-cheat-sheet.html` to `index.html`.
2. Push it to your repository.
3. Go to **Settings → Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. After a minute, the site is live.

## Notes

- `git switch` and `git restore` need Git 2.23 or newer. On older versions, use `git checkout`.
- Your language, view, favorites, and drill progress are stored in your browser's `localStorage`. Nothing is sent anywhere.

## Tech

Plain HTML, CSS, and vanilla JavaScript in one self-contained file.

## Contributing

Found a typo or a wrong translation? Open an issue or send a pull request. Arabic wording improvements are especially welcome.

## License

MIT. See `LICENSE`.

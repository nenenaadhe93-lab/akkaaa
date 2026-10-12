# Akka Birthday Website 🎂

Folder layout:
```
akka-birthday/
  index.html
  photos/        (all your photos + hero.jpg)
  music.mp3      (optional - add your own; off by default)
```

## Edit your details
Open `index.html` in any text editor and find `const CONFIG = {` near the bottom.
- `akkaName` - her name (big script text)
- `fromName` - your name
- `message` - your message, one paragraph per chat bubble. Paste it exactly as you wrote it.
- `bavaMessage` - the last paragraph (Bava card)
- `closing` - the closing line in the finale
- `photos` - captions (`cap`) and alt text (`alt`) for each photo

## Host free
**Netlify Drop:** go to app.netlify.com/drop, drag the whole `akka-birthday` folder in, copy the link, send on WhatsApp.
**GitHub Pages:** create a repo, upload all files, Settings > Pages > Deploy from branch `main` / root.

## Notes
- Missing photos are skipped automatically.
- For the WhatsApp preview image, after hosting change `og:image` and `twitter:image` in `index.html` to the full URL, e.g. `https://yoursite.netlify.app/photos/hero.jpg`.
- Music: put `music.mp3` next to `index.html`, then tap the speaker button (top-left).

# Vance Music — Landing Page

## Structure

```
vance-music-app/
├── index.html          # The landing page (hero screenshot is embedded directly inside)
└── public/
    └── VanceMusic.apk   # App installer — replace this with your real signed APK
```

## Making the download button work with your real app

1. Build/export your signed release `.apk`.
2. Replace `public/VanceMusic.apk` with that file, keeping the same filename.
   (If you use a different filename, update the two `href="public/VanceMusic.apk"`
   attributes in `index.html` to match.)
3. Deploy the whole `vance-music-app/` folder as-is to any static host
   (Netlify, Vercel, GitHub Pages, S3, your own server, etc.) — the relative
   path keeps working as long as `public/` sits next to `index.html`.

No JavaScript is required for the download to work: both download buttons are
plain `<a href="public/VanceMusic.apk" download>` links, so the browser
downloads whatever file is currently sitting in `public/`.

## Hero screenshot

The app home-screen screenshot in the hero phone mockup is embedded directly
inside `index.html` as inline image data — it's part of the page itself, so
there's nothing to place in a folder and no separate image file to manage.
If you ever want to swap it for a different screenshot, just ask and it'll
be re-embedded the same way.


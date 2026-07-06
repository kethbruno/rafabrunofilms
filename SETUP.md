# Rafa Bruno Films — Hero Section Setup

## Files

- `index.html` — self-contained hero page (CSS + JS embedded)
- `reel.mp4` — your portfolio reel (not included; download separately)

## To add the reel

The reel video file should be placed in the repo root and named `reel.mp4`. The HTML page expects it there and will gracefully show a dark placeholder if it's missing.

**Option 1: Git LFS (recommended for large files)**
```bash
git lfs install
git lfs track "*.mp4"
git add reel.mp4
git commit -m "Add reel.mp4"
git push
```

**Option 2: Direct upload via GitHub web**
1. Go to the repository
2. Click "Add file" → "Upload files"
3. Drag `reel.mp4` into the upload area
4. Commit to the branch

The page is fully responsive (1280px / 768px / 375px) and works without the video — it shows the dark background as a fallback while the page loads and animates.

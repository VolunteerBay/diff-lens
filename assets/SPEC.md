# Assets to create for diff-lens

## logo.png вЂ” 256x256, transparent, dark theme
🔀 Neon shield/gear motif matching $diff-lens$ brand color. See master prompt in _shared docs.

## banner.png вЂ” 1280x640, background #0d1117
Large bold title $diff-lens$, subtitle gray #8b949e, thin gradient line #00ff9dв†’#bc8cff.

## screenshots/main.png вЂ” 1280x800
Side-by-side file diff with syntax highlighting

## screenshots/settings.png вЂ” 1280x800
Folder tree comparison — changed/added/deleted badges

## screenshots/results.png вЂ” 1280x800
Image diff — overlay mode with opacity slider

## gifs/demo.gif вЂ” 800x500, 8s, 12fps, <8MB
1. Open app, 2. click main action, 3. status turns green, 4. toggle a feature, 5. return.
ffmpeg: -vf "fps=12,scale=800:-1:flags=lanczos,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse"
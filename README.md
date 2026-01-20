# Weekly Date Plans

A simple, dramatic slideshow for sharing weekly date plans with my girlfriend.

**Live site:** https://idankar.github.io/looz/

## How to Update

1. Edit `index.html`
2. Find the `<div class="slide">` sections
3. Update the emoji, day name, time, and description
4. Commit and push - GitHub Pages will auto-deploy

## Slide Structure

```html
<div class="slide" style="background: linear-gradient(to right, #color1, #color2);">
    <div class="emoji anim-slam">🍕</div>
    <h1 class="anim-slam">יום שלישי</h1>
    <p class="anim-slam">19:00<br>תיאור הפעילות</p>
</div>
```

## Animation Types

- `anim-slam` - Zoom in dramatically
- `anim-spin` - Spin and reveal
- `anim-rise` - Rise from bottom

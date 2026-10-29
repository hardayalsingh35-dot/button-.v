# 🦸 Hero Buttons

**70 animated CSS buttons in a single HTML file** — Marvel, DC, Indian superheroes
(Shaktimaan, Krrish, Chhota Bheem, G.One, Nagraj, Dhruva, Mr. India…), anime, and
modern UI styles (neon, glass, neumorphic, cyberpunk, 8-bit, confetti…).

Zero dependencies. Works offline. Open source (MIT).

## Features
- 🔎 Filter by category + live search
- `</> Code` on every card → copy the button's HTML + CSS
- `⬇` on every card → download that button as a standalone `.html`
- 🛠 **Button Maker** — design your own button (colors, radius, glow, 3D, idle animation,
  hover effect) with live preview, then copy or download the code
- ⬇ Download the whole website, LICENSE and README from the page itself

## Use
Just open `index.html` in a browser. To use a button in your project, paste the copied
HTML into your page and the CSS into your stylesheet. A few demo buttons (ripple,
loading, magnetic, confetti, download-progress) include a tiny JS snippet, which is
bundled automatically when you download them.

## Contribute
Add a new card inside `<main class="grid">`:

```html
<article class="card" data-cat="indian" data-name="My Hero">
<style>
.b-myhero { /* your CSS */ }
</style>
<div class="stage" style="--bg:#101010"><button class="b-myhero">MY HERO</button></div>
<div class="meta"><div><b>My Hero</b><span class="chip indian">Indian</span></div>
<div class="acts"><button class="code">&lt;/&gt; Code</button><button class="dl">⬇</button></div></div>
</article>
```

Categories: `marvel`, `dc`, `indian`, `anime`, `others`, `style`.

## License
MIT — free for personal and commercial use.

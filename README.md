# BIRTHDAY CAKE

A Birthday Cake animation made with HTML / CSS / JS 

# HOW TO USE

Open .html file in any browser or code editor then click on cake to burn candel 😋

# CUSTOMISING 

| To change | Where |
| --- | --- |
| Background color | `--bg` in `:root` |
| Headline text | The two `<span class="word">` elements in the `<header>` |
| Letter colors | `colors` array in the script (colors repeat in order) |
| Letter tilt | `tilts` array in the script (`HAPPY` is set to 0 so it stays straight) |
| Writing speed | `0.74s` in `animation-delay: calc(var(--i) * 0.74s + 0.3s)`. Total time is roughly 0.74s times the number of letters |
| Headline size | `.word-1` and `.word-2` `font-size` |
| Cake colors | `fill` values in the SVG: frosting `#dc2f55`, sponge `#fbc9a6`, plate `#c01f48`, frosting shine `#ff93ab` |
| Candle stripes | The two `<rect>` fills inside `<pattern id="stripes">` |
| Flame colors | `fill` on the three `.f` paths |
| Button text | The `<button id="toggle">` element |
| Number of hearts | `i < 10` in `spawnHearts` |
| How far hearts travel | `dy` in `spawnHearts` |
| Heart size | `rand(14, 30)` in `spawnHearts` |

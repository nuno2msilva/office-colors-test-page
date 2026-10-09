# Office Theme Colors

A single-page site that repaints itself in every built-in Microsoft Office color set. Step through them with the arrow buttons, the ← → keys, or a swipe on a phone.

Each element carries a small hint naming the color slot it uses (Dark 1, Light 2, Accent 3, Hyperlink and so on) and its hex code. Click an accent tile or a swatch in the top strip to copy its hex code.

## What's included

- **Office 2007–2010 (21 sets):** Office, Grayscale, Apex, Aspect, Civic, Concourse, Equity, Flow, Foundry, Median, Metro, Module, Opulent, Oriel, Origin, Paper, Solstice, Technic, Trek, Urban, Verve
- **Office 2013 and later (19 sets):** Office, Office 2013–2022, Blue Warm, Blue, Blue II, Blue Green, Green, Green Yellow, Yellow, Yellow Orange, Orange, Orange Red, Red Orange, Red, Red Violet, Violet, Violet II, Marquee, Slipstream
- **Unofficial:** Corporate, a theme seen in a pre-release build of Office 2007 that never shipped. Its colors are estimates from a blurry video.

Some sets were renamed later: Equity is identical to Orange Red, and Trek is identical to Yellow Orange.

## Sources

The hex values come from two independent theme tables, which agree wherever they overlap:

- [SpreadJS ThemeColors](https://developer.mescius.com/spreadjs/api/classes/GC.Spread.Sheets.ThemeColors) (values from the `@grapecity/spread-sheets` npm package)
- [ONLYOFFICE sdkjs, ColorSchemes.js](https://github.com/ONLYOFFICE/sdkjs/blob/master/common/Shapes/ColorSchemes.js)

## Running it

Plain HTML, CSS and JavaScript with no build step. Open `index.html` in a browser, or serve it with GitHub Pages (Settings → Pages → deploy from the `main` branch).

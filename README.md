# Citation Badge
This badge shows the number of citations of a paper / DOI. Updated daily. Free of charge.

When first queried, it may take a few seconds for all citations to be scraped and the number of citations is probably too low.
In the next 24 hours the correct number of citations (from google scholar) should appear.

To have more style options (color, edges, etc.) you can also combine this badge with [shields.io/endpoint](https://shields.io/endpoint)

<img src="https://api.juleskreuer.eu/citation-badge.php?doi=10.1126/science.1058040" height="25">
<img src="https://api.juleskreuer.eu/citation-badge.php?doi=a-wrong-doi" height="25">
<img src="https://img.shields.io/endpoint?style=flat-square&url=https%3A%2F%2Fapi.juleskreuer.eu%2Fcitation-badge.php%3Fdoi%3Dstats%26shield" height="25">

## Usage
Go to [juleskreuer.eu/projekte/citation-badge/](https://juleskreuer.eu/projekte/citation-badge/) and paste your doi. Alternatively you can replace YOURDOI.

### Markdown
```md
[![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=YOURDOI)](https://juleskreuer.eu/projekte/citation-badge/)
```

### HTML IMG Tag
```html
<a href="https://juleskreuer.eu/projekte/citation-badge/"><img alt="Citation Badge" src="https://api.juleskreuer.eu/citation-badge.php?doi=YOURDOI"></a>
```

### Shield Endpoint
```
https://api.juleskreuer.eu/citation-badge.php?shield&doi=YOURDOI
```

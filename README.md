The custom CSS I use for my Jellyfin server, more or less entirely an [Ultrachromic](https://github.com/CTalvio/Ultrachromic) setup with a couple adjustments.

Server-wide custom CSS:
```css
@import url("https://cdn.jsdelivr.net/gh/hagretek/jellyfin-css/jellyfin-sgrastar.css");
```

TV-specific custom theme (the thing slows to a crawl with all the funky effects of the above):
```css
@import url("https://cdn.jsdelivr.net/gh/hagretek/jellyfin-css/jellyfin-tizen.css");
```

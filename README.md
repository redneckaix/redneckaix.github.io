# redneckaix.github.io

Home of the apps by redneckaix, published with GitHub Pages at https://redneckaix.github.io/

## Layout

```
index.html              main page, one card per app
assets/site.css         shared styles for the main page and app pages
<app>/index.html        the app's page
<app>/privacy/          the app's privacy policy (the live URL goes into Google Play)
<app>/icon.png          the app icon
```

Currently: `sbpt/` (Simple BP Tracker).

## Adding an app

1. Copy `sbpt/` to a new folder, for example `myapp/`, and edit the text, icon and screenshots.
2. Write the privacy policy in `myapp/privacy/index.html`.
3. Copy the `<article class="card">` block in `index.html` and point it at `/myapp/` and `/myapp/privacy/`.

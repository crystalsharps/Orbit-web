# Orbit Browser

Orbit is a Chromium/Kiwi-based Android browser fork with a custom **Crystal Sharp** New Tab Page, theme switcher, and developer menu.

## New Tab Page

Custom NTP lives in:

```
chrome/browser/resources/new_tab_page/
  index.html
  style.css
  script.js
```

Features: search/URL bar, shortcut tiles, clock, theme switcher (Crystal / Light / Nord / Dracula / Monokai), and a developer menu with LocalStorage persistence.

## Local build

Full APK builds need a complete Chromium Android checkout (not this overlay alone). See `build-orbit.sh` and `ORBIT_ROADMAP.md`.

```bash
./build-orbit.sh
```

## License

See [LICENSE](LICENSE).

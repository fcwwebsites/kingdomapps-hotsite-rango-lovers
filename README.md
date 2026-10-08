# Kingdomapps — Rango Lovers Restaurante e Hamburgueria Delivery preview hotsite

Public preview gate for **Rango Lovers Restaurante e Hamburgueria Delivery** (Kingdomapps). A PIN-protected landing page at the repo root unlocks three static hotsite versions.

## Structure

```
/
  index.html      # preview gate
  gate.css / gate.js
  v1/ v2/ v3/     # static hotsites (HTML/CSS/JS + assets/)
```

## GitHub Pages

Pages is enabled from the `main` branch, site root `/`.

- Gate: https://fcwwebsites.github.io/kingdomapps-hotsite-rango-lovers/
- Versions: `/v1/`, `/v2/`, `/v3/`

## Local preview

```bash
python3 -m http.server 8765
```

Then open `http://127.0.0.1:8765/`.

## Content

Contacts and business facts come only from the confirmed lead file. The menu sections are clearly badged as simulated ("Cardápio simulado") for preview purposes.

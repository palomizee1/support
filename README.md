# Support — Finora Budget · Vitals Flow · Smart Utility Hub

**Live page: https://palomizee1.github.io/support/**

Available in English, Español, Deutsch, Français and Português (Brasil) via the language
selector, and linkable per language:

| Locale | URL |
|---|---|
| English | https://palomizee1.github.io/support/?lang=en |
| Español | https://palomizee1.github.io/support/?lang=es |
| Deutsch | https://palomizee1.github.io/support/?lang=de |
| Français | https://palomizee1.github.io/support/?lang=fr |
| Português (BR) | https://palomizee1.github.io/support/?lang=pt-BR |

## Editing

`index.html` is **generated** — don't hand-edit it. The source is the `SUPPORT*.md` files in
the PersonalSuite repository:

```
python3 Scripts/build_pages.py support <path-to-this-repo>
```

The build redacts the contact email to `panosvigasdev@gmail.com` and refuses to write a file that
still contains it — this repo is public and its history is permanent, so that field is filled
in on the live page by hand.

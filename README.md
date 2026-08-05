# Privacy Policies — GiBri Apps

Public privacy policy pages for GiBri Apps' Android apps, hosted via GitHub Pages.

## Structure

One folder per app, each with its own `index.html`:

```
privacy-policies/
├── liteexcel/
│   └── index.html
└── (more apps added here over time)
```

This keeps each app's policy at a stable, memorable URL and lets a policy carry its own
assets/subpages later if it ever needs them, without disturbing any other app's folder.

## Live URLs

| App | Policy URL |
| --- | --- |
| LiteExcel — Excel Reader (`com.gibriapps.liteexcel`) | https://vgirinathan.github.io/privacy-policies/liteexcel/ |

## Adding a new app

1. Create a new folder named after the app (lowercase, no spaces — matches the pattern above).
2. Add an `index.html` inside it — a normal, self-contained HTML file (inline CSS, no external
   requests) so it renders correctly on GitHub Pages with nothing else to configure.
3. Add a row to the table above.
4. Commit and push to `main` — Pages redeploys automatically, typically within a minute or two.

## Hosting

Served by GitHub Pages from the `main` branch, root folder. Settings → Pages in this repo.

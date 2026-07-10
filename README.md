# Nós Stória

*The history and culture of Cape Verde.*

> Cape Verde was not discovered. It was built.

A static magazine-style site telling the history and culture of Cape Verde — the
Kriolu language, the slave trade told honestly, Amílcar Cabral, Cesária Évora and
*sodade*, and the diaspora.

## Structure

```
.
├── index.html                        # masthead, editor's letter, contents
├── styles.css                        # shared styles
└── articles/
    ├── amilcar-cabral.html           # Nº 001
    ├── cape-verde-slave-trade.html   # Nº 002
    └── cesaria-evora.html            # Nº 003
```

## Running locally

It's a plain static site — no build step, no dependencies. Open `index.html`
directly, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Deployed on Vercel as a static site with no build step (see `vercel.json`).

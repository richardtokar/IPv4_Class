# IPv4 Class Challenge

A fast browser game to practice IPv4 classes and their default subnet masks.

## Play locally

1. Open `index.html` directly in your browser, or
2. Run a local server:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Rules

- You get 15 rounds per game.
- Questions are randomly interspersed between:
  - identifying Class A, B, or C from an IPv4 address, and
  - selecting the default subnet mask for the shown address.
- Your best score is saved in local browser storage.

## IPv4 class ranges used

- Class A: 1–126 → 255.0.0.0
- Class B: 128–191 → 255.255.0.0
- Class C: 192–223 → 255.255.255.0

> Note: 127.x.x.x (loopback range) is excluded from game prompts.

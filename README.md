# IPv4 Class Challenge

A fast browser game to practice IPv4 address class identification.

## Play locally

1. Open `index.html` directly in your browser, or
2. Run a local server:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Rules

- You get 15 rounds per game.
- For each IPv4 address, choose Class A, B, C, D, or E based on the first octet.
- Your best score is saved in local browser storage.

## IPv4 class ranges used

- Class A: 1–126
- Class B: 128–191
- Class C: 192–223
- Class D: 224–239
- Class E: 240–255

> Note: 127.x.x.x (loopback range) is excluded from game prompts.

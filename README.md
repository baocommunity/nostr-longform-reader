# Nostr Long-Form Reader

A single-page HTML app that fetches kind:30023 long-form articles from public Nostr relays.

## Features

- Fetches 21 kind:30023 articles from multiple public relays
- Displays hashtags (`t` tags) with occurrence counts
- Filter articles by hashtag with **AND / OR** toggle
- Shows article title, author name/picture, and timestamp
- Pure HTML/CSS/JS — no build step required

## Live demo

<https://baocommunity.github.io/nostr-longform-reader/>

## Run locally

```bash
git clone https://github.com/baocommunity/nostr-longform-reader.git
cd nostr-longform-reader
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## Relays used

- wss://nos.lol
- wss://relay.snort.social
- wss://nostr.mom
- wss://relay.damus.io
- wss://relay.nostr.band

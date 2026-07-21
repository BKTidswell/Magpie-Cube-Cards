---
Played Drafts:
---
## Cards Stickered
```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - note["Sticker Applier"].contains("Unknown")
    image: note.image
    imageFit: contain
    cardSize: 100

```

## Cards Killed
```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - note["Killed by"].contains("Unknown")
    image: note.image
    imageFit: contain
    cardSize: 100

```

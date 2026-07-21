---
Played Drafts: Draft X
---
## Cards Stickered
```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - note["Sticker Applier"].contains("Sam")
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
        - note["Killed by"].contains("Sam")
    image: note.image
    imageFit: contain
    cardSize: 100

```

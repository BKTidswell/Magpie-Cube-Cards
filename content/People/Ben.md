---
Played Drafts: Draft X, Draft 1, Draft 2
---
## Cards Stickered
```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - note["Sticker Applier"].contains("Ben")
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
        - note["Killed by"].contains("Ben")
    image: note.image
    imageFit: contain
    cardSize: 100

```

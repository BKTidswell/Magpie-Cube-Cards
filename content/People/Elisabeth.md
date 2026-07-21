---
Played Drafts: Draft X, Draft 1
---
## Cards Stickered
```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - note["Sticker Applier"].contains("Elisabeth")
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
        - note["Killed by"].contains("Elisabeth")
    image: note.image
    imageFit: contain
    cardSize: 100

```

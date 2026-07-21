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
        - note["Sticker Applier"].contains("Schuyler")
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
        - note["Killed by"].contains("Schuyler")
    image: note.image
    imageFit: contain
    cardSize: 100

```

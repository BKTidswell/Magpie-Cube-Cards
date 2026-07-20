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
        - note["Sticker Applier"].contains("Ben")
    image: note.image
    imageFit: contain

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

```

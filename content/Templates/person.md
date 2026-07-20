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
        - note["Sticker Applier"].contains("{{Title}}")
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
        - note["Killed by"].contains("{{Title}}")
    image: note.image
    imageFit: contain

```

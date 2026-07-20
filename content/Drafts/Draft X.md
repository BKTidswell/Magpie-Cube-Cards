
## Cards Modified
```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - Drafts.contains("Draft X")
    image: note.image
    imageFit: contain

```

## Players
```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - note["Played Drafts"].contains("Draft X")
    image: note.image
    imageFit: contain

```

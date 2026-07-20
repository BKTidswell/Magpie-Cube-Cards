
## Cards Modified
```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - Drafts.contains("{{Title}}")
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
        - note["Played Drafts"].contains("{{title}}")
    image: note.image
    imageFit: contain

```

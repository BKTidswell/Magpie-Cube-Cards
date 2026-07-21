
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
    cardSize: 100

```

## Cards Killed
```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - note["Killed in"].contains("{{Title}}")
    image: note.image
    imageFit: contain
    cardSize: 100

```

## Players
```base
views:
  - type: list
    name: Table
    filters:
      and:
        - note["Played Drafts"].contains("{{title}}")
    image: note.image
    imageFit: contain

```

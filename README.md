# allegro-actions/create-tag

This action creates tag and pushes it to remote

## Basic usage:

```
steps:
  - uses: allegro-actions/create-tag@v1
    if: github.ref == 'refs/heads/main'
    with:
      tag: v1.0.0
      current-tag: v0.0.9
```

## Inputs

`tag` - tag to create

`current-tag` - current tag, action won't create new tag when executed on current release tag.
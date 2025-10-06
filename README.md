# allegro-actions/create-tag

This action creates tag and pushes it to remote

## Basic usage:

```
steps:
  - uses: allegro-actions/create-tag@v1
    if: github.ref == 'refs/heads/main'
    with:
      tag: v1.0.0
```

## Inputs

`tag` - tag to create.

`user-name` - the username that is associated with Git commits/tags, optional parameter.

`user-email` - the user email that is associated with Git commits/tags, optional parameter.

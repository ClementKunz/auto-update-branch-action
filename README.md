# Auto update branch action

This action allow to iterate through all opened pull requests, find the ones marked “auto merge” and, if possible, update the source branch.

## Inputs

### `bearer-token`

A token with read and write access to the repository must be provided.

## Example usage

```yaml
uses: actions/ClementKunz/auto-update-branch-action@v1.0
with:
  bearer-token: ${{ secrets.my_token }}
```
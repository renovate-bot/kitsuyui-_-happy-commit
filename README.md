# happy-commit

[![codecov](https://codecov.io/gh/kitsuyui/happy-commit/branch/main/graph/badge.svg?token=FM7RYWGV0P)](https://codecov.io/gh/kitsuyui/happy-commit)

- GitHub Action to celebrate your commits on PR.

## Example

<img width="1189" alt="happy-commit" src="https://user-images.githubusercontent.com/2596972/199675141-e640c276-21d7-4ede-a1a6-1850b1bdc291.png">

## Example usage

```yaml
      - uses: kitsuyui/happy-commit
        with:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

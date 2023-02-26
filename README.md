# hadolint-action

## How to use

```
jobs:
  codelint:
    if: github.event_name == 'pull_request'
    runs-on: ubuntu-latest

    steps:
      - name: Check-out
        uses: actions/checkout@v3
        with:
          fetch-depth: 1

      - name: Hadolint
        uses: wintero92/hadolint-action@v1
```

## Inputs

See `action.yaml` for possible inputs.
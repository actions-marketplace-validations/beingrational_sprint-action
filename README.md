# Sprint the world action

This action prints "Sprint World" or "Sprint" + the name of a person to sprint to the log.

## Inputs

### `whom-to-sprint`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we sprinted you.

## Example usage

uses: beingrational/sprint-action@v3.0
with:
  whom-to-sprint: 'Mona the Octocat'

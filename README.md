# `action-complete-pr-comment`

> Removes the 'eyes' reaction and adds a completion reaction ('rocket' or 'confused') to the triggering PR comment.

## Usage

```yaml
- uses: Framework-R-D/action-complete-pr-comment@8591587d60acdd9d4d7a84bd99d81abce82ca420 # v2
  with:
    input-name: value
```

## Inputs

| Name | Description | Required | Default |
|------|-------------|----------|---------|
| `status` | The status of the workflow. If 'success', a 'rocket' reaction is added. For any non-success status (including 'failure', 'cancelled', or 'skipped'), a 'confused' reaction is added. Defaults to 'success'. | false | `success` |

## Outputs

| Name | Description |
|------|-------------|
(none)

## License

[Apache 2.0](LICENSE)

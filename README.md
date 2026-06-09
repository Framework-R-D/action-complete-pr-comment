# `action-complete-pr-comment`

> Removes the 'eyes' reaction and adds a completion reaction ('rocket' or 'confused') to the triggering PR comment.

## Usage

```yaml
- uses: Framework-R-D/action-complete-pr-comment@b018afa43e5bf24dc76000e9c9f831ad60dea5ad # v1
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

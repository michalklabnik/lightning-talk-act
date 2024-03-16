# Ex. 4 Workflows

```shell
act --list
```

```shell
act
```

Event push and all jobs.

## Workflows

```shell
act --workflows './.github/workflows/workflow-1.yml'
act --list --workflows './.github/workflows/workflow-1.yml'
```

```shell
act --workflows './.github/workflows/workflow-2.yml'
act --list --workflows './.github/workflows/workflow-2.yml'
```

```shell
act --workflows './.github/workflows/workflow-3.yml'
act --list --workflows './.github/workflows/workflow-3.yml'
```

## Events

```shell
act push
```

```shell
act pull_request
```

## Jobs

```shell
act --job 'Alpha'
```

```shell
act pull_request --job 'Alpha'
```

```shell
act --workflows './.github/workflows/workflow-1.yml' --job 'Alpha'
```

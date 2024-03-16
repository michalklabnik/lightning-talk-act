# Ex. 2 Code, Variables, ENV and Secrets

## Code

```shell
act --job Job-Code
```

## Variables

```shell
act --job Job-Variables --var-file .local/my.variables
```

```shell
act --job Job-Variables --var ACT_VAR_PING=pong --var ACT_VAR_BLUE=green
```

## ENV

```shell
act --job Job-Env --env-file .local/.env
```

```shell
act --job Job-Env --env ACT_ENV_HELLO=Port7 --env ACT_ENV_I_AM='environment variable as parameter'
```

## Secrets

```shell
act --job Job-Secrets --secret-file .local/.secrets
```

```shell
act --job Job-Secrets --secret ACT_SECRET_ONE=22 --secret ACT_SECRET_THREE=4444
```

## Run tests

```bash
devbox shell

task cluster-create

task test-watch

# Stop watching with `ctrl+c`

task cluster-destroy

exit
```

## Publish To Upbound

```bash
devbox shell

# Replace `[...]` with the Upbound Cloud account
export UP_ACCOUNT=[...]

# Replace `[...]` with the Upbound Cloud token
export UP_TOKEN=[...]

# Replace `[...]` with the version of the package (e.g., `v0.5.0`)
export VERSION=[...]

task package-publish

exit
```

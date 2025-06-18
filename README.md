#  IBM Storage 
Meta configuration for IBM Storage Github Org

This repository contains the metadata configuration for the IBM Storage GitHub Organizations. The data here is consumed by the [peribolos](https://docs.prow.k8s.io/docs/components/cli-tools/peribolos/) tool to manage the organization and memberships, as well as team creation and deletion.

# Notes:

To get existing config:
```
./cmd/peribolos --log-level info --dump ibmstorage --github-token-path /path/to/git-token
```

To update config, defaults as a dry-run. Add `--confirm` to make the change:
```
./cmd/peribolos --config-path ./config/org.yaml --github-token-path /path/to/git-token
```

peribolos install, saved to GOBIN:
```
GOBIN=$(OUTPUT_BIN_DIR) go install sigs.k8s.io/prow/cmd/peribolos@main
```

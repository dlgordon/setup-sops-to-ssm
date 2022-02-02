# :gear: `setup-sops-to-ssm`

## About
This action can be run on `ubuntu-latest` GitHub Actions runners, and will install and expose a specified version of the `sops-to-ssm` CLI on the runner environment.

## Usage

Setup the `sops-to-ssm` CLI:

```yaml
steps:
- uses: dlgordon/setup-sops-to-ssm@v1
```

A specific version of the `gh` CLI can be installed:

```yaml
steps:
- uses: github-developer/setup-sops-to-ssm@v1
  with:
    version:
      1.1.0
```

## Inputs
The actions supports the following inputs:

- `version`: The version of `sops-to-env` to install, defaulting to `0.0.2`

## License
[MIT](LICENSE).

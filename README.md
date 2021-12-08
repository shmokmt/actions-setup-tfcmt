# actions-setup-tfcmt

[![Setup test](https://github.com/shmokmt/actions-setup-tfcmt/actions/workflows/test.yml/badge.svg)](https://github.com/shmokmt/actions-setup-tfcmt/actions/workflows/test.yml)

The shmokmt/setup-tfcmt action installs [suzuki-shunsuke/tfcmt](https://github.com/suzuki-shunsuke/tfcmt) to the `PATH` in your GitHub Actions.

## `Inputs`

version
Optional The version of tfcmt. Default "latest".

## Usage

This action can run be on `ubuntu-latest` and `macos-latest`.

Use latest version

```
steps:
- uses: shmokmt/setup-tfcmt@v1
```

Use specific version

```
steps:
- uses: shmokmt/setup-tfcmt@v1
  with:
    terraform_version: v2.1.0
```

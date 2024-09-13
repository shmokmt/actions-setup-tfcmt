# actions-setup-tfcmt

[![Setup test](https://github.com/shmokmt/actions-setup-tfcmt/actions/workflows/test.yml/badge.svg)](https://github.com/shmokmt/actions-setup-tfcmt/actions/workflows/test.yml)

The shmokmt/actions-setup-tfcmt action installs [suzuki-shunsuke/tfcmt](https://github.com/suzuki-shunsuke/tfcmt) to the `PATH` in your GitHub Actions.

## `Inputs`

### `version`

Optional. The version of tfcmt. Default is "latest".

## Usage

This action can run be on `ubuntu-latest` and `macos-latest`.

Use latest version

```yaml
steps:
  - uses: shmokmt/actions-setup-tfcmt@v2
```

Use specific version

```yaml
steps:
  - uses: shmokmt/actions-setup-tfcmt@v2
    with:
      version: v4.13.0
```

# References

- [tfcmt official docs](https://suzuki-shunsuke.github.io/tfcmt/)
- [tfcmt のいい感じのテンプレート Zenn](https://zenn.dev/bm_sms/articles/b1e4778f5b40e9)

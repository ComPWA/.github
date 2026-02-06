# Public ComPWA GitHub profile

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/ComPWA/.github/main.svg)](https://results.pre-commit.ci/latest/github/ComPWA/.github/main)
[![Spelling checked](https://img.shields.io/badge/cspell-checked-brightgreen.svg)](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

This repository manages the GitHub profile and repository templates for the [ComPWA Organization](https://github.com/ComPWA).

- [`profile/README.md`](./profile/README.md) is the profile content seen on the [ComPWA Organization page](https://github.com/ComPWA).
- [`workflow-templates`](./workflow-templates) provide [shared workflow templates](https://docs.github.com/en/actions/learn-github-actions/sharing-workflows-with-your-organization).

## Contributing

Install [`uv`](https://docs.astral.sh/uv) and install [`pre-commit-uv`](https://pypi.org/project/pre-commit-uv) as a tool:

```shell
uv tool install pre-commit --with pre-commit-uv --force-reinstall
```

Next, install the pre-commit hooks (see [`.pre-commit-config.yaml`](./.pre-commit-config.yaml))

```shell
pre-commit install --install-hooks
```

so that style checks are performed whenever you commit to this repository.

# Prerequisites

* `Node` >= 14.x
* `yarn` >= 1.12.15
* `vercel cli` >= 24.2.4
* [`pre-commit`](https://pre-commit.com/) >= 2.19.0

#### `pre-commit` configuration

Run the following command from the root of the repo to setup hooks:

```bash
pre-commit install # for all hooks
pre-commit install --hook-type commit-msg # for commitlint checks
```

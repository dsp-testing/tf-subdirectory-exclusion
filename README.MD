# Example repository to test dependabot

We created this repo to reproduce the behavior when dependabot runs in a sub-directory of a repository.

## How to reproduce

1. Clone this repository
2. Install the [dependabot cli](https://github.com/dependabot/cli?tab=readme-ov-file#installation)
3. Run the following command from the root of this repo:

```bash
dependabot update terraform dsp-testing/tf-subdirectory-exclusion -d examples/basic
```

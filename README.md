# 31420

Reproduction repo for [Discussion 31420](https://github.com/renovatebot/renovate/discussions/31420).

## Current behavior

When [tracking tags in .gitmodules](https://docs.renovatebot.com/modules/manager/git-submodules/#updating-to-specific-tag-values), if a submodule uses branches with semver naming, renovate will update to branches instead of only tracking tags.

## Expected behavior

When tracking tags in .gitmodules, renovate only updates to tags with a higher version, not to branches with names that match the semver pattern of a higher version.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/31420

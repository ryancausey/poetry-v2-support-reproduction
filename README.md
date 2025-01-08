# #33455

Support Poetry v2 dependency format

## Current behavior

Currently, renovate bot will only update the dependency value in the
`project.dependencies`, and `project.optional-dependencies` lists, and will not update
the lockfile.

## Expected behavior

The renovate bot should also update the lockfile.

## Link to the Renovate issue or Discussion

[Original discussion](https://github.com/renovatebot/renovate/discussions/33455)

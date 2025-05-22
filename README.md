# 36086

## Current behavior

1. Renovate detects a multiple updates.
2. The last major and minor updates are always less than 2 weeks old, so Renovate does not create PRs for them.
4. I get PRs only for very old versions.

On 2025-05-22 15:37
* Current dependency version: `40.3.4`

## Expected behavior

1. Let's say, there is a major update.
2. If any version within the range of this major update was release more than 2 weeks ago, a PR is created for the version.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/36086

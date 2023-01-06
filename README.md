## Description

Create major, minor and patch sematic version tags of an existing Docker image,
utilizing info from release-please pull requests.

The existing Docker image must have the commit's SHA as tag, and a corresponding
merged pull request created by release-please. Otherwise the SHA ref can't be looked up.

<!-- action-docs-inputs -->

## Inputs

| parameter       | description                                                                                                                                                                                                   | required | default             |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ------------------- |
| image           | Name of the docker image (e.g. `"my-namespace/my-image"`)                                                                                                                                                     | `true`   |                     |
| version         | Manually provided semantic version (e.g: 0.3.4)                                                                                                                                                               | `true`   |                     |
| registry        | Docker registry                                                                                                                                                                                               | `true`   | docker.io           |
| username        | Docker username                                                                                                                                                                                               | `true`   |                     |
| password        | Docker password                                                                                                                                                                                               | `true`   |                     |
| push-latest-tag | Push `latest` tag to repository, in addition to version tags                                                                                                                                                  | `false`  | true                |
| add-pr-label    | Add label `"version tagged: $inputs.registry"` to the relevant release-please created pull request                                                                                                            | `true`   | true                |
| pr-label-color  | PR label color                                                                                                                                                                                                | `true`   | #0db7ed             |
| token           | Token for interacting with the Github API. Default to using the special GITHUB_TOKEN. Because of limitations imposed by GitHub, this must be set if you want the setting of the PR label to trigger an event. | `true`   | ${{ github.token }} |

<!-- action-docs-inputs -->

<!-- action-docs-outputs -->

## Outputs

| parameter  | description                                  |
| ---------- | -------------------------------------------- |
| version    | The version that was passed in to the action |
| commit-sha | Commit SHA that correlates to this version   |
| pr-number  | PR number that correlates to this version    |

<!-- action-docs-outputs -->

<!-- action-docs-runs -->

## Runs

This action is a `composite` action.

<!-- action-docs-runs -->

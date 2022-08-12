<!-- action-docs-description -->

## Description

Create major, minor and patch sematic version tags of an existing Docker image.

The existing Docker image must have the commit's SHA as tag, and a corresponding
merged pull request created by release-please. Otherwise the SHA ref can't be looked up.

<!-- action-docs-description -->

<!-- action-docs-inputs -->

## Inputs

| parameter       | description                                                                                               | required | default |
| --------------- | --------------------------------------------------------------------------------------------------------- | -------- | ------- |
| version         | Manually provided semantic version (e.g: 0.3.4)                                                           | `true`   |         |
| docker-registry | Docker registry                                                                                           | `true`   |         |
| docker-username | Docker username                                                                                           | `true`   |         |
| docker-password | Docker password                                                                                           | `true`   |         |
| docker-image    | Name of the docker image                                                                                  | `true`   |         |
| add-pr-label    | Add label `"version tagged: $inputs.docker-registry"` to the relevant release-please created pull request | `true`   | true    |
| pr-label-color  | PR label color                                                                                            | `true`   | #0db7ed |

<!-- action-docs-inputs -->

<!-- action-docs-outputs -->

## Outputs

| parameter  | description                                  |
| ---------- | -------------------------------------------- |
| version    | The version that was passed in to the action |
| commit_sha | Commit SHA                                   |

<!-- action-docs-outputs -->

<!-- action-docs-runs -->

## Runs

This action is a `composite` action.

<!-- action-docs-runs -->

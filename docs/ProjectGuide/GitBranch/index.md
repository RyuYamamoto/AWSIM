# Git branch

!!! warning

    We have not started this branch operation yet, we will start it after the main branch is stable. 

## Branches

|branch|explain|
|:--|:--|
|main|Stable branch. All the latest releases are included.|
|develop|Development Branch. Develops pre-release functionality.|
|feature/***|Feature implementation branch created from develop. <br>After implementation, it is merged into develop.|
|release/***|Release branch containing release functionality created from the develop branch. <br>it is merge into main.|
|gh-pages|Documentation hosted on GitHub pages.|

## Branch flow

![](image_0.png)

1. Create `feature/***` branch from develop.
1. Implement in `feature/***` branch.
1. Create a PR from the `feature/***` branch to `develop` branch. Merge.
1. Create `release/*** branch` from develop.
1. Create a PR from the `release/*** branch` to `main` branch. Merge.
<br>
<br>
<br>
<br>
<br>

    
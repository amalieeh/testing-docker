# Dr. Dropin Fysikalske: Contributing Documentation

In this guide, you will get an overview of the contribution workflow: Going from
opening an issue, resolving that issue, creating a pull request, reviewing
another developer's pull request, and merging your code into the `main` branch.

To get an overview of the project, please read through the root
[`README.md`](README.md).

## Issue tracking

### Templates

GitHub issue templates have been set up to streamline the process of creating a
new issue. A reference guide can be found using
[this link](https://docs.github.com/es/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository).

An issue can either be a
[**Feature Request**](.github/ISSUE_TEMPLATE/feature_request.md), a
[**Bug**](.github/ISSUE_TEMPLATE/bug_report.md) or **Uncategorized**. Please inspect
the raw Markdown code when viewing these templates.

### Labels

Each issue is assigned one or multiple labels. The labels serve to
prioritize, scope and categorize the issues.

### Connecting issues to pull requests

An issue should always be closed by a pull request, unless the issue is
obviously not connected to part of the code base.

### Scope of an issue

An issue should not be too large. We seek to scope an issue to a maximum work
length of 12 hours. If the issue must be larger than that, the issue must have a
checklist of subtasks.

#### Example: Scope of an issue

Issue name: **#10 - Setup frontend**

- [x] Add dependencies
- [ ] Make controllers
- [ ] etc...

## Commit Culture

In short, a commit should be short, concise and descriptive.

### Commit title

For some commits, only a commit title is sufficient. Sometimes, adding a
description explaining what is done, and why it is done is helpful for new
developers joining the project.

Commit messages must be categorized. One should not blend or mix categories in
one single commit, in order to maintain a clean Git timeline and to increase
readability for the developer.

## Branches and pull requests

### Naming

Branch names should be clear and concise, and be marked with the id number of
the issue it resolves. Example: `feat/#10-frontend`.

### Description

The description of a pull request includes a **Changelog / Summary** of the new
functionality added. Optionally, a short description about how to test the new
functionality can be added in order to help the code reviewer.

### Squash and merge

Before merging, the commits in the branch to merge must be squashed. This cleans
up the Git timeline.

### Important to note

All origin branches are deleted after merging in order to keep the Git timeline
clean. This causes individual commits per branch to be squashed, and thus not
visible from the main branch.

If you wish to inspect individual commits per merged branch, please navigate to
the pull request in the remote repository on GitHub.

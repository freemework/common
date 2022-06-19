# Freemework

[Freemework](https://docs.freemework.org) is a general purposes framework with goal to provide cross language API. Learn API once - develop for any programming language.

## Freemework Common Library

This is workspace branch of **Freemework Common Library** multi project repository based on [orphan](https://git-scm.com/docs/git-checkout#Documentation/git-checkout.txt---orphanltnew-branchgt) branches.

Branches (sub-projects):

* `docs` - Sources of library [documentation](https://docs.freemework.org/common).
* `src-csharp` - C# Sources
* `src-dart` - Dart Sources
* `src-python` - Python Sources
* `src-typescript` - TypeScript Sources

## Get Started

```shell
git clone git@github.com:freemework/common.git freemework.common
cd freemework.common
for BRANCH in docs src-csharp src-dart src-python src-typescript; do git worktree add "${BRANCH}" "${BRANCH}"; done
code "Freemework Common.code-workspace"
```

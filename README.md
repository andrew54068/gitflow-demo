# gitflow-demo

A walkthrough of the Git Flow branching workflow. It illustrates how feature branches, bug fixes, releases, and hotfixes interact across `develop` and `main` — including a bug that reappears across releases and a critical bug that has to be hotfixed against an older release line.

## Sequence

1. feature 1-1
2. bug 1-1
3. release 1-1
4. feature 1-2
5. bug 1-1 (recurs)
6. release 1-2
7. feature 2-1
8. release 2-1
9. critical bug 1-2 (hotfix against release 1-2)

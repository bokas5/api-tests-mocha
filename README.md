
# End to end API tests
The project was created to eliminate the need for Postman and to have a more structured and flexible approach to writing API tests. It will also be
easier to run the tests on the pipeline and have the latest version, no matter how many collaborators there are.

# Setup

```bash
$ npm install
```

# Contribution rules
If you want to add to the project, you should follow some basic steps regarding branch creation and commits.

## Branches
The branch name should reflect the intention of the work you're doing. If you're adding new tests, the branch name should be
prefixed with `test_<branch_name>`, if the work is fixing some existing issues/bugs, it should be prefixed `fix_<branch_name>`.

## Commit messages
The commit message doesn't have to be long, but is should describe the work that was done. Again, as with the branch names, the
commit prefix should let the reader know right away what the change is about, if it's a new test, you should
add `test: <commit_message>`, if it's a fix, then `fix: <commit_message>`.

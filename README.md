tsclint
================

Pre-commit hook that runs `tsc` to check for compile-time errors.

For pre-commit: see https://github.com/pre-commit/pre-commit


### Using tsclint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/GoodTimeio/tsclint
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: tsc

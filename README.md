prettier-tslint mirror
================

Mirror of prettier-tslint package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For prettier-tslint: see https://github.com/palantir/tslint


### Using prettier-tslint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/GoodTimeio/mirrors-tslint
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: tslint

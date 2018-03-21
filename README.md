puppet-lint mirror
================

Mirror of puppet-lint gem for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For puppet-lint: see http://puppet-lint.com


### Using puppet-lint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/pre-commit/mirrors-puppet-lint
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: puppet-lint

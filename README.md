# minimal-reproduction-template

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

The Ansible manager detects the dependency as `spellchecker/disable-line` which
is clearly coming from the comment.

## Expected behavior

The Ansible manager should detect the dependency as `community.hashi_vault`.

## Link to the Renovate issue or Discussion



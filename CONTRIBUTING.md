# How to Contribute

Thank you for taking your time and wanting to contribute to this project. Please follow these guidelines on how to contribute.

## Project Vision

This project is a very lightweight wrapper on top of `jq` and `fzf`.
It strictly relies on `fzf`, `jq` and `sh` for the heavy lifting.
Complex shell gymnastics is not to be done in this project.
Simplicity has some very important advantages. A small codebase means:
* less bugs
* fixing bugs is more evident
* less maintenance

tl;dr - Keep it Simple, Stupid!

## These PR-s will not be merged

To align with the projects vision, most PR-s adding net new functionality will be rejected.
* PR-s for OS-specific, or compositor-specific logic will likely be rejected
* PR-s for shell-specific logic that's not zsh will be rejected. This project is a zsh plugin.
* Changes that include 20+ net new lines of code in a single change. See the project vision.

Forking is encouraged in case you want to have that functionality anyway.

## How a good PR looks like

When submitting PR-s please focus on scope.

* Don't pack PR-s with several different distinct changes
* Don't fix bugs in a feature PR
* Don't add doc changes like usage tips to bug fix or feature PR-s. Stick to documenting the feature.
* Keep the change small. Getting multiple small and incremental changes has a higher chance of getting some of them merged.

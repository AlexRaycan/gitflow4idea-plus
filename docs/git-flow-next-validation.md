# git-flow-next Integration Validation

Manual steps to verify the plugin recognizes git-flow-next:

1. Install git-flow-next (for example via Homebrew: `brew install gittower/tap/git-flow-next`).
2. Restart the IDE and open a Git repository with git-flow initialized.
3. Open the IDE status bar widget. It should display "Gitflow" instead of the unsupported version warning.
4. Run any git-flow command from the UI (e.g. start a feature) and confirm it completes without CLI errors.
5. If the widget reports an unsupported version, check that `git flow version` outputs a line containing `git-flow-next` and that the binary is resolvable on the system `PATH`.

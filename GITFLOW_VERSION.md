The plugin requires a maintained Git Flow implementation. We support and recommend [git-flow-next](https://github.com/gittower/git-flow-next), which keeps compatibility with the classic workflow while providing active development and modern binaries.

**How to check your Git Flow version**

Run `git flow version`. Any output that mentions `git-flow-next` is supported. The unmaintained NVIE 0.4.x release and older custom builds are not.

**Recommended installation**

- macOS/Linux (Homebrew):
	- `brew install gittower/tap/git-flow-next`
- Alternative: download the latest release from [GitHub Releases](https://github.com/gittower/git-flow-next/releases), place the `git-flow` binary somewhere on your `PATH`, and make it executable (`chmod +x /path/to/git-flow`).

**Replacing older versions**

If you previously installed `git-flow` via Homebrew, uninstall it before switching:

```
brew uninstall git-flow
```

Then install `git-flow-next` as shown above.

**Troubleshooting**

If you see errors like `Gitflow is not installed` or `git: 'flow' is not a git command`, ensure that the `git-flow` binary provided by git-flow-next is available on your `PATH`. For additional help, review [issue #7](https://github.com/OpherV/gitflow4idea/issues/7).

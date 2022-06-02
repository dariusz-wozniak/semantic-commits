# Semantic Commit Messages

See how a minor change to your commit message style can make you a better programmer.

Format: `<type> (<scope>): <subject>`

`<scope>` is optional

## Example

```
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style [...]
```

Or, with the scope:

```
feat (main page): add hat wobble
^--^ ^--------^  ^------------^
|    |           |
|    +-> Scope (optional)
|                |
|                +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style [...]
```

## Prefixes

- `benchmark`: benchmarks-related code
- `buildfix`: e.g. add missing semicolon
- `bump`: version update
- `chore`: e.g. updating grunt tasks; no production code change
- `config`: changes in configuration
- `cross-cutting`: e.g. logging, dependency injection
- `ci`: changes to the build/release config
- `deploy`: changes to deployment scripts
- `docs`: changes to the documentation
- `feat`: new feature for the user, not a new feature for build script
- `fix`: bug fix for the user, not a fix to a build script
- `format`: formatting, e.g. tabs to/from spaces, remove trailing whitespace
- `localize`: translations update
- `performance`: performance improvements
- `refactor`: refactoring production code
- `style`: change in frontend styling
- `test`: adding missing tests, refactoring tests; no production code change

# References

- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html
- https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716

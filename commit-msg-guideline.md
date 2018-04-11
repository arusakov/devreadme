Commit Message Guidelines
=========================
Based on [angular-cli](https://github.com/angular/angular-cli/blob/master/CONTRIBUTING.md#commit) contributing guide.

Format
------
```
<issue_id> <type>(<scope>): <subject>
```
`<issue_id>` and `(<scope>)` are optional

Type
----
Must be one of the following:
* `build`: Changes that affect the build system or external dependencies
* `ci`: Changes to our CI configuration files and scripts
* `docs`: Documentation only changes
* `feat`: A new feature
* `fix`: A bug fix
* `perf`: A code change that improves performance
* `refactor`: A code change that neither fixes a bug nor adds a feature
* `style`: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
* `test`: Adding missing tests or correcting existing tests
* `chore`: If none of the above is appropriate

Scope
-----
Scope describes some logical peace of changing, for example:
* part of complex logic/functional
* section of website (for frontend)
* HTTP endpoint (for backend)

Subject
-------
The subject contains succinct description of the change:
* use the imperative, present tense: "change" not "changed" nor "changes"
* don't capitalize first letter
* no dot (.) at the end
# Fullstack Web Project (Angular + NestJS)

## Installation

```bash
git clone https://github.com/Lakhdher/projet_web_angular.git
cd projet_web_angular
git submodule init
git submodule update --remote --rebase
git submodule foreach --recursive git checkout dev
```

## Standards

### commit messages:

commit messages should follow the following pattern:

```bash
type(<scope*>): subject
```
*: scope is optional

>The commit type can include the following:
>- **feat** : a new feature is introduced with the changes
>- **fix** : a bug fix has occurred
>- **chore** : changes that do not relate to a fix or feature and don't modify src or test files (for example updating dependencies)
>- **refactor** : refactored code that neither fixes a bug nor adds a feature
>- **docs** : updates to documentation such as a the README or other markdown files
>- **style** : changes that do not affect the meaning of the code, likely related to code formatting such as white-space, missing semi-colons, and so on.
>- **test** : including new or correcting previous tests
>- **perf** : performance improvements
>- **ci** : continuous integration related
>- **build** : changes that affect the build system or external dependencies
>- **revert** : reverts a previous commit

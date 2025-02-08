# ZNGR DYNAMICS
## Creating stunning web experiences. 
Carefully manufactured web-experiences to represent your mission world-wide. From individuals to corporate. 

Welcome to [ZNGR DYNAMICS](https://zngr-dynamics.ch/). 

This GitHub organization includes all projects from ZNGR, created for clients or for the platform itself. 

Documentation about the platform and projects is private. 

## Tech Stack
We create stunning web-experiences incorporating newest trends and features with the help of the following tech stack. 

<img src="https://skillicons.dev/icons?i=nextjs,react,vite,ts,html,css,js,php,mysql,mongodb,notion,md,figma"/>

## Git Convention
The following naming convention helps maintain an organized workspace across all ZNGR DYNAMICS projects with git <img src="https://skillicons.dev/icons?i=git" width="24" height="24" /> 

### Commits
Convention across commits through git. 
#### Function Types
All commits focus on different types of changes, like implementing a new feature `feat:`, changes to styling `style:`, or refactoring `refactor:` a piece of code inside a file. Here's a list of all function types of commits performable in commits. Function in this context is not to confuse with code-functions. 



- `feat:` Commits, implementing a feature or otherwise new addition to the code-base.
- `style:` Commits, primarily affecting changes in styling. Every feature may include styling changes, the `feature` type should be prioritized. 
- `build:` Commits, affecting build components, like build-tool, dependencies, ci pipeline, project version, etc.
- `test:` Commits, implementing missing tests or maintaining existing.
- `fix:` Commits, fixing a bug or other issue tied to a previously committed feature. 
- `refactor:` Commits, refactoring or otherwise editing code, without implementing or removing functionality.
- `ops:` Commits, affecting infrastructure, deployment, backup, recovery.
- `chore:` Miscellaneous commits, e.g. modifying .gitignore.

#### Scopes
With every change, the commit can be narrowed down to a feature or section of the code. Scopes are optional and added through parenthesis `(<scope>)` before the colon `:`, but should be used where applicable. The content of scopes varies by project. All function types are applicable to scopes. 

Scopes should always be written out to avoid any confusion, e.g. `(navigation)`, not `(nav)` | `(dependency)`, not `(dep)`.

- `feat(menu):` Feature commits, implementing, adding functionality, or adding a feature to the menu.
- `test(navigation):` Test commit, implementing or maintaining a written test, testing nav behavior.

#### Commit Message
Commits should always have a short, precise, and informative message of changes made in the commit. Commit messages should be written in the infinitive. The commit message should not explain why a commit has been made (this is kept in the project management tool). 

#### Indicators
By adding one of the three characters before colons `:`, commits can be marked as `breaking` through `!`, `warning` through `?`, or `in progress` as `*`. 

Breaking changes, marked as `!` should indicate changes which may cause incompatibility with other code components or cause errors. 

Changes marked with an `?` should indicate current commits to possibly throw warnings. 

Commits set as `in-progress` changes through `*` indicate the scope or code-function to be still in work, or the feature not being complete, and therefore behaving unexpectedly. In-Progress commits can only be marked as such, when the expected is already known, through a task entry, e.g. in the project management tool. 

> [!NOTE]
> Indicators are especially useful when not being able to resolve an error or warning directly, and it is to be pushed. Pulling a marked commit avoids confusion, why an error or warning appears in the logs. 

- `build(dependency)!` Build commit, signaling the changes to cause errors, or be uncompatible with the previous commit.
- `refactor(button)?` Refactor commit, signaling the button to throw a warning, which is yet to be resolved. 
- `style(navigation)*` Style commit, signaling the scope to be incomplete. 

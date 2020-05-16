# Andrius B. (WIP)

I am a software developer based in Vilnius, Lithuania. I am working in software development since 2005.

This page is a summary of what technologies and practices I am familiar with and my notes in various form: cheatsheets, bookmarks, project-starter-templates, proof-of-concepts, etc.

## Technologies

Notation of knowledge level:

- `***` I know it well, no additional studying would be needed (studied in detail / used in real projects recently)
- `**` Some studying/refreshing may be needed (studied it / used in real projects a while ago / have some proof-of-concepts, etc)
- `*` Studying would be needed (I know _why_ and _when_ it should be used, but not much about _how_)

Other notation:

- `PN` TODO to study more with prio N
- `TODO` TODO to update this page

| Category                  | Level | Technology       | Notes                                 |
| :------------------------ | :---- | :--------------- | ------------------------------------- |
| **FRONTEND DEVELOPMENT**  |       |                  |                                       |
| Styling                   | `**`  | HTML+CSS/SASS    |                                       |
|                           | `**`  | Bootstrap        |                                       |
| Languages                 | `***` | Javascript (ES6) |                                       |
|                           | `**`  | Typescript       |                                       |
| App frameworks            | `***` | React+Flux/Redux |                                       |
|                           | `**`  | Vue+Vuex         | `P1`                                  |
| Libraries                 | `**`  | jQuery           |                                       |
|                           | `*`   | RxJS             | `P2`                                  |
| Tools                     | `**`  | Webpack          |                                       |
|                           | `**`  | ESLint           |                                       |
|                           | `**`  | Bower+Grunt/Gulp |                                       |
|                           | `**`  | NPM              |                                       |
|                           | `*`   | Yarn             | `P2`                                  |
| **BACKEND DEVELOPMENT**   |       |                  |                                       |
| **(PYTHON STACK)**        |       |                  |                                       |
|                           |       | ...              |                                       |
| **BACKEND DEVELOPMENT**   |       |                  |                                       |
| **(PYTHON DJANGO STACK)** |       |                  |                                       |
|                           |       | ...              |                                       |
| **BACKEND DEVELOPMENT**   |       |                  |                                       |
| **(.NET STACK)**          |       |                  |                                       |
|                           |       | ...              |                                       |
| **DEVELOPMENT (OTHER)**   |       |                  |                                       |
| Version control           | `**`  | Git              | [cheatsheet](notes/git/cheatsheet.md) |
| Selenium tests            | `**`  | Robot framework  | `TODO` add POC                        |
| **DEVOPS**                |       |                  |                                       |
| Tools                     | `**`  | Docker           |                                       |
|                           | `**`  | Docker compose   |                                       |
|                           | `**`  | Kubernetes       |                                       |
|                           | `**`  | Bash scripting   |                                       |
| CI/CD systems             | `***` | GitLab CI        |                                       |
|                           | `**`  | Jenkins          |                                       |
|                           | `*`   | Travis CI        |                                       |

## Best practices

Notation of pactice usage level:

- `***` I have used it and would use in next projects
- `**` I have not used it, but willing to try in next projects
- `*` I have not used it and also have doubts if it is for every situation

| Category                       | Level | Practice                               | Tools                                                      |
| :----------------------------- | :---- | :------------------------------------- | ---------------------------------------------------------- |
| **DEVELOPMENT ENV & CI SETUP** |       |                                        |                                                            |
| Local dev environment          | `***` | One line command to start the project  | `docker-compose`, `make`                                   |
|                                | `***` | Makefiles to manage package installs   | `make`                                                     |
| Checks (local & CI)            | `***` | Unit testing                           | `jest`, `pytest`                                           |
|                                | `***` | Enforced code style                    | Linters `eslint`, `flake8`, formatters `prettier`, `black` |
|                                | `**`  | Enforced code complexity limit         | `flake8` with `max-complexity` param                       |
|                                | `***` | Enforced unit test coverage percentage | `pytest-cov` with `fail_under` param                       |
|                                | `***` | Static security checks                 | `npm audit`, `snyk`, `bandit`                              |

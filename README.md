# Andrius B. (WIP)

I am a software developer based in Vilnius, Lithuania. I am working in software development since 2005.

This page is a summary of what technologies and practices I am familiar with and my notes in various form: cheatsheets, bookmarks, project-starter-templates, proof-of-concepts, etc.

## Roles

These are the roles I worked in. Some of them overlap in time, as I have been covering several roles in parallel in recent years.

**2016-2020**

Tech lead:

- Performing daily code reviews
- Tech discussions with architects and other teams
- Documenting the architecture
- Holding career meetings & job interviews
- Introducing and supporting new team memebers

Devops:

- CI/CD setup
- Performance testing and tuning
- Preparing deployment plans, performing deployments
- Setting up new environments in cooperation with ops.

**2014-2020**

Senior developer:

- Building systems from scratch
- Rewriting systems
- Refactoring major parts

Scrum master / technical project manager:

- Setting and documenting the development process:
  - Git process
  - Jira workflow
  - Sprint goals and other measurements
  - Retrospective notes and tracking improvements
- Arranging and holding scrum meetings:
  - weekly/bi-weekly sprint planning calls (review, demo, planning, retrospective)
  - backlog grooming sessions
  - daily devs discussions & daily scrum
- Plan preparation with service owners and product owners (goals, schedule, versions, tickets):
- Performing feature demonstrations, other presentations
- Making sure there is always clear work and priorities for everyone in the team

**2005-2014**

Developer:

- Doing development tasks
- Participating in system design discussions with team

**2005-2007**

System analyst:

- Discussing & collecting requirements with clients
- Documenting requirements

## Technologies

In short:

- 2016-2020 React + python single page app development
- 2005-2016 ASP.NET + SQL Server app development
- Studied and experimented with a lot more

Notation:

- `***` I know it well, no additional studying would be needed (studied in detail / used in real projects recently)
- `**` Some studying/refreshing may be needed (studied it / used in real projects a while ago)
- `*` Studying would be needed (I know _why_ and _when_ it should be used, but not much about the details of _how_)
- `PN` TODO to study more with prio N
- `TD` TODO to add notes
- `TDPOC` TODO to add Proof-Of-Concept

| Category                         | Level     | Technology                   | Notes / starter-templates / experiments          |
| :------------------------------- | :-------- | :--------------------------- | :----------------------------------------------- |
| **FRONTEND DEVELOPMENT**         |           |                              |                                                  |
| Styling                          | `**`      | HTML+CSS/SASS                |                                                  |
|                                  | `**`      | Bootstrap                    |                                                  |
| Languages                        | `***`     | Javascript (ES6)             |                                                  |
|                                  | `**`      | Typescript                   |                                                  |
| App frameworks                   | `***`     | React + Flux/Redux           |                                                  |
|                                  | `**` `P1` | Vue+Vuex                     |                                                  |
| Libraries                        | `***`     | jQuery                       |                                                  |
|                                  | `*` `P2`  | RxJS                         |                                                  |
| Tools                            | `**`      | Webpack                      |                                                  |
|                                  | `**`      | ESLint                       |                                                  |
|                                  | `**`      | Bower + Grunt/Gulp           |                                                  |
|                                  | `**`      | NPM                          |                                                  |
|                                  | `*` `P2`  | Yarn                         |                                                  |
| **BACKEND DEVELOPMENT (PYTHON)** |           |                              |                                                  |
| Langauge                         | `***`     | Python                       |                                                  |
| App frameworks                   | `***`     | Bottle                       |                                                  |
|                                  | `**`      | Flask                        |                                                  |
|                                  | `*`       | Django                       |                                                  |
| ORMs & migration tools           | `**`      | SqlAlchemy + Alembic `TDPOC` |                                                  |
|                                  | `**`      | DjangoORM `TDPOC`            |                                                  |
| REST API                         | `*` `P1`  | FlaskRest `TDPOC`            |                                                  |
|                                  | `*` `P1`  | Schematics                   |                                                  |
|                                  | `*`       | DjangoREST `TDPOC`           |                                                  |
| GraphQL API                      | `*`       | Graphene                     |                                                  |
| Async tasks                      | `*`       | Celery + RabbitMQ `TDPOC`    |                                                  |
| Queue                            | `*`       | pika + RabbitMQ `TDPOC`      |                                                  |
| Web server setup                 | `**`      | nginx + uwsgi                | Starter template: [uwsgi-nginx](poc/uwsgi-nginx) |
| **BACKEND DEVELOPMENT (.NET)**   |           |                              |                                                  |
| ...                              |           | ... `TD`                     | Notes: [dotnetcore](notes/dotnetcore.md)         |
| **DATABASES**                    |           |                              |                                                  |
| Relational                       | `*`       | PostgreSQL `TDPOC`           |                                                  |
|                                  | `*`       | MySQL                        |                                                  |
|                                  | `**`      | MS SQL Server                |                                                  |
| NoSQL                            | `**`      | Redis `TDPOC`                |                                                  |
|                                  | `*`       | MongoDB `TDPOC`              |                                                  |
| Search engines                   | `*`       | Elastic search               |                                                  |
| **DEVELOPMENT (OTHER)**          |           |                              |                                                  |
| Version control                  | `**`      | Git                          | Notes: [git](notes/git.md)                       |
| Selenium tests                   | `**`      | Robot framework              | Starter template: [robots](poc/robots)           |
| Authentication                   | `**`      | OAuth, JWT `TDPOC`           |                                                  |
| **DEVOPS**                       |           |                              |                                                  |
| Tools                            | `**`      | Docker & docker-compose      | Notes: [docker](notes/docker.md)                 |
|                                  | `P1`      | Helm                         |                                                  |
|                                  | `**`      | Kubernetes                   | Notes: [kubectl](notes/kubectl.md)               |
|                                  | `**`      | Bash                         | Notes: [bash](notes/bash.md)                     |
| CI/CD systems                    | `***`     | GitLab CI                    |                                                  |
|                                  | `**`      | Jenkins                      |                                                  |
|                                  | `*`       | Travis CI                    |                                                  |
| Monitoring                       | `**`      | NewRelic                     |                                                  |
|                                  | `**`      | Graylog                      |                                                  |
|                                  | `*`       | Sentry                       |                                                  |
|                                  | `*`       | Graphite & Graphana `TDPOC`  |                                                  |
|                                  | `*`       | Google analytics             |                                                  |
| Perofmance testing               | `**`      | Locust                       | Starter template: [perf-tests](poc/perf-tests)   |

## Best practices

Notation:

- `***` I have used it and would use in next projects
- `**` I have not used it, but willing to try in next projects
- `*` I have not used it and also have doubts if it is for every situation
- `?` Just an untested idea

| Category            | Level | Practice (tools used)                                            | Notes / starter-templates / experiments                   |
| :------------------ | :---- | :--------------------------------------------------------------- | :-------------------------------------------------------- |
| **ENVS & CI/CD**    |       |                                                                  |                                                           |
| Local env           | `***` | One line command to start the project (`docker-compose`, `make`) |                                                           |
|                     | `***` | Makefiles to manage package installs (`make`)                    |                                                           |
|                     | `**`  | Prod-like dev env (`docker`)                                     |                                                           |
|                     | `**`  | Convenient way to reload (`webpack hot-reload`)                  |                                                           |
|                     | `**`  | Convenient way to debug (IDE in-line debugger, source-maps)      |                                                           |
| CI & local env      | `***` | Unit tests ( `jest`, `pytest` )                                  |                                                           |
|                     | `***` | Enforced code style - linters (`eslint`, `flake8` )              |                                                           |
|                     | `***` | Enforced code style - formatters (`prettier`, `black`)           |                                                           |
|                     | `**`  | Contolled code complexity `flake8` with param `max-complexity`   |                                                           |
|                     | `***` | Enforced test coverage (`pytest-cov` with param `fail_under`)    |                                                           |
|                     | `***` | Static security checks (`npm audit`, `snyk`, `bandit`)           |                                                           |
| CI                  | `***` | CI runs not only on commit, but also nightly                     |                                                           |
|                     | `*`   | Dynamic security tests (`OWASP ZAP`)                             |                                                           |
|                     | `***` | Integration tests (`robot-framework with selenium2`)             | Starter template: [robots](poc/robots)                    |
|                     | `***` | Prealpha environment for smoke testing before alpha              |                                                           |
|                     | `?`   | Automated memory leak checks                                     | Experiments: [memory-leaks](poc/mem-leaks)                |
|                     | `?`   | Ensuring clean error log during integration tests                |                                                           |
|                     | `?`   | Performance measurements during integration tests                |                                                           |
| CD                  | `***` | Keep track of deployed envs automatically (`GitLab CI` envs)     |                                                           |
|                     | `*`   | Pre-deploy dependency checks                                     |                                                           |
|                     | `***` | After-deploy version checks `TD`                                 |                                                           |
|                     | `**`  | Auto-scaling (`kubernetes`)                                      |                                                           |
|                     | `**`  | Rolling updates and avoided downtime (`kubernetes`)              |                                                           |
|                     | `**`  | Liveness, readyness checks and auto-recovery (`kubernetes`)      |                                                           |
| Monitoring          | `*`   | User usage metrics (`google-analytics`)                          |                                                           |
|                     | `***` | Server performance & alerts (`new relic`)                        |                                                           |
|                     | `**`  | Aggregated logs (`graylog`)                                      |                                                           |
|                     | `*`   | Custom metrics (`grafana`) `TDPOC`                               |                                                           |
|                     | `*`   | Incident tracker (`sentry`)                                      |                                                           |
|                     | `?`   | Health/smoke tests with selenium in production                   |                                                           |
| **APP DESIGN**      |       |                                                                  |                                                           |
| Any kind of apps    | `***` | Extensive logging                                                | Notes: [logging](notes/app-design/logging.md)             |
|                     | `***` | Special endpoints (version, liveness & readyness)                | Notes: [endpoints](notes/app-design/endpoints.md)         |
|                     | `***` | Stateless web app - external session and cache (`redis`)         |                                                           |
|                     | `***` | Framework / abstract class to enforce dev consistancy            |                                                           |
|                     | `***` | Mechanism to handle localizations properly                       | Notes: [localizations](notes/app-design/localizations.md) |
|                     | `**`  | (If needed) Consistant way to access various contexts            | Notes: [contexts](notes/app-design/contexts.md)           |
|                     | `**`  | (If needed) Feature switches (possibly for some users only)      |                                                           |
| Single page apps    | `*`   | Collect frontend logs to server                                  |                                                           |
|                     | `**`  | Keep permission & workflow logic in one place (backend)          |                                                           |
| API                 | `**`  | Documentation + callable client (`OpenAPI (swagger)`)            |                                                           |
|                     | `**`  | Strong input validation and clear messages                       |                                                           |
| Library development | `**`  | Semantic versioning                                              |                                                           |
|                     | `*`   | Strong typing language/features (Python3 type hints + `mypy`)    |                                                           |
|                     | `**`  | Change log / release notes                                       |                                                           |
|                     | `**`  | Upgrade example / instructions for breaking changes              |                                                           |
| DB design           | `*`   | Schema control even if no-sql does not enforce it                |                                                           |
|                     | `*`   | Change scripts should go with migrations + rollback script       |                                                           |
|                     | `*`   | Immutability (`event-sourcing`) or at least full audit           |                                                           |
|                     | `*`   | Full audit (`temporal tables`) if not immutability               |                                                           |
| User experience     | `**`  | Avoid heavily used sessions                                      |                                                           |
|                     | `*`   | (If session used heavily) Session expiration handling            |                                                           |
|                     | `**`  | Everything / many things should be accessible via url            |                                                           |
|                     | `**`  | Consistant form validation mechanism `TD`                        |                                                           |
|                     | `**`  | Consistant ajax loader mechanism                                 |                                                           |
| **DEV PROCESS**     |       |                                                                  |                                                           |
| Project-kickoff     | `***` | Define git-process                                               |                                                           |
|                     | `***` | Task workflow (states)                                           |                                                           |
|                     | `***` | Define definition of done                                        | Notes: [dod](notes/process/dod.md)                        |
| Daily development   | `***` | Commenting task merge request to the ticket (`GitLab` MRs)       |                                                           |
|                     | `***` | Peer review is performed before merging (`GitLab` MRs)           |                                                           |
|                     | `***` | Daily group review for knowledge sharing                         | Notes: [group-review](notes/process/group-review.md)      |
|                     | `**`  | Daily scrum                                                      |                                                           |
|                     | `**`  | Continous delivery to alpha                                      |                                                           |
|                     | `**`  | Marking external dependencies - in ticket and/or in code         |                                                           |
|                     | `*`   | Tests for new functionality and for new bugs found               |                                                           |
| Once in sprint      | `***` | Sprint review (overview, demo, feedback)                         |                                                           |
|                     | `***` | Sprint planning (goals, schedule, versions, tickets)             |                                                           |
|                     | `**`  | Backlog grooming and estimating                                  |                                                           |
|                     | `***` | Retrospective                                                    | Notes: [retro](notes/process/retro.md)                    |
| Before releases     | `***` | Arrange deployment freeze and regression testing in alpha        |                                                           |
|                     | `***` | Collect approvals (CAB)                                          |                                                           |
|                     | `***` | Release notes                                                    | Notes: [release-notes](notes/process/release-notes.md)    |
|                     | `***` | (When needed) Deployment plan and it's approvals                 |                                                           |
|                     | `***` | (When needed) Technical documentation updates                    |                                                           |
|                     | `**`  | (When needed) Performance testing in beta                        | Starter template: [perf-tests](poc/perf-tests)            |
|                     | `***` | (When needed) Security audit                                     |                                                           |
| **DOCUMENTATION**   |       |                                                                  |                                                           |
|                     |       | `TD`                                                             |                                                           |

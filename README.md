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
- Performance testing
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
- `TODO` TODO to update this page

| Category                         | Level     | Technology           | Notes                                 |
| :------------------------------- | :-------- | :------------------- | :------------------------------------ |
| **FRONTEND DEVELOPMENT**         |           |                      |                                       |
| Styling                          | `**`      | HTML+CSS/SASS        |                                       |
|                                  | `**`      | Bootstrap            |                                       |
| Languages                        | `***`     | Javascript (ES6)     |                                       |
|                                  | `**`      | Typescript           |                                       |
| App frameworks                   | `***`     | React + Flux/Redux   |                                       |
|                                  | `**` `P1` | Vue+Vuex             |                                       |
| Libraries                        | `***`     | jQuery               |                                       |
|                                  | `*` `P2`  | RxJS                 |                                       |
| Tools                            | `**`      | Webpack              |                                       |
|                                  | `**`      | ESLint               |                                       |
|                                  | `**`      | Bower + Grunt/Gulp   |                                       |
|                                  | `**`      | NPM                  |                                       |
|                                  | `*` `P2`  | Yarn                 |                                       |
| **BACKEND DEVELOPMENT (PYTHON)** |           |                      |                                       |
| Langauge                         | `***`     | Python               |                                       |
| App frameworks                   | `***`     | Bottle               |                                       |
|                                  | `**`      | Flask                |                                       |
|                                  | `*`       | Django               |                                       |
| ORMs & migration tools           | `**`      | SqlAlchemy + Alembic | `TODO` add POC                        |
|                                  | `**`      | DjangoORM            | `TODO` add POC                        |
| REST API                         | `*` `P1`  | FlaskRest            | `TODO` add POC                        |
|                                  | `*` `P1`  | Schematics           |                                       |
|                                  | `*`       | DjangoREST           | `TODO` add POC                        |
| GraphQL API                      | `*`       | Graphene             |                                       |
| Async tasks                      | `*`       | Celery + RabbitMQ    | `TODO` add POC                        |
| Queue                            | `*`       | pika + RabbitMQ      | `TODO` add POC                        |
| Web server setup                 | `**`      | nginx + uwsgi        | `TODO` add POC                        |
| **BACKEND DEVELOPMENT (.NET)**   |           |                      |                                       |
| ...                              |           | ...                  |                                       |
| **DATABASES**                    |           |                      |                                       |
| Relational                       | `*`       | PostgreSQL           | `TODO` add POC                        |
|                                  | `**`      | MS SQL Server        |                                       |
|                                  | `*`       | MySQL                |                                       |
| NoSQL                            | `**`      | Redis                | `TODO` add POC                        |
|                                  | `*`       | MongoDB              | `TODO` add POC                        |
| Search engines                   | `*`       | Elastic search       |                                       |
| **DEVELOPMENT (OTHER)**          |           |                      |                                       |
| Version control                  | `**`      | Git                  | [cheatsheet](notes/git/cheatsheet.md) |
| Selenium tests                   | `**`      | Robot framework      | `TODO` add POC                        |
| Authentication                   | `**`      | OAuth, JWT           | `TODO` add POC                        |
| **DEVOPS**                       |           |                      |                                       |
| Tools                            | `**`      | Docker               |                                       |
|                                  | `**`      | Docker compose       |                                       |
|                                  | `P1`      | Helm                 |                                       |
|                                  | `**`      | Kubernetes           |                                       |
|                                  | `**`      | Bash                 |                                       |
| CI/CD systems                    | `***`     | GitLab CI            |                                       |
|                                  | `**`      | Jenkins              |                                       |
|                                  | `*`       | Travis CI            |                                       |
| Monitoring                       | `**`      | NewRelic             |                                       |
|                                  | `**`      | Graylog              |                                       |
|                                  | `*`       | Sentry               |                                       |
|                                  | `*`       | Graphite & Graphana  | `TODO` add POC                        |
|                                  | `*`       | Google analytics     |                                       |
| Perofmance testing               | `**`      | Locust               | `TODO` add POC                        |

## Best practices

Notation:

- `***` I have used it and would use in next projects
- `**` I have not used it, but willing to try in next projects
- `*` I have not used it and also have doubts if it is for every situation
- `?` Just an untested idea

| Category            | Level | Practice                                                    | Notes / Tools used                              |
| :------------------ | :---- | :---------------------------------------------------------- | :---------------------------------------------- |
| **ENVS & CI/CD**    |       |                                                             |                                                 |
| Local env           | `***` | One line command to start the project                       | `docker-compose`, `make`                        |
|                     | `***` | Makefiles to manage package installs                        | `make`                                          |
|                     | `**`  | Prod-like dev env                                           | `docker`                                        |
|                     | `**`  | Convenient way to reload                                    | `webpack hot-reload`                            |
|                     | `**`  | Convenient way to debug                                     | Pycharm, VS code in-line debugger, source-maps  |
| CI & local env      | `***` | Unit tests                                                  | `jest`, `pytest`                                |
|                     | `***` | Enforced code style - linters                               | `eslint`, `flake8`                              |
|                     | `***` | Enforced code style - formatters                            | `prettier`, `black`                             |
|                     | `**`  | Enforced code complexity limit                              | `flake8` with `max-complexity` param            |
|                     | `***` | Enforced unit test coverage percentage                      | `pytest-cov` with `fail_under` param            |
|                     | `***` | Static security checks                                      | `npm audit`, `snyk`, `bandit`                   |
| CI                  | `***` | CI runs not only on commit, but also nightly                |                                                 |
|                     | `*`   | Dynamic security tests                                      | `OWASP ZAP`                                     |
|                     | `*`   | Integration tests                                           | `robot-framework with selenium2`                |
|                     | `***` | Prealpha environment for smoke testing before alpha         |                                                 |
|                     | `?`   | Automated memory leak checks                                | `TODO` add POC                                  |
|                     | `?`   | Ensuring clean error log during integration tests           |                                                 |
|                     | `?`   | Performance measurements during integration tests           |                                                 |
| CD                  | `***` | Keep track of deployed envs automatically                   | `GitLab CI environments`                        |
|                     | `*`   | Pre-deploy dependency checks                                | custom mechanism                                |
|                     | `***` | After-deploy version checks                                 | custom /version endpoints / `TODO` add snippet  |
|                     | `**`  | Auto-scaling                                                | `kubernetes`                                    |
|                     | `**`  | Rolling updates and avoided downtime                        | `kubernetes`                                    |
|                     | `**`  | Liveness, readyness checks and auto-recovery                | `kubernetes`                                    |
| Monitoring          | `*`   | User usage metrics                                          | `google-analytics`                              |
|                     | `***` | Server performance & alerts                                 | `new relic`                                     |
|                     | `**`  | Aggregated logs                                             | `graylog`                                       |
|                     | `*`   | Custom metrics                                              | `grafana` / `TODO` add POC                      |
|                     | `*`   | Incident tracker                                            | `sentry`                                        |
|                     | `?`   | Health/smoke tests with selenium in production              | `robot-framework with selenium2`                |
| **APP DESIGN**      |       |                                                             |                                                 |
| Any kind of apps    | `***` | Extensive logging                                           | [notes](notes/app-design/logging.md)            |
|                     | `***` | Special endpoints (version, liveness & readyness)           | [notes](notes/app-design/endpoints.md)          |
|                     | `***` | Stateless web app - external session and cache              | `redis`                                         |
|                     | `***` | Framework / abstract class to enforce dev consistancy       |                                                 |
|                     | `***` | Mechanism to handle localizations properly                  | [notes](notes/app-design/localizations.md)      |
|                     | `**`  | (If needed) Consistant way to access various contexts       | [notes](notes/app-design/contexts.md)           |
|                     | `**`  | (If needed) Feature switches (possibly for some users only) |                                                 |
| Single page apps    | `*`   | Collect frontend logs to server                             |                                                 |
|                     | `**`  | Keep permission & workflow logic in one place (backend)     |                                                 |
| API                 | `**`  | Documentation + callable client                             | `OpenAPI (swagger)`                             |
|                     | `**`  | Strong input validation and clear messages                  |                                                 |
| Library development | `**`  | Semantic versioning                                         |                                                 |
|                     | `*`   | Strong typing language or lang features                     | Python3 type hints + `mypy`                     |
|                     | `**`  | Change log / release notes                                  |                                                 |
|                     | `**`  | Upgrade example / instructions for breaking changes         |                                                 |
| DB design           | `*`   | Schema control even if no-sql does not enforce it           |                                                 |
|                     | `*`   | Change scripts should go with migrations + rollback script  |                                                 |
|                     | `*`   | Immutability or at least full audit of changes              | `event-sourcing`, or at least `temporal tables` |
| User experience     | `**`  | Avoid heavily used sessions                                 |                                                 |
|                     | `*`   | (If session used heavily) Session expiration handling       |                                                 |
|                     | `**`  | Everything / many things should be accessible via url       |                                                 |
|                     | `**`  | Consistant form validation mechanism                        | `TODO`                                          |
|                     | `**`  | Consistant ajax loader mechanism                            |                                                 |
| **DEV PROCESS**     |       |                                                             |                                                 |
| Project-kickoff     | `***` | Define git-process                                          |                                                 |
|                     | `***` | Task workflow (states)                                      |                                                 |
|                     | `***` | Define definition of done                                   | [notes](notes/process/dod.md)                   |
| Daily development   | `***` | Commenting task merge request to the ticket                 | `GitLab` merge requests                         |
|                     | `***` | Peer review is performed before merging                     | `GitLab` merge requests                         |
|                     | `***` | Daily group review for knowledge sharing                    | [notes](notes/process/group-review.md)          |
|                     | `**`  | Daily scrum                                                 |                                                 |
|                     | `**`  | Continous delivery to alpha                                 |                                                 |
|                     | `**`  | Marking external dependencies                               | In ticket and/or in code                        |
|                     | `*`   | Tests for new functionality and for new bugs found          |                                                 |
| Once in sprint      | `***` | Sprint review (overview, demo, feedback)                    |                                                 |
|                     | `***` | Sprint planning (goals, schedule, versions, tickets)        |                                                 |
|                     | `**`  | Backlog grooming and estimating                             |                                                 |
|                     | `***` | Retrospective                                               | [notes](notes/process/retro.md)                 |
| Before releases     | `***` | Arrange deployment freeze and regression testing in alpha   |                                                 |
|                     | `***` | Collect approvals (CAB)                                     |                                                 |
|                     | `***` | Release notes                                               | [notes](notes/process/release-notes.md)         |
|                     | `***` | (When needed) Deployment plan and it's approvals            |                                                 |
|                     | `***` | (When needed) Technical documentation updates               |                                                 |
|                     | `**`  | (When needed) Performance testing in beta                   |                                                 |
|                     | `***` | (When needed) Security audit                                |                                                 |
| **DOCUMENTATION**   |       |                                                             |                                                 |
|                     |       |                                                             | `TODO`                                          |

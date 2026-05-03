# Test-Driven Development (test-driven-development)
A software development approach where tests are written before the actual code, following a red-green-refactor cycle to ensure code quality and maintainability. TDD requires developers to write failing tests first, then write minimal code to make them pass, then refactor. It supports the full software development lifecycle from design through deployment and maintenance and is foundational to agile and extreme programming methodologies.

**URL:** [Visit APIs.json URL](https://en.wikipedia.org/wiki/Test-driven_development)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Agile, Best Practices, Continuous Integration, Extreme Programming, Methodology, Software Development, Testing

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### GitHub Actions API
REST API for GitHub Actions enabling CI/CD workflow automation, test execution, and status checks as part of TDD workflows on pull requests and commits.

**Human URL:** [https://docs.github.com/en/rest/actions](https://docs.github.com/en/rest/actions)

#### Tags:

 - CI/CD, Continuous Integration, GitHub, Test Automation

#### Properties

- [Documentation](https://docs.github.com/en/rest/actions)
- [OpenAPI](https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json)

### CircleCI API
REST API for CircleCI continuous integration platform, supporting pipeline management, test execution, and workflow orchestration as part of TDD CI/CD workflows.

**Human URL:** [https://circleci.com/docs/api/v2/](https://circleci.com/docs/api/v2/)

#### Tags:

 - CI/CD, Continuous Integration, Pipelines, Test Automation

#### Properties

- [Documentation](https://circleci.com/docs/api/v2/)
- [OpenAPI](https://circleci.com/api/v2/openapi.json)

### Jenkins API
REST API for Jenkins automation server supporting build triggers, test execution, and pipeline management for TDD-based development workflows.

**Human URL:** [https://www.jenkins.io/doc/book/using/remote-access-api/](https://www.jenkins.io/doc/book/using/remote-access-api/)

#### Tags:

 - Automation, Build Management, CI/CD, Continuous Integration

#### Properties

- [Documentation](https://www.jenkins.io/doc/book/using/remote-access-api/)

### SonarQube API
REST API for SonarQube code quality and security analysis platform, supporting test coverage metrics, code smells, and quality gate enforcement in TDD pipelines.

**Human URL:** [https://docs.sonarsource.com/sonarqube/latest/extension-guide/web-api/](https://docs.sonarsource.com/sonarqube/latest/extension-guide/web-api/)

#### Tags:

 - Code Coverage, Code Quality, Static Analysis, Testing

#### Properties

- [Documentation](https://docs.sonarsource.com/sonarqube/latest/extension-guide/web-api/)

### Codecov API
REST API for Codecov code coverage reporting service, enabling programmatic access to coverage reports, branch comparisons, and coverage trends in TDD workflows.

**Human URL:** [https://docs.codecov.com/reference](https://docs.codecov.com/reference)

#### Tags:

 - Code Coverage, Reporting, Testing

#### Properties

- [Documentation](https://docs.codecov.com/reference)
- [APIReference](https://docs.codecov.com/reference)

### Coveralls API
REST API for Coveralls code coverage history and statistics service, tracking test coverage over time and integrating with GitHub for TDD feedback loops.

**Human URL:** [https://docs.coveralls.io](https://docs.coveralls.io)

#### Tags:

 - Code Coverage, Reporting, Testing

#### Properties

- [Documentation](https://docs.coveralls.io)

## Common Properties

- [Documentation](https://en.wikipedia.org/wiki/Test-driven_development)
- [Documentation](https://martinfowler.com/bliki/TestDrivenDevelopment.html)

## Features

| Name | Description |
|------|-------------|
| Red-Green-Refactor Cycle | Write failing tests first, implement minimal code to pass them, then refactor while keeping tests green. |
| Test Coverage Enforcement | Ensure all production code is covered by tests written before implementation. |
| Continuous Feedback | Get immediate feedback on code correctness through automated test runs on every change. |
| Design by Contract | Use failing tests to define the API contract and behavior before implementation begins. |
| Regression Prevention | Build a comprehensive regression suite as a side effect of the TDD development process. |
| Refactoring Safety | Refactor code with confidence knowing the full test suite will catch regressions. |

## Use Cases

| Name | Description |
|------|-------------|
| API Design Validation | Use TDD to validate API contracts before writing implementation code. |
| Bug-Driven Development | Write a failing test that reproduces a bug before fixing it to prevent recurrence. |
| Legacy Code Modernization | Apply TDD when refactoring legacy code to ensure behavior is preserved. |
| Microservice Development | Use TDD to build well-tested microservice APIs with clear contracts. |
| Continuous Integration | Run TDD test suites automatically on every commit to maintain code quality. |

## Integrations

| Name | Description |
|------|-------------|
| GitHub Actions | Run TDD test suites automatically on pull requests using GitHub Actions workflows. |
| Jest | Use Jest for JavaScript TDD with fast test execution and snapshot testing. |
| JUnit | Use JUnit for Java TDD with test lifecycle management and assertion libraries. |
| pytest | Use pytest for Python TDD with fixtures, parametrize, and plugin ecosystem. |
| RSpec | Use RSpec for Ruby TDD with behavior-driven development syntax. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [TDD Cycle Schema](json-schema/test-driven-development-cycle-schema.json)
- [Coverage Report Schema](json-schema/test-driven-development-coverage-report-schema.json)
- [Test Spec Schema](json-schema/test-driven-development-test-spec-schema.json)

### JSON Structure

- [TDD Cycle Structure](json-structure/test-driven-development-cycle-structure.json)
- [Coverage Report Structure](json-structure/test-driven-development-coverage-report-structure.json)
- [Test Spec Structure](json-structure/test-driven-development-test-spec-structure.json)

### JSON-LD

- [Test-Driven Development Context](json-ld/test-driven-development-context.jsonld)

### Examples

- [TDD Cycle Example](examples/test-driven-development-cycle-example.json)
- [Coverage Report Example](examples/test-driven-development-coverage-report-example.json)
- [Test Spec Example](examples/test-driven-development-test-spec-example.json)

## Vocabulary

- [Test-Driven Development Vocabulary](vocabulary/test-driven-development-vocabulary.yml) — Unified taxonomy mapping 3 resources, 6 actions, and 3 personas across TDD domains.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

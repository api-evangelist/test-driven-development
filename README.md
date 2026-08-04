# Test-Driven Development (test-driven-development)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A software development approach where tests are written before the actual code, following a red-green-refactor cycle to ensure code quality and maintainability. TDD requires developers to write failing tests first, then write minimal code to make them pass, then refactor. It supports the full software development lifecycle from design through deployment and maintenance and is foundational to agile and extreme programming methodologies.

**APIs.json:** [https://en.wikipedia.org/wiki/Test-driven_development](https://en.wikipedia.org/wiki/Test-driven_development)

## Tags

- Agile
- Best Practices
- Continuous Integration
- Extreme Programming
- Methodology
- Software Development
- Testing

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### GitHub Actions API

REST API for GitHub Actions enabling CI/CD workflow automation, test execution, and status checks as part of TDD workflows on pull requests and commits.

- **Human URL:** [https://docs.github.com/en/rest/actions](https://docs.github.com/en/rest/actions)
- **Base URL:** `https://api.github.com`

#### Tags

- CI/CD
- Continuous Integration
- GitHub
- Test Automation

#### Properties

- [Documentation](https://docs.github.com/en/rest/actions)
- [OpenAPI](https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/test-driven-development.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-driven-development.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CircleCI API

REST API for CircleCI continuous integration platform, supporting pipeline management, test execution, and workflow orchestration as part of TDD CI/CD workflows.

- **Human URL:** [https://circleci.com/docs/api/v2/](https://circleci.com/docs/api/v2/)
- **Base URL:** `https://circleci.com/api/v2`

#### Tags

- CI/CD
- Continuous Integration
- Pipelines
- Test Automation

#### Properties

- [Documentation](https://circleci.com/docs/api/v2/)
- [OpenAPI](https://circleci.com/api/v2/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/test-driven-development.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-driven-development.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jenkins API

REST API for Jenkins automation server supporting build triggers, test execution, and pipeline management for TDD-based development workflows.

- **Human URL:** [https://www.jenkins.io/doc/book/using/remote-access-api/](https://www.jenkins.io/doc/book/using/remote-access-api/)
- **Base URL:** `https://your-jenkins.example.com`

#### Tags

- Automation
- Build Management
- CI/CD
- Continuous Integration

#### Properties

- [Documentation](https://www.jenkins.io/doc/book/using/remote-access-api/)
- [Postman Collection](collections/test-driven-development.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-driven-development.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SonarQube API

REST API for SonarQube code quality and security analysis platform, supporting test coverage metrics, code smells, and quality gate enforcement in TDD pipelines.

- **Human URL:** [https://docs.sonarsource.com/sonarqube/latest/extension-guide/web-api/](https://docs.sonarsource.com/sonarqube/latest/extension-guide/web-api/)
- **Base URL:** `https://your-sonar.example.com/api`

#### Tags

- Code Coverage
- Code Quality
- Static Analysis
- Testing

#### Properties

- [Documentation](https://docs.sonarsource.com/sonarqube/latest/extension-guide/web-api/)
- [Postman Collection](collections/test-driven-development.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-driven-development.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Codecov API

REST API for Codecov code coverage reporting service, enabling programmatic access to coverage reports, branch comparisons, and coverage trends in TDD workflows.

- **Human URL:** [https://docs.codecov.com/reference](https://docs.codecov.com/reference)
- **Base URL:** `https://api.codecov.io/api/v2`

#### Tags

- Code Coverage
- Reporting
- Testing

#### Properties

- [Documentation](https://docs.codecov.com/reference)
- [API Reference](https://docs.codecov.com/reference)
- [Postman Collection](collections/test-driven-development.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-driven-development.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coveralls API

REST API for Coveralls code coverage history and statistics service, tracking test coverage over time and integrating with GitHub for TDD feedback loops.

- **Human URL:** [https://docs.coveralls.io](https://docs.coveralls.io)
- **Base URL:** `https://coveralls.io`

#### Tags

- Code Coverage
- Reporting
- Testing

#### Properties

- [Documentation](https://docs.coveralls.io)
- [Postman Collection](collections/test-driven-development.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-driven-development.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Documentation](https://en.wikipedia.org/wiki/Test-driven_development)
- [Documentation](https://martinfowler.com/bliki/TestDrivenDevelopment.html)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [JSON Schema](json-schema/test-driven-development-cycle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/test-driven-development-coverage-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/test-driven-development-test-spec-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/test-driven-development-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/test-driven-development-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com

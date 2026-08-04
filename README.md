# Test Suites (test-suites)

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

A collection of organized test cases designed to validate specific functionality or features of software applications and APIs. Test suites group related test cases into logical units that can be executed together, providing comprehensive coverage of a system's behavior. They are widely used by developers to build, maintain, and scale software testing across functional testing, regression testing, contract testing, and compliance validation. Test suites range from unit test collections in JUnit and pytest to API test collection suites in Postman, Bruno, and Karate.

**APIs.json:** [https://en.wikipedia.org/wiki/Test_suite](https://en.wikipedia.org/wiki/Test_suite)

## Tags

- API Testing
- Collections
- Quality Assurance
- Software Development
- Test Management
- Testing

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### Postman Collections API

Postman Collections are the primary organizational unit for grouping API test cases into test suites. The Postman API allows programmatic management of collections, enabling creation, retrieval, and execution of API test suites via the Collections API and Newman CLI runner.

- **Human URL:** [https://www.postman.com/](https://www.postman.com/)
- **Base URL:** `https://api.getpostman.com`

#### Tags

- Collections
- API Testing
- Test Management

#### Properties

- [Documentation](https://learning.postman.com/docs/collections/collections-overview/)
- [OpenAPI](https://www.postman.com/postman/postman-public-workspace/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/test-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### JUnit 5

JUnit 5 is the Java testing framework used to organize test cases into test suites. The @Suite annotation enables test class grouping, tag-based filtering, and hierarchical suite composition, making it the standard Java test suite management solution for unit, integration, and API tests.

- **Human URL:** [https://junit.org/junit5/](https://junit.org/junit5/)
- **Base URL:** `https://junit.org/junit5/`

#### Tags

- Java
- Test Suite
- Unit Testing

#### Properties

- [Documentation](https://junit.org/junit5/docs/current/user-guide/)
- [Git Hub Org](https://github.com/junit-team/junit5)
- [Postman Collection](collections/test-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### pytest

pytest is the Python testing framework supporting test suite organization through test classes, directories, markers, and fixtures. Its plugin architecture enables test suite reporting, parallel execution, and integration with coverage analysis and CI/CD systems.

- **Human URL:** [https://pytest.org/](https://pytest.org/)
- **Base URL:** `https://pytest.org/`

#### Tags

- Python
- Test Suite
- Testing

#### Properties

- [Documentation](https://docs.pytest.org/en/latest/)
- [Git Hub Org](https://github.com/pytest-dev/pytest)
- [Postman Collection](collections/test-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jasmine

Jasmine is a behavior-driven JavaScript testing framework that organizes test cases into describe/it suite blocks. It is commonly used for organizing API client test suites in Node.js environments and browser-based JavaScript applications.

- **Human URL:** [https://jasmine.github.io/](https://jasmine.github.io/)
- **Base URL:** `https://jasmine.github.io/`

#### Tags

- BDD
- JavaScript
- Test Suite

#### Properties

- [Documentation](https://jasmine.github.io/tutorials/your_first_suite)
- [Git Hub Org](https://github.com/jasmine/jasmine)
- [Postman Collection](collections/test-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mocha

Mocha is a flexible JavaScript test suite framework supporting both synchronous and asynchronous API tests. It provides describe/it nesting for suite organization, rich reporting, and integration with assertion libraries such as Chai and Sinon.

- **Human URL:** [https://mochajs.org/](https://mochajs.org/)
- **Base URL:** `https://mochajs.org/`

#### Tags

- JavaScript
- Node.js
- Test Suite

#### Properties

- [Documentation](https://mochajs.org/#getting-started)
- [Git Hub Org](https://github.com/mochajs/mocha)
- [Postman Collection](collections/test-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jest

Jest is a zero-configuration JavaScript testing framework with built-in test suite runner, mocking, coverage reporting, and snapshot testing. Widely used for React applications and Node.js API services, Jest organizes test cases into describe blocks and supports parallel test suite execution.

- **Human URL:** [https://jestjs.io/](https://jestjs.io/)
- **Base URL:** `https://jestjs.io/`

#### Tags

- JavaScript
- React
- Test Suite

#### Properties

- [Documentation](https://jestjs.io/docs/getting-started)
- [Git Hub Org](https://github.com/jestjs/jest)
- [Postman Collection](collections/test-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bruno

Bruno is an open-source API client and test suite manager that stores API collections as plain files alongside application code. It enables version- controlled test suites in a format designed for git-based collaboration, with scripting support for pre-request and post-request test logic.

- **Human URL:** [https://www.usebruno.com/](https://www.usebruno.com/)
- **Base URL:** `https://www.usebruno.com/`

#### Tags

- API Testing
- Collections
- Open Source

#### Properties

- [Documentation](https://docs.usebruno.com/)
- [Git Hub Org](https://github.com/usebruno/bruno)
- [Postman Collection](collections/test-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hurl

Hurl is a command-line tool that runs HTTP requests defined in a simple plain-text format, enabling lightweight API test suites that can be committed to source control and executed in CI/CD pipelines without additional runtime dependencies.

- **Human URL:** [https://hurl.dev/](https://hurl.dev/)
- **Base URL:** `https://hurl.dev/`

#### Tags

- API Testing
- CLI
- Test Suite

#### Properties

- [Documentation](https://hurl.dev/docs/installation.html)
- [Git Hub Org](https://github.com/Orange-OpenSource/hurl)
- [Postman Collection](collections/test-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TestNG

TestNG is a Java testing framework inspired by JUnit and NUnit that provides advanced test suite configuration including grouping, prioritization, parameterized tests, and parallel execution. It is widely used for API integration test suites alongside REST Assured.

- **Human URL:** [https://testng.org/](https://testng.org/)
- **Base URL:** `https://testng.org/`

#### Tags

- Java
- Test Suite
- Integration Testing

#### Properties

- [Documentation](https://testng.org/doc/documentation-main.html)
- [Git Hub Org](https://github.com/testng-team/testng)
- [Postman Collection](collections/test-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Git Hub Org](https://github.com/api-evangelist/test-suites)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/test-suites/main/json-schema/test-suites-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/test-suites/main/json-structure/test-suites-structure.json)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/test-suites/main/json-ld/test-suites-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/test-suites/main/vocabulary/test-suites-vocabulary.yml)

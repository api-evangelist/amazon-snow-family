# Amazon Snow Family (amazon-snow-family)

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

The Amazon Snow Family is a collection of physical devices that migrate large amounts of data into and out of AWS and run compute at the edge.

**URL:** [https://aws.amazon.com/snowball/](https://aws.amazon.com/snowball/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Edge Computing, Data Transfer, Data Migration, Hybrid Cloud

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon Snow Family API

The Amazon Snow Family is a collection of physical devices that migrate large amounts of data into and out of AWS and run compute at the edge.

**Human URL:** [https://aws.amazon.com/snowball/](https://aws.amazon.com/snowball/)

#### Tags:

 - Data Transfer, Edge Computing, Hybrid Cloud

#### Properties

- [Documentation](https://docs.aws.amazon.com/snowball/latest/developer-guide/api-reference.html)
- [OpenAPI](openapi/amazon-snow-family.yaml)
- [GettingStarted](https://aws.amazon.com/snowball/)
- [Pricing](https://aws.amazon.com/snowball/pricing/)

## Common Properties

- [Portal](https://aws.amazon.com/snowball/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [GitHubOrganization](https://github.com/aws)
- [StatusPage](https://health.aws.amazon.com/health/status)

## Features

| Name | Description |
|------|-------------|
| Petabyte-scale Data Transfer | Transfer large datasets to AWS using physical devices. |
| Edge Computing | Run compute workloads at the edge with Snowball Edge and Snowcone. |
| Encryption | All data is automatically encrypted with 256-bit encryption. |

## Use Cases

| Name | Description |
|------|-------------|
| Large Data Migration | Migrate terabytes to petabytes of data to AWS. |
| Disconnected Edge Computing | Run AWS compute in environments with no internet connectivity. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Transfer data directly to S3 buckets using Snow devices. |
| AWS IoT Greengrass | Run IoT Greengrass on Snowball Edge for edge IoT workloads. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-snow-family.yaml](openapi/amazon-snow-family.yaml)

### JSON Schema

- [amazon-snow-family-address-schema.json](json-schema/amazon-snow-family-address-schema.json)
- [amazon-snow-family-address-type-schema.json](json-schema/amazon-snow-family-address-type-schema.json)
- [amazon-snow-family-cancel-cluster-request-schema.json](json-schema/amazon-snow-family-cancel-cluster-request-schema.json)
- [amazon-snow-family-cancel-cluster-result-schema.json](json-schema/amazon-snow-family-cancel-cluster-result-schema.json)
- [amazon-snow-family-cancel-job-request-schema.json](json-schema/amazon-snow-family-cancel-job-request-schema.json)
- ... and 97 more

### JSON Structure

- [amazon-snow-family-address-structure.json](json-structure/amazon-snow-family-address-structure.json)
- [amazon-snow-family-address-type-structure.json](json-structure/amazon-snow-family-address-type-structure.json)
- [amazon-snow-family-cancel-cluster-request-structure.json](json-structure/amazon-snow-family-cancel-cluster-request-structure.json)
- [amazon-snow-family-cancel-cluster-result-structure.json](json-structure/amazon-snow-family-cancel-cluster-result-structure.json)
- [amazon-snow-family-cancel-job-request-structure.json](json-structure/amazon-snow-family-cancel-job-request-structure.json)
- ... and 97 more

### JSON-LD

- [amazon-snow-family-context.jsonld](json-ld/amazon-snow-family-context.jsonld)

### Examples

- [amazon-snow-family-address-example.json](examples/amazon-snow-family-address-example.json)
- [amazon-snow-family-address-type-example.json](examples/amazon-snow-family-address-type-example.json)
- [amazon-snow-family-cancel-cluster-request-example.json](examples/amazon-snow-family-cancel-cluster-request-example.json)
- [amazon-snow-family-cancel-cluster-result-example.json](examples/amazon-snow-family-cancel-cluster-result-example.json)
- [amazon-snow-family-cancel-job-request-example.json](examples/amazon-snow-family-cancel-job-request-example.json)
- ... and 97 more

## Capabilities

Naftiko capabilities organized as shared per-API definitions.

### Shared Per-API Definitions

- [amazon-snow-family.yaml](capabilities/shared/amazon-snow-family.yaml) — Amazon Snow Family operations for resource management

## Vocabulary

- [Amazon Snow Family Vocabulary](vocabulary/amazon-snow-family-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas

## Rules

- [Amazon Snow Family Spectral Rules](rules/amazon-snow-family-spectral-rules.yml) — Rules enforcing Amazon Snow Family API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

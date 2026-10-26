# HL7 FHIR (hl7-fhir)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

HL7 FHIR (Fast Healthcare Interoperability Resources) is the standard API specification for healthcare data exchange, published by Health Level Seven International (HL7). FHIR REST APIs provide access to patient, clinical, financial, and administrative healthcare data in JSON, XML, and RDF formats with a CC0 open license.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Clinical
- FHIR
- Healthcare
- HL7
- Interoperability

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-19

## APIs

### HL7 FHIR R5 Healthcare API

HL7 FHIR R5 (Release 5) is the current published FHIR standard for healthcare data exchange. FHIR R5 REST APIs provide access to patient demographics, observations, conditions, medications, encounters, and care plans in both JSON and XML formats across EHR systems, published March 2023.

- **Human URL:** [https://www.hl7.org/fhir/](https://www.hl7.org/fhir/)
- **Base URL:** `https://fhir-server.example.com/fhir/R5`

#### Tags

- Clinical
- FHIR
- Healthcare
- HL7
- Interoperability
- JSON
- XML

#### Properties

- [Documentation](https://www.hl7.org/fhir/)
- [Reference](https://www.hl7.org/fhir/http.html)
- [Authentication](https://www.hl7.org/fhir/security.html)
- [Changelog](https://www.hl7.org/fhir/history.html)
- [Postman Collection](collections/hl7-fhir-r4.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hl7-fhir-r4.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HL7 FHIR R4 Healthcare API

HL7 FHIR R4 (v4.0.1) is a widely adopted normative FHIR standard for healthcare data exchange. FHIR R4 REST APIs are the most commonly implemented version across US healthcare systems, supporting patient data, clinical resources, medications, diagnostics, and financial resources.

- **Human URL:** [https://www.hl7.org/fhir/R4/](https://www.hl7.org/fhir/R4/)
- **Base URL:** `https://fhir-server.example.com/fhir/R4`

#### Tags

- Clinical
- FHIR
- Healthcare
- HL7
- Interoperability
- JSON
- XML

#### Properties

- [Documentation](https://www.hl7.org/fhir/R4/)
- [Reference](https://www.hl7.org/fhir/R4/http.html)
- [Changelog](http://hl7.org/fhir/R4/history.html)
- [OpenAPI](openapi/hl7-fhir-r4-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hl7-fhir-r4.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hl7-fhir-r4.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMART on FHIR Authentication

SMART on FHIR (v2.2.0) defines OAuth 2.0-based authorization patterns for client applications to authorize, authenticate, and integrate with FHIR-based data systems. It enables EHR launch, standalone launch, and backend service authorization workflows.

- **Human URL:** [http://hl7.org/fhir/smart-app-launch/ImplementationGuide/hl7.fhir.uv.smart-app-launch](http://hl7.org/fhir/smart-app-launch/ImplementationGuide/hl7.fhir.uv.smart-app-launch)
- **Base URL:** `https://fhir-server.example.com/fhir`

#### Tags

- Authentication
- FHIR
- Healthcare
- OAuth2
- SMART

#### Properties

- [Documentation](http://hl7.org/fhir/smart-app-launch/ImplementationGuide/hl7.fhir.uv.smart-app-launch)
- [Authentication](http://hl7.org/fhir/smart-app-launch/ImplementationGuide/hl7.fhir.uv.smart-app-launch)
- [Postman Collection](collections/hl7-fhir-r4.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hl7-fhir-r4.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.hl7.org/fhir/)
- [Documentation](https://www.hl7.org/fhir/)
- [Reference](https://www.hl7.org/fhir/http.html)
- [Authentication](https://www.hl7.org/fhir/security.html)
- [Changelog](https://www.hl7.org/fhir/history.html)
- [Getting Started](https://www.hl7.org/fhir/downloads.html)
- [Website](https://www.hl7.org/)
- [GitHub Organization](https://github.com/HL7)
- [OpenAPI](openapi/hl7-fhir-r4-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/hl7-fhir-patient-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/hl7-fhir-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

# LawTrades

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

LawTrades is a legal talent marketplace, founded in 2016, that matches companies with vetted
independent attorneys, paralegals, and legal operations professionals on flexible, on-demand terms.
The platform covers eleven practice areas and handles matching, work-log management, invoicing,
payments, and real-time spend analytics, with a human-in-the-loop AI layer that drafts documents and
flags risk for lawyer review.

- Website: https://www.lawtrades.com/
- Application: https://app.lawtrades.com/login
- Backed by: 500 Global, Draper Associates, Social Capital, AngelList ($6M Series A)

## API surface

**LawTrades publishes no public API.** An enrichment probe on 2026-07-19 found:

- `api.lawtrades.com`, `docs.lawtrades.com`, `developer.lawtrades.com`, and
  `developers.lawtrades.com` all NXDOMAIN
- no OpenAPI, AsyncAPI, GraphQL, or Postman collection
- no `/llms.txt` and no `/.well-known/` documents (the `app.` host returns HTTP 200 for every
  path — an SPA catch-all, not a discovery surface)
- no first-party SDKs on npm or PyPI; no company GitHub organization
  (`github.com/lawtrades` is an individual employee account)
- no status page, no published pricing page, and no published compliance program
  (no SOC 2 / ISO 27001 / GDPR claims found)

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Domain security | `security/lawtrades-domain-security.yml` | probed |
| Well-known (negative) | `well-known/lawtrades-well-known.yml` | searched |
| llms.txt | `llms/lawtrades-llms.txt` | generated |

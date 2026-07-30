# LawTrades

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

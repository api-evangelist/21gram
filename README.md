# 21gram

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

21gram (21그램) is a South Korean pet end-of-life care company. It operates pet funeral
homes and an online booking and consultation platform for pet funerals — founded in Seoul,
led by Kwon Shin-gu, and venture-backed (Korea Investment Partners, GS Retail, Coway,
SB Partners, Wadiz Partners, JCurve Investment, Waterbear Capital). It began as an online
brokerage connecting owners to licensed pet funeral homes nationwide, then moved into
operating its own facilities, including Korea's first pet funeral hall (Arongi Cheonguk,
Gwangju, Gyeonggi Province), branches in Gwangju, Namyangju and Cheonan, and a large
charnel house.

- Website: https://21gram.co.kr/
- Harvest source: https://equityzen.com/company/21gram (secondary-market backlog)

## API surface

**None found.** 21gram publishes no developer program, no API reference, and no
machine-readable contract. Contract discovery on 2026-09-05 probed the registrable domain
and `www`: `/openapi.json`, `/swagger.json`, `/api-docs`, `/docs`, `/graphql`, `/apis.json`
and `/apis.yml` all returned 404; every named `/.well-known/` path returned 404 on both
hosts (with a negative-control path also returning 404, so the host is not a catch-all);
and `api.`, `developer.` and `docs.21gram.co.kr` do not resolve. The 138-URL sitemap
contains no developer, API or documentation page. The site runs on the hosted **imweb**
site builder, so the company does not operate its own web platform.

One real provider-published document was found: `https://21gram.co.kr/llms.txt` (HTTP 200),
saved verbatim in `llms/`. It is a four-line robots-style AI-usage policy granting
commercial and research use — not an llms.txt link index.

**Name collisions — read before adding anything here.** Several unrelated companies share
this name and their artifacts must never land in this repo: 21GRAMS (US healthcare
marketing agency, acquired by W2O), 21grams (Nordic outbound-document company, acquired by
Unifiedpost Group), and 21Gram Consulting (publisher of the `@21gram-consulting` npm
scope). See `packages/21gram-packages.yml` for the rejections on record.

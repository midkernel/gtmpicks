# Suggest a resource

GTM Picks curates resources that help solo founders do specific go-to-market work. Useful submissions give someone a repeatable process, a template, a reference, or a skill they can apply with an agent.

Open an issue with the source link and a short explanation of what it helps someone do. If you prefer a pull request, add a single entry to `catalog.json`.

- Use a stable public HTTPS source. Strip tracking, referral, invite, and account identifiers. Flag paywalls, sign-in requirements, and commercial affiliations in the suggestion.
- Write an original one-sentence description. Link to the resource without reposting its contents.
- Keep personal information, private links, customer material, account details, and internal work out of the issue, PR, and metadata. GitHub issues, PRs, and contributor profiles are public here.
- Choose `gtm`, `search`, or `agents`. Give the entry a unique lowercase ID with hyphens, and set a format such as `Guide`, `Template`, or `Skill`.

The GTM Picks curator bot may submit one batched pull request per day containing several entries. Each entry in a batch must follow every other rule here, validate against `catalog.schema.json`, and link its source post. Human contributors keep the one-entry-per-PR rule.

Maintainers check relevance, accessibility, link integrity, and duplicates before merging. The site reads the catalog from the main branch, so a merge updates what the site serves.

Original descriptions and other material submitted for inclusion are shared under the repository’s [license](LICENSE.md).

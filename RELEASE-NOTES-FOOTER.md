# Release-notes footer

Paste the block below at the **end of every release body** in
`skalesapp/skales`, under the SHA-256 list. It is the same text every time, so
that the licence and the brand terms travel with every download rather than
living only in a repository nobody opens.

Rules for the block: plain text, no em-dashes, and no line break in the middle
of a sentence (GitHub renders every break hard).

---

```markdown
---

**Licence and brand.** Skales is proprietary software under the
[Skales End User Licence Agreement](https://github.com/skalesapp/skales/blob/main/LICENSE),
version 1.3 of 9 November 2026; the current version is always at https://skales.app/licence.
It is not open source and it is not source-available. Private individuals, students, teachers, non-commercial educational institutions, freelancers and businesses of up to two people use it free of charge; handing your own workflows or plugins to a client needs our written okay first. Larger companies and public bodies need a written commercial licence, and SaaS, hosting, bundling, white-labelling and resale need a written contract: request@skales.app. Run Skales as it is published: do not bypass its integrity, attestation or authentication mechanisms, do not operate it as a component or backend of another program, do not resell or broker access to it, and do not claim to be a partner or reseller of Skales.

The name Skales, the logo and the icon are trademarks and are not licensed with the software. You may refer to Skales by name to describe, review or link to the unmodified original software; a modified or rebranded copy must not carry the name or the logo. See
[TRADEMARK.md](https://github.com/skalesapp/skales/blob/main/TRADEMARK.md).

Verify what you downloaded against the SHA-256 list above. Signed builds identify themselves; a build that is not in our release record is not ours.
```

---

## Where else the same two links belong

| Place | What it needs |
|---|---|
| Release body in `skalesapp/skales` | the block above, after the SHA-256 list |
| `skalesapp/skales` repo root | `LICENSE`, `TRADEMARK.md` |
| `skalesapp/.github` profile page | the licence paragraph with both links |
| The downloaded package itself | `LICENSE` and `TRADEMARK.md` next to `THIRD-PARTY-NOTICES.md` in `Resources/` |
| skales.app download page | one line with both links, plus the `/licence` page |

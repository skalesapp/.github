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

**Licence and brand.** Skales is source-available under the
[Business Source License 1.1](https://github.com/skalesapp/skales/blob/main/LICENSE):
personal, educational and internal business use is free. SaaS, hosting,
bundling or resale need a
[commercial licence](https://github.com/skalesapp/skales/blob/main/COMMERCIAL-LICENSE.md).
The name Skales, the logo and the icon are not covered by that licence. You may
redistribute these unmodified original files; a modified or rebranded build must
not carry the name or the logo. See
[TRADEMARK.md](https://github.com/skalesapp/skales/blob/main/TRADEMARK.md).

Verify what you downloaded against the SHA-256 list above. Signed builds
identify themselves; a build that is not in our release record is not ours.
```

---

## Where else the same two links belong

| Place | What it needs |
|---|---|
| Release body in `skalesapp/skales` | the block above, after the SHA-256 list |
| `skalesapp/skales` repo root | `LICENSE`, `COMMERCIAL-LICENSE.md`, `TRADEMARK.md` |
| `skalesapp/.github` profile page | the licence paragraph with both links |
| The downloaded package itself | `LICENSE` and `TRADEMARK.md` next to `THIRD-PARTY-NOTICES.md` in `Resources/` |
| skales.app download page | one line with both links |

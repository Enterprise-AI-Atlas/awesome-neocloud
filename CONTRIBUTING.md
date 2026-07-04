# Contributing

Contributions are welcome. Please read this guide before opening a pull request.

## What belongs in this list

This registry is for resources that help people research and evaluate **Neocloud** providers and the AI-native cloud ecosystem. Acceptable entries include:

- Neocloud providers (GPU-as-a-Service, bare-metal AI clouds, sovereign AI clouds).
- NVIDIA Cloud Partner (NCP) documentation and reference architecture resources.
- Independent ratings, benchmarks, and market research on Neoclouds.
- Financial, funding, IPO, and energy/sustainability research relevant to Neoclouds.
- Software and tools used to build or operate Neocloud infrastructure.

## What does **not** belong

- General cloud providers without an explicit AI/GPU focus.
- Vendor marketing pages with no informational or research value.
- Duplicate entries.
- Closed-source or paywalled-only resources with no public documentation.

## Quality bar

Every submission must be:

1. **Publicly accessible** — open source or publicly documented.
2. **Current** — last meaningful update within the last 12 months (exceptions for canonical official docs).
3. **Documented** — a real page with details a researcher can act on.
4. **Correctly categorized** — placed under the section it primarily belongs to.
5. **Honestly labeled** — use `Official`, `Provider`, `Research`, `Analysis`, `Rating`, or `Platform` as appropriate.

## Entry format

Use this pattern:

```markdown
- **[Name](URL)** `Label` — One-sentence description.
  - Note: extra detail if needed.
```

If there is no extra detail, omit the second line.

## Product sections

The README is organized by **research topic**, not by provider. New sections are allowed only if they contain at least three entries.

## Pull request process

1. Fork the repository.
2. Add your entry in the correct section.
3. Run `./scripts/validate-links.sh` and fix any broken links or anchors.
4. Open a pull request with a clear description of the resource and why it fits.

One resource per pull request is preferred.

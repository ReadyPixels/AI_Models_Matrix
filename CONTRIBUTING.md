# Contributing to AI Models Matrix

Thank you for your interest in contributing. This guide explains how to propose changes, report issues, and keep the list accurate.

> **Note:** The main documentation is located in `docs/readme.md`. All table entries should be added or updated there, not in this file.

## How to Contribute

### Suggesting a New Model or Tool

1. Open an issue using the **New Model / Tool Request** template.
2. Include the following required information:
   - **Name**: Official product name exactly as the developer writes it
   - **Developer**: Organization or company behind the model
   - **Official Source URL**: Link to official documentation or product page
   - **Pricing**: Cost in USD per 1M tokens (API) or monthly subscription
   - **Key Features**: Main capabilities and use cases
3. Only suggest items you can back with an official or primary source.

### Submitting a Pull Request (Adding New Models)

1. Fork the repository and create a branch from `main`.
2. Add your entry to `docs/readme.md` following the existing table format.
3. Every factual claim must link to an official or primary source.
4. Keep entries concise — one line per item, no marketing language.
5. Submit your pull request with a clear title describing the change.

### Updating Existing Entries

When updating pricing, benchmarks, or other information:

1. Open an issue using the **Error Report** template OR submit a direct PR
2. Include: the entry to update, what is wrong, and a link to the correct official source
3. Verification requirements:
   - All pricing updates must link to the official pricing page
   - Benchmark updates must reference the specific benchmark and date
   - Include the date you verified the information

#### Example of Proper Update Format

```markdown
| **Model Name** | Developer | [Official Docs](url) | $X.XX/1M | Feature 1, Feature 2 |
```

**Important:** Always use the most recent official pricing and verify links are functional before submitting.

## Required Fields for New Entries

All new model entries must include:

| Field | Description | Example |
|-------|-------------|---------|
| Name | Official product name | **Claude Opus 4.6** |
| Developer | Organization or company | Anthropic |
| Official Source URL | Direct link to official documentation | [Link](https://docs.anthropic.com) |
| Pricing | USD per 1M tokens or monthly subscription | $15.00/1M input |
| Key Features | Main capabilities separated by commas | Claude 3.5 Sonnet, vision support, tool use |

## Curation Criteria

All entries must meet the following standards:

- **Public Documentation**: Must have official, publicly accessible documentation
- **Active Development**: Must be currently maintained (not archived, deprecated, or abandoned)
- **Verifiable Claims**: All claims must be backed by official sources — no blog summaries or aggregator sites
- **No Fabricated Entries**: Do not add fictional, hypothetical, or unverified models
- **Primary Sources Only**: Link to official documentation, release announcements, or pricing pages

Items that will be rejected:
- Models without verifiable official documentation
- Projects that have been archived or abandoned
- Entries with unverified or fabricated benchmark scores
- Marketing language or promotional content

## Table Style Guide

### Column Order

Tables follow this standard column order:
1. Model/Tool Name (with link to official source)
2. Developer
3. Official Source URL
4. Pricing
5. Key Features

### Formatting Guidelines

- Use `**bold**` for model/tool names in table cells
- Use [brackets](URL) for inline links to official sources
- End descriptions with a period
- Keep table rows aligned and readable
- Separate features with commas (no bullet points)
- Use emojis sparingly and consistently (e.g., 📖 for documentation, 💰 for pricing)

### Example Entry

```markdown
| **[Claude Opus 4.6](https://www.anthropic.com/claude/opus)** | Anthropic | [📖 Docs](https://docs.anthropic.com) | $15.00/1M input, $75.00/1M output | Advanced reasoning, code generation, vision |
```

## Content Guidelines

- **Primary sources only.** Link to official documentation, release announcements, or pricing pages — not blog summaries or aggregators.
- **No unmaintained or deprecated items.** If a project has been archived or abandoned, do not add it.
- **Consistent naming.** Use the official product name exactly as the developer writes it (e.g., `Claude Opus 4.6`, not `claude-opus-4.6`).
- **Pricing in USD per 1M tokens** for API models, or monthly subscription cost where applicable.
- **Benchmark scores** should reference the specific benchmark version and date.

## Style

- Use `**bold**` for model/tool names in table cells.
- End descriptions with a period.
- Keep table rows aligned and readable.
- Do not add badges or CI status indicators to the README.

## Code of Conduct

Be respectful and constructive. Contributions that include spam, self-promotion without relevance, or hostile language will be closed.

## Questions?

Open a [Discussion](https://github.com/ReadyPixels/AI_Models_Matrix/discussions) or file an issue.
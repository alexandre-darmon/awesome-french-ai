# Contributing to Awesome French AI

Thanks for helping keep this map of the French AI ecosystem accurate and useful. Contributions of all sizes are welcome — a new entry, a fixed link, a sharper description.

This guide takes 2 minutes to read. Please skim it before opening a pull request.

## What belongs here

Add an entry only if it **builds** AI in France. The test: *would someone trying to work in or with French AI need to know this?*

✅ **In scope**
- Labs and frontier model builders
- Open-source models, libraries, and datasets from French teams
- AI-native startups (companies whose core product is AI)
- Research institutions and academic labs
- AI infrastructure and compute providers
- Investors actively funding French AI
- Communities, events, and people directly shaping the ecosystem

❌ **Out of scope**
- General tech companies that merely *use* AI
- Personal blogs, tutorials, or courses
- French-language NLP datasets (covered by [french-ai/french-nlp](https://github.com/french-ai/french-nlp))
- Companies with no meaningful French footprint
- Anything inactive, abandoned, or vaporware

"French" means founded in France, headquartered in France, or with a major French research/engineering presence.

## Formatting rules

Every entry follows the same one-line format:

```markdown
- [Name](https://url.com) — One sentence describing what it does and why it matters.
```

- **One line per entry.** No multi-paragraph descriptions.
- **Factual, not promotional.** Write "enterprise AI agent platform," not "the revolutionary game-changing platform."
- **Use the official URL** (homepage or main repo), not a blog post or news article.
- **Alphabetical or significance order** within a section — match what's already there.
- **No duplicate entries** across sections; pick the best-fit category.

## How to contribute

The workflow is the standard GitHub fork-and-pull-request flow.

**1. Fork the repository**

Click "Fork" at the top right of the repo page.

**2. Create a branch**

Don't commit directly to `main`. Create a descriptive branch:

```bash
git checkout -b add-mistral-ocr
```

**3. Make your change**

Edit `README.md`. Add your entry in the right section, respecting the format above.

**4. Commit with a clear message**

Use a short, descriptive commit message:

```bash
git commit -m "Add Mistral OCR to Open-Source Models"
```

**5. Push and open a pull request**

```bash
git push origin add-mistral-ocr
```

Then open a PR. In the description, answer one question: **why does this entry belong here?** One or two sentences is enough.

## Pull request checklist

Before submitting, confirm:

- [ ] The entry is in scope (it *builds* AI in France)
- [ ] The link works and points to the official source
- [ ] The description is one factual sentence
- [ ] It's in the right section, with no duplicate
- [ ] The format matches `[Name](url) — description`

## Editing or removing entries

Found a broken link, an outdated description, or a project that's no longer active? Open a PR with the fix or removal, and briefly explain why. Keeping the list current matters as much as adding to it.

## Disagreements

This is a curated list, so maintainer judgment applies — not every submission will be merged. If an entry is borderline, open an issue first to discuss before investing time in a PR.

## Code of conduct

Be respectful and constructive. We're mapping an ecosystem, not ranking winners and losers. Personal attacks, spam, and self-promotion disguised as contributions will be closed without discussion.

---

Thank you for contributing. Every accurate entry makes this more useful for the next person trying to navigate French AI.

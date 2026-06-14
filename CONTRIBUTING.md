# Contributing

Thanks for helping improve this Building a Second Brain awesome list.

## What belongs here

- Resources should be directly useful for Building a Second Brain, PARA, progressive summarization, personal knowledge management, or practical second-brain implementations.
- Prefer canonical, maintained, high-signal resources over thin summaries, generic productivity posts, or promotional pages.
- Use the most specific existing section. Add a new section only when several related resources need it.
- Avoid duplicate links and affiliate links.

## How to add a resource

1. Add one Markdown list item to `README.md`.
2. Use the format `- [Title](https://example.com)`.
3. Keep titles clear and match the resource title when possible.
4. Place the item near similar resources in the same section.
5. Check that the link resolves and does not require a private account.

## Local checks

Install dependencies and run the Markdown checks:

```sh
npm ci
npm test
```

GitHub Actions also runs Lychee to check links in Markdown files.

## Pull requests

- Keep pull requests focused on a small set of related additions or fixes.
- Include a short note explaining why new resources are worth including.
- If a link checker failure is caused by rate limiting or bot protection, mention it in the pull request.

# Contribution Guidelines

Thanks for helping improve this list. Please read these guidelines before opening a pull request.

By contributing you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## What belongs here

A resource is a good fit when it is:

- **About learning Go.** Tutorials, docs, articles, videos, talks and practice projects. Not a general library catalog, see [awesome-go](https://github.com/avelino/awesome-go) for that.
- **High quality.** Accurate, clearly written, and useful to someone learning the topic.
- **Still relevant.** It works with a currently supported Go version and does not teach deprecated practices, such as `GOPATH`-only workflows.
- **Not a duplicate.** Search the README first. If two resources cover the same thing, keep the better one.
- **Accessible.** The link works and the content is readable without signing up. Paid resources are allowed if they are tagged `Paid`.

Please do not submit:

- Your own content unless it is a genuinely strong resource. Say in the PR that you are the author.
- Link shorteners, affiliate links or tracking parameters such as `?utm_source=` or `&si=`.
- Single pages of a larger resource that is already listed.

## Entry format

Each entry is one line. Tags go before the description so awesome-lint can check that the description ends with a period:

```markdown
- [Title](https://example.com) - `Beginner` `Free` One-sentence description.
```

- **Title:** the resource's real title, with the site or channel name removed.
- **Description:** your own words, one sentence. Start with a capital letter, end with a period. Say what it covers, not how great it is. No marketing words.
- **Level tag:** one of `Beginner`, `Intermediate` or `Advanced`. Leave it out for general references useful at any stage.
- **Price tag:** `Free` or `Paid`. Always include one.

## Ordering

Within each section, entries are sorted by level, then alphabetically by title (case-insensitive):

1. Untagged general references
2. `Beginner`
3. `Intermediate`
4. `Advanced`

## Pull requests

- **One resource per pull request.** This keeps review quick and history clean.
- Use a title like `Add <Resource Title>`.
- Fill in the pull request checklist.
- If a section does not exist for your resource, suggest one in the PR description rather than adding it.

## Reporting problems

- Dead or moved link: open a [broken link report](../../issues/new?template=broken-link.yml).
- Not sure if something fits: open a [resource suggestion](../../issues/new?template=suggest-resource.yml) first.

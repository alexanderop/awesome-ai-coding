# CLAUDE.md

## Project Purpose

This is an "awesome list" repository for AI coding resources. The README.md contains curated links to blog posts, YouTube videos, and people to follow in the AI coding space.

## Workflow: Adding Resources

When the user pastes a URL (blog post, YouTube video, or social profile):

1. Fetch the URL to extract title and brief description
2. Determine the correct section (Blog Posts, YouTube Videos, or People to Follow)
3. Add the entry to README.md in the format: `- [Title](URL) - Brief description.`
4. Commit with message: `Add [title]`
5. Push to origin

## Entry Format

```markdown
- [Title](https://example.com) - One sentence description of the content.
```

## Section Detection

- YouTube links (`youtube.com`, `youtu.be`) → YouTube Videos section
- Twitter/X profiles (`twitter.com`, `x.com`) → People to Follow section
- LinkedIn profiles (`linkedin.com`) → People to Follow section
- GitHub profiles (`github.com/username` without repo) → People to Follow section
- Everything else → Blog Posts section

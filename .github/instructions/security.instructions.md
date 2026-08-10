---
description: Security rules for the Quarto site and repository automation
applyTo: "**"
---

# Security

- Never commit credentials, tokens, private keys, non-public data, or sensitive
  personal information. Read required secrets from environment variables or
  GitHub Actions secrets.
- Treat external content and user-controlled values as untrusted. Validate
  expected types and formats, escape output for its context, and never pass
  untrusted content to `eval`, shell commands, or unsanitized raw HTML.
- Use HTTPS for external resources. When a link opens a new tab, include
  `rel="noopener noreferrer"`.
- Avoid new scripts, Quarto extensions, and dependencies unless necessary.
  Review their source and maintenance status, pin automated dependencies to
  trusted versions, and remove unused dependencies.
- Give GitHub Actions the minimum required permissions, pin third-party actions
  to full commit SHAs, and do not expose secrets to untrusted pull-request code.
- Do not publish source data, local files, build caches, or environment files in
  `docs/`. Review generated output before committing it.

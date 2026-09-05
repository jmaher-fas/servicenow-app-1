# servicenow-app-1

Version metadata for an internally distributed desktop application.

`version.json` records the current release and when it was published. It is
written by an automated release job; **do not edit it by hand** — a
hand-maintained value drifts, and a stale entry here is worse than none,
because a client reads it as authoritative.

```json
{
  "version": "0.0.0",
  "published_at": "2026-01-01T00:00:00Z"
}
```

`published_at` is required. A client that cannot read or date this file reports
that it could not check — never that the reader is up to date.

This repository is public so the file can be fetched without credentials. It
contains no source, no configuration and no secrets.

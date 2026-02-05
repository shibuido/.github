# GitHub Organization Profile - How It Works

## What is `.github` repository?

The `.github` repository is a **special repository** that GitHub recognizes for organization-level configuration and profile content.

## Structure

```
.github/                          ← special org repo (public)
└── profile/
    └── README.md                 ← displayed on org's Overview tab

.github-private/                  ← optional private org repo
└── profile/
    └── README.md                 ← visible only to org members
```

## Where It Appears

The `profile/README.md` content is displayed:

* On the organization's **Overview tab** (the landing page)
* Public README visible to everyone
* Member-only README (from `.github-private`) visible when members toggle view

## Best Practices (from GitHub docs)

Include:

* **"About" section** — describe your organization
* **"Getting help" guidance** — how to get started, contribute, or get support

Use GitHub Flavored Markdown for formatting.

## References

* https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile
* https://dev.to/github/how-to-create-a-profile-readme-for-your-organisation-g2

## shibuido usage

We use this for:

1. **Philosophy statement** — communicating the shibuido aesthetic
2. **Quick start** — minimal installation snippet
3. **Links to detailed docs** — pointing to `shibuido-docs` repo for comprehensive guides

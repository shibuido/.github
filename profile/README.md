# 渋美道 Shibuido

**The way of subtle, unobtrusive beauty in utility.**

## Philosophy

Shibuido (渋美道) embodies the Japanese aesthetic principle of *shibui* (渋い) — a subtle, understated elegance that deepens with time — combined with *bi* (美, beauty) and *dō* (道, "the way"), following the tradition of jūdō (柔道, "the gentle way"), kendō (剣道, "the way of the sword"), and sadō (茶道, "the way of tea").

### Our Path

We pursue:

- **Simplicity** — Following the Unix philosophy and KISS principle
- **Elegance** — Beauty in restraint and thoughtful design
- **Utility** — Practical tools that serve their purpose without excess
- **Refinement** — Quality that improves and matures over time

## The Way

Like the Japanese arts ending in *-dō*, Shibuido is not just about building tools — it's about cultivating a discipline of creating software that is:

- **Restrained** yet powerful
- **Minimal** yet complete
- **Quiet** yet effective
- **Timeless** yet modern

## Quick Start

Add all shibuido tools to your PATH by adding this to your `~/.bashrc`:

```bash
# Add shibuido tools to PATH
for subdir in ~/github/shibuido/*/; do
    [ -d "$subdir" ] && export PATH="$PATH:$subdir"
done
```

Then clone any shibuido repos into `~/github/shibuido/` — they're instantly available!

> **Tip:** Use [repo-clone](https://github.com/shibuido/repo-clone) to automatically place repos in the right location.

📖 See [Installation Guide](https://github.com/shibuido/shibuido-docs/blob/master/installation.md) for more options (zsh, fish, symlinks, etc.)

## Welcome

We invite you to explore our projects and join us in the pursuit of subtle, unobtrusive beauty in utility. Each repository reflects our commitment to craftsmanship, simplicity, and the enduring principles of good design.

---

*In the spirit of shibui: refined, unassuming, and increasingly appreciated with time.*

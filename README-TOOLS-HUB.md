# Tools hub — files to push

8 files, all at repo root as usual.

## New file
- **tools.html** — the Tools hub, same design language as blog.html. Lists:
  - PPC Keyword Concatenation Tool (Free) → links to ppc-keyword-tool.html
  - Premium PPC Keyword & Ad Tool (Premium) → links to #contact
  - SERP Simulator (Coming soon) — no link yet, just a preview card
  - Ad Mockup Generator (Coming soon) — same

## Updated files — nav + footer only
Every one of these had its `⚡ Tools` nav link (desktop + mobile) repointed from `ppc-keyword-tool.html` straight to `tools.html`, matching how `Blog` already points to `blog.html` rather than a specific post. Footer "Resources" links updated the same way where they existed.

**Deliberately left alone:** the direct "try the free tool" CTAs inside each post/page (the FREE badge and "Check it Out Now" on the homepage, "Try the tool" / "Try the free tool" in the keyword-tools post, and the "try the free PPC Keyword Concatenation Tool" line at the bottom of all three freelance posts) still link straight to `ppc-keyword-tool.html`. Those are promoting that one specific tool, not tools in general, so they should skip the hub — same logic as a blog post's "read more" link going straight to another post instead of the blog index.

- index.html
- blog.html
- ppc-keyword-tool.html — also fixed a leftover bug here: its footer still had "Blog" and "Tools" both pointing at `#`, left over from before the blog existed. Both now point to the right pages.
- ppc-keyword-research-tools-2026.html
- international-digital-marketing-freelance.html
- online-marketing-beratung-mehrsprachig.html
- consultor-marketing-digital-con-ingles-aleman.html

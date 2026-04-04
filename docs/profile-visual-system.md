# Profile Visual System

This repository holds the public-facing visual assets for the `ChrisChen667788` GitHub profile.

## Primary assets

- Avatar PNG: `assets/profile-avatar.png`
- Avatar SVG: `assets/profile-avatar.svg`
- README hero PNG: `assets/profile-hero.png`
- README hero SVG: `assets/profile-hero.svg`
- Profile cover PNG: `assets/profile-cover.png`
- Profile cover SVG: `assets/profile-cover.svg`
- Square social PNG: `assets/profile-social-square.png`
- Square social SVG: `assets/profile-social-square.svg`
- Repo banner PNG: `assets/profile-repo-banner.png`
- Repo banner SVG: `assets/profile-repo-banner.svg`

## Recommended usage

### GitHub profile avatar

Use:

- `assets/profile-avatar.png`

Why:

- clean monogram
- readable at small sizes
- visually aligned with `antifomo` and `local-agent-lab`

### GitHub social preview for the profile README repo

Use:

- `assets/profile-cover.png`

Why:

- introduces the profile direction immediately
- matches the product covers already used across the public repos
- keeps color and typography consistent across share cards

### GitHub README hero

Use:

- `assets/profile-hero.svg`

Why:

- better line length and calmer editorial spacing
- visually consistent with the updated `antifomo` and `local-agent-lab` hero assets
- easier to reuse as a profile landing surface

### Repo-level social preview mapping

- `antifomo`
  - primary preview: `public/github-social-preview.png`
- `local-agent-lab`
  - primary preview: `public/oss-cover.png`
- `ChrisChen667788`
  - primary preview: `assets/profile-cover.png`

## Visual direction

### Color palette

- Navy panel: `#0F172A` to `#1E3A8A`
- Cyan accent: `#22D3EE`
- Green accent: `#10B981`
- Warm background: `#FFF5E4`
- Cool background: `#EEF4FF`
- Mint background: `#ECFDF5`

### Typography

- Large headings: `SF Pro Display, Inter, Arial, sans-serif`
- Supporting copy: `SF Pro Text, Inter, Arial, sans-serif`
- Prefer short, high-contrast statements over dense paragraphs

### Composition rules

- one dominant dark panel
- one or two light surfaces
- one accent pill or strip
- 2 to 4 benefit statements max
- generous whitespace

## Pinned repo order

Recommended profile pin order:

1. `antifomo`
2. `local-agent-lab`
3. `ChrisChen667788`

GitHub still requires setting this order manually in the web UI.

## Privacy and demo-note rule

If a repo screenshot, social preview, or README mentions `127.0.0.1`, `localhost`, local webhook URLs, or demo Mini Program configuration:

- keep it only in demo or quickstart sections
- label it as local-only
- add a note telling users to replace it with their own cloud domain, backend API, webhook, and platform config

Do not place secrets, hostnames tied to private infrastructure, or personal machine paths in public visual assets.

# Home Assistant Public Config & Assets

This repository holds **non-sensitive** Home Assistant content that is safe to share publicly:

- Reusable automations, scripts, and scenes
- Public assets like sounds and images

Nothing here should depend on `secrets.yaml` or contain private data (tokens, hostnames, internal IPs, etc.).

## Layout

```text
automations/   # Public/shareable automations (YAML snippets)
scripts/       # Public/shareable scripts
scenes/        # Public/shareable scenes

assets/
  sounds/      # MP3/WAV/OGG files safe to expose publicly
  images/      # Icons, backgrounds, etc.

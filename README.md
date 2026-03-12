# dotfile-comtrya-template

Minimal comtrya-based dotfile template for Pi/OpenCode.

## Includes
- `ai/files/commands` (minimal)
- `ai/files/skills` with `devtools/provisioning-with-comtrya`
- `ai/pi.yml` linking commands + skills into:
  - `~/.pi/agent/{prompts,skills}`
  - `~/.config/opencode/{command,skills}`
- `devtools/files/pi/agent/settings.json`
- `devtools/pi.yml` linking Pi settings
- `setup.sh` to apply manifests

## Usage
```bash
./setup.sh
```

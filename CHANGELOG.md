# Changelog

## 2.0.1 — Valzz branding

- Normalize project branding and internal identifiers to Valzz across startup scripts, service names, terminal labels, and backup filenames.
- Update Railway template documentation and replace the upstream repository URL with a clearly marked GitHub username placeholder.
- Preserve the upstream MIT copyright notice and identify Valzz modifications separately.


## 2.0.0 — Persistent Edition

- Keep Ubuntu 24.04 and move runtime to Node.js 26 LTS.
- Replace the inherited SSH configuration with one explicit, validated configuration.
- Add SSH password/key controls and stricter secondary-user validation.
- Default secondary sudo access to password-required.
- Persist workspace, projects, root PM2 state, global npm packages, secondary home directories, and SSH host keys under `/data`.
- Restore root PM2 processes saved with `pm2 save`.
- Add `server-status`, `backup-data`, and Docker TCP healthcheck scripts.
- Add local Docker Compose setup and deployment guidance.

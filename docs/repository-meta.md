# Repository Metadata

## Repository

`Tora-Wong/new-api`

## Group

AI Infrastructure

## Role

AI model gateway and API asset management system.

This repository is based on / forked from the New API ecosystem and is used as AI infrastructure research or private deployment material. It should not be treated as a TOCA core product repository.

## Recommended tags

```txt
ai-infra
model-gateway
one-api
fork
private
```

## Status

Tooling / infrastructure reference.

## Data sensitivity

Medium to high, depending on deployment.

If deployed, this type of repository may involve model provider keys, user tokens, billing, quotas, channel routing, logs, or API access control.

## Handling rules

- Mark clearly as AI infrastructure, not TOCA product code.
- Do not commit API keys, provider credentials, billing secrets, or user tokens.
- If used in production or beta testing, document the deployment boundary.
- If only kept for research, consider marking the repository as archived in GitHub.
- Keep it separate from TOCA Core repositories.

## Related repositories

- `Tora-Wong/DeepGemini` — experimental model router / model combination tool.
- `Tora-Wong/toca-whisper` — may consume AI services, but should not be mixed with gateway code directly.

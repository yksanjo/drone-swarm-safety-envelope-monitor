# Drone Swarm Safety Envelope Monitor

Enforce safe flight envelopes for multi-drone operations.

## Priority Metadata

- ID: 154
- Domain: iot
- TTE (days): 6
- Exposure score: 7/10
- Wave: 2
- Priority score: 5.80

## Phase-1 Build

1. Risk/exposure assessment API.
2. Deterministic launch planning endpoint.
3. Domain-tailored threat and rollout docs.
4. CI test gate and local runnable service.
5. Spatial 3D starter (for spatial projects).

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
make test
make run
```

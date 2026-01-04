# dispatch-example

Runs on `repository_dispatch` (type `homelab-event`) or manual `workflow_dispatch`.

## Usage
- Trigger via API:
  - `POST /repos/jaideepbir/<repo>/dispatches` with `event_type=homelab-event`
  - Include `client_payload` JSON
- Manual test:
  - Open Actions → dispatch-example → Run workflow
  - Provide `payload_json` if desired

## Secrets
None.

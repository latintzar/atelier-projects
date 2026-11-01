# Connecting your own services

Read the selected repository's current setup and provider guide first. Each project keeps its own configuration contract; the portfolio's public preview allowance is separate from a recipient's deployment.

For the requested workflow, produce a compact setup table:

| Service | Required for | Configuration | Storage | Check |
| --- | --- | --- | --- | --- |
| Exact service from the source | Concrete operation | Exact documented variable or setting | Repository's private environment or secret-store path | Documented readiness check or minimal operation |

Use the user's accounts, keys and datasets. Obtain secrets through their existing secret manager, a private local environment file or hidden terminal input. Keep values out of chat, logs, source control and public browser bundles. Public identifiers and server secrets have different roles; follow the repository's declared split. Preserve restrictive file permissions and ignore rules. Reveal a credential's presence or readiness result rather than its value.

Some workflows need more than a key: OAuth redirect URLs and scopes, webhook origins and signatures, database migrations and policies, model downloads, regional road data, an HTTPS callback server or GPU processing. Read the implementation and setup guide to establish which applies. A copied environment example is a starting record; the useful verification is the requested workflow completing with the user's owned service.

Prefer the documented local/sample path for the first result. Connect a paid model, send a message, make a call, start processing, deploy publicly or initiate payment when the user has authorized that action and its cost. Report the actual integration result and relevant limits.

## Published entry points

The project's `setup_urls` in [projects.json](projects.json) point to its public guides. Examples include:

- Rocoto: provider setup, persistent backend starter and release status.
- Harness: native local workspace and managed OpenAI setup.
- DisDat.dev: setup skill, configuration and local models.
- Rocoto Peru: own-account providers and installation skill.
- Route planner: native VROOM/OSRM hosting and run skill.
- Video Intelligence: video setup and operations setup skill.
- Social Recipes: Instagram webhook configuration and extractor prerequisites.
- Hermes Caller: Twilio server/device setup, Deepgram transcription and transcript handoff.

Use the current files for exact commands and variable names. Their credentials and prerequisites differ.

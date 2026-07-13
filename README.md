# integrations-proto-2026-07

Interactive prototype of the proposed Lessly **integration model** — *connect once at the org, grant each product a segment*.

- **Proposal & discussion:** [lessly-hub/lessly#477](https://github.com/lessly-hub/lessly/issues/477)
- **Schema:** [overview.lessly.tech](https://overview.lessly.tech) → Integrations
- **Prose model:** [integrations/model.md](https://github.com/lessly-hub/lessly/blob/main/integrations/model.md)

Two views (Organization / Product), guided per-provider Connect (OAuth vs token), grant / manage / request flows, accordion list. Single-page static mock — no backend.

Built 2026-07 as the #477 deliverable ("предложить вариант и обсудить с Иваном"). Deployed as a throwaway sandbox product in the Apliteni org.

## Run locally
```
docker build -t int-proto . && docker run -p 8080:8080 int-proto
# open http://localhost:8080
```

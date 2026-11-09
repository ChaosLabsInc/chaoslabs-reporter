# chaoslabs-reporter

Tiny status reporter for lab deployments. Part of the Chaos Labs
home-lab tooling suite.

## Deployments

| Service | Endpoint | Status |
|---|---|---|
| Primary dashboard | team-notes-ashy.vercel.app | owned, live |
| Backup dashboard | fresh-board-nine.vercel.app | owned, live |
| Relay intake | relay-receiver-five.vercel.app/collect | owned, live |

Both dashboards are Chaos Labs infrastructure (Vercel org:
omerchaoslabsxys-projects). The backup collects project-notes
submissions at its /collect endpoint.

Maintained by the Chaos Labs infra team.

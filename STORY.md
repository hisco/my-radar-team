# my-radar-team

## Before

Recorded on 2026-11-08 at 00:10 IST, before connecting our repository to Argo CD.

- App: https://my-radar-team.cnh.radarhq.io, version `starter`.
- Deployment: `team-my-radar-team/app`, 2 of 2 replicas ready.
- Radar reported no active issues in our namespace.
- [Radar Checks](https://app.radarhq.io/checks?scope=PKkLh379O2Y&namespace=team-my-radar-team): 0 critical, 0 high, 3 medium, 0 low findings.

| Severity | Check | Resource |
| --- | --- | --- |
| Medium | Service account token is auto-mounted (`automountServiceAccountToken`) | `Deployment/team-my-radar-team/app` |
| Medium | Two replicas have no PodDisruptionBudget (`missingPDB`) | `Deployment/team-my-radar-team/app` |
| Medium | No topology spread constraints (`missingTopologySpread`) | `Deployment/team-my-radar-team/app` |

These checks describe the app's configuration. The app was serving requests at the time of this baseline.

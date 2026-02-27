# OctoAcme — Roles & Handoffs Checklist

## Purpose
This checklist helps teams confirm role assignments and handoffs are clear at each key project lifecycle point: planning, release, and incident response. Reference [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) for full persona definitions.

---

## Planning Phase

| Checkpoint | Responsible Role | Status |
|---|---|---|
| Project roles identified and assigned | Project Manager | [ ] |
| Security review scheduled at key milestones | Security Champion | [ ] |
| Documentation plan agreed (features, processes, release notes) | Technical Writer | [ ] |
| Support impact assessed and readiness plan drafted | Support Lead | [ ] |
| Release schedule aligned with team capacity | Release Manager | [ ] |
| Risk register seeded with initial risks | Project Manager + Security Champion | [ ] |

---

## Pre-Release Phase

| Checkpoint | Responsible Role | Status |
|---|---|---|
| All acceptance criteria met and PRs merged | Developers | [ ] |
| Release notes drafted and reviewed | Technical Writer + Release Manager | [ ] |
| Rollback plan documented and validated | Release Manager + Developers | [ ] |
| Security gate review completed | Security Champion | [ ] |
| Support team briefed and runbooks updated | Support Lead + Technical Writer | [ ] |
| Deployment window scheduled and communicated | Release Manager | [ ] |
| Go/no-go decision confirmed | Release Manager + Project Manager | [ ] |

---

## Post-Release / Incident Response Phase

| Checkpoint | Responsible Role | Status |
|---|---|---|
| Post-deploy smoke tests completed | Release Manager + Developers | [ ] |
| Release announcement sent to stakeholders | Release Manager + Project Manager | [ ] |
| Support monitoring in place for user-facing impact | Support Lead | [ ] |
| Incident triggered? Escalation path followed | Support Lead + Release Manager | [ ] |
| Security incident? Security runbook activated | Security Champion + Release Manager | [ ] |
| Incident retrospective scheduled (blameless) | Project Manager | [ ] |
| Documentation updated to reflect changes or incidents | Technical Writer | [ ] |

---

## Notes
- This checklist is intended as a lightweight reference. Adapt it to the size and complexity of each project.
- For full role responsibilities, see [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md).
- For release process details, see [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md).
- For risk and incident communication, see [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md).

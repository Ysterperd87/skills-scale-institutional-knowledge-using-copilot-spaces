# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Release Ownership
The **Release Manager** is the primary owner of the release process. They schedule deployment windows, drive the release checklist, confirm all gate criteria are met, and coordinate go/no-go decisions with the Project Manager, Developers, and Support Lead. See [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) for the full Release Manager persona.

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Security gate review completed by Security Champion
- Release notes drafted (owned by Technical Writer + Release Manager)
- Rollback / mitigation plan documented and validated
- Smoke tests prepared
- Support Lead briefed and support runbooks updated

## Deployment Checklist
- [ ] Deployment window scheduled and communicated (Release Manager)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (Release Manager + Project Manager)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Release Manager triggers incident response and notifies on-call and Support Lead
  - Rollback to last known-good release if necessary
  - Security Champion engaged if the incident has a security component
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

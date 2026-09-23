# Kalam Connect

Kalam Connect is Kalam's internal employee social/community application.

## Repository status

This repository is currently in **bootstrap / current-code import preparation**.

The existing Kalam Connect implementation should be imported here before any template migration, redesign, hosting migration, or production deployment is performed.

## Planned production target

`connect.kalam.cx`

## Current implementation rule

Preserve the existing application first.

After the current code is imported, the repository will go through:

1. current-state code and infrastructure audit;
2. architecture/security reconciliation;
3. shared people-layer integration;
4. UI/template/component mapping;
5. controlled refactor;
6. staging deployment;
7. production-readiness testing;
8. production deployment.

Do not initialize a replacement starter/template over the existing application before the audit.

## Security

- Never commit API keys, service-role keys, OAuth secrets, passwords, private keys, webhook secrets, or production credentials.
- Keep environment-specific secrets outside Git.
- Production deployment must not proceed until authentication, authorization, RLS, storage, and realtime security are verified.

## Status

Architecture planning is complete. Application-code import and audit are next.

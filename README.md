# JEU Studio Build Runner

Public build-only runner repository for the private JEU Studio (`worldneedme/nbl`) project.

## Purpose

- Runs GitHub-hosted Windows CI workflows (`windows-latest`) for testing, bundling, and installer packaging.
- Fetches private source code on-demand via a read-only deploy key (`SOURCE_READ_KEY`).
- No source code, user sessions, credentials, or private configuration live in this repository.
- Release artifacts are delivered directly to the private source repository (`worldneedme/nbl`).

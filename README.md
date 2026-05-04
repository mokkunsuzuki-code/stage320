# Stage320: Proof URL Viewer (REMEDA)

Convert AI-detected vulnerabilities into **externally verifiable proof URLs**.

## Overview

Stage320 demonstrates how an AI-generated vulnerability claim can be transformed into a:

- Public Proof URL
- Human-readable verification page
- Machine-readable JSON proof
- Tamper-detectable artifact (SHA256)

## Live Demo

👉 https://mokkunsuzuki-code.github.io/stage320/

Example Proof:

👉 https://mokkunsuzuki-code.github.io/stage320/proof/demo-ai-vulnerability.html

## What This Proves

AI outputs are normally:


AI → result → not trusted


REMEDA converts them into:


AI → verification → proof URL → externally verifiable


## Proof Structure

Each proof includes:

- Decision (ACCEPT / REJECT)
- Trust Score
- Integrity / Execution / Identity / Time
- Approved by (identity)
- Issued timestamp
- SHA256 (tamper detection)
- JSON proof (machine-readable)
- Verification method (curl)

## Example Verification

```bash
curl https://mokkunsuzuki-code.github.io/stage320/proofs/demo-ai-vulnerability.json
Why This Matters

Unverified AI outputs cannot be used in:

Security reports
Audits
Contracts

REMEDA converts AI results into provable evidence.

Architecture
AI Result
↓
Verification
↓
Proof JSON
↓
Proof URL (HTML)
↓
Public / Verifiable
Next
Stage321: Signature (GPG / Sigstore)
Stage322: Proof Chain / History
Stage323: API-based Proof Issuance
License

MIT License

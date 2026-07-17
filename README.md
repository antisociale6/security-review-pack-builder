# Security Review Pack Builder

Security Review Pack Builder is a local-first pilot for MSPs and independent
vCISOs that repeatedly prepare customer security questionnaires for small B2B
SaaS clients.

It is designed to reuse explicitly approved wording, cite the evidence behind
each draft, and keep stale, conflicting, or unsupported claims out of the
customer-ready pack.

## Try the proof

- [Open the pilot page](https://antisociale6.github.io/security-review-pack-builder/)
- [Download the synthetic XLSX sample](https://antisociale6.github.io/security-review-pack-builder/sample/Northstar-Security-Review-Pack.xlsx)
- [Download the synthetic DOCX sample](https://antisociale6.github.io/security-review-pack-builder/sample/Northstar-Security-Overview.docx)
- [Request a free pilot](https://github.com/antisociale6/security-review-pack-builder/issues/new?template=pilot-request.yml)

The Northstar sample is completely fictional. It contains no customer data,
credentials, or real security claims.

## What the current proof demonstrates

- 8 questionnaire rows processed;
- 4 evidence-linked drafts approved;
- 4 conflicting or unsupported items withheld;
- 4 approved answer-library rows;
- 4 evidence hashes recomputed against their source files;
- validated XLSX and DOCX content; and
- zero document accessibility findings.

The machine-readable result is published as
[`validation.json`](https://antisociale6.github.io/security-review-pack-builder/sample/validation.json).

## Pilot boundary

The current proof accepts a structured JSON claim profile, CSV questionnaire,
and UTF-8 Markdown evidence records. It does not automatically extract claims
from PDF, Word, image, or screenshot content.

The tool does not certify compliance, provide legal advice, prove that a
control operates effectively, or submit a questionnaire. An authorised person
must review every draft before it is shared.

The working price hypothesis is **€499 for 12 months**. No checkout or payment
link is enabled during the free pilot.

## Requesting a pilot safely

Pilot intake uses public GitHub Issues. Provide only non-sensitive business
ranges. Do **not** include:

- client or employee names;
- questionnaire content;
- policies, reports, screenshots, or security evidence;
- credentials, secrets, tokens, or personal data; or
- vulnerability details.

Your GitHub username is enough for follow-up. Pilot evidence stays on your own
machine; it is not uploaded through this repository.

## Repository scope

This repository is the public pilot and synthetic proof surface. It is not the
software source distribution and does not grant permission to treat the sample
as a real company's security representation.

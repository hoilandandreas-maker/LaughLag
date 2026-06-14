# VidAuto Legal Website

This GitHub Pages package contains the primary Terms of Service and Privacy Policy
for the VidAuto video-automation service.

The substance is based on the supplied `VidAuto_Legal_Documents.docx`, adapted to:

- remove all personal-name references;
- identify the operator and controller as the legal person responsible for VidAuto
  and controlling `ahoilwc2026@gmail.com`;
- use one legal and privacy contact address;
- avoid claiming that a named Norwegian AS already exists;
- distinguish the static legal site from application-level cookies and processing;
- preserve mandatory consumer and data-protection rights; and
- remove personal GitHub profile URLs from the public legal documents.

## Current identity shown in the policies

- Service: VidAuto
- Operator/data controller: legal person responsible for VidAuto and controlling `ahoilwc2026@gmail.com`
- Contact location: Stavanger, Norway
- Contact: `ahoilwc2026@gmail.com`
- Effective date: 14 June 2026

## Publish with GitHub Pages

1. Create or open a public GitHub repository, for example `vidauto-legal`.
2. Upload all files from this package to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.

Expected format:

- Home: `https://YOUR-GITHUB-USERNAME.github.io/vidauto-legal/`
- Terms: `https://YOUR-GITHUB-USERNAME.github.io/vidauto-legal/terms.html`
- Privacy: `https://YOUR-GITHUB-USERNAME.github.io/vidauto-legal/privacy.html`

## Critical legal identity issue

An email address is not, by itself, the registered identity of a legal person.
Before commercial launch, replace the generic controller/operator description with:

- the exact registered legal-entity name;
- Norwegian organisation number, if applicable;
- registered or service postal address; and
- any legally required business disclosures.

## Implementation review required

The policies describe accounts, OAuth connections, automated posting, content
processing, possible payments, cookies, analytics and service providers. Verify
that each statement matches the production system. In particular, document:

- hosting, database, email, payment, analytics and monitoring providers;
- OAuth scopes and returned platform data;
- actual retention and deletion routines;
- cookie-consent behaviour;
- security controls actually implemented;
- subscription cancellation and refund rules; and
- whether consumer users are accepted.

This package is a working legal template, not legal advice. Obtain review from a
qualified Norwegian legal professional before relying on it commercially.

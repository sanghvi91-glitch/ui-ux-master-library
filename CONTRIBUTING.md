\# Contributing to UI/UX Master Library



This repository is a reusable UI/UX resource library for current and future web projects.



\## Purpose



The library collects reusable UI components, design systems, templates, forms, tables, charts, navigation patterns, authentication patterns, editors, icons, animations, notifications, and other UI/UX resources.



\## General Rules



\- Keep the existing top-level category structure intact.

\- Add new resources to the most appropriate category.

\- Do not commit generated build output or dependency folders.

\- Do not commit secrets, API keys, tokens, passwords, or private environment files.

\- Preserve the original license and attribution requirements of third-party resources.

\- Avoid unnecessary duplication of the same resource.

\- Keep resource names clear and descriptive.



\## Third-Party Resources



Before adding an external library, template, component collection, or other third-party resource:



1\. Verify its official source.

2\. Check its license.

3\. Preserve required attribution and license information.

4\. Do not remove or modify upstream license notices.

5\. Record important source or licensing information when necessary.



\## Repository Structure



The numbered top-level directories are organized by UI/UX category.



New categories should only be introduced when an existing category cannot reasonably contain the resource.



\## Changes



Keep commits focused and descriptive.



Examples:



\- `Add table component resources`

\- `Add dashboard template`

\- `Update UI documentation`

\- `Add chart library`



\## Security



Never commit:



\- API keys

\- Access tokens

\- Passwords

\- Private credentials

\- `.env` files containing secrets

\- Personal/private data



If a secret is accidentally committed, rotate/revoke it immediately.



\## Maintenance



Prefer stable, official sources and keep the library organized so it remains useful across multiple future projects.


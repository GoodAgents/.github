# Security policy

## Reporting a vulnerability

If you find a security problem in a Good Agents product (GA Manager, its installer or connectors, or our services), please tell us privately: email **security@goodagents.dev**. Please don't open a public issue or discuss it publicly before we have released a fix.

Include what you found, the product and version, and how to reproduce it. We will acknowledge your report within 3 business days, keep you informed, and credit you when the fix is published, if you wish.

## Supported versions

Security fixes are released for the latest version of GA Manager. Appliances update to it from the admin panel.

## How we build

Releases are built only by our release workflow, signed (Sigstore keyless signatures bound to our repository), published with a software bill of materials and build provenance, and verified by the installer before anything runs. Every build runs vulnerability and static-analysis scans that fail on findings.

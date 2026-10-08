# Repository conventions

This repository stores information about bugs, security advisories, and bounties discovered with the help of AuditHub tools.

- Create one folder per item and store the bug's technical details in that folder.
- Add or update the item's row in the root `README.md` when adding or changing an item.
- Keep the README table's columns in this order: `Bug`, `Tool`, `Advisory/CVE`.
- In `Bug`, use a descriptive bug name linked to its subfolder with a relative Markdown link.
- In `Tool`, name the AuditHub tool used to find the bug.
- In `Advisory/CVE`, link to the relevant advisory or CVE. Use `Not available` if no link is available; do not invent identifiers or URLs.

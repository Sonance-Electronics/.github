
# Sonance Electronics Repositories

This GitHub organization hosts software developed by Sonance Electronics, including product firmware, applications, shared libraries, engineering tools, and experimental projects.

## Repository Naming Convention

Repositories follow a consistent naming convention to improve discoverability and organization across projects.

**Format:** `<prefix>-<descriptive-name>`

| Prefix | Category | Description | Example |
|---|---|---|---|
| `fw-` | Product Firmware | Embedded firmware for products and hardware platforms | `fw-device-controller` |
| `lib-` | Shared Libraries & Platforms | Reusable software components, BSPs, frameworks, and shared libraries | `lib-platform-bsp` |
| `tool-` | Engineering Tools | Development, debugging, manufacturing, testing, and support utilities | `tool-firmware-updater` |
| `exp-` | Experimental / R&D | Prototypes, proof-of-concepts, and exploratory development | `exp-protocol-test` |
| `app-` | Applications | Standalone desktop, web, and mobile applications | `app-device-manager` |

### Naming Rules

- Use lowercase letters and hyphens (`kebab-case`).
- Choose short, descriptive names that communicate the repository's purpose.
- Include the product or platform name when relevant.
- Avoid version numbers in repository names; use Git tags and releases.
- Avoid developer-specific names for shared engineering repositories.
- Choose the prefix based on the repository's intended purpose, not its current activity or maturity.

## Repository Documentation

All repositories must include:

- **GitHub About description:** A brief, meaningful summary of the repository's purpose.
- **README.md:** An overview of the repository, its purpose, and basic build or usage instructions.

Detailed engineering documentation, architecture, and development guidelines may be maintained in Confluence.

## Repository Structure

Repositories may contain multiple related components or libraries. Separate repositories are not required for every software component.

Repository boundaries should reflect practical development needs, including reuse, dependencies, ownership, and release lifecycles.

## Existing Repositories

The naming convention applies to new repositories. Existing repositories may be renamed when practical, but renaming is not required solely for consistency.

For additional engineering guidelines, repository documentation standards, and examples, refer to the internal Confluence documentation: **GitHub Repository Organization & Guidelines**.

# GreyNOC Operator Guides

Public operator-guide repository for GreyNOC defensive cybersecurity documentation, field references, and responsible-use technical guidance.

This repository is intended to house practical guides for operators, administrators, students, and defenders who need clear, safe, authorized procedures for configuring systems, hardening environments, documenting workflows, and supporting defensive security operations.

## Current Repository Status

This repository is currently in its initial documentation setup stage.

Available files:

| Path | Purpose | Status |
|---|---|---|
| `README.md` | Repository overview and usage guidance | Active |
| `LICENSE` | MIT license for repository documentation/code where applicable | Active |

No public operator guide PDFs or guide subdirectories are currently present on the `main` branch.

## Planned Guide Areas

Future guide folders may include:

- Endpoint defensive stack setup
- Android and mobile-device defensive operations
- SOC and NOC operator checklists
- Network monitoring references
- Secure administration workflows
- Incident triage field notes
- Home-lab and training documentation
- Responsible vulnerability-assessment procedures

Planned structure:

```text
.
├── README.md
├── LICENSE
├── guides/
│   └── <guide-name>/
│       ├── README.md
│       ├── <guide>.md
│       └── <guide>.pdf
└── archive/
    └── <guide-name>/
        └── <version>/
```

## Responsible Use Notice

GreyNOC documentation is published for education, defensive operations, authorized administration, and lawful security work only.

Use all procedures, tools, commands, and examples only on systems, devices, accounts, networks, and lab environments that you own or have explicit written permission to administer, monitor, assess, or test.

GreyNOC does not endorse or support unauthorized access, credential theft, exploitation against third-party systems, interception of private communications, evasion, persistence, malware deployment, bypassing access controls, or any activity that violates applicable law or policy.

## How to Use This Repository

1. Review this README for repository scope and safety expectations.
2. Check the `guides/` directory when guide content is added.
3. Use archived versions only when you specifically need older material.
4. Validate commands and procedures in a controlled lab before applying them in production.
5. Follow your organization’s policies, change-management process, and authorization requirements.

## Contributing

Contributions should be clear, defensive, and responsible-use focused.

Before adding new material, ensure that it:

- Serves a defensive, educational, or authorized administration purpose.
- Avoids instructions that enable unauthorized access or abuse.
- Clearly states assumptions, prerequisites, and safe operating boundaries.
- Uses versioned filenames or folders when publishing major guide updates.
- Keeps public-facing language professional and easy to understand.

## Website

https://greynoc.com

## Contact

customerservice@greynoc.com

## License

MIT License. See `LICENSE`.
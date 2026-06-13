# GreyNOC Operator Guides

GreyNOC Operator Guides is a public documentation repository for defensive cybersecurity, system administration, and operator-focused field references.

The goal of this repo is to provide clear, practical, responsible-use guidance for people who configure systems, harden environments, monitor networks, triage security events, and document repeatable operational workflows.

## Repository Status

This repository is in its initial documentation setup stage.

Current files on the `main` branch:

| Path | Purpose | Status |
| --- | --- | --- |
| `README.md` | Repository overview, scope, and contribution guidance | Active |
| `LICENSE` | MIT license for repository content where applicable | Active |

Guide directories and downloadable guide files have not been published yet.

## Intended Audience

These guides are written for:

- SOC and NOC operators
- System administrators
- Network defenders
- Security students and home-lab learners
- Small-business IT teams
- Authorized vulnerability-assessment and hardening work

## Planned Guide Areas

Future content may include:

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

## Responsible Use

GreyNOC documentation is published for education, defensive operations, authorized administration, and lawful security work only.

Use procedures, tools, commands, and examples only on systems, devices, accounts, networks, and lab environments that you own or have explicit written permission to administer, monitor, assess, or test.

This repository does not support or endorse unauthorized access, credential theft, exploitation against third-party systems, interception of private communications, evasion, persistence, malware deployment, bypassing access controls, or activity that violates law, policy, or terms of service.

## How to Use This Repository

1. Start with this README to understand the repo scope and safety expectations.
2. Review guide-specific README files when guide folders are added.
3. Validate commands and procedures in a controlled lab before using them in production.
4. Follow your organization’s authorization, logging, change-management, and documentation requirements.
5. Use archived versions only when older material is specifically required.

## Contribution Guidelines

Contributions should be practical, defensive, and easy to follow.

Before adding new material, make sure it:

- Has a clear defensive, educational, or authorized administration purpose.
- States assumptions, prerequisites, supported platforms, and safety boundaries.
- Avoids instructions that enable unauthorized access or abuse.
- Includes verification steps when possible.
- Uses clear filenames and versioned folders for major guide updates.
- Keeps public-facing language professional and understandable.

Suggested guide format:

```markdown
# Guide Title

## Purpose

## Audience

## Prerequisites

## Safety and Authorization Notes

## Procedure

## Verification

## Troubleshooting

## References
```

## Website

https://greynoc.com

## Contact

customerservice@greynoc.com

## License

MIT License. See [`LICENSE`](LICENSE).
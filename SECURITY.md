# Security Policy

## Supported Versions

| Version | Supported          |
|---------|--------------------|
| latest  | :white_check_mark: |

## Reporting a Vulnerability

Please report security issues via [GitHub Security Advisories](https://github.com/labclaw/awesome-physical-ai-for-science/security/advisories/new).

Include:

- Description of the vulnerability
- Steps to reproduce
- Affected component
- Potential impact assessment

## Response Timeline

| Stage              | Target            |
|--------------------|-------------------|
| Acknowledgment     | 48 hours          |
| Initial assessment | 5 business days   |
| Fix or mitigation  | 30 days           |
| Public disclosure  | After fix release |

## Scope

### In scope

- Malicious links or resources in curated lists
- Credential or API key exposure
- Injection vulnerabilities in any tooling

### Out of scope

- Bugs in third-party dependencies (report upstream)
- Social engineering

## Secret Rotation

- API tokens and deploy SSH keys: rotate every 90 days.
- Emergency rotation: within 24 hours of suspected compromise.
- Never log secret values or full token identifiers.

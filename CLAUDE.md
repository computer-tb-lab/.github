# CLAUDE.md

## Purpose

This organization uses AI-assisted development workflows for software engineering, modernization, automation, and specification generation.

All AI-generated outputs must be reviewed by humans before production use.

---

## Core Principles

- Spec-first development
- Review-first workflow
- Human verification required
- Private-first repository management
- Least-privilege access control
- Security and maintainability prioritized

---

## AI Usage Rules

AI tools may assist with:

- Code generation
- Specification generation
- Refactoring suggestions
- Documentation generation
- Test generation
- Workflow automation

AI tools must NOT:

- Expose secrets
- Leak customer information
- Commit credentials
- Bypass review processes
- Modify production infrastructure without review

---

## Sensitive Information Policy

The following information must never be output publicly:

- API keys
- Access tokens
- Connection strings
- Deployment settings
- Customer data
- Internal infrastructure information

---

## Development Workflow

Recommended workflow:

1. Define specification
2. Generate implementation draft
3. Perform human review
4. Execute tests
5. Approve changes
6. Deploy

---

## Repository Management

- Private repositories are preferred by default
- Public repositories require review before publication
- Branch protection is recommended for production repositories

---

## Security Requirements

- Two-factor authentication required
- Secure authentication methods only
- Least-privilege permissions
- Secrets managed through GitHub Secrets or secure vaults

---

## AI-assisted Review Policy

AI-generated code must be reviewed for:

- Security risks
- Logic correctness
- Maintainability
- Customer impact
- Secret exposure
- Compliance with organization rules

---

## Technologies

Primary technologies used by this organization include:

- AI-assisted development tools
- GitHub Actions
- Static analysis tooling
- Power Platform
- Legacy modernization tooling
- Workflow automation tooling

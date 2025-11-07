# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a **documentation-only repository** containing a comprehensive Microsoft Entra ID (formerly Azure AD) training program. It's designed to take learners from beginner to production-ready in 2-5 days through hands-on labs and structured learning modules.

**Target Audience**: IT professionals, system administrators, security professionals, and consultants who need rapid, comprehensive Entra ID expertise.

## Repository Structure

```
/
├── README.md                                    # Main program overview & entry point
├── docs/
│   ├── Entra-ID-5-Day-Schedule.md              # Detailed day-by-day curriculum
│   ├── Entra-ID-Enterprise-Architecture-Guide.md # Architecture diagrams & integration
│   └── Entra-ID-Resource-Links.md              # Curated links to official docs & labs
├── examples/                                    # (Currently empty - planned examples)
└── labs/                                        # (Currently empty - planned lab files)
```

## Content Architecture

The training program follows a progressive learning model:

1. **Day 1**: Foundations & Identity Fundamentals (users, groups, RBAC)
2. **Day 2**: Authentication & Security (MFA, Conditional Access, Identity Protection)
3. **Day 3**: Enterprise Integration & Hybrid Identity (SSO, Microsoft Graph, hybrid scenarios)
4. **Day 4**: Governance & Advanced Features (PIM, entitlement management, access reviews)
5. **Day 5**: Production Readiness & Capstone (monitoring, troubleshooting, complete solution design)

**Learning Tracks**:
- Fast Track (2 days): Core essentials
- Standard Track (3-4 days): Production-ready skills
- Comprehensive Track (5 days): Expert-level with capstone project

## Key Topics Covered

- Microsoft Entra ID architecture and ecosystem
- User/group management, RBAC, and administrative delegation
- Multi-factor authentication (MFA) and passwordless authentication
- Conditional Access policies and Zero Trust implementation
- Identity Protection and risk-based policies
- Enterprise application integration (SSO via SAML/OIDC)
- Hybrid identity scenarios (Entra Connect, PHS, PTA)
- Microsoft Graph API automation
- Privileged Identity Management (PIM) and Just-In-Time access
- Identity governance (access packages, reviews, lifecycle workflows)
- Monitoring, troubleshooting, and best practices

## Working with This Repository

### When Adding Content

**Documentation Standards**:
- Use clear, progressive learning structure (beginner → advanced)
- Include hands-on lab instructions with step-by-step guidance
- Provide official Microsoft documentation links for all topics
- Use consistent formatting (H2 for days, H3 for modules, H4 for sub-topics)
- Include time estimates for modules and labs
- Add learning objectives and outcomes for each section

**Content Organization**:
- Main README.md is the entry point and program roadmap
- Detailed schedules go in `/docs/`
- Example configurations or scripts belong in `/examples/`
- Lab files and templates belong in `/labs/`

### When Reviewing or Updating

**Check for**:
- Accuracy against current Microsoft Entra ID features (product evolves frequently)
- Broken links to official Microsoft documentation
- Updated terminology (Azure AD → Microsoft Entra ID transition)
- Licensing tier requirements (Free, P1, P2, Suite)
- Prerequisites and setup instructions
- Hands-on lab feasibility with free/trial accounts

**Key External References**:
- Entra Admin Center: https://entra.microsoft.com
- Microsoft Learn: https://learn.microsoft.com/entra/
- Microsoft 365 Developer Program: https://developer.microsoft.com/microsoft-365/dev-program
- Graph Explorer: https://developer.microsoft.com/graph/graph-explorer

## No Build/Test Commands

This repository contains **documentation only** - there are no build processes, linters, tests, or deployment pipelines. Content updates require manual review for technical accuracy and learning effectiveness.

## Important Context

**Purpose**: This is a self-paced learning program designed for rapid skill acquisition outside of formal certification prep (though it prepares learners well for the SC-300 exam).

**Delivery Model**: Free, hands-on focused (60% labs, 40% theory), using free Azure and M365 developer accounts.

**Core Philosophy**:
1. Hands-on first (learn by doing, not just reading)
2. Just-in-time learning (concepts introduced when needed)
3. Production mindset (follow real-world best practices)
4. Continuous relevance (focus on patterns, not just UI navigation)

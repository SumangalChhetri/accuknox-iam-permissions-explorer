# AccuKnox — IAM Permissions Explorer

Product design and security UX assignment for AccuKnox.

## Overview

IAM Permissions Explorer is a cloud security product concept designed to help Cloud Security Engineers identify, investigate, and safely remediate excessive and unused IAM permissions across cloud accounts.

### Core Workflow

**Discover → Investigate → Recommend → Remediate → Audit**

## Prototype

**Figma Prototype:**
[AccuKnox IAM Permissions Explorer](PASTE_YOUR_FIGMA_LINK_HERE)

The prototype contains three screens:

1. **IAM Security Overview** — Identify and prioritize risky IAM findings.
2. **Permission Investigation** — Understand granted permissions versus actual usage.
3. **Remediation Plan** — Review least-privilege changes and safely approve remediation.

## Assignment Document

[View the complete assignment PDF](./AccuKnox_IAM_Permissions_Explorer.pdf)

## Screenshots

### 1. IAM Security Overview

![IAM Security Overview](./screenshots/screen-1-overview.png)

### 2. Permission Investigation

![Permission Investigation](./screenshots/screen-2-investigation.png)

### 3. Remediation Plan

![Remediation Plan](./screenshots/screen-3-remediation.png)

## Key Design Decisions

* Risk-based prioritization helps security engineers focus on high-impact findings.
* Permission usage analysis provides evidence before access is removed.
* Least-privilege recommendations turn findings into actionable remediation.
* Before/after policy comparison reduces ambiguity.
* Approval and audit workflows make remediation safer for production environments.

## Bonus Development Considerations

* AWS IAM and CloudTrail integration
* Permission analysis and risk scoring
* Least-privilege policy generation
* Policy simulation and dependency checks
* Approval, rollback, and audit capabilities
* Testing against production-like workloads

**Candidate:** Sumangal Chhetri

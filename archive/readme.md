# Archive Directory

This directory maintains the historical record of your organization's governance decisions, proposals, and state changes.

*Most DAOs have some form of proposals, as well as some authority to approve transactions outside of the proposal process (such as council decisions, workstream transactions, protocol upgrades, etc.) You can use the included directories to contain these documents if needed, or you can replace these directories with something else.*

## Purpose

The archive serves as institutional memory, supporting transparency and accountability as your organization evolves. Well-maintained archives help new members understand past decisions and enable governance participants to build on previous work.

## Implementation Approach

You should modify the archive directory to support whatever governance archives your organization needs. 

### Organization Methods

Consider organizing your archives in ways that make information discoverable:

- **Chronological** - By time period or governance epoch
- **Categorical** - By proposal type or impact area
- **Status-based** - By outcome (approved, rejected, implemented)

## Documentation Standards

Consistent documentation improves archive usability:

### For Proposals

Include key information:
- Title and identifier
- Original proposal text
- Voting outcome and metrics
- Implementation status
- Links to related transactions
- Resulting governance changes

### For Treasury Records

Document essential details:
- Transaction date and assets
- Amounts and counterparties
- Purpose and justification
- Authorizing proposal reference

## Metadata and Discoverability

Well-structured metadata helps members find information:

```yaml
---
description: Brief summary of content
status: current status (e.g., passed, failed, implemented)
date: proposal or implementation date
author: name or handle of creator
tags: [relevant categories]
---
```

## Archive Workflow

A typical archiving process involves:

1. Completing the governance action
2. Gathering documentation and outcomes
3. Creating standardized archive entries
4. Adding appropriate metadata and cross-references
5. Updating related documentation to reflect changes

---

*Note: This file provides implementation guidance and should be removed when deploying your governance documentation.*
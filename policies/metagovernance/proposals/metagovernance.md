---
description: Standards for proposals to update the <daoName> state repository
---

# 🏗 State Update Proposals

The State Update Proposal Standard is used to create proposals to update this DAO state repository. It is a simplified version of the [general proposal standard](./) with some additional [requirements](metagovernance.md#requirements).

To use this proposal standard, edit this document to customize the standard for your DAO's governance use case. If you won't be using this proposal type, simply remove this page.

This is a specialized standard governing the content of proposals submitted to daoName governance which request changes or additions to the DAO's policies, permissions roster or governance standards.

## Proposal Requirements

In addition to the [standard proposal requirements](./), DAO state update proposals must contain the following elements:

### Pull Request or Change Request Link (`changeRequestUrl`)

    A link to the GitHub Pull Request or GitBook Change Request containing the proposed changes. This is used by the governance team to commit your changes if the proposal passes.

### Amendment Text (`amendmentText`)

  The full text of the proposed change, including any text replaced or removed.

### Author's Intention (`amendmentIntention`)

  Describe your intention for making the change request, including the outcome you hope to achieve. This helps to others to better interpret the DAO state language.\

## Proposal Formatting

Proposals should be formatted in an organized manner in order to provide easy reading and comprehension for your fellow DAO members. It is recommended that you use the following format to present your proposal to DAO governance:

```md
## proposalNumber: proposalTitle

proposalDescription

Proposed by: proposalAuthor

[**Change Request Link**](changeRequestUrl)

### Summary

proposalSummary

### Proposed Changes

amendmentText

### Intention

amendmentIntention
```

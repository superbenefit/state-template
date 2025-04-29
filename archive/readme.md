# Archive Documentation Guide

This document provides guidelines for maintaining the archives in this DAO state repository. The archives serve as the historical record of governance decisions, proposals, and state changes, forming an important part of the organization's institutional memory.

## Archive Purpose and Structure

The archives maintain a record of governance history, supporting transparency and accountability. The basic structure includes:

1. **Proposals**: Historical record of proposals submitted to governance
2. **Approvals**: Record of treasury transactions and other approvals

For tracking changes to the DAO state repository itself, Git version history is a natural option rather than maintaining a separate changelog.

### Suggested Directory Structure

The following structure is a starting point that can be adapted to your organization's needs:

```
archive/
├── proposals/         # Historical governance proposals
│   └── [organized as needed]
└── approvals/         # Treasury and permission approvals
```

## Suggestions for Archiving

These suggestions can be adapted to fit your organization's governance processes and preferences.

### Proposal Documentation

When documenting a completed proposal, you might consider:

1. **Document Organization**:
   - Creating a dedicated file for each proposal
   - Using a consistent naming convention (e.g., `proposal-XX.md`) 
   - Including helpful metadata in frontmatter

2. **Content Considerations**:
   - Title and proposal identifier
   - Original proposal text
   - Voting outcome
   - Implementation status
   - Links to relevant transactions
   - Resulting changes to governance

3. **Links and References**:
   - Using relative links for internal documents
   - Using absolute links for external resources
   - Ensuring links remain accessible over time

### Treasury Documentation

When recording treasury activities, consider including:

1. **Transaction Information**:
   - Date of transaction
   - Assets involved
   - Transaction amounts
   - Counterparties
   - Description of purpose
   - Connection to authorizing proposals

2. **Documentation Options**:
   - Linking to block explorer pages for on-chain verification
   - Grouping related transactions for context
   - Organizing by network, time period, or purpose

### Repository Change Documentation

Git version history provides built-in change tracking. Some practices that might enhance its usefulness:

1. **Commit Practices**:
   - Writing descriptive commit messages
   - Referencing proposals when implementing governance decisions
   - Using consistent formatting for commit messages
   - Considering Git tags for significant milestones

## Organizational Approaches

Many different approaches can work for maintaining archives. Some considerations that might help:

### Archive Management

Potential approaches to managing archives include:

1. **Proposal Lifecycle Management**:
   - Determining when a proposal is ready for archiving
   - Deciding who is responsible for creating archive entries
   - Establishing review processes if desired

2. **Epoch Transitions**:
   - Considering how to handle transitions between governance periods
   - Determining if and how to reorganize archives during transitions
   - Planning for continuity across governance changes

3. **Repository Maintenance**:
   - Periodic reviews for consistency or broken links
   - Balancing detail with accessibility
   - Considering search and discovery needs

## Suggested Metadata

Including consistent metadata can help with organization and searchability. Some metadata fields to consider:

1. **For Proposals**:
   ```yaml
   ---
   description: Brief summary of the proposal content
   status: current status (e.g., passed, failed, implemented)
   date: proposal date
   ---
   ```

2. **Optional Fields**:
   ```yaml
   author: author name or handle
   epoch: governance period identifier
   tags: [relevant categories]
   implementation_date: when implemented (if applicable)
   ```

## Discovery and Access

Helping members find relevant information is important for transparency. Some approaches:

1. **Organization Options**:
   - Chronological organization
   - Categorization by type or impact
   - Collections of related decisions

2. **Search Considerations**:
   - Using consistent terminology
   - Including relevant keywords in descriptions
   - Creating index documents for complex areas

The archive approach should ultimately serve your organization's specific governance needs and culture. These suggestions can be adapted or extended as appropriate for your context.
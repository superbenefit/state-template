---
description: A template for DAO governance documentation
---

# 🔏 DAO State Repository Template

A template for documenting DAO governance through version-controlled, transparent workflows.

*This template is meant to serve as a starting place for developing your organization's governance documentation. You should copy this template and customize it to suit your organization's unique context.*

## What is a DAO State Repository?

A DAO State Repository serves as the canonical source of truth for governance within a Decentralized Autonomous Organization. Unlike traditional documentation that often becomes outdated or scattered across platforms, this centralized approach provides a transparent history of all governance decisions and documents. Members gain equal access to information about how the organization operates, makes decisions, and evolves over time.

The repository creates a complete governance ecosystem with transparent records of decisions, clear pathways for participation, and accountability for treasury management. By structuring governance information within a version-controlled system, DAOs can build institutional memory while maintaining flexibility for future evolution.

## Git-Based Governance

Using git as the foundation for DAO governance documentation aligns naturally with decentralized principles. This approach leverages git's inherent properties to create governance systems that mirror blockchain technology's values.

Git provides an ideal infrastructure for governance with its distributed nature allowing multiple participants to maintain complete history copies. Its transparency makes all changes visible and attributable, while immutability ensures historical records remain unaltered without detection. The branch-based collaboration model enables proposal processes that naturally align with governance workflows.

For DAOs with on-chain operations, this repository bridges smart contract actions with their human-readable context. This connection maintains alignment between technical implementations and their intended purposes, providing context that blockchain transactions alone cannot express.

## Getting Started

### Setup

The simplest way to use this template is through GitHub:

1. Click the "Use this template" button on GitHub
2. Name your repository (recommended: `governance`)
3. Replace all instances of `<daoName>` with your organization's name
4. Set appropriate access permissions for contributors

If you prefer command line setup, clone the repository and initialize it manually:

```bash
git clone https://github.com/rathermercurial/state-template.git governance
cd governance
# Configure your remote repository and push your initial commit
```

### Repository Structure

The template organizes governance documentation into three main sections:

**Agreements** contain commitments between participants including codes of conduct, community guidelines, and operating agreements. These documents establish the foundation for community interactions and decision-making.

**Policies** house procedures and standards for various activities, organized into administrative, operational, and metagovernance categories. These formalize how the organization operates day-to-day.

**Archives** maintain historical records including past proposals and approvals, providing institutional memory and accountability.

## File Disposition Guide

This template contains several types of files, each serving a different purpose during implementation. This guide will help you understand what to do with each file type when deploying for your organization.

### Files to Customize and Keep

These files form the core of your governance documentation:

- **index.md files** - Navigation pages for your members. Customize these with your organization's specific information.
- **constitution.md** - Replace the template content with your organization's foundational principles.
- **governance.md** - Adapt to reflect your documentation management processes.
- **Agreement files** - (code_of_conduct.md, community_guidelines.md, operating_agreement.md): Customize with your organization's specific agreements.
- **Policy directories** - Populate with your organization's specific policies.

### Files to Either Customize or Remove

These files may or may not be relevant to your deployed documentation:

- **README.md** - Either replace with your organization-specific content or rename to something more appropriate for your members.
- **contributing.md** - Either customize to reflect your technical contribution guidelines or remove if not needed.

### Files to Remove

These files are only for implementation guidance and should be removed from your production deployment:

- **All readme.md files** - These contain implementation guidance only and should be removed when deploying.
- **Template instructions** - Any sections marked with customization comments should be replaced with your content.

### Platform-Specific Deployment

#### GitHub Pages

For GitHub Pages deployment:
- Keep the structure as is, with index.md files serving as landing pages for each directory.

#### GitBook

For GitBook deployment:
1. Rename the root index.md to SUMMARY.md
2. Rename all other index.md files to readme.md
3. Delete the existing readme.md files first to avoid conflicts

## Customization Guide

After initial setup, begin customizing the repository to reflect your organization's specific governance model. Start by updating the essential files including README.md, operating agreements, and metagovernance policies. Remove all template instruction blocks and replace example text with your actual content.

### Content Customization

When customizing the repository structure, maintain consistent document organization with clear relationships between different documentation types. Use standard formatting for headers, sections, and examples. Connect related documents through relative paths and section anchors for easy navigation.

For effective integration with your organization's operations, link documentation to external tools and discussion forums. Document how governance decisions flow to implementation and how responsibilities transition between stakeholders.

### Implementation Strategy

A phased approach to customization works best:

Begin with initial setup focusing on basic identification and essential documents. Develop core documentation with fundamental agreements and policies. Extend the structure with additional categories and specialized documents as needed. Integrate with existing tools and workflows. Continuously refine documentation based on actual usage.

When developing your governance documentation, prioritize discoverability by making important documents easy to find. Maintain consistency in naming and organization patterns. Ensure completeness by including all necessary governance information. Clarify document purposes and relationships. Design for future adaptation as your organization evolves.

## Resources & Credits

- Based on the [All In For Sport DAO State](https://state.allinforsport.org/)
- Inspired by the [Krause House Governance State Repository](https://github.com/Krause-House/org)
- Created by [rathermercurial.eth](https://rathermercurial.eth.xyz/) as part of the [DAO Primitives Project](https://superbenefit.org/dao-primitive-project) at [SuperBenefit](https://superbenefit.org/)

## License

This template is unlicensed and free to use, edit, and distribute as needed.
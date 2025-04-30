---
description: The official state repository template for DAO governance.
---

# 🔏 DAO State Repository Template

A simple template for documenting, maintaining, and evolving DAO governance through git-based workflows.

## What is a DAO State Repository?

A DAO State Repository serves as the canonical source of truth for all governance activities, agreements, and policies within a Decentralized Autonomous Organization (DAO). Unlike traditional documentation that can become outdated or fragmented across multiple platforms, this repository provides:

- **A Single Source of Truth**: Centralized, version-controlled governance documentation
- **Transparent History**: Complete audit trail of all governance changes
- **Accessible Governance**: Clear pathways for members to understand and participate in governance
- **Proposal Tracking**: Standardized processes for submitting, discussing, and implementing governance changes
- **Treasury Accountability**: Transparent records of financial decisions and transactions

This template is designed to help DAOs establish robust governance documentation practices, ensuring that all members have equal access to information about how the organization operates, makes decisions, and evolves over time.

## Git-Based Governance: Concept and Value

Using git as the foundation for DAO governance documentation aligns naturally with the decentralized ethos of web3 organizations. At its core, this approach leverages the distributed, transparent, and immutable properties of git repositories to create governance systems that mirror the values of blockchain technology.

### Why Git for Governance?

Git provides several fundamental properties that make it ideal for governance:

- **Distributed nature**: Like blockchains, git allows multiple parties to maintain copies of the entire history
- **Transparency**: All changes are visible, attributable, and timestamped
- **Immutability**: Historical records cannot be altered without detection
- **Branch-based exploration**: Enables experimentation and parallel governance proposals
- **Merge processes**: Provides clear mechanisms for integrating changes after approval

### Bridging Onchain and Offchain Governance

For onchain organizations, git-based governance documentation creates a natural bridge between onchain actions (voting, treasury management, permission updates) and the human-readable context and rationale behind those actions. This connection helps maintain alignment between:

- Smart contract implementations and their intended purposes
- Technical parameters and their governance justifications
- Treasury transactions and their authorized purposes

The repository becomes not just documentation, but a living system that evolves alongside the onchain components of the organization, providing context and continuity that blockchain transactions alone cannot express.

---

## Getting Started with the DAO State Repository Template

This guide will help you set up and deploy the DAO State Repository Template for your organization. It focuses on initial setup and configuration steps to get your governance documentation system up and running.

### Understanding the Repository Purpose

The DAO State Repository Template provides a structured framework for documenting and maintaining governance information using version control. It offers:

- A consistent organization for governance documentation
- Version-controlled history of changes
- Templates for common governance document types
- A foundation for transparent governance processes

### Repository Structure

The template is organized into three main sections:

1. **Agreements** - Commitments between participants, including codes of conduct, community guidelines, and operating agreements
2. **Policies** - Procedures and standards for various activities, organized into administrative, operational, and metagovernance categories
3. **Archives** - Historical records including past proposals and approvals

This structure helps keep documentation organized while making it accessible to participants.

### Initial Setup

1. **Create a new GitHub repository**
   - Go to GitHub and create a new repository
   - Name it simply `governance` 
   - Choose public or private visibility based on your transparency needs

2. **Download the template**
   - Clone or download the [DAO State Repository Template](https://github.com/rathermercurial/state-template)
   ```bash
   git clone https://github.com/rathermercurial/state-template.git governance
   ```
   - Or download and extract the ZIP file if you prefer

3. **Initialize your repository**
   - If you downloaded the ZIP, initialize a new git repository
   ```bash
   cd governance
   git init
   git add .
   git commit -m "Initial commit from template"
   ```
   - Connect to your remote repository
   ```bash
   git remote add origin https://github.com/your-organization/governance.git
   git push -u origin main
   ```

#### Basic Configuration

1. **Update repository identification**
   - Replace all instances of `<daoName>` with your organization's name
   - Update the repository description in GitHub settings
   - Update the README.md with your organization's information

2. **Configure repository settings**
   - Enable appropriate branch protection if desired
   - Set up access permissions for contributors
   - Consider enabling Discussions or other GitHub features you'll use

### First Steps After Setup

Once your repository is set up, take these initial steps:

1. **Review the template structure**
   - Explore each directory to understand its purpose
   - Read the template files to understand their intended use

2. **Update essential files**
   - README.md - Update with your organization's information
   - index.md - Customize the navigation structure
   - Agreements/operating_agreement.md - Add your fundamental operating procedures
   - Policies/metagovernance/index.md - Define how your documentation will be managed

3. **Remove template instructions**
   - Find and remove template instruction blocks (usually in HTML comments)
   - Replace example text with your actual content or placeholders

4. **Make your first commit**
   - Once you've made initial customizations, commit them
   ```bash
   git add .
   git commit -m "Initial customization"
   git push
   ```

5. **Share with your team**
   - Provide access to relevant team members
   - Explain how to navigate the documentation

---

# Customizing Your DAO State Repository

This guide provides instructions for adapting the DAO State Repository Template to fit your organization's specific governance context. It focuses on how to modify the template structure and content while maintaining a coherent documentation system.

## Understanding the Template Architecture

The template follows a modular architecture with three main sections:

1. **Agreements**: Commitments among participants (code of conduct, operating agreements, etc.)
2. **Policies**: Procedures and standards for organizational activities
3. **Archives**: Historical records of decisions and changes

This architecture is designed to separate different types of governance documentation while maintaining clear relationships between them. Most customizations should work within this structure rather than fundamentally altering it.

## Customization Approaches

### Basic Content Customization

Start by replacing template placeholder content with your organization's information:

1. **Update organization information**
   - Replace all instances of `<daoName>` with your organization's name
   - Update descriptions to reflect your organization's purpose
   - Customize examples to align with your context

2. **Adapt agreement documents**
   - Modify `operating_agreement.md` to reflect your operating procedures
   - Customize `code_of_conduct.md` to align with your community values
   - Update `community_guidelines.md` to reflect your participation norms

3. **Customize policy templates**
   - Adapt proposal processes in `/policies/metagovernance/proposals/`
   - Modify voting thresholds and processes to match your governance model
   - Customize operational policies to reflect your actual workflows

### Structural Customization

You can modify the directory structure while maintaining the template's organization principles:

1. **Adding directories**
   - Create subdirectories to organize related documents
   - Include an `index.md` in each directory explaining its purpose
   - Update parent directory index files to include links to new sections

2. **Creating new document types**
   - Design templates for organization-specific document types
   - Place templates in appropriate directories
   - Document their purpose and usage

3. **Extending existing sections**
   - Add specialized subcategories to main sections
   - Create index files for navigation
   - Maintain consistent naming and organization patterns

#### Document Structure

Maintain consistent document structure:

1. **Headers**
   - Use appropriate header levels (# for title, ## for sections)
   - Follow a logical hierarchy

2. **Sections**
   - Include standard sections appropriate to the document type
   - Use consistent section ordering

3. **Examples**
   - Provide concrete examples where applicable
   - Use standard Markdown code blocks for technical content
   ```
   Example content here
   ```

### Document Cross-Referencing

Maintain document coherence with proper linking:

1. **Relative links**
   - Use relative paths for internal document links
   ```markdown
   [Operating Agreement](../agreements/operating_agreement.md)
   ```

2. **Section anchors**
   - Link to specific sections within documents
   ```markdown
   [Treasury Policies](../policies/operations/treasury.md#approval-thresholds)
   ```

3. **Navigation consistency**
   - Update index files when adding or moving documents
   - Ensure all documents are accessible through navigation

## Integration with External Tools

### Platform-Independent Integration

You can link your documentation with external systems while maintaining compatibility:

1. **Link to external systems**
   - Add references to related tools and resources
   - Document how governance connects to implementation

2. **Communication references**
   - Connect documentation to discussion forums
   - Reference communication channels for specific governance activities

3. **Workflow documentation**
   - Document how decisions flow to action
   - Specify responsibility handoffs

## Customization Considerations

When customizing your repository, consider:

1. **Discoverability**: Ensure important documents are easy to find
2. **Consistency**: Maintain consistent naming and organization patterns
3. **Completeness**: Include all necessary governance information
4. **Clarity**: Make document purpose and relationships clear
5. **Adaptability**: Design for future growth and evolution

## Implementation Strategy

A phased approach to customization is recommended:

1. **Initial setup**: Basic organization identification and essential documents
2. **Core documentation**: Fundamental agreements and policies
3. **Extended structure**: Additional categories and specialized documents
4. **Integration**: Connections with tools and workflows
5. **Refinement**: Ongoing improvements based on usage

By thoughtfully customizing the DAO State Repository Template, you'll create governance documentation that reflects your organization's unique context while maintaining a coherent structure that supports transparent and effective governance.

---

## Resources & Credits

- This template is based on the [All In For Sport DAO State](https://state.allinforsport.org/)
- Inspired by the [Krause House Governance State Repository](https://github.com/Krause-House/org)
- Created by [rathermercurial.eth](https://rathermercurial.eth.xyz/) as part of the [DAO Primitives Project](https://superbenefit.org/dao-primitive-project) at [SuperBenefit](https://superbenefit.org/)

---

## License

This template is unlicensed and free to use, edit, and distribute as needed.
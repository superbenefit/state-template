---
description: >-
  Template for creating standardized proposal archive pages within the <daoName>
  DAO State Repository
---

# Proposal Archive Page Template

This template can be used to quickly create archive pages for proposals submitted to daoName governance.

## Required Fields

Copy the following fields from the proposal content and/or voting platform data to populate the archive page.

| Element          |       Placeholder |                     Description                    |
| ---------------- | ----------------: | :------------------------------------------------: |
| Title            |   `proposalTitle` | The title of the proposal (including # + Standard) |
| Description      |     `description` |       Sentence-length summary of the proposal      |
| Author(s)        |  `proposalAuthor` |            The author(s) of the document           |
| Discussion       |   `discussionUrl` |      Link to the discussion forum or workspace     |
| Voting Page      |         `voteUrl` |           Link to the voting platform URL          |
| Publish Date     |         `pubDate` |     Date of proposal submission to voting space    |
| Proposal Content | `proposalContent` |            The body text of the document           |
| Votes            |       `voteTally` |     The number of votes per result (% or count)    |
| Vote Result      |      `voteResult` |      The result of the vote (Passed or Failed)     |
| State Changes    |     `stateChange` |    DAO State changes resulting from the proposal   |

### Field Definitions

#### Title (`proposalTitle`)

The title of your document as a level-1 heading.

#### Description (`proposalDescription)`

A single-sentence summary of your proposal, often displayed in the header as a subtitle.

#### Author (`proposalAuthor)`

The author or co-authors of the proposal.

#### Discussion Page (`discussionUrl`)

A link to the proposal's discussion forum thread or RFC post. \
Display as a pretty link (`[🗣️`` `**`Discussion`**`](discussionUrl)`)

#### Voting Page (`voteUrl`)

A link to the proposal's voting page on Snapshot or similar (or link to Discord post, etc. if voting page isn't available).
Display as a pretty link (`[⚡️`` `**`Snapshot`**`](voteUrl)`)

#### Submission Date (`pubDate)`

The date on which the proposal was submitted to the voting space.

#### Vote Result (`voteResult`)

The result of the vote (Passed, Failed, Etc.)\
You may want to add an emoji to help indicate the result at a glance.

#### Proposal Content (`proposalContent`)

The full text content of the original proposal. Be sure to omit any fields already included in the archive page to avoid redundancy.

#### Votes (`voteTally`)

The number or percent or votes for each option. Be sure to boldly label each option (e.g. **Yes:** 100%), separate with commas and omit options with "0" value for legibility.

#### State Changes (`stateChange`)

Describe the governance state changes made as a result of the proposal.

### Proposal Archive Format

```md
## `proposalTitle`

`description`

Proposed by: `proposalAuthor`

🗣️ Discussion
🌡️⚡⛓️ Snapshot

**Submitted:** `pubDate`\
**Result:** `voteResult` ✅ ❌

`proposalContent`

### 🗳️ Voting Result

**Votes:** `voteTally`\
**Result:** `voteResult`

### 🏗️ Governance State Changes

`stateChange`
```

#### Proposal Archive Templates

```md
# proposalTitle

description

Proposed by: proposalAuthor

[🗣️ Discussion](discussionUrl)  
[🌡️⚡⛓️ Snapshot](voteURL)

**Submitted:** pubDate  
**Result:** voteResult ✅ ❌

proposalContent

## 🗳️ Voting Result

**Votes:**  voteTally  
**Result:**  voteResult

## 🏗️ Governance State Changes

```

#### How to Use Archive Templates

1. Copy the relevant template above.
2. Paste the template into your preferred text editor (i.e. VS Code or Notepad).
3. Replace the element placeholders (such as `proposalTitle`) with your written content.
4. Copy and paste the completed document into your destination (Snapshot, Station, Discord, Notion, etc).

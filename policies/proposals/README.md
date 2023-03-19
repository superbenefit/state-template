---
description: Standards for proposals submitted to <daoName> governance.
---

# 📃 Proposal Standards

{% hint style="warning" %}
This is an example proposal standard. You should edit or replace this standard to reflect your DAO's proposal requirements.
{% endhint %}

<mark style="color:yellow;">Briefly describe your DAO's use of proposal standards here.</mark>

The purpose of this proposal standard is to ensure that voting members of the DAO have sufficient information to accurately assess incoming governance proposals, participate in constructive debate and cast well-informed votes.

* [Proposal Requirements](./#proposal-requirements)
* [Proposal Formatting](./#proposal-formatting)
* [Proposal Templates](./#proposal-templates)

### Types of Proposals <a href="#types" id="types"></a>

Proposals are requests for community consensus and can result in an update to the DAO State document. Here are some things that proposals can do:

* [Change the way the DAO governs itself](metagovernance.md)

More proposal types can be added by proposing a new standard via a [Governance State Update](metagovernance.md).

## Proposal Requirements <a href="#requirements" id="requirements"></a>

All proposals submitted for vote by the DAO must meet the following requirements:

*   #### Proposal Number (`proposalNumber`)

    The sequential number of your proposal within the voting space.
*   #### Title (`proposalTitle`) <a href="#title" id="title"></a>

    The title of your proposal as a level-1 heading. Your title should be descriptive and concise (ie. "Set up a Partnerships Team").
*   #### Description (`proposalDescription`)

    A single sentence summarizing your proposal and its purpose.
*   #### Author (`proposalAuthor`)

    The author or co-authors of your proposal.&#x20;
*   #### Replaces/Amends (`replacesOrAmends)`

    Description (with pretty links) of previous proposals amended or replaced by the current proposal. This can be removed if not relevant to your proposal.
*   #### Summary (`proposalSummary`)

    A short paragraph summarizing your proposal and its intended outcome.
*   #### Body Text (`proposalBody`)

    The full text content of your proposal. Body text must comply with the requirements for your particular [proposal type](./#types-of-proposals).
*   #### Proposed Outcome (`proposalOutcome`)

    The intended outcome of voting for each option in the poll, and description of next steps as needed.

## Proposal Formatting <a href="#format" id="format"></a>

Proposals should be formatted in an organized manner in order to provide easy reading and comprehension for your fellow DAO members. It is recommended that you use the following format to present your proposal to DAO governance:

<details>

<summary>Proposal Model</summary>

## proposalNumber: proposalTitle

proposalDescription

Proposed by: proposalAuthor

_replacesOrAmends_

### Summary

proposalSummary

proposalBody

### Proposed Outcome

proposalOutcome

</details>

<details>

<summary>Example Proposal</summary>

<mark style="color:yellow;">TBD - Initial gov state proposal to be used as example</mark>

</details>

### Proposal Templates <a href="#templates" id="templates"></a>

Preformatted templates are available for DAO members who wish to author their own proposals.&#x20;

{% tabs %}
{% tab title="Markdown" %}
<pre class="language-markdown" data-title="Generic Markdown" data-line-numbers><code class="lang-markdown"># proposalNumber: proposalTitle

proposalDescription

Proposed by: proposalAuthor

<strong>*replacesOrAmends*
</strong>
## Summary

proposalSummary

proposalBody

## Proposed Outcome

proposalOutcome
</code></pre>
{% endtab %}

{% tab title="GitHub" %}
{% code title="GitHub-Flavored Markdown" lineNumbers="true" %}
```markdown
---
description: >-
  proposalDescription
---
# proposalNumber: proposalTitle

Proposed by: proposalAuthor

{% raw %}
{% hint %}*replacesOrAmends*{% endhint %}
{% endraw %}

## Summary

proposalSummary

proposalBody

##Proposed Outcome

proposalOutcome
```
{% endcode %}
{% endtab %}

{% tab title="Telegram/Discord" %}
<pre class="language-markdown" data-title="Discord-Flavored Markdown" data-line-numbers><code class="lang-markdown">__**proposalNumber: proposalTitle**__
proposalDescription
*Proposed by: proposalAuthor*

<strong>__replacesOrAmends__
</strong>
**Summary**
proposalSummary

proposalBody

**Proposed Outcome**
proposalOutcome
</code></pre>
{% endtab %}
{% endtabs %}

#### How to Use Proposal Templates

You can use these templates to create your own proposals using this format by following the instructions below.

1. Prepare your proposal content using the [requirements](./#proposal-requirements) listed above.
2. Copy the relevant proposal template and paste the into your preferred text editor (VS Code, Notion, Snapshot, Station, etc).
3. Replace the element placeholders (such as `proposalTitle`) with your proposal content.
4. Copy and paste the completed proposal into your destination (Snapshot, Station, Discord, Notion, etc).

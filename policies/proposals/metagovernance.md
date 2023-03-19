---
description: Standards for proposals to update the <daoName> state repository
---

# 🏗 State Update Proposals

{% hint style="warning" %}
The State Update Proposal Standard is used to create proposals to update this DAO state repository. It is a simplified version of the [general proposal standard](./) with some additional [requirements](metagovernance.md#requirements).

To use this proposal standard, edit this document to customize the standard for your DAO's governance use case. If you won't be using this proposal type, simply remove this page.
{% endhint %}

This is a specialized standard governing the content of proposals submitted to <mark style="color:yellow;">daoName</mark> governance which request changes or additions to the DAO's policies, permissions roster or governance standards.

### Proposal Requirements <a href="#requirements" id="requirements"></a>

In addition to the [standard proposal requirements](./), DAO state update proposals must contain the following elements:

*   #### Pull Request or Change Request Link (`changeRequestUrl`)

    A link to the GitHub Pull Request or GitBook Change Request containing the proposed changes. This is used by the governance team to commit your changes if the proposal passes.
* **Amendment Text (`amendmentText`)**\
  The full text of the proposed change, including any text replaced or removed.&#x20;
* **Author's Intention (`amendmentIntention`)**\
  Describe your intention for making the change request, including the outcome you hope to achieve. This helps to others to better interpret the DAO state language.\


## Proposal Formatting <a href="#format" id="format"></a>

Proposals should be formatted in an organized manner in order to provide easy reading and comprehension for your fellow DAO members. It is recommended that you use the following format to present your proposal to DAO governance:

<details>

<summary>Proposal Model</summary>

## proposalNumber: proposalTitle <a href="#proposalnumber-proposaltitle" id="proposalnumber-proposaltitle"></a>

proposalDescription

Proposed by: proposalAuthor

[**Change Request Link**](https://markdownlivepreview.com/changeRequestUrl)

### Summary <a href="#summary" id="summary"></a>

proposalSummary

### Proposed Changes <a href="#proposed-changes" id="proposed-changes"></a>

amendmentText

### Intention <a href="#intention" id="intention"></a>

amendmentIntention

</details>

<details>

<summary>Example Proposal</summary>

<mark style="color:yellow;">TBD - Initial gov state proposal to be used as example</mark>

</details>

### Proposal Templates <a href="#templates" id="templates"></a>

{% tabs %}
{% tab title="Markdown" %}
{% code title="Generic Markdown" lineNumbers="true" %}
```markdown
# proposalNumber: proposalTitle

proposalDescription

Proposed by: proposalAuthor

**[Change Request Link](changeRequestUrl)**

## Summary

proposalSummary

## Proposed Changes

amendmentText

## Intention

amendmentIntention
```
{% endcode %}
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

**[Change Request Link](changeRequestUrl)**

## Summary

proposalSummary

## Proposed Changes

amendmentText

## Intention

amendmentIntention
```
{% endcode %}
{% endtab %}
{% endtabs %}

#### How to Use Proposal Templates

You can use these templates to create your own proposals using this format by following the instructions below.

1. Prepare your proposal content using the [requirements](metagovernance.md#proposal-requirements) listed above.
2. Copy the relevant proposal template and paste the into your preferred text editor (VS Code, Notion, Snapshot, Station, etc).
3. Replace the element placeholders (such as `proposalTitle`) with your proposal content.
4. Copy and paste the completed proposal into your destination (Snapshot, Station, Discord, Notion, etc).
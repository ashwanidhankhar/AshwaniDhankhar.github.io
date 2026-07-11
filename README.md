# Monthly Data Collection Tool

A simple internal web tool for collecting monthly team data, tracking submissions, preparing reminder lists, and shaping records for a Power BI dashboard.

## Live tool

Open the tool here:

**[Launch Monthly Data Collection Tool](https://ashwanidhankhar.github.io/Data-Collection-GPT-Tool/)**

## Features

- Configurable reporting month and monthly submission deadline
- Reminder list for outstanding owners
- Team-level submission tracker
- Actual vs. target data entry
- Power BI-ready JSON data contract
- Recommended flow: collection → database → Power Automate reminders → Power BI dashboard

## Power BI data flow

```mermaid
flowchart LR
  A[Users submit monthly data] --> B[(Dataverse or SharePoint List)]
  B --> C[Power Automate]
  C --> D[Reminder emails]
  B --> E[Power BI Dataflow]
  E --> F[Power BI Dashboard]

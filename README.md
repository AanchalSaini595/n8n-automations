# n8n Automation Workflows

A collection of automation workflows built with n8n.

## Workflow 1: Daily Quote Automation

### What it does
Every day at 9am, this workflow automatically:
1. Fetches a random motivational quote from the ZenQuotes API
2. Processes and formats the quote with author and date
3. Ready to send via email or save to a file

### Tech Stack
- n8n — workflow automation
- ZenQuotes API — free quote REST API
- JavaScript — data processing in Code node

### Nodes
| Node | Purpose |

| Schedule Trigger | Runs every day at 9am |
| HTTP Request | Fetches random quote from API |
| Code | Formats quote, author and date |

### Screenshot
![Daily Quote Workflow]

 More workflows coming soon
- Job Application Tracker
- GitHub Activity Notifier

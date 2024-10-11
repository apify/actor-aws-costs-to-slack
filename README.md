# AWS Costs to Slack

This tool integrates with AWS to monitor service usage costs and posts a summary of these costs to a Slack channel. The summary includes costs for various AWS services along with a chart that provides a visual breakdown of the costs over time.

## Features

- Posts a detailed breakdown of AWS service costs to a Slack channel.
- Provides cost summaries for key AWS services including EC2, DynamoDB, S3, RDS, and more.
- Supports graphical representation of costs with a downloadable chart link.
- Automated daily/weekly reporting to track AWS costs over time.

## How It Works

1. **Cost Collection**: The tool uses AWS APIs to gather the cost data for various AWS services.
2. **Slack Integration**: The tool formats the cost data and posts it to a Slack channel using the provided Slack bot token and channel name.
3. **Chart Generation**: The tool generates a visual chart for cost breakdown and includes a link to the chart in the Slack message.

## Requirements

- **AWS Access Key & Secret**: Needed to query AWS cost data.
- **Slack Bot Token**: A token to allow the tool to post messages to a Slack workspace.
- **Slack Channel**: The Slack channel where cost reports should be posted.

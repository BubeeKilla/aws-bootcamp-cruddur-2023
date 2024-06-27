# Week 0 — Billing and Architecture

# AWS CLI 
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

# Gitpod Browser VSC credentials config command - (in terminal) aws configure, or configure env with export to bash

![gitpod yml](https://github.com/BubeeKilla/aws-bootcamp-cruddur-2023/assets/76734789/87ef64e9-f623-4a8d-b7e8-50ec63fcdb5d)

# Budget commands 
https://docs.aws.amazon.com/cli/latest/reference/budgets/#available-commands

# How can I monitor daily EstimatedCharges and activate a CloudWatch alarm based on my usage threshold? 
https://repost.aws/knowledge-center/cloudwatch-estimatedcharges-alarm

# Removing sensitive data from a repository 
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository 
https://rtyley.github.io/bfg-repo-cleaner/


tasks:
  - name: aws-cli
    env:
      AWS_CLI_AUTO_PROMPT: on-partial
    init: |
      cd /workspace
      curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
      unzip awscliv2.zip
      sudo ./aws/install
      cd $THEIA_WORKSPACE_ROOT

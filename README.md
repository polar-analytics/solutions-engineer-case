# Case Study – Customer ID Unification

## Background

We've just partnered with a major skincare brand generating over $200M in GMV. They've chosen Polar as their data platform to support their analytics and growth needs across all channels.

Our champions at the brand are the Retention team, who came to us with a specific challenge.

## The Challenge

Shopify assigns a unique customer ID for every customer who transacts either online or in retail. This ID is derived from a hash of the customer's email address.

Here's the issue: if a customer uses multiple email addresses, Shopify will treat them as completely different customers. For example:

- A shopper makes their first three purchases using a Gmail account.
- Later, they buy again with their Outlook account.
- Shopify creates two separate IDs, splitting their history across two "customers."

This can also happen due to:

- Typos in email addresses
- Switching between personal and work emails
- Other inconsistencies in identifiers

The retention team suspects that their true retention metrics are stronger than what Shopify reports, because repeat customers are being counted as "new."

## Your Task

Build a solution that creates a reliable Customer ID spanning all transactions. Think of this as project we can ship tomorrow—not just a query. Keep it practical, production-minded, and ready to roll out.

## Use of AI

We expect you to make extensive use of AI throughout this exercise. How you integrate it is up to you, but you’re responsible for the quality and accuracy of the final solution.

## Data

You are provided with an S3 bucket containing a table of all transactions across every distribution channel. Data is streamed into this bucket every 15 minutes.
The dataset is available at: https://solutions-engineer-case.s3.amazonaws.com/

## Support

If you would like additional data points or have questions, email me at alexis@polaranalytics.co
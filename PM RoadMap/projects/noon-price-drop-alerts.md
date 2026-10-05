# Worked Example — Noon Price Drop Alerts

This example is adapted from the publicly readable Canva design **“FEATURE PROPOSAL — Noon App — Price Drop Alerts”** by Rahma Hashish, Product Management Trainee, Starks MU.

## Problem

A user wants a product but the current price is too high. They may miss a later discount because they cannot check the product every day.

## User story

> As a Noon user, I want to enable “Notify me when price drops” on a product so that I receive an alert when the price decreases or a discount becomes available.

## Core behavior captured in the source

1. The user selects a **Notify me when price drops** action on the product page.
2. The user receives a notification when the price decreases or a sale becomes available.
3. The product page shows the last notified price so the user can understand the difference.

## PM practice prompts

- What is the target segment and how often does this problem occur?
- What counts as a meaningful price drop?
- Which channels and notification preferences should be supported?
- What is the MVP: one product, one alert, one channel?
- What guardrails prevent notification fatigue?
- Which metrics matter: alert opt-in, notification open rate, conversion, unsubscribe rate, and incremental purchase rate?
- What edge cases require acceptance criteria: out-of-stock, price increases, expired discounts, duplicate alerts, and canceled orders?

## Acceptance-criteria template

- [ ] A user can enable and disable an alert from the product page.
- [ ] The system records the price at the moment of opt-in.
- [ ] A notification is sent only when the defined threshold is met.
- [ ] The user can see the previous notified price and current price.
- [ ] The user can manage notification preferences.
- [ ] Duplicate or misleading alerts are prevented.

## Source

[Original Canva design](https://canva.link/7c6mxfzk6cot1tj)

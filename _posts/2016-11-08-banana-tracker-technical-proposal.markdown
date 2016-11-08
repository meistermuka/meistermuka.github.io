---
layout: post
title:  "Technical Proposal: Banana Tracker"
date:   2016-11-08 15:53:00 -0500
categories: update
---
# Banana Tracker
## Technical Proposal

### Introduction
Have the ability to track the ever changing price of bananas in general stores and fruit stores in and around my city.

### Cost of Deferring
Being in the dark when it comes to the price of bananas at any given time of the day. Not knowing where to find the best priced bananas in my neighbourhood, city or even region.

### Proposal
A simple location on the web to keep notes on the prices of bananas in different stores. It would be comprised of a form allowing you to enter data on the banana(s) such as net price by weight. There would also be information about the store that offers such merchandise with information about its location, store hours, etc...
The following is an initial draft of the tables for such an endavour:

item table:

| name        | type    |
|-------------|---------|
| id          | VARCHAR(32) |
| location_id | INT     |

item_price table:

| name    | type    |
|---------|---------|
| pp_kg   | VARCHAR(10) |
| pp_lbs  | VARCHAR(10) |
| item_id | VARCHAR(32) |

location table:

| name        | type         |
|-------------|--------------|
| id          | INT          |
| address     | VARCHAR(MAX) |
| postal_code | VARCHAR(50)  |
| hours       | VARCHAR(255) |
| coordinates | VARCHAR(MAX) |

### Impact
The world will keep on spinning. BUT, the fact that I don't know the price of bananas will be annoying.

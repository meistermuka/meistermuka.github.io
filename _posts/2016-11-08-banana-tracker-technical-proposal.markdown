---
layout: post
title:  "Technical Proposal: Banana Tracker"
date:   2016-11-08 15:53:00
categories: update
tags: 
- technical proposal
- new project
---
Banana Tracker
==============

Technical Proposal
------------------

### Introduction
Have the ability to track the ever changing price of bananas in general stores and fruit stores in and around my city.

### Cost of Deferring
Being in the dark when it comes to the price of bananas at any given time of the day. Not knowing where to find the best priced bananas in my neighbourhood, city or even region.

### Proposal
A simple location on the web to keep notes on the prices of bananas in different stores. It would be comprised of a form allowing you to enter data on the banana(s) such as net price by weight. There would also be information about the store that offers such merchandise with information about its location, store hours, etc...
The following is an initial draft of the tables for such an endavour:

### item table
<table>
  <tr>
  <th>name</th>
  <th>type</th>
  </tr>
  <tr>
  <td>id</td>
  <td>VARCHAR(32)</td>
  </tr>
  <tr>
  <td>location_id</td>
  <td>INT</td>
  </tr>
</table>

### item_price table
<table>
  <tr>
  <th>name</th>
  <th>type</th>
  </tr>
  <tr>
  <td>pp_kg</td>
  <td>VARCHAR(10)</td>
  </tr>
  <tr>
  <td>pp_lbs</td>
  <td>VARCHAR(10)</td>
  </tr>
  <tr>
  <td>item_id</td>
  <td>VARCHAR(32)</td>
  </tr>
</table>

### location table
<table>
  <tr>
  <th>name</th>
  <th>type</th>
  </tr>
  <tr>
  <td>id</td>
  <td>INT</td>
  </tr>
  <tr>
  <td>address</td>
  <td>VARCHAR(MAX)</td>
  </tr>
  <tr>
  <td>postal_code</td>
  <td>VARCHAR(50)</td>
  </tr>
  <tr>
  <td>hours</td>
  <td>VARCHAR(255)</td>
  </tr>
  <tr>
  <td>coordinates</td>
  <td>VARCHAR(MAX)</td>
  </tr>
</table>


### Impact
The world will keep on spinning. BUT, the fact that I don't know the price of bananas will be annoying.

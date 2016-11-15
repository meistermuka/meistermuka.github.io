---
layout: post
title:  "Database: Banana Tracker"
date:   2016-11-15 15:12
categories: update
tags: 
- database
- new project
---

Banana Tracker
==============

The following is what I believe will be relevant data stored in the database:

**Items**
* item_id: a unique identifier for the banana
* item_location_id: a unique identifier for the location of the banana (the store)
* item_category_id: a unique identifier used to include the item in multiple sub groups

**Prices**
* price_id: a unique identifier for a price
* price: price per kg in CAD
* item_id: unique identifier for associated item
* timestamp: when the price was inserted

**Locations**
* location_id: a unique identifier for a location
* address: street number, name
* city: the name of the city
* country: the name of the country
* postal_code: postal code or zip code
* coordinate_lat: latitude coordinate value
* coordinate_long: longitude coordinate value

**Categories**
* category_id: a unique identifier for a category
* is_bio: flag identifying the item as being bio
* is_mini: flag identifying item as being mini banana
* is_plantain: flag identifying item as being plantain

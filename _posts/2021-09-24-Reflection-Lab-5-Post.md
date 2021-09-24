---
layout: post
title:  "Reflection on Lab 5"
date:   2021-09-24 15:28:35 -0500
categories: Lab Reflections
author: Thomas Sebring
---

# Assumptions
I assumed that the Schema would be a lot harder to make than the entity relationship diagram as it just looked more intimidating, but that wasn't necessarily the case. The Schema diagram became a lot easier to make after I finished my entity relationship diagram because I could use those relationships to easily make the keys and attributes of entities in the Schema. In the end the one that took more time was the entity relationship diagram, because I assumed turning text into relationships would be easy; Instead of easy it was tedious. The entity relationships look cool though so work payed off.

# ER Diagram
![Grocery Store Entity Relationship Diagram](/blog/assets/images/CSCI340Lab5_er.png)

I assume there might be some complications with the make relationship that I added between customer and order, but I'm not sure whether or not it is a necessary relationship. The customer has to have an account in order to make an order but at the same time the account doesn't make the order, so I'm not sure how to represent that. Other than that, I am satisfied with how my diagram looks.

# Schema
![Grocery Store Schema](/blog/assets/images/CSCI340Lab5_schema.png)

I assume there might be complications between order and contains because there is no value inside of order that ties it to the items it contains, however contains has the order_id so I hope that is suitable. I searched online about it, and the answer I was looking for said that it would be redundant to have both contains ids and order ids in each table so I left it out. Other than that I like how my schema is set up to tackle the problem.

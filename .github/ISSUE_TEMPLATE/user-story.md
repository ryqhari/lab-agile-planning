---
name: User Story
about: This template is used for creating use stories.
title: ''
labels: ''
assignees: ''

---

As a Marketing Manager
I need  customer names, their email addresses and contact numbers
So that I can inform them on promotions and new items that arrive  
   
Details and Assumptions
Customers prefer promotional ads and new items alert via contact numbers
We keep customers names, email addresses and contact numbers
Customers have subscribed to promotional alerts and new items arrivals

 ### Acceptance Criteria
We have 100 customers in our database
And 90 have opted-in to receive promotional alerts and new items arrivals
When I request the email addresses and contacts list of customers
Then I should have 90 contacts list of customers

 ```gherkin
Given that we have 100 customers in all 16 regions in Ghana in our database
When we request for all data of customers
Then we have 100 customers with their email addresses and contact numbers
 ```

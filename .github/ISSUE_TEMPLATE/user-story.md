---
name: User Story
about: Create a user story
title: ''
labels: ''
assignees: ''
---

As a user  
I need to manage products in the catalog  
So that I can add, update, view, and delete products easily  

### Acceptance Criteria:

```gherkin
Given a user wants to create a product
When valid product details are entered
Then the product should be created successfully

Given a user wants to retrieve a product
When a valid product ID is provided
Then the product details should be displayed

Given a user wants to update a product
When updated product details are submitted
Then the product should be updated successfully

Given a user wants to delete a product
When a valid product ID is selected
Then the product should be deleted successfully

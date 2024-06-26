# Frontend Mentor - Product feedback app solution

This is a solution to the [Product feedback app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-feedback-app-wbvUYqjR6). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Expected behaviour](#expected-behaviour)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)

## Overview

### The challenge

Users should be able to:

- (DONE) View the optimal layout for the app depending on their device's screen size
- (DONE) See hover states for all interactive elements on the page
- (DONE) Create, read, update, and delete product feedback requests
- (DONE) Receive form validations when trying to create/edit feedback requests
- (DONE) Sort suggestions by most/least upvotes and most/least comments
- (DONE) Filter suggestions by category
- (DONE) Add comments and replies to a product feedback request
- (DONE) Upvote product feedback requests
- (DONE) Keep track of any changes, even after refreshing the browser (`localStorage` could be used for this if you're not building out a full-stack app)

### Expected Behaviour

- (DONE) Suggestions page

  - Only product feedback requests with a status of `suggestion` should be shown on the Suggestions page.

- (DONE) Roadmap

  - Feedback requests with a status of `planned`, `in-progress`, or `live` should show up on the roadmap, and should be placed in the correct column based on their status.
  - Columns should be ordered by upvote totals.

- (DONE) Creating a product request

  - When creating a new piece of feedback, an ID needs to be assigned which increments the current highest product request ID by 1.
  - The default status for a new piece of feedback is `suggestion`. This places it on the Suggestions page.

- (DONE) Editing feedback

  - If a piece of feedback has its status updated to `planned`/`in-progress`/`live` it moves through to the roadmap and should show up in the correct column based on its new status.

- (DONE) Add comments/replies
  - Use the data from the `currentUser` object in the `data.json` file to populate the user data for any new comments or replies.
  - Any comment/reply can have a maximum of 250 characters.

### Screenshot

![](./screenshots/desktop-suggestions.png)
![](./screenshots/desktop-roadmap.png)
![](./screenshots/desktop-feedback-detail.png)
![](./screenshots/desktop-edit-feedback.png)

![](./screenshots/tablet-suggestions.png)
![](./screenshots/tablet-roadmap.png)
![](./screenshots/tablet-feedback-detail.png)
![](./screenshots/tablet-edit-feedback.png)

![](./screenshots/mobile-suggestions.png)
![](./screenshots/mobile-roadmap.png)
![](./screenshots/mobile-feedback-detail.png)
![](./screenshots/mobile-edit-feedback.png)
![](./screenshots/mobile-edit-feedback-active.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties/vars
- Desktop-first workflow-
- React
- React Router
- Accessibility in mind

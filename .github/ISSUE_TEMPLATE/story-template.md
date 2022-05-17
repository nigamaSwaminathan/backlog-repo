---
name: Story template
about: Create a user story
title: "[STORY]"
labels: story
assignees: ''

---

### Summary

A user story should typically have a summary structured this way:

1. **As a** [user concerned by the story]
1. **I want** [goal of the story]
1. **so that** [reason for the story]

The “so that” part is optional if more details are provided in the description.

This can then become “As a user managing my properties, I want notifications when adding or removing images.”

You can read about some reasons for this structure in this [nicely put article][1].

### Description

We’re using the following template to create user stories. 

Since we have mentioned the type of user, the user story can refer to it with “I”.
This is useful for **consistency** and to **avoid repetition** in the Acceptance criteria.
It’s also good to practice a little **empathy**.

For example:

```markdown
1. I click on the “submit” button.
1. A modal window appears if I don’t have enough credits.
1. The modal window contains the following:
  1. […]
```

The template uses [markdown][2].
You should get familiar with it if you’re not already, **it’s awesome!**

### Template

```markdown
[
The user story should have a reason to exist: what do I need as the user described in the summary?
This part details any detail that could not be passed by the summary.
]


### Acceptance Criteria

1. [If I do A.]
1. [B should happen.]

[
Also, here are a few points that need to be addressed:

1. Constraint 1;
1. Constraint 2;
1. Constraint 3.
]


### Resources:

* Mockups: [Here goes a URL to or the name of the mockup(s) in inVision];
* Testing URL: [Here goes a URL to the testing branch or IP];
* Staging URL: [Here goes a URL to the feature on staging];


### Notes

[Some complementary notes if necessary:]

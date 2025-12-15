---
layout: essay
type: essay
title: "This Should Take Two Hours, Maybe Four, Possibly Eight: Lessons from Estimating and Tracking Time"
# All dates must be YYYY-MM-DD format!
date: 2025-12-14
published: true
labels:
  - Effort Estimation
  - Tracking Effort
---

<img width="200px" class="rounded float-start pe-4" src="../img/clockman.jpg">

Estimating and tracking effort is a core software engineering practice, but it becomes far more complex once real development work begins. Throughout our project, I used GitHub project boards to estimate and record both coding and non-coding effort across multiple milestones. While my estimates were often inaccurate, the process helped me better understand my workflow, plan my time better, and improve future estimates.

## It’s not just a guess, it’s educated: Estimating Effort

I started effort estimation with a cautious approach. I would start with an optimistic estimate of how long I thought a task would take and then add one or two hours to account for errors, uncertainty in how to go about doing the task, and unexpected problems. As the project progressed, I based my estimates more on past work by comparing new issues to similar completed issues. I also took into account my work habits, like needing time to get into the groove on larger tasks, and allowances for AI use and debugging.

For example, in Milestone 2, I estimated 10 hours for creating a new recipes page with a form. This included reviewing prior coursework, deciding on page content, customizing the form to match the application, handling errors, using AI, and getting into the workflow. Later in the same milestone, I estimated 8 hours for creating an edit user profile page by referencing the 12 hours spent on the add recipe page and subtracting 4 hours that had been used resolving a secret exposure issue. By Milestone 3, I estimated 6 hours for adding an inline edit feature for vendor ingredients based on the prior edit page task. Even when my estimates weren’t exact, making them ahead of time helped me plan when to work on each issue. For example, if I estimated that an issue would take more than 8 hours, I avoided starting it late in the afternoon and instead scheduled to start it in the morning so I could have enough time to get the issue done and still have more time in the day in case any problems arose.


## It felt like eight hours, but it was actually ten: Tracking Effort

Tracking actual effort proved just as valuable as estimation. To track my effort I recorded my start and end times for each work session and periodically paused to take brief notes describing what I was doing, such as coding, planning, debugging, or using AI. These notes allowed me to separate coding effort from non-coding effort and calculate totals at the end of each issue. Although I rounded times for hour-based reporting, I found the tracking was reasonable and fairly accurate. For instance, about 40 minutes of debugging or 25 minutes of planning was rounded to 1 hour or 0.5 hours.

This tracking helped me plan my schedule more effectively and understand how long tasks realistically take me. Knowing how much time similar issues had required in the past helped me decide when to start new work and whether a task was feasible to complete in a single session. It also became more aware of where time was spent, especially on research, planning, and AI-assisted problem solving.

## It’s not C-3PO, but still: AI Assistance

I used ChatGPT (free version) as an AI assistant for both coding and non-coding tasks during this project. My usual process was to explain the problem I was working on, paste the issue description, paste the files I had so far that pertained to the problem, and add any error messages if something was not working. The amount of time spent using AI depended on the issue, but it was usually half or less than half of the total effort. Most of this time was spent writing prompts and reviewing generated responses, and almost all AI-generated output required manual changes before being added to the project. Only one response, related to adding the inline edit feature for vendor ingredients, was used mostly as-is.

## Time’s up

Estimating and tracking effort made my work more intentional and manageable. The process encouraged me to plan ahead, helped me manage my time, and gave useful data for improving future estimates. If I were to repeat this experience, I think I would like to use an actual time tracker to improve accuracy and reduce overestimation. Overall, this experience showed me that effort estimation is less about predicting the future perfectly and more about learning from past work to make better decisions moving forward.

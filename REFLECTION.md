# Reflection: Daily Schedule Simulator

## What was your approach to designing the schedule?
I chose to model my day around how I usually approach a study session before an assignment is due. I included real-life habits like checking my phone in the morning, drinking coffee, studying, and getting distracted occasionally.

## What was one challenge or unexpected behavior you encountered?
One challenge was understanding the timing of 'setTimeout'. I thought the activities would run instantly but then I realized each delay was relative to when the script starts and not the last activity. Once I figured that out this, the timing felt more natural.

## What does this assignment teach you about async code?
It taught me that asynchronous code doesn’t wait for one task to finish before starting another. You control timing with functions like 'setTimeout'. Compared to regular top-down scripts, this gives a more dynamic and real-time feel to how code runs, which is important in things like UI animation or scheduling.

## What creative element did you add?
I added a “surprise twist” where a random event appears in the middle of the day. It can be a nap, a walk or sometimes getting distracted. This makes the simulation more fun and realistic since days hardly go exactly as planned.

## How does this project simulate or differ from real-world schedules?
It simulates a real schedule in how it follows a time-based sequence, but it’s different because we speed up time a lot using short delays. In real life, things take hours and here it is condensed into a few seconds. But it still captures the idea of asynchronous events happening over time.

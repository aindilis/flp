
# Table of Contents

1.  [The Free Life Planner](#orgc218108)
    1.  [THIS README IS UNDER CONSTRUCTION](#org0ee899a)
    2.  [Overview](#orgd6a07b1)
    3.  [Status](#orgb29caeb)
    4.  [Some Things that the Free Life Planner helps with:](#orgde51581)
    5.  [In-Depth Overview](#org8546940)
        1.  [Workflow Manager](#orgce1b899)
        2.  [Health](#org7ef760f)
        3.  [Time Management](#org52f146f)
        4.  [Organization](#orge29ce4a)
        5.  [Self-Discipline](#orgb9fbc15)
        6.  [Transportation/Shopping/Errands](#orge5b182b)
        7.  [Document Management](#orgae1f073)
        8.  [Financial Planner](#orgad13546)
        9.  [Emergency Preparedness](#org4c0e94a)


<a id="orgc218108"></a>

# The Free Life Planner


<a id="org0ee899a"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orgd6a07b1"></a>

## Overview

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="orgb29caeb"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgde51581"></a>

## Some Things that the Free Life Planner helps with:

-   [Workflow Manager](#orgce1b899) (Guides user through all other systems)
-   [Health](#org7ef760f) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org442e526) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org52f146f) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orge29ce4a) (Inventory Management)
-   [Self-Discipline](#orgb9fbc15) (State Machine)
-   [Paperwork](#orgae1f073) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgad13546) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org4c0e94a) ()


<a id="org8546940"></a>

## In-Depth Overview


<a id="orgce1b899"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org7ef760f"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#orgb9fbc15) for dieting
        -   [ ] Specialty diets (medical or ethical)
        -   [ ] [Show pictures here]

3.  Doctor's Visits and Orders

    -   [ ] Tracking visits
    -   [ ] Following through on instructions
    -   [ ] For when a physician is unavailable
        -   [ ] First aid course of action system
        -   [ ] Symptom and condition tracker

4.  Medications

    -   [ ] Refill Tracker
    -   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org52f146f"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planning
    
    2.  Plan Monitoring
    
        -   [ ] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
            -   [ ] Behavior trees
                -   [ ] Execution of generated (PDDL/AgentSpeak(L)/BT/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orge29ce4a"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">
    
    -   Pantry management


<a id="orgb9fbc15"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="orge5b182b"></a>

### Transportation/Shopping/Errands

1.  Transportation

    -   [ ] API mashups
        -   [ ] Hours of operation look-ups
        -   [ ] Route planning
    -   [-] Location Logic
        -   [X] [Owntracks](https://owntracks.org/) integration
        -   [ ] Reverse geocoding
        -   [ ] Locational Rules
            -   [ ] e.g. Silence my phone when at any movie theater

2.  Shopping

    -   [ ] Receipt parsers
    -   [X] Online order Tracker
        -   [X] Checks against Bank OFX export
    -   [X] Online Delivery Tracker
    -   [ ] Integration with pantry and inventory management


<a id="orgae1f073"></a>

### Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgad13546"></a>

### Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org4c0e94a"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


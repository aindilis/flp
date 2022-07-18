
# Table of Contents

1.  [The Free Life Planner](#org166b434)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org84b214b)
    2.  [Overview](#orgde1a0a6)
    3.  [Status](#org704c6c8)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#org0f3c095)
    5.  [In-Depth Overview](#org5892a1c)
        1.  [Workflow Manager](#org1859e44)
        2.  [Health](#org460d734)
        3.  [Time Management](#orgd038283)
        4.  [Organization](#orgad8b79b)
        5.  [Self-Discipline](#orgcbee147)
        6.  [Transportation/Shopping/Errands](#org091846f)
        7.  [Document Management](#orgf61e05f)
        8.  [Financial Planner](#orgfabd24c)
        9.  [Emergency Preparedness](#org58786c8)


<a id="org166b434"></a>

# The Free Life Planner


<a id="org84b214b"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="orgde1a0a6"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org704c6c8"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="org0f3c095"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Workflow Manager](#org1859e44) (Guides user through all other systems)
-   [Health](#org460d734) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org71f9cc8) (Nutrition, Taste, Cost, etc)
-   [Time Management](#orgd038283) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orgad8b79b) (Inventory Management)
-   [Self-Discipline](#orgcbee147) (State Machine)
-   [Paperwork](#orgf61e05f) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgfabd24c) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org58786c8) ()


<a id="org5892a1c"></a>

## In-Depth Overview


<a id="org1859e44"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org460d734"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#orgcbee147) systems helps you achieve the diet you want
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


<a id="orgd038283"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planners
    
        -   9 temporal planners
            -   [X] CLG, Colin2<sub>CLP</sub>, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan522
        -   1 contingent planner
            -   [X] DNFct
        -   [X] More than 200 temporal life planning domains
    
    2.  Plan Monitoring
    
        -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgad8b79b"></a>

### Organization

1.  Inventory Management

    [[![img](https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg)]]
    
    -   Pantry management


<a id="orgcbee147"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="org091846f"></a>

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


<a id="orgf61e05f"></a>

### Document Management

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders
-   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgfabd24c"></a>

### Financial Planner

-   [X] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="org58786c8"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


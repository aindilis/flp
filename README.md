
# Table of Contents

1.  [The Free Life Planner](#org6eabda6)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org7cfea90)
    2.  [Overview](#orgcaf544c)
    3.  [Status](#org4140671)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#org35a1612)
    5.  [In-Depth Overview](#org922a495)
        1.  [Health](#org6a0b9d5)
        2.  [Time Management](#orga5c135e)
        3.  [Transportation/Shopping/Errands](#orgf6562d1)
        4.  [Document Management System](#org9219d38)
        5.  [Financial Planning System](#orgd6f8391)
        6.  [Emergency Preparedness](#orgd02d08a)


<a id="org6eabda6"></a>

# The Free Life Planner


<a id="org7cfea90"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="orgcaf544c"></a>

## Overview

-   A Life Planner that helps
-   Automate almost every aspect of your life
-   Cognitive Prosthetic for Executive Function


<a id="org4140671"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="org35a1612"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Health](#org6a0b9d5) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   Meal Planning (Nutrition, Taste, Cost, etc)
-   [Time Management](#orga5c135e) (Recurrences, Calendaring, SPSE2/Verber/FLP/etc)
-   Organization and Self-Discipline ()
-   Paperwork (Mail, Receipts, Doctors Orders etc)
-   Financial (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgd02d08a) ()


<a id="org922a495"></a>

## In-Depth Overview


<a id="org6a0b9d5"></a>

### Health

1.  Exercise

    -   [X] Use Alexa voice interface to say "Alexa, tell David - Andy did his morning exercises"

2.  Nutrition

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] Self-discipline systems helps you achieve the diet you want
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


<a id="orga5c135e"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planners
    
        -   10 temporal planners
            -   CLG, Colin2<sub>CLP</sub>, DNFct, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan522
        -   > 200 temporal life planning domains
        -   [X] Contingent planning
    
    2.  Plan Monitoring
    
        -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    -   How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgf6562d1"></a>

### Transportation/Shopping/Errands

1.  Transportation

    -   [ ] API mashups
        -   [ ] Hours of operation look-ups
        -   [ ] Route planning
    -   [-] Location Logic
        -   [X] Owntracks integration
        -   [ ] Reverse geocoding
        -   [ ] Locational Rules
            -   [ ] e.g. Silence my phone when at any movie theater

2.  Shopping

    -   [X] Order Tracker
        -   [X] Checks against Bank OFX export
    -   [X] Online Delivery Tracker
    -   [ ] Integrates with Pantry and Inventory Management


<a id="org9219d38"></a>

### Document Management System

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders


<a id="orgd6f8391"></a>

### Financial Planning System

-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="orgd02d08a"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


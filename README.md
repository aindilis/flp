
# Table of Contents

1.  [The Free Life Planner](#org64f4dbb)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org43b5507)
    2.  [Solution Concept](#org15b18ac)
    3.  [Status](#org8a9111d)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#org78bac59)
    5.  [In-Depth Overview](#org62e37ee)
        1.  [Health](#org537ce28)
        2.  [Time Management](#orgc855634)
        3.  [Transportation/Shopping/Errands](#org6a4175e)
        4.  [Document Management System](#orgaed4f6d)
        5.  [Financial Planning System](#org38d7b49)
        6.  [Emergency Preparedness](#org6be3816)


<a id="org64f4dbb"></a>

# The Free Life Planner


<a id="org43b5507"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org15b18ac"></a>

## Solution Concept

-   A Life Planner that helps
-   Automate almost every aspect of your life
-   Cognitive Prosthetic for Executive Function


<a id="org8a9111d"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="org78bac59"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Health](#org537ce28) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [ ] Meal Planning (Nutrition, Taste, Cost, etc)
-   [Time Management](#orgc855634) (Recurrences, Calendaring, SPSE2/Verber/FLP/etc)
-   Organization and Self-Discipline ()
-   Paperwork (Mail, Receipts, Doctors Orders etc)
-   Financial (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org6be3816) ()


<a id="org62e37ee"></a>

## In-Depth Overview


<a id="org537ce28"></a>

### Health

1.  Exercise

    -   Use Alexa voice interface to say "Alexa, tell David - Andy did his morning exercises"

2.  Nutrition

    -   [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   Improves nutrition and taste
    -   Reduces cost and prep time 4X
    -   Self-discipline systems helps you achieve the diet you want
    -   [Show pictures here]

3.  Doctor's Visits and Orders

    -   Tracking visits
    -   Following through on instructions
    -   For when a physician is unavailable
        -   First aid course of action system
        -   Symptom and condition tracker

4.  Medications

    -   Refill Tracker
    -   [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="orgc855634"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planners
    
        -   10 temporal planners
            -   CLG, Colin2<sub>CLP</sub>, DNFct, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan522
        -   > 200 temporal life planning domains
        -   Contingent planning
    
    2.  Plan Monitoring
    
        -   [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
        -   [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org6a4175e"></a>

### Transportation/Shopping/Errands

1.  Transportation

    -   API mashups
        -   Hours of operation look-ups
        -   Route planning
    -   Location Logic
        -   Owntracks integration
        -   Reverse geocoding
        -   Locational Rules
            -   e.g. Silence my phone when at any movie theater

2.  Shopping

    -   [X] Order Tracker
        -   [X] Checks against Bank OFX export
    -   [X] Online Delivery Tracker
    -   Integrates with Pantry and Inventory Management


<a id="orgaed4f6d"></a>

### Document Management System

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders


<a id="org38d7b49"></a>

### Financial Planning System

-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="org6be3816"></a>

### Emergency Preparedness

-   [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


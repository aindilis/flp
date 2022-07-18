
# Table of Contents

1.  [The Free Life Planner](#org619d2a8)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#orgcff46dd)
    2.  [Solution Concept](#orgdfab522)
    3.  [Status](#org8f10f56)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#org6a4e650)
    5.  [In-Depth Overview](#org90cc980)
        1.  [Health](#org2dbaa02)
        2.  [Time Management](#org07706a9)
        3.  [Transportation/Shopping/Errands](#org49b2cf2)
        4.  [Document Management System](#orgb7169ec)
        5.  [Financial Planning System](#org0219da0)
        6.  [Emergency Preparedness](#org88972ce)


<a id="org619d2a8"></a>

# The Free Life Planner


<a id="orgcff46dd"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="orgdfab522"></a>

## Solution Concept

-   A Life Planner that helps
-   Automate almost every aspect of your life
-   Cognitive Prosthetic for Executive Function


<a id="org8f10f56"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="org6a4e650"></a>

## DONE Summary of Some Areas that the Free Life Planner helps with:

-   [Health](#org2dbaa02) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [ ] Meal Planning (Nutrition, Taste, Cost, etc)
-   [Time Management](#org07706a9) (Recurrences, Calendaring, SPSE2/Verber/FLP/etc)
-   Organization and Self-Discipline ()
-   Paperwork (Mail, Receipts, Doctors Orders etc)
-   Financial (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org88972ce) ()


<a id="org90cc980"></a>

## In-Depth Overview


<a id="org2dbaa02"></a>

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
        -   First Aid Course Of Action system
        -   Symptom and Condition tracker

4.  Medications

    -   Refill Tracker
    -   [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org07706a9"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planners
    
        -   10 temporal planners
        -   > 200 temporal life planning domains
        -   Contingent planning
    
    2.  Plan Monitoring
    
        -   [Plan Monitoring](https://github.com/aindilis/plan-monitor)
        -   [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org49b2cf2"></a>

### Transportation/Shopping/Errands

1.  Transportation

    -   Location Logic
        -   Owntracks integration
    -   API mashups
        -   Hours of operation look-ups
        -   Route planning
        -   Reverse geocoding

2.  Shopping

    -   Order Tracker
        -   Checks against Bank OFX export
    -   Online Delivery Tracker
    -   Integrates with Pantry and Inventory Management


<a id="orgb7169ec"></a>

### Document Management System

-   Scan and OCR all paperwork
-   Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   Backup in git
-   Export selected documents and folders


<a id="org0219da0"></a>

### Financial Planning System

-   Quickly forecast finances almost indefinitely into the future
-   Metaplanners help develop contingency plans for different financial problems
    -   Unexpected delays
    -   Overcharges and Unapproved Charges
    -   Cash flow problems and hardships


<a id="org88972ce"></a>

### Emergency Preparedness

-   [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


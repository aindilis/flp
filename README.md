
# Table of Contents

1.  [The Free Life Planner](#org405318d)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org99c32c7)
    2.  [Solution Concept](#orgec6319c)
    3.  [Status](#org4842426)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#orgcb0c7dc)
    5.  [In-Depth Overview](#orgce50d4e)
        1.  [Health](#orgad32417)
        2.  [Time Management](#orgde1845b)
        3.  [Transportation/Shopping/Errands](#org1e717c8)
        4.  [Document Management System](#org182d788)
        5.  [Financial Planning System](#org51e322e)
        6.  [Emergency Management and Preparedness](#org75abbc0)


<a id="org405318d"></a>

# The Free Life Planner


<a id="org99c32c7"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="orgec6319c"></a>

## Solution Concept

-   A Life Planner that helps
-   Automate almost every aspect of your life
-   Cognitive Prosthetic for Executive Function


<a id="org4842426"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="orgcb0c7dc"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Health](#orgad32417) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
-   [Time Management](#orgde1845b) (Recurrences, Calendaring)
-   Organization and Self-Discipline ()
-   Sequencing (SPSE2/Verber/FLP/etc)
-   Meal Planning (Nutrition, Taste, Cost, etc)
-   Paperwork (Mail, Receipts, Doctors Orders etc)
-   Financial (Bills, Recurrences, Meal)
-   Emergency Preparedness ()


<a id="orgce50d4e"></a>

## In-Depth Overview


<a id="orgad32417"></a>

### Health

1.  Fitness Management

    -   Use Alexa voice interface to say 'Alexa, tell David - Andy did
        his morning exercises'

2.  "Gourmet Meal Planner"

    -   [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   Improves nutrition and taste
    -   Reduces cost and time 4X
    -   Self-discipline systems helps you achieve the diet you want
    -   [Show pictures here]

3.  Akahige Medical Expert System

    -   Tracking Doctor's Visits
    -   Following through on Doctor's Instructions
    -   For when a physician is unavailable
        -   Symptom tracker


<a id="orgde1845b"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Verber
    
    2.  IEM

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org1e717c8"></a>

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


<a id="org182d788"></a>

### Document Management System

-   Scan and OCR all paperwork
-   Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   Backup in git
-   Export selected documents and folders


<a id="org51e322e"></a>

### Financial Planning System

-   Quickly forecast finances almost indefinitely into the future
-   Metaplanners help develop contingency plans for different financial problems
    -   Unexpected delays
    -   Overcharges and Unapproved Charges
    -   Cash flow problems and hardships


<a id="org75abbc0"></a>

### Emergency Management and Preparedness

-   [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


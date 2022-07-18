
# Table of Contents

1.  [The Free Life Planner](#org0d957f3)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org7f3e709)
    2.  [Solution Concept](#org7d2ef25)
    3.  [Status](#orgd6851b0)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#orgea69f4c)
    5.  [In-Depth Overview](#orga14e184)
        1.  [Health](#org8584689)
        2.  [Time Management](#orgfc022e8)
        3.  [Transportation/Shopping/Errands](#org69310c9)
        4.  [Document Management System](#org7bde3a8)
        5.  [Time Management](#org4f9e24c)
        6.  [Financial Planning System](#orgbe899b2)
        7.  [Emergency Management and Preparedness](#org10078c0)


<a id="org0d957f3"></a>

# The Free Life Planner


<a id="org7f3e709"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org7d2ef25"></a>

## Solution Concept

-   A Life Planner that helps
-   Automate almost every aspect of your life
-   Cognitive Prosthetic for Executive Function


<a id="orgd6851b0"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="orgea69f4c"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [1.5.1](#org8584689) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
-   [1.5.2](#orgfc022e8) (Recurrences, Calendaring)
-   Organization and Self-Discipline ()
-   Sequencing (SPSE2/Verber/FLP/etc)
-   Meal Planning (Nutrition, Taste, Cost, etc)
-   Paperwork (Mail, Receipts, Doctors Orders etc)
-   Financial (Bills, Recurrences, Meal)
-   Emergency Preparedness ()


<a id="orga14e184"></a>

## In-Depth Overview


<a id="org8584689"></a>

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


<a id="orgfc022e8"></a>

### Time Management

-   blah blah


<a id="org69310c9"></a>

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


<a id="org7bde3a8"></a>

### Document Management System

-   Scan and OCR all paperwork
-   Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   Backup in git
-   Export selected documents and folders


<a id="org4f9e24c"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Verber
    
    2.  IEM

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgbe899b2"></a>

### Financial Planning System

-   Quickly forecast finances almost indefinitely into the future
-   Metaplanners help develop contingency plans for different financial problems
    -   Unexpected delays
    -   Overcharges and Unapproved Charges
    -   Cash flow problems and hardships


<a id="org10078c0"></a>

### Emergency Management and Preparedness

-   [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)



# Table of Contents

1.  [The Free Life Planner](#org40e5d0b)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#orgb7b5850)
    2.  [Solution Concept](#org87e5e0a)
    3.  [Status](#org8ad46ea)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#org970e68d)
    5.  [In-Depth Overview](#org8d8cb15)
        1.  [Health](#org4202c9c)
        2.  [Transportation/Shopping/Errands](#org73c2901)
        3.  [Document Management System](#org0b5a3fc)
        4.  [Time Management](#orge53148f)
        5.  [Financial Planning System](#org9ebe658)
        6.  [Emergency Management and Preparedness](#org33da9f6)


<a id="org40e5d0b"></a>

# The Free Life Planner


<a id="orgb7b5850"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org87e5e0a"></a>

## Solution Concept

-   A Life Planner that helps
-   Automate almost every aspect of your life


<a id="org8ad46ea"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="org970e68d"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   Health (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
-   Time Management (Recurrences, Calendaring)
-   Organization (????/????)
-   Sequencing (SPSE2/Verber/FLP/etc)
-   Meal Planning (Nutrition, Taste, Cost, etc)
-   Paperwork (Mail, Receipts, Doctors Orders etc)
-   Financial (Bills, Recurrences, Meal)
-   Emergency Preparedness ()


<a id="org8d8cb15"></a>

## In-Depth Overview


<a id="org4202c9c"></a>

### Health

1.  Fitness Management

    -   Use Alexa voice interface to say 'Alexa, tell David - Andy did
        his morning exercises'

2.  "Gourmet" Meal Planner

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


<a id="org73c2901"></a>

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


<a id="org0b5a3fc"></a>

### Document Management System

-   Scan and OCR all paperwork
-   Extract dates using TIMEX3 parsers and integrate with planning
    scheduling and execution system
-   Backup in git
-   Export selected documents and folders


<a id="orge53148f"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Verber
    
    2.  IEM

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org9ebe658"></a>

### Financial Planning System

-   Quickly forecast finances almost indefinitely into the future
-   Metaplanner helps develop contingency plans for different financial problems
    -   Unexpected delays
    -   Overcharges and Unapproved Charges


<a id="org33da9f6"></a>

### Emergency Management and Preparedness

-   [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)



# Table of Contents

1.  [The Free Life Planner](#org22b44e3)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#orgf8a8cad)
    2.  [Solution Concept](#org8ec9a30)
    3.  [Status](#orged58de6)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#org524e9ca)
    5.  [In-Depth Overview](#org63efa2f)
        1.  [Health](#org06c200c)
        2.  [Transportation/Shopping/Errands](#orga6c2983)
        3.  [Document Management System](#org3509796)
        4.  [Time Management](#org93abdb7)
        5.  [Financial Planning System](#orgad99847)


<a id="org22b44e3"></a>

# The Free Life Planner


<a id="orgf8a8cad"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org8ec9a30"></a>

## Solution Concept

-   A Life Planner that helps

-   Automate almost every aspect of your life


<a id="orged58de6"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="org524e9ca"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   Health (Exercise, Nutrition, Doctor's Visits & Orders, Medications)

-   Time Management (Recurrences, Calendaring)

-   Organization (????/????)

-   Sequencing (SPSE2/Verber/FLP/etc)

-   Meal Planning (Nutrition, Taste, Cost, etc)

-   Paperwork (Mail, Receipts, Doctors Orders etc)

-   Financial (Bills, Recurrences, Meal)


<a id="org63efa2f"></a>

## In-Depth Overview


<a id="org06c200c"></a>

### Health

1.  Fitness Management

    -   Use Alexa voice interface to say 'Alexa, tell David - Andy did
        his morning exercises'

2.  "Gourmet" Meal Planner

    -   Link to MealPlanningResources
    
    -   Improves nutrition and taste
    
    -   Reduces cost and time 4X
    
    -   Self-discipline systems helps you achieve the diet you want
    
    -   [Show pictures here]

3.  Akahige Medical Expert System

    -   Tracking Doctor's Visits
    
    -   Following through on Doctor's Instructions
    
    -   For when a physician is unavailable


<a id="orga6c2983"></a>

### Transportation/Shopping/Errands

1.  Transportation

    -   Location Logic

2.  Shopping

    -   Order Tracker
        -   (checks against Bank OFX export)
    
    -   Delivery Tracker
    
    -   Integrates with Pantry and Inventory Management


<a id="org3509796"></a>

### Document Management System

-   Scan and OCR all paperwork

-   Extract dates using TIMEX3 parsers and integrate with planning
    scheduling and execution system

-   Backup in git

-   Export selected documents and folders


<a id="org93abdb7"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Verber
    
    2.  IEM

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgad99847"></a>

### Financial Planning System

-   Quickly forecast finances almost indefinitely into the future

-   Metaplanner helps develop contingency plans for different financial problems
    -   Unexpected delays
    -   Overcharges and Unapproved Charges

[![Personal Emergency Management]()](<https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4>)


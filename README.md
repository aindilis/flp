
# Table of Contents

1.  [The Free Life Planner](#orgd2436d1)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#orga178c6f)
    2.  [Solution Concept](#org36c02a2)
    3.  [Status](#org33e63bf)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#org3f2f53a)
    5.  [In-Depth Overview](#orgad9083e)
        1.  [Health](#orgc627a03)
        2.  [Transportation/Shopping/Errands](#org030fe30)
        3.  [Document Management System](#org5d616ef)
        4.  [Time Management](#org9271c43)
        5.  [Financial Planning System](#org88ef7ed)


<a id="orgd2436d1"></a>

# The Free Life Planner


<a id="orga178c6f"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org36c02a2"></a>

## Solution Concept

-   A Life Planner that helps

-   Automate almost every aspect of your life


<a id="org33e63bf"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="org3f2f53a"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   Health (Exercise, Nutrition, Doctor's Visits & Orders, Medications)

-   Time Management (Recurrences, Calendaring)

-   Organization (????/????)

-   Sequencing (SPSE2/Verber/FLP/etc)

-   Meal Planning (Nutrition, Taste, Cost, etc)

-   Paperwork (Mail, Receipts, Doctors Orders etc)

-   Financial (Bills, Recurrences, Meal)


<a id="orgad9083e"></a>

## In-Depth Overview


<a id="orgc627a03"></a>

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


<a id="org030fe30"></a>

### Transportation/Shopping/Errands

1.  Transportation

    -   Location Logic

2.  Shopping

    -   Order Tracker
        -   (checks against Bank OFX export)
    
    -   Delivery Tracker
    
    -   Integrates with Pantry and Inventory Management


<a id="org5d616ef"></a>

### Document Management System

-   Scan and OCR all paperwork

-   Extract dates using TIMEX3 parsers and integrate with planning
    scheduling and execution system

-   Backup in git

-   Export selected documents and folders


<a id="org9271c43"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Verber
    
    2.  IEM

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org88ef7ed"></a>

### Financial Planning System

-   Quickly forecast finances almost indefinitely into the future

-   Metaplanner helps develop contingency plans for different financial problems
    -   Unexpected delays
    -   Overcharges and Unapproved Charges

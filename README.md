
# Table of Contents

1.  [The Free Life Planner](#org55bc757)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#orgeb654b3)
    2.  [Solution Concept](#org20145b1)
    3.  [Status](#org1ce2aa2)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#org36ee95e)
    5.  [In-Depth Overview](#org753e368)
        1.  [Health](#org3b34012)
        2.  [Transportation/Shopping/Errands](#orgd896fbc)
        3.  [Document Management System](#org94e27c3)
        4.  [Time Management](#org728181e)
        5.  [Financial Planning System](#orgc4c30c1)
        6.  [Emergency Management and Preparedness](#orge58e0d1)


<a id="org55bc757"></a>

# The Free Life Planner


<a id="orgeb654b3"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org20145b1"></a>

## Solution Concept

-   A Life Planner that helps
-   Automate almost every aspect of your life


<a id="org1ce2aa2"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="org36ee95e"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   Health (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
-   Time Management (Recurrences, Calendaring)
-   Organization (????/????)
-   Sequencing (SPSE2/Verber/FLP/etc)
-   Meal Planning (Nutrition, Taste, Cost, etc)
-   Paperwork (Mail, Receipts, Doctors Orders etc)
-   Financial (Bills, Recurrences, Meal)
-   Emergency Preparedness ()


<a id="org753e368"></a>

## In-Depth Overview


<a id="org3b34012"></a>

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


<a id="orgd896fbc"></a>

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


<a id="org94e27c3"></a>

### Document Management System

-   Scan and OCR all paperwork
-   Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   Backup in git
-   Export selected documents and folders


<a id="org728181e"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Verber
    
    2.  IEM

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgc4c30c1"></a>

### Financial Planning System

-   Quickly forecast finances almost indefinitely into the future
-   Metaplanner helps develop contingency plans for different financial problems
    -   Unexpected delays
    -   Overcharges and Unapproved Charges


<a id="orge58e0d1"></a>

### Emergency Management and Preparedness

-   [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


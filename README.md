
# Table of Contents

1.  [The Free Life Planner](#org125cd2e)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org302e849)
    2.  [Overview](#org5465d62)
    3.  [Status](#org14a717c)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#orgd5faddf)
    5.  [In-Depth Overview](#org73fced4)
        1.  [Workflow Manager](#org54d915b)
        2.  [Health](#orga3d4f06)
        3.  [Time Management](#orgb60ef47)
        4.  [Organization](#org36b7ca2)
        5.  [Self-Discipline](#org5a49ac1)
        6.  [Transportation/Shopping/Errands](#orgfc08bc4)
        7.  [Document Management](#orgece3ea3)
        8.  [Financial Planner](#orgd84fad6)
        9.  [Emergency Preparedness](#orgca3f473)


<a id="org125cd2e"></a>

# The Free Life Planner


<a id="org302e849"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org5465d62"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org14a717c"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="orgd5faddf"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Workflow Manager](#org54d915b) (Guides user through all other systems)
-   [Health](#orga3d4f06) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org5c2a9f8) (Nutrition, Taste, Cost, etc)
-   [Time Management](#orgb60ef47) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org36b7ca2) (Inventory Management)
-   [Self-Discipline](#org5a49ac1) (State Machine)
-   [Paperwork](#orgece3ea3) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgd84fad6) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgca3f473) ()


<a id="org73fced4"></a>

## In-Depth Overview


<a id="org54d915b"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="orga3d4f06"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org5a49ac1) systems helps you achieve the diet you want
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


<a id="orgb60ef47"></a>

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


<a id="org36b7ca2"></a>

### Organization

1.  Inventory Management

    [[![img](https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg)]]
    
    -   Pantry management


<a id="org5a49ac1"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="orgfc08bc4"></a>

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


<a id="orgece3ea3"></a>

### Document Management

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders
-   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgd84fad6"></a>

### Financial Planner

-   [X] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="orgca3f473"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


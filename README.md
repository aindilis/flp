
# Table of Contents

1.  [The Free Life Planner](#org6eacf40)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org5d89b49)
    2.  [Overview](#org40d832b)
    3.  [Status](#org05c46a5)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#orgcf12aa9)
    5.  [In-Depth Overview](#orga406095)
        1.  [Workflow Manager](#org673560e)
        2.  [Health](#org1282a4b)
        3.  [Time Management](#org161e46a)
        4.  [Organization](#orgab188e7)
        5.  [Self-Discipline](#org46471dc)
        6.  [Transportation/Shopping/Errands](#org2258093)
        7.  [Document Management](#org9a798cb)
        8.  [Financial Planner](#orgc13af0b)
        9.  [Emergency Preparedness](#orgc91e62e)


<a id="org6eacf40"></a>

# The Free Life Planner


<a id="org5d89b49"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org40d832b"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org05c46a5"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="orgcf12aa9"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Workflow Manager](#org673560e) (Guides user through all other systems)
-   [Health](#org1282a4b) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org269d769) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org161e46a) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orgab188e7) (Inventory Management)
-   [Self-Discipline](#org46471dc) (State Machine)
-   [Paperwork](#org9a798cb) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgc13af0b) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgc91e62e) ()


<a id="orga406095"></a>

## In-Depth Overview


<a id="org673560e"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org1282a4b"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org46471dc) systems helps you achieve the diet you want
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


<a id="org161e46a"></a>

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


<a id="orgab188e7"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">
    
    -   Pantry management


<a id="org46471dc"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="org2258093"></a>

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


<a id="org9a798cb"></a>

### Document Management

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders
-   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgc13af0b"></a>

### Financial Planner

-   [X] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="orgc91e62e"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


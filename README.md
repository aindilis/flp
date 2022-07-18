
# Table of Contents

1.  [The Free Life Planner](#orgee1ad41)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org7ab9c44)
    2.  [Overview](#orgf702e1b)
    3.  [Status](#org1f6ba45)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#org61ba709)
    5.  [In-Depth Overview](#org6b1e3fd)
        1.  [Workflow Manager](#org372b0f9)
        2.  [Health](#orgb669fa3)
        3.  [Time Management](#orga2222a3)
        4.  [Organization](#orgbb1eb6c)
        5.  [Self-Discipline](#org32ed449)
        6.  [Transportation/Shopping/Errands](#org33c892f)
        7.  [Document Management](#org8b77819)
        8.  [Financial Planner](#org40dcd6a)
        9.  [Emergency Preparedness](#org63adb65)


<a id="orgee1ad41"></a>

# The Free Life Planner


<a id="org7ab9c44"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="orgf702e1b"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org1f6ba45"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="org61ba709"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Workflow Manager](#org372b0f9) (Guides user through all other systems)
-   [Health](#orgb669fa3) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org7629a2f) (Nutrition, Taste, Cost, etc)
-   [Time Management](#orga2222a3) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orgbb1eb6c) (Inventory Management)
-   [Self-Discipline](#org32ed449) (State Machine)
-   [Paperwork](#org8b77819) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org40dcd6a) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org63adb65) ()


<a id="org6b1e3fd"></a>

## In-Depth Overview


<a id="org372b0f9"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="orgb669fa3"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org32ed449) systems helps you achieve the diet you want
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


<a id="orga2222a3"></a>

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


<a id="orgbb1eb6c"></a>

### Organization

1.  Inventory Management

    ![img](https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg)
    
    -   Pantry management


<a id="org32ed449"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="org33c892f"></a>

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


<a id="org8b77819"></a>

### Document Management

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders
-   [ ] Integration of document-related tasks into Workflow Manager


<a id="org40dcd6a"></a>

### Financial Planner

-   [X] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="org63adb65"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


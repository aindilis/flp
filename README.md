
# Table of Contents

1.  [The Free Life Planner](#orgf679044)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org25550cb)
    2.  [Overview](#org4d9b36d)
    3.  [Status](#org7af08e9)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#org7d7b477)
    5.  [In-Depth Overview](#org8fa1292)
        1.  [Workflow Manager](#orgacd32fd)
        2.  [Health](#org060f424)
        3.  [Time Management](#org4072af1)
        4.  [Organization](#org6466a0e)
        5.  [Self-Discipline](#org4c0d9bf)
        6.  [Transportation/Shopping/Errands](#orgadb9989)
        7.  [Document Management](#org0a05318)
        8.  [Financial Planner](#orgc85ad6f)
        9.  [Emergency Preparedness](#org17fd084)


<a id="orgf679044"></a>

# The Free Life Planner


<a id="org25550cb"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org4d9b36d"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org7af08e9"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="org7d7b477"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Workflow Manager](#orgacd32fd) (Guides user through all other systems)
-   [Health](#org060f424) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#orgf875c02) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org4072af1) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org6466a0e) (Inventory Management)
-   [Self-Discipline](#org4c0d9bf) (State Machine)
-   [Paperwork](#org0a05318) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgc85ad6f) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org17fd084) ()


<a id="org8fa1292"></a>

## In-Depth Overview


<a id="orgacd32fd"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org060f424"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org4c0d9bf) systems helps you achieve the diet you want
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


<a id="org4072af1"></a>

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


<a id="org6466a0e"></a>

### Organization

1.  Inventory Management

    -   ![img](https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg)
    -   Pantry management


<a id="org4c0d9bf"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="orgadb9989"></a>

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


<a id="org0a05318"></a>

### Document Management

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders
-   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgc85ad6f"></a>

### Financial Planner

-   [X] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="org17fd084"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


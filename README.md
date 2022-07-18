
# Table of Contents

1.  [The Free Life Planner](#org517dc63)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org2f5d061)
    2.  [Overview](#org08774c5)
    3.  [Status](#orgd5bf2cf)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#org4273db8)
    5.  [In-Depth Overview](#orge4be9a5)
        1.  [Workflow Manager](#orgafccb74)
        2.  [Health](#orgf6faaf3)
        3.  [Time Management](#org2644468)
        4.  [Organization](#org59f34dd)
        5.  [Self-Discipline](#org710ccd9)
        6.  [Transportation/Shopping/Errands](#org2a9a132)
        7.  [Document Management](#org7b7a2a3)
        8.  [Financial Planner](#org28a5b08)
        9.  [Emergency Preparedness](#orgf5d154f)


<a id="org517dc63"></a>

# The Free Life Planner


<a id="org2f5d061"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org08774c5"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="orgd5bf2cf"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="org4273db8"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Workflow Manager](#orgafccb74) (Guides user through all other systems)
-   [Health](#orgf6faaf3) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#orge54b6d6) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org2644468) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org59f34dd) (Inventory Management)
-   [Self-Discipline](#org710ccd9) (State Machine)
-   [Paperwork](#org7b7a2a3) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org28a5b08) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgf5d154f) ()


<a id="orge4be9a5"></a>

## In-Depth Overview


<a id="orgafccb74"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="orgf6faaf3"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org710ccd9) systems helps you achieve the diet you want
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


<a id="org2644468"></a>

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


<a id="org59f34dd"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="100px">
    
    -   Pantry management


<a id="org710ccd9"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="org2a9a132"></a>

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


<a id="org7b7a2a3"></a>

### Document Management

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders
-   [ ] Integration of document-related tasks into Workflow Manager


<a id="org28a5b08"></a>

### Financial Planner

-   [X] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="orgf5d154f"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


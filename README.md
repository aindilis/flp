
# Table of Contents

1.  [The Free Life Planner](#org8dcb37e)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org9c13d91)
    2.  [Overview](#org62dd8df)
    3.  [Status](#org882930b)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#orgcc40037)
    5.  [In-Depth Overview](#orgdd6ebcd)
        1.  [Workflow Manager](#orgaa6e2ea)
        2.  [Health](#org8182748)
        3.  [Time Management](#org6a12cf2)
        4.  [Organization](#org4176424)
        5.  [Self-Discipline](#orgb0f0fe0)
        6.  [Transportation/Shopping/Errands](#orgb84b569)
        7.  [Document Management System](#org5de6875)
        8.  [Financial Planning System](#orge1ba741)
        9.  [Emergency Preparedness](#org57eaae3)


<a id="org8dcb37e"></a>

# The Free Life Planner


<a id="org9c13d91"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org62dd8df"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org882930b"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="orgcc40037"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Workflow Manager](#orgaa6e2ea) (to control all other systems)
-   [Health](#org8182748) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   Meal Planning (Nutrition, Taste, Cost, etc)
-   [Time Management](#org6a12cf2) (Recurrences, Calendaring, SPSE2/Verber/FLP/etc)
-   Organization ()
-   [Self-Discipline](#orgb0f0fe0) ()
-   Paperwork (Mail, Receipts, Doctors Orders etc)
-   Financial (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org57eaae3) ()


<a id="orgdd6ebcd"></a>

## In-Depth Overview


<a id="orgaa6e2ea"></a>

### Workflow Manager

-   [ ] An overarching FLP subsystem which pages through and helps complete all necessary tasks


<a id="org8182748"></a>

### Health

1.  Exercise

    -   [X] Use Alexa voice interface to say "Alexa, tell David - Andy did his morning exercises"

2.  Nutrition

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#orgb0f0fe0) systems helps you achieve the diet you want
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


<a id="org6a12cf2"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planners
    
        -   10 temporal planners
            -   CLG, Colin2<sub>CLP</sub>, DNFct, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan522
        -   > 200 temporal life planning domains
        -   [X] Contingent planning
    
    2.  Plan Monitoring
    
        -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    -   How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org4176424"></a>

### Organization


<a id="orgb0f0fe0"></a>

### Self-Discipline


<a id="orgb84b569"></a>

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

    -   [X] Order Tracker
        -   [X] Checks against Bank OFX export
    -   [X] Online Delivery Tracker
    -   [ ] Integrates with Pantry and Inventory Management


<a id="org5de6875"></a>

### Document Management System

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders
-   [ ] Integrate documents into FLP workflow management


<a id="orge1ba741"></a>

### Financial Planning System

-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="org57eaae3"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


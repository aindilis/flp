
# Table of Contents

1.  [The Free Life Planner](#orgaa767fe)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org0922407)
    2.  [Overview](#org9e3ce38)
    3.  [Status](#orgb35b904)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#orgdcbe9b9)
    5.  [In-Depth Overview](#orgc4bea90)
        1.  [Workflow Manager](#orgb1b504f)
        2.  [Health](#org43e0c8d)
        3.  [Time Management](#org0545a43)
        4.  [Organization](#org493b152)
        5.  [Self-Discipline](#orgd28a69d)
        6.  [Transportation/Shopping/Errands](#org410b075)
        7.  [Document Management System](#org915ec17)
        8.  [Financial Planning System](#orgbb6b2fb)
        9.  [Emergency Preparedness](#org58c8cef)


<a id="orgaa767fe"></a>

# The Free Life Planner


<a id="org0922407"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org9e3ce38"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="orgb35b904"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="orgdcbe9b9"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Workflow Manager](#orgb1b504f) (to control all other systems)
-   [Health](#org43e0c8d) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   Meal Planning (Nutrition, Taste, Cost, etc)
-   [Time Management](#org0545a43) (Recurrences, Calendaring, SPSE2/Verber/FLP/etc)
-   Organization ()
-   [Self-Discipline](#orgd28a69d) ()
-   Paperwork (Mail, Receipts, Doctors Orders etc)
-   Financial (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org58c8cef) ()


<a id="orgc4bea90"></a>

## In-Depth Overview


<a id="orgb1b504f"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org43e0c8d"></a>

### Health

1.  Exercise

    -   [X] Use Alexa voice interface to say "Alexa, tell David - Andy did his morning exercises"

2.  Nutrition

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#orgd28a69d) systems helps you achieve the diet you want
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


<a id="org0545a43"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planners
    
        -   10 temporal planners
            -   CLG, Colin2<sub>CLP</sub>, DNFct, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan522
        -   More than 200 temporal life planning domains
        -   [X] Contingent planning
    
    2.  Plan Monitoring
    
        -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    -   How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org493b152"></a>

### Organization


<a id="orgd28a69d"></a>

### Self-Discipline


<a id="org410b075"></a>

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


<a id="org915ec17"></a>

### Document Management System

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders
-   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgbb6b2fb"></a>

### Financial Planning System

-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="org58c8cef"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


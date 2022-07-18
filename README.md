
# Table of Contents

1.  [The Free Life Planner](#org9ce0ee0)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org7dd6dd4)
    2.  [Overview](#orge932575)
    3.  [Status](#org8a222c9)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#org1e64cf2)
    5.  [In-Depth Overview](#org0cd8eb6)
        1.  [Workflow Manager](#org28737b6)
        2.  [Health](#org371337d)
        3.  [Time Management](#orgdbc2189)
        4.  [Organization](#orgecbd97a)
        5.  [Self-Discipline](#org9045082)
        6.  [Transportation/Shopping/Errands](#org87df4cf)
        7.  [Document Management System](#org7c508f2)
        8.  [Financial Planning System](#org860c0cf)
        9.  [Emergency Preparedness](#orgacdaf35)


<a id="org9ce0ee0"></a>

# The Free Life Planner


<a id="org7dd6dd4"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="orge932575"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org8a222c9"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="org1e64cf2"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Workflow Manager](#org28737b6) (to control all other systems)
-   [Health](#org371337d) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   Meal Planning (Nutrition, Taste, Cost, etc)
-   [Time Management](#orgdbc2189) (Recurrences, Calendaring, SPSE2/Verber/FLP/etc)
-   Organization ()
-   [Self-Discipline](#org9045082) ()
-   Paperwork (Mail, Receipts, Doctors Orders etc)
-   Financial (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgacdaf35) ()


<a id="org0cd8eb6"></a>

## In-Depth Overview


<a id="org28737b6"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org371337d"></a>

### Health

1.  Exercise

    -   [X] Use Alexa voice interface to say "Alexa, tell David - Andy did his morning exercises"

2.  Nutrition

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org9045082) systems helps you achieve the diet you want
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


<a id="orgdbc2189"></a>

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

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgecbd97a"></a>

### Organization


<a id="org9045082"></a>

### Self-Discipline


<a id="org87df4cf"></a>

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


<a id="org7c508f2"></a>

### Document Management System

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders
-   [ ] Integration of document-related tasks into Workflow Manager


<a id="org860c0cf"></a>

### Financial Planning System

-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="orgacdaf35"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


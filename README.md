
# Table of Contents

1.  [The Free Life Planner](#org7442b8d)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#orgffd6db6)
    2.  [Overview](#orgcacdd51)
    3.  [Status](#org3338e14)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#orga1b753c)
    5.  [In-Depth Overview](#org84d5fda)
        1.  [Workflow Manager](#org5a38a6d)
        2.  [Health](#orgd1bf572)
        3.  [Time Management](#org302525b)
        4.  [Organization](#orgfc74e3f)
        5.  [Self-Discipline](#orgd37b473)
        6.  [Transportation/Shopping/Errands](#org54f4eae)
        7.  [Document Management](#org75e0b69)
        8.  [Financial Planner](#org629c4ce)
        9.  [Emergency Preparedness](#orge43d655)


<a id="org7442b8d"></a>

# The Free Life Planner


<a id="orgffd6db6"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="orgcacdd51"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org3338e14"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="orga1b753c"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Workflow Manager](#org5a38a6d) (to control all other systems)
-   [Health](#orgd1bf572) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   Meal Planning (Nutrition, Taste, Cost, etc)
-   [Time Management](#org302525b) (Recurrences, Calendaring, SPSE2/Verber/FLP/etc)
-   [Organization](#orgfc74e3f) ()
-   [Self-Discipline](#orgd37b473) ()
-   [Paperwork](#org75e0b69) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org629c4ce) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orge43d655) ()


<a id="org84d5fda"></a>

## In-Depth Overview


<a id="org5a38a6d"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="orgd1bf572"></a>

### Health

1.  Exercise

    -   [X] Use Alexa voice interface to say "Alexa, tell David - Andy did his morning exercises"

2.  Nutrition

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#orgd37b473) systems helps you achieve the diet you want
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


<a id="org302525b"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planners
    
        -   9 temporal planners
            -   CLG, Colin2<sub>CLP</sub>, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan522
        -   1 contingent planner
            -   [X] DNFct
        -   More than 200 temporal life planning domains
    
    2.  Plan Monitoring
    
        -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgfc74e3f"></a>

### Organization


<a id="orgd37b473"></a>

### Self-Discipline


<a id="org54f4eae"></a>

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


<a id="org75e0b69"></a>

### Document Management

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders
-   [ ] Integration of document-related tasks into Workflow Manager


<a id="org629c4ce"></a>

### Financial Planner

-   [X] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="orge43d655"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


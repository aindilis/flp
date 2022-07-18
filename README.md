
# Table of Contents

1.  [The Free Life Planner](#org6fc9c59)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#orgb14a9bf)
    2.  [Overview](#orgf679d5f)
    3.  [Status](#org23dcd5a)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#orgeb443e2)
    5.  [In-Depth Overview](#org7b3139e)
        1.  [Workflow Manager](#org4c67010)
        2.  [Health](#org014349c)
        3.  [Time Management](#org14c4966)
        4.  [Organization](#org26a9a98)
        5.  [Self-Discipline](#orgae1c647)
        6.  [Transportation/Shopping/Errands](#org00d05fb)
        7.  [Document Management](#orgbf03201)
        8.  [Financial Planner](#org8017684)
        9.  [Emergency Preparedness](#orgd079303)


<a id="org6fc9c59"></a>

# The Free Life Planner


<a id="orgb14a9bf"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="orgf679d5f"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org23dcd5a"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="orgeb443e2"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Workflow Manager](#org4c67010) (to control all other systems)
-   [Health](#org014349c) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   Meal Planning (Nutrition, Taste, Cost, etc)
-   [Time Management](#org14c4966) (Recurrences, Calendaring, SPSE2/Verber/FLP/etc)
-   Organization ()
-   [Self-Discipline](#orgae1c647) ()
-   Paperwork (Mail, Receipts, Doctors Orders etc)
-   Financial (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgd079303) ()


<a id="org7b3139e"></a>

## In-Depth Overview


<a id="org4c67010"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org014349c"></a>

### Health

1.  Exercise

    -   [X] Use Alexa voice interface to say "Alexa, tell David - Andy did his morning exercises"

2.  Nutrition

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#orgae1c647) systems helps you achieve the diet you want
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


<a id="org14c4966"></a>

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


<a id="org26a9a98"></a>

### Organization


<a id="orgae1c647"></a>

### Self-Discipline


<a id="org00d05fb"></a>

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


<a id="orgbf03201"></a>

### Document Management

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders
-   [ ] Integration of document-related tasks into Workflow Manager


<a id="org8017684"></a>

### Financial Planner

-   [X] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="orgd079303"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


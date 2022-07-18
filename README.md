
# Table of Contents

1.  [The Free Life Planner](#org160176b)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org96c6133)
    2.  [Overview](#org519f8e2)
    3.  [Status](#org6b16c5f)
    4.  [Summary of Some Areas that the Free Life Planner helps with:](#orge7a7a25)
    5.  [In-Depth Overview](#org20692bc)
        1.  [Workflow Manager](#org1835448)
        2.  [Health](#orge101d48)
        3.  [Time Management](#org9881ff9)
        4.  [Organization](#orgecc122a)
        5.  [Self-Discipline](#org7cdae9f)
        6.  [Transportation/Shopping/Errands](#orgee045cc)
        7.  [Document Management](#org0c29c9b)
        8.  [Financial Planner](#orga52da00)
        9.  [Emergency Preparedness](#org97b167f)


<a id="org160176b"></a>

# The Free Life Planner


<a id="org96c6133"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org519f8e2"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org6b16c5f"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub


<a id="orge7a7a25"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   [Workflow Manager](#org1835448) (Guides user through all other systems)
-   [Health](#orge101d48) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org1c6bfe3) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org9881ff9) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orgecc122a) (Inventory Management)
-   [Self-Discipline](#org7cdae9f) (State Machine)
-   [Paperwork](#org0c29c9b) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orga52da00) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org97b167f) ()


<a id="org20692bc"></a>

## In-Depth Overview


<a id="org1835448"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="orge101d48"></a>

### Health

1.  Exercise

    -   [X] Use Alexa voice interface to say "Alexa, tell David - Andy did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org7cdae9f) systems helps you achieve the diet you want
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


<a id="org9881ff9"></a>

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


<a id="orgecc122a"></a>

### Organization

1.  Inventory Management

    -   Pantry management


<a id="org7cdae9f"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="orgee045cc"></a>

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


<a id="org0c29c9b"></a>

### Document Management

-   [X] Scan and OCR all paperwork
-   [X] Extract dates using TIMEX3 parsers and integrate with planning,
    scheduling, and execution system
-   [X] Backup in git
-   [X] Export selected documents and folders
-   [ ] Integration of document-related tasks into Workflow Manager


<a id="orga52da00"></a>

### Financial Planner

-   [X] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="org97b167f"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)



# Table of Contents

1.  [The Free Life Planner](#org35db975)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#orgcd2d628)
    2.  [Overview](#org387ac6f)
    3.  [Status](#org47a10a2)
    4.  [Some Things that the Free Life Planner helps with:](#org20fb316)
    5.  [In-Depth Overview](#org9156349)
        1.  [Workflow Manager](#org35fb975)
        2.  [Health](#org2ec9686)
        3.  [Time Management](#org11ab0a1)
        4.  [Organization](#org6199f20)
        5.  [Self-Discipline](#org2773390)
        6.  [Transportation/Shopping/Errands](#org915c311)
        7.  [Document Management](#org6cdd833)
        8.  [Financial Planner](#org4afa77c)
        9.  [Emergency Preparedness](#orga71280e)


<a id="org35db975"></a>

# The Free Life Planner


<a id="orgcd2d628"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org387ac6f"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org47a10a2"></a>

## Status

-   Currently working to release the latest version of FLP onto GitHub
-   Interoperability between all systems


<a id="org20fb316"></a>

## Some Things that the Free Life Planner helps with:

-   [Workflow Manager](#org35fb975) (Guides user through all other systems)
-   [Health](#org2ec9686) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org0a380f7) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org11ab0a1) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org6199f20) (Inventory Management)
-   [Self-Discipline](#org2773390) (State Machine)
-   [Paperwork](#org6cdd833) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org4afa77c) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orga71280e) ()


<a id="org9156349"></a>

## In-Depth Overview


<a id="org35fb975"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org2ec9686"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org2773390) for dieting
        -   [ ] Specialty diets (medical or ethical)
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


<a id="org11ab0a1"></a>

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


<a id="org6199f20"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">
    
    -   Pantry management


<a id="org2773390"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="org915c311"></a>

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


<a id="org6cdd833"></a>

### Document Management

-   [X] Scan and OCR all paperwork
-   [X] Extract date and time references (w/ TIMEX3) and integrate with workflow
-   [X] Backup w/ git
-   [X] Export selected documents and folders
-   [ ] Integration of document-related tasks into Workflow Manager


<a id="org4afa77c"></a>

### Financial Planner

-   [X] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
-   [X] Quickly forecast finances almost indefinitely into the future
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships


<a id="orga71280e"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)



# Table of Contents

1.  [The Free Life Planner](#orgf6bffd5)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#org246ce95)
    2.  [Overview](#org2f95086)
    3.  [Status](#org547b8fe)
    4.  [Some Things that the Free Life Planner helps with:](#orgb4a377e)
    5.  [In-Depth Overview](#org186996e)
        1.  [Workflow Manager](#org39cb455)
        2.  [Health](#org9aa27e3)
        3.  [Time Management](#orgd92f0af)
        4.  [Organization](#org093088d)
        5.  [Self-Discipline](#org341978c)
        6.  [Transportation/Shopping/Errands](#org43cdd79)
        7.  [Document Management](#org7e2a3a1)
        8.  [Financial Planner](#org7be7357)
        9.  [Emergency Preparedness](#orge146b97)


<a id="orgf6bffd5"></a>

# The Free Life Planner


<a id="org246ce95"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="org2f95086"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org547b8fe"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgb4a377e"></a>

## Some Things that the Free Life Planner helps with:

-   [Workflow Manager](#org39cb455) (Guides user through all other systems)
-   [Health](#org9aa27e3) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org3a564f0) (Nutrition, Taste, Cost, etc)
-   [Time Management](#orgd92f0af) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org093088d) (Inventory Management)
-   [Self-Discipline](#org341978c) (State Machine)
-   [Paperwork](#org7e2a3a1) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org7be7357) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orge146b97) ()


<a id="org186996e"></a>

## In-Depth Overview


<a id="org39cb455"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org9aa27e3"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org341978c) for dieting
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


<a id="orgd92f0af"></a>

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


<a id="org093088d"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">
    
    -   Pantry management


<a id="org341978c"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="org43cdd79"></a>

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


<a id="org7e2a3a1"></a>

### Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] Extract date and time references (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="org7be7357"></a>

### Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="orge146b97"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


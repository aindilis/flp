
# Table of Contents

1.  [The Free Life Planner](#org448b20a)
    1.  [THIS OVERVIEW PAGE IS UNDER CONSTRUCTION](#orged90c2b)
    2.  [Overview](#orgeb335df)
    3.  [Status](#org7134b07)
    4.  [Some Things that the Free Life Planner helps with:](#orgd1d4ff3)
    5.  [In-Depth Overview](#orgc6904b2)
        1.  [Workflow Manager](#org29a6b91)
        2.  [Health](#org19e1a03)
        3.  [Time Management](#org2ba6c2a)
        4.  [Organization](#org5079b16)
        5.  [Self-Discipline](#org82ad984)
        6.  [Transportation/Shopping/Errands](#org9ddea03)
        7.  [Document Management](#org48c5adc)
        8.  [Financial Planner](#org81bb194)
        9.  [Emergency Preparedness](#org6acd4d5)


<a id="org448b20a"></a>

# The Free Life Planner


<a id="orged90c2b"></a>

## THIS OVERVIEW PAGE IS UNDER CONSTRUCTION


<a id="orgeb335df"></a>

## Overview

-   A life planner that helps
-   Automate almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="org7134b07"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgd1d4ff3"></a>

## Some Things that the Free Life Planner helps with:

-   [Workflow Manager](#org29a6b91) (Guides user through all other systems)
-   [Health](#org19e1a03) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org0614d2d) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org2ba6c2a) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org5079b16) (Inventory Management)
-   [Self-Discipline](#org82ad984) (State Machine)
-   [Paperwork](#org48c5adc) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org81bb194) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org6acd4d5) ()


<a id="orgc6904b2"></a>

## In-Depth Overview


<a id="org29a6b91"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org19e1a03"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org82ad984) for dieting
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


<a id="org2ba6c2a"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planners
    
        -   9 [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) temporal planners
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


<a id="org5079b16"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">
    
    -   Pantry management


<a id="org82ad984"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="org9ddea03"></a>

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


<a id="org48c5adc"></a>

### Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] Extract date and time references (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="org81bb194"></a>

### Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org6acd4d5"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


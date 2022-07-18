
# Table of Contents

1.  [The Free Life Planner](#orgd71fe61)
    1.  [THIS README IS UNDER CONSTRUCTION](#org04054c3)
    2.  [Overview](#org06ba9aa)
    3.  [Status](#orgaff03b7)
    4.  [Some Things that the Free Life Planner helps with:](#orga0977bc)
    5.  [In-Depth Overview](#org7fc25d2)
        1.  [Workflow Manager](#org676f7b1)
        2.  [Health](#org44cacdb)
        3.  [Time Management](#orgb81e725)
        4.  [Organization](#org0dedbb5)
        5.  [Self-Discipline](#org8494fde)
        6.  [Transportation/Shopping/Errands](#org1c0385e)
        7.  [Document Management](#org9df595e)
        8.  [Financial Planner](#org2e46833)
        9.  [Emergency Preparedness](#org61d3991)


<a id="orgd71fe61"></a>

# The Free Life Planner


<a id="org04054c3"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org06ba9aa"></a>

## Overview

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="orgaff03b7"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orga0977bc"></a>

## Some Things that the Free Life Planner helps with:

-   [Workflow Manager](#org676f7b1) (Guides user through all other systems)
-   [Health](#org44cacdb) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#orgd1432af) (Nutrition, Taste, Cost, etc)
-   [Time Management](#orgb81e725) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org0dedbb5) (Inventory Management)
-   [Self-Discipline](#org8494fde) (State Machine)
-   [Paperwork](#org9df595e) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org2e46833) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org61d3991) ()


<a id="org7fc25d2"></a>

## In-Depth Overview


<a id="org676f7b1"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org44cacdb"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org8494fde) for dieting
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


<a id="orgb81e725"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planners
    
        -   9 [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) temporal planners
            -   [X] CLG, Colin2<sub>CLP</sub>, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan522
        -   1 contingent planner
            -   [X] DNFct
        -   [X] More than 200 PDDL life planning domains
        -   [ ] Behavior trees
            -   [ ] Execution of generated (PDDL/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
            -   [ ] Routine domains for life planning
    
    2.  Plan Monitoring
    
        -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org0dedbb5"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">
    
    -   Pantry management


<a id="org8494fde"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="org1c0385e"></a>

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


<a id="org9df595e"></a>

### Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="org2e46833"></a>

### Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org61d3991"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


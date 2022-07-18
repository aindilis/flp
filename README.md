
# Table of Contents

1.  [The Free Life Planner](#orgf59d38c)
    1.  [THIS README IS UNDER CONSTRUCTION](#org032c785)
    2.  [Overview](#org1dd2406)
    3.  [Status](#org67e5a5f)
    4.  [The Free Life Planner helps with:](#org6d6bb06)
    5.  [Nontechnical Overview](#org27a10bb)
        1.  [Workflow Manager](#orge9b4ea3)
        2.  [Health](#org5271a23)
        3.  [Time Management](#org5d5cc7c)
        4.  [Organization](#org614bc3c)
        5.  [Self-Discipline](#orga620051)
        6.  [Transportation/Shopping/Errands](#org2d9a64c)
        7.  [Document Management](#org9cb243a)
        8.  [Financial Planner](#orgbdcd216)
        9.  [Emergency Preparedness](#org6bd5e3c)
    6.  [Technical Overview](#org381b23b)
        1.  [Time Management](#orgdafb716)


<a id="orgf59d38c"></a>

# The Free Life Planner


<a id="org032c785"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org1dd2406"></a>

## Overview

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="org67e5a5f"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org6d6bb06"></a>

## The Free Life Planner helps with:

-   [Workflow Manager](#orge9b4ea3) (Guides user through all other systems)
-   [Health](#org5271a23) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org44f6a02) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org5d5cc7c) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org614bc3c) (Inventory Management)
-   [Self-Discipline](#orga620051) (State Machine)
-   [Paperwork](#org9cb243a) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgbdcd216) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org6bd5e3c) ()


<a id="org27a10bb"></a>

## Nontechnical Overview


<a id="orge9b4ea3"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org5271a23"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#orga620051) for dieting
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


<a id="org5d5cc7c"></a>

### Time Management

1.  Recurrences

2.  Calendaring

3.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planning
    
        -   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) (usually temporal) planning
        -   [X] Contingent planning
        -   [X] Behavior tree reactive planning
        -   [X] [BDI Agent](http://jason.sourceforge.net/)
    
    2.  Plan Monitoring
    
        -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="org614bc3c"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">
    
    -   Pantry management


<a id="orga620051"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="org2d9a64c"></a>

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


<a id="org9cb243a"></a>

### Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgbdcd216"></a>

### Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org6bd5e3c"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="org381b23b"></a>

## Technical Overview


<a id="orgdafb716"></a>

### Time Management

1.  Recurrences

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).

2.  Calendaring

3.  Planning, Scheduling and Execution

    -   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) planning
        -   [X] CLG, Colin2<sub>CLP</sub>, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan<sub>522</sub>
            -   [X] [More than 200 PDDL life planning domains](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/templates)
    -   [X] Contingent planning
        -   [X] DNFct
            -   [X] More than 10 contingent life planning domains
    -   [X] Behavior tree reactive planning
        -   [X] Plan Monitor
            -   [ ] Behavior trees
                -   [ ] Execution of generated (PDDL/AgentSpeak(L)/BT/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
    -   [X] BDI Agent
        -   [X] Jason/AgentSpeak(L) w/ SWIPL integration
            -   [X] [More than 10 BDI domains](https://github.com/aindilis/jason/tree/master/examples)


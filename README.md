
# Table of Contents

1.  [The Free Life Planner](#org5aa87ad)
    1.  [THIS README IS UNDER CONSTRUCTION](#org8732d71)
    2.  [Overview](#orgd323049)
    3.  [Status](#orgff5dbc8)
    4.  [Some Things that the Free Life Planner helps with:](#org281ff2a)
    5.  [In-Depth Overview](#org4da4aa7)
        1.  [Workflow Manager](#orgaddadfe)
        2.  [Health](#orge614b0a)
        3.  [Time Management](#orgacec2a3)
        4.  [Organization](#orgd166917)
        5.  [Self-Discipline](#orgc9b8bf5)
        6.  [Transportation/Shopping/Errands](#org32c8dae)
        7.  [Document Management](#org9d3e3f1)
        8.  [Financial Planner](#org0ac3e8c)
        9.  [Emergency Preparedness](#orgd5aa657)


<a id="org5aa87ad"></a>

# The Free Life Planner


<a id="org8732d71"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orgd323049"></a>

## Overview

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="orgff5dbc8"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org281ff2a"></a>

## Some Things that the Free Life Planner helps with:

-   [Workflow Manager](#orgaddadfe) (Guides user through all other systems)
-   [Health](#orge614b0a) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#orgb0e5898) (Nutrition, Taste, Cost, etc)
-   [Time Management](#orgacec2a3) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orgd166917) (Inventory Management)
-   [Self-Discipline](#orgc9b8bf5) (State Machine)
-   [Paperwork](#org9d3e3f1) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org0ac3e8c) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgd5aa657) ()


<a id="org4da4aa7"></a>

## In-Depth Overview


<a id="orgaddadfe"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="orge614b0a"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#orgc9b8bf5) for dieting
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


<a id="orgacec2a3"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planning
    
        -   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) planning
            -   [X] CLG, Colin2<sub>CLP</sub>, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan<sub>522</sub>
                -   [X] More than 200 PDDL life planning domains
        -   [X] Contingent planning
            -   [X] DNFct
                -   [X] More than 10 contingent life planning domains
        -   [X] Behavior tree reactive planning
            -   [X] Plan Monitor
        -   [X] [BDI Agent](https://github.com/aindilis/jason/tree/master/examples)
            -   [X] Jason/AgentSpeak(L) w/ SWIPL integration
                -   [X] More than 10 BDI domains
    
    2.  Plan Monitoring
    
        -   [ ] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
            -   [ ] Behavior trees
                -   [ ] Execution of generated (PDDL/AgentSpeak(L)/BT/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgd166917"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">
    
    -   Pantry management


<a id="orgc9b8bf5"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="org32c8dae"></a>

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


<a id="org9d3e3f1"></a>

### Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="org0ac3e8c"></a>

### Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="orgd5aa657"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


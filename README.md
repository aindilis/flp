
# Table of Contents

1.  [The Free Life Planner](#org9fa46d5)
    1.  [THIS README IS UNDER CONSTRUCTION](#org76905a3)
    2.  [Overview](#orgc0a89a6)
    3.  [Status](#org35b972d)
    4.  [Some Things that the Free Life Planner helps with:](#orgf3e5a72)
    5.  [In-Depth Overview](#org89f168c)
        1.  [Workflow Manager](#org015a7e4)
        2.  [Health](#orgbd8b0a2)
        3.  [Time Management](#org2fd145d)
        4.  [Organization](#orge951302)
        5.  [Self-Discipline](#org8fb2483)
        6.  [Transportation/Shopping/Errands](#org7f8813b)
        7.  [Document Management](#orgc69e700)
        8.  [Financial Planner](#orgbe579f0)
        9.  [Emergency Preparedness](#orgc1ba222)


<a id="org9fa46d5"></a>

# The Free Life Planner


<a id="org76905a3"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orgc0a89a6"></a>

## Overview

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="org35b972d"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgf3e5a72"></a>

## Some Things that the Free Life Planner helps with:

-   [Workflow Manager](#org015a7e4) (Guides user through all other systems)
-   [Health](#orgbd8b0a2) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org06a11c0) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org2fd145d) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orge951302) (Inventory Management)
-   [Self-Discipline](#org8fb2483) (State Machine)
-   [Paperwork](#orgc69e700) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgbe579f0) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgc1ba222) ()


<a id="org89f168c"></a>

## In-Depth Overview


<a id="org015a7e4"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="orgbd8b0a2"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org8fb2483) for dieting
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


<a id="org2fd145d"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planners
    
        -   9 [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) temporal planners
            -   [X] CLG, Colin2<sub>CLP</sub>, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan522
        -   1 contingent planner
            -   [X] DNFct
        -   [X] More than 200 PDDL life planning domains
        -   [ ] Behavior trees domains for life planning
    
    2.  Plan Monitoring
    
        -   [ ] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
            -   [ ] Behavior trees
                -   [ ] Execution of generated (PDDL/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orge951302"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">
    
    -   Pantry management


<a id="org8fb2483"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="org7f8813b"></a>

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


<a id="orgc69e700"></a>

### Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgbe579f0"></a>

### Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="orgc1ba222"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


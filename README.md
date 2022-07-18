
# Table of Contents

1.  [The Free Life Planner](#org683a593)
    1.  [THIS README IS UNDER CONSTRUCTION](#orgc14d3ed)
    2.  [Overview](#org043c3ca)
    3.  [Status](#orgb68ae4e)
    4.  [The Free Life Planner helps with:](#org09313c4)
    5.  [Nontechnical Overview](#org110d297)
        1.  [Workflow Manager](#orga24a93f)
        2.  [Health](#org16229eb)
        3.  [Time Management](#org96385a3)
        4.  [Organization](#orgc2d448a)
        5.  [Self-Discipline](#org8730fbf)
        6.  [Transportation/Shopping/Errands](#orgc2b75e3)
        7.  [Document Management](#org896ae7f)
        8.  [Financial Planner](#org3ef4e31)
        9.  [Emergency Preparedness](#orgfd63922)
    6.  [Technical Overview](#org508c527)
        1.  [Time Management](#org27e4045)


<a id="org683a593"></a>

# The Free Life Planner


<a id="orgc14d3ed"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org043c3ca"></a>

## Overview

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="orgb68ae4e"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org09313c4"></a>

## The Free Life Planner helps with:

-   [Workflow Manager](#orga24a93f) (Guides user through all other systems)
-   [Health](#org16229eb) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#orgcf998f1) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org96385a3) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orgc2d448a) (Inventory Management)
-   [Self-Discipline](#org8730fbf) (State Machine)
-   [Paperwork](#org896ae7f) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org3ef4e31) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgfd63922) ()


<a id="org110d297"></a>

## Nontechnical Overview


<a id="orga24a93f"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org16229eb"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org8730fbf) for dieting
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


<a id="org96385a3"></a>

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
    
        -   [ ] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
            -   [ ] Behavior trees
                -   [ ] Execution of generated (PDDL/AgentSpeak(L)/BT/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="orgc2d448a"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">
    
    -   Pantry management


<a id="org8730fbf"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="orgc2b75e3"></a>

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


<a id="org896ae7f"></a>

### Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="org3ef4e31"></a>

### Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="orgfd63922"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="org508c527"></a>

## Technical Overview


<a id="org27e4045"></a>

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
    -   [X] BDI Agent
        -   [X] Jason/AgentSpeak(L) w/ SWIPL integration
            -   [X] [More than 10 BDI domains](https://github.com/aindilis/jason/tree/master/examples)


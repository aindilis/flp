
# Table of Contents

1.  [The Free Life Planner](#org29b61b8)
2.  [THIS README IS UNDER CONSTRUCTION](#org96eab26)
3.  [Overview](#orgcfe22c8)
4.  [Status](#org526733c)
5.  [The Free Life Planner helps with:](#org777bb28)
6.  [Overview](#org2a1faaa)
    1.  [Workflow Manager](#org8fb3495)
    2.  [Health](#orge3d2560)
        1.  [Exercise](#orgaddf2e0)
        2.  [Nutrition](#org308f8c4)
        3.  [Doctor's Visits and Orders](#org5d7c4be)
        4.  [Medications](#orgf984532)
    3.  [Time Management](#org4b42153)
        1.  [Recurrences](#org27fcb05)
        2.  [Calendaring](#org1fdc207)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#orge5bedcb)
    4.  [Organization](#orgbf601ed)
        1.  [Inventory Management](#orgefa21cb)
    5.  [Self-Discipline](#org0b0a3c6)
        1.  [Self-Discipline State Machine](#org50f9cd4)
    6.  [Transportation/Shopping/Errands](#org5831f1b)
        1.  [Transportation](#org6ba49eb)
        2.  [Shopping](#orgbaed150)
    7.  [Document Management](#org338c5c9)
    8.  [Financial Planner](#orgf5a9cc6)
    9.  [Emergency Preparedness](#org0e086cc)
7.  [Technical Overview](#orgd57f0c8)
    1.  [Time Management](#org8abd529)
        1.  [Recurrences](#org7a8c9ac)
        2.  [Calendaring](#org5ff5481)
        3.  [Planning, Scheduling and Execution](#org3a20444)


<a id="org29b61b8"></a>

# The Free Life Planner


<a id="org96eab26"></a>

# THIS README IS UNDER CONSTRUCTION


<a id="orgcfe22c8"></a>

# Overview

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="org526733c"></a>

# Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org777bb28"></a>

# The Free Life Planner helps with:

-   [Workflow Manager](#org8fb3495) (Guides user through all other systems)
-   [Health](#orge3d2560) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#orge1930ee) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org4b42153) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orgbf601ed) (Inventory Management)
-   [Self-Discipline](#org0b0a3c6) (State Machine)
-   [Paperwork](#org338c5c9) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgf5a9cc6) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org0e086cc) ()


<a id="org2a1faaa"></a>

# Overview


<a id="org8fb3495"></a>

## Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="orge3d2560"></a>

## Health


<a id="orgaddf2e0"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org308f8c4"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org0b0a3c6) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="org5d7c4be"></a>

### Doctor's Visits and Orders

-   [ ] Tracking visits
-   [ ] Following through on instructions
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system
    -   [ ] Symptom and condition tracker


<a id="orgf984532"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org4b42153"></a>

## Time Management


<a id="org27fcb05"></a>

### Recurrences


<a id="org1fdc207"></a>

### Calendaring


<a id="orge5bedcb"></a>

### Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

1.  Planning

    -   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) (usually temporal) planning
    -   [X] Contingent planning
    -   [X] Behavior tree reactive planning
    -   [X] [BDI Agent](http://jason.sourceforge.net/)

2.  Plan Monitoring

    -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
    -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="orgbf601ed"></a>

## Organization


<a id="orgefa21cb"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="org0b0a3c6"></a>

## Self-Discipline


<a id="org50f9cd4"></a>

### Self-Discipline State Machine


<a id="org5831f1b"></a>

## Transportation/Shopping/Errands


<a id="org6ba49eb"></a>

### Transportation

-   [ ] API mashups
    -   [ ] Hours of operation look-ups
    -   [ ] Route planning
-   [-] Location Logic
    -   [X] [Owntracks](https://owntracks.org/) integration
    -   [ ] Reverse geocoding
    -   [ ] Locational Rules
        -   [ ] e.g. Silence my phone when at any movie theater


<a id="orgbaed150"></a>

### Shopping

-   [ ] Receipt parsers
-   [X] Online order Tracker
    -   [X] Checks against Bank OFX export
-   [X] Online Delivery Tracker
-   [ ] Integration with pantry and inventory management


<a id="org338c5c9"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgf5a9cc6"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org0e086cc"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="orgd57f0c8"></a>

# Technical Overview


<a id="org8abd529"></a>

## Time Management


<a id="org7a8c9ac"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org5ff5481"></a>

### Calendaring


<a id="org3a20444"></a>

### Planning, Scheduling and Execution

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


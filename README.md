
# Table of Contents

1.  [The Free Life Planner](#org9fdcdd6)
    1.  [THIS README IS UNDER CONSTRUCTION](#org6243f5a)
2.  [Introduction](#org73b0661)
3.  [Status](#org72a88d1)
4.  [Summary](#org6892ffe)
5.  [Overview](#org6887449)
    1.  [Workflow Manager](#org540ec9f)
    2.  [Health](#org290c075)
        1.  [Exercise](#orgefe4a98)
        2.  [Nutrition](#org5f5a4ff)
        3.  [Doctor's Visits and Orders](#org967135e)
        4.  [Medications](#orgb2cfdf8)
    3.  [Time Management](#org5e45439)
        1.  [Recurrences](#org3e3315b)
        2.  [Calendaring](#org06873cf)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#org4e24e97)
    4.  [Organization](#org4f5707d)
        1.  [Inventory Management](#orge21fa72)
    5.  [Self-Discipline](#orgaafd548)
        1.  [Self-Discipline State Machine](#org096d499)
    6.  [Transportation/Shopping/Errands](#org8198e53)
        1.  [Transportation](#org93cfa6f)
        2.  [Shopping](#org92f739a)
    7.  [Document Management](#org700739d)
    8.  [Financial Planner](#orgb561db7)
    9.  [Emergency Preparedness](#orgd8a89e8)
6.  [Technical Overview](#orgcb71cfe)
    1.  [Time Management](#orgdeddcd3)
        1.  [Recurrences](#orgc85bbe0)
        2.  [Calendaring](#org71e87d3)
        3.  [Planning, Scheduling and Execution](#org92e0b6f)


<a id="org9fdcdd6"></a>

# The Free Life Planner


<a id="org6243f5a"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org73b0661"></a>

# Introduction

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="org72a88d1"></a>

# Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org6892ffe"></a>

# Summary

-   [Workflow Manager](#org540ec9f) (Guides user through all other systems)
-   [Health](#org290c075) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#orge6ab9b2) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org5e45439) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org4f5707d) (Inventory Management)
-   [Self-Discipline](#orgaafd548) (State Machine)
-   [Paperwork](#org700739d) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgb561db7) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgd8a89e8) ()


<a id="org6887449"></a>

# Overview


<a id="org540ec9f"></a>

## Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org290c075"></a>

## Health


<a id="orgefe4a98"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org5f5a4ff"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#orgaafd548) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="org967135e"></a>

### Doctor's Visits and Orders

-   [ ] Tracking visits
-   [ ] Following through on instructions
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system
    -   [ ] Symptom and condition tracker


<a id="orgb2cfdf8"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org5e45439"></a>

## Time Management


<a id="org3e3315b"></a>

### Recurrences


<a id="org06873cf"></a>

### Calendaring


<a id="org4e24e97"></a>

### Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

1.  Planning

    -   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) (usually temporal) planning
    -   [X] Contingent planning
    -   [X] Behavior tree reactive planning
    -   [X] [BDI Agent](http://jason.sourceforge.net/)

2.  Plan Monitoring

    -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
    -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="org4f5707d"></a>

## Organization


<a id="orge21fa72"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="orgaafd548"></a>

## Self-Discipline


<a id="org096d499"></a>

### Self-Discipline State Machine


<a id="org8198e53"></a>

## Transportation/Shopping/Errands


<a id="org93cfa6f"></a>

### Transportation

-   [ ] API mashups
    -   [ ] Hours of operation look-ups
    -   [ ] Route planning
-   [-] Location Logic
    -   [X] [Owntracks](https://owntracks.org/) integration
    -   [ ] Reverse geocoding
    -   [ ] Locational Rules
        -   [ ] e.g. Silence my phone when at any movie theater


<a id="org92f739a"></a>

### Shopping

-   [ ] Receipt parsers
-   [X] Online order Tracker
    -   [X] Checks against Bank OFX export
-   [X] Online Delivery Tracker
-   [ ] Integration with pantry and inventory management


<a id="org700739d"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgb561db7"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="orgd8a89e8"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="orgcb71cfe"></a>

# Technical Overview


<a id="orgdeddcd3"></a>

## Time Management


<a id="orgc85bbe0"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org71e87d3"></a>

### Calendaring


<a id="org92e0b6f"></a>

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


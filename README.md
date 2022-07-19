
# Table of Contents

1.  [The Free Life Planner](#orgca2bceb)
    1.  [THIS README IS UNDER CONSTRUCTION](#orgf3c6745)
2.  [Introduction](#orgdc01244)
3.  [Status](#org499dac3)
4.  [Summary](#org23744b2)
5.  [Overview](#orgcfc3143)
    1.  [Workflow Manager](#orgd4a5d80)
    2.  [Health](#org4fec3c9)
        1.  [Exercise](#orgae10b49)
        2.  [Nutrition](#org6c22561)
        3.  [Doctor's Visits and Orders](#org8cd16c8)
        4.  [Medications](#orga60d10f)
    3.  [Time Management](#org17dc2a1)
        1.  [Recurrences](#org5c0b410)
        2.  [Calendaring](#orgff865a8)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#org007a432)
    4.  [Organization](#org73ec5bb)
        1.  [Inventory Management](#org04dcdb1)
    5.  [Self-Discipline](#org9cb594d)
        1.  [Self-Discipline State Machine](#org8b8574f)
    6.  [Transportation/Shopping/Errands](#org99ba387)
        1.  [Transportation](#orga506ead)
        2.  [Shopping](#orgc320444)
    7.  [Document Management](#orgf0ccae3)
    8.  [Financial Planner](#org638e9de)
    9.  [Emergency Preparedness](#org20bd9a7)
6.  [Technical Overview](#orga5818db)
    1.  [Health](#orgafb5cc8)
        1.  [Medications](#org571d7ce)
    2.  [Time Management](#orgf123107)
        1.  [Recurrences](#orge5854bc)
        2.  [Calendaring](#org324fc50)
        3.  [Planning, Scheduling and Execution](#org5788c85)
        4.  [Additional Planning System](#org3df5b3e)
    3.  [Organization](#org529b288)
        1.  [Inventory Management](#orge52c5d9)
    4.  [Self-Discipline](#org240e3ed)
        1.  [Self-Discipline State Machine](#org568970e)
    5.  [Transportation/Shopping/Errands](#orgee7ba1d)
    6.  [Document Management](#org72b2b0b)
    7.  [Financial Planner](#org0e6acc6)
    8.  [Emergency Preparedness](#org982c5eb)


<a id="orgca2bceb"></a>

# The Free Life Planner


<a id="orgf3c6745"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orgdc01244"></a>

# Introduction

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="org499dac3"></a>

# Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org23744b2"></a>

# Summary

-   [Workflow Manager](#orgd4a5d80) (Guides user through all other systems)
-   [Health](#org4fec3c9) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org40bbd53) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org17dc2a1) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org73ec5bb) (Inventory Management)
-   [Self-Discipline](#org9cb594d) (State Machine)
-   [Paperwork](#orgf0ccae3) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org638e9de) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org20bd9a7) ()


<a id="orgcfc3143"></a>

# Overview


<a id="orgd4a5d80"></a>

## Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org4fec3c9"></a>

## Health


<a id="orgae10b49"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org6c22561"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org9cb594d) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="org8cd16c8"></a>

### Doctor's Visits and Orders

-   [ ] Tracking visits
-   [ ] [Following through on instructions](#orgf0ccae3)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system
    -   [ ] Symptom and condition tracker


<a id="orga60d10f"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="org17dc2a1"></a>

## Time Management


<a id="org5c0b410"></a>

### Recurrences


<a id="orgff865a8"></a>

### Calendaring


<a id="org007a432"></a>

### Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

1.  Planning

    -   [ ] Workflow Manager
    -   [ ] Metaplanning
    -   [X] Temporal planning
    -   [X] Contingent planning
    -   [X] Behavior tree reactive planning
    -   [X] [BDI reactive planning](http://jason.sourceforge.net/)

2.  Plan Monitoring

    -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
    -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="org73ec5bb"></a>

## Organization


<a id="org04dcdb1"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="org9cb594d"></a>

## Self-Discipline


<a id="org8b8574f"></a>

### Self-Discipline State Machine


<a id="org99ba387"></a>

## Transportation/Shopping/Errands


<a id="orga506ead"></a>

### Transportation

-   [ ] API look-up mashups
    -   [ ] Hours of operation
    -   [ ] Weather
    -   [ ] Route planning
-   [-] Location Logic
    -   [X] [Owntracks](https://owntracks.org/) integration
    -   [ ] Reverse geocoding
    -   [ ] Locational Rules
        -   [ ] e.g. Silence my phone when at any movie theater


<a id="orgc320444"></a>

### Shopping

-   [ ] Receipts
    -   [ ] Parsers and storage for online store receipts
    -   [ ] Parsers for brick and mortar store receipts
        -   [ ] OCR for physical receipts
-   [X] Online order Tracker
    -   [X] Check against OFX export
-   [X] Online Delivery Tracker
-   [ ] Integration with pantry and inventory management


<a id="orgf0ccae3"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="org638e9de"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org20bd9a7"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)

\#####################################################################################################################
\#####################################################################################################################
\#####################################################################################################################


<a id="orga5818db"></a>

# Technical Overview


<a id="orgafb5cc8"></a>

## Health


<a id="org571d7ce"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="orgf123107"></a>

## Time Management


<a id="orge5854bc"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org324fc50"></a>

### Calendaring

1.  Integrations

    -   [ ] Google Calendar
    -   [ ] Org-agenda
    -   [ ] SPSE2
    -   [ ] ICS import


<a id="org5788c85"></a>

### Planning, Scheduling and Execution

-   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) planning
    -   [X] CLG, Colin2<sub>CLP</sub>, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan<sub>522</sub>
        -   [X] [More than 200 PDDL life planning domains](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/templates)
    -   [X] [SPSE2](https://frdcsa.org/visual-aid/pdf/Temporal-Planning-and-Inferencing-for-Personal-Task-Management-with-SPSE2.pdf)
-   [X] Contingent planning
    -   [X] DNFct
        -   [X] More than 10 contingent life planning domains
-   [ ] Behavior tree reactive planning
    -   [ ] Plan Monitor
        -   [ ] Execution of generated (PDDL/AgentSpeak(L)/BT/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
-   [X] BDI Agent
    -   [X] Jason/AgentSpeak(L) w/ SWIPL integration
        -   [X] [More than 10 BDI domains](https://github.com/aindilis/jason/tree/master/examples)


<a id="org3df5b3e"></a>

### Additional Planning System

-   [ ] Do system (todo lists)
-   [ ] Do-Convert system
-   [ ] Factored planning
-   [X] Planning systems
    -   [X] Verber
    -   [X] SPSE2
    -   [X] SPSE2-Formalog
-   [-] Digital twin
    -   [X] World State Monitor
    -   [X] Fitness Manager
    -   [ ] Checklists
-   [ ] Kanban
-   [ ] Goalban
-   [X] User Agenda (for recurrences)
-   [X] Habit tracker
-   [ ] Resource Manager (plans over inventory/etc)
    -   [ ] Productivity Requirements
-   [ ] Subsystem monitoring
    -   [ ] Mission Control
    -   [ ] Normal Form
-   [-] Gamification
    -   [X] Score
    -   [ ] Rewards/Penalties
    -   [X] Manager


<a id="org529b288"></a>

## Organization


<a id="orge52c5d9"></a>

### Inventory Management

-   Pantry management


<a id="org240e3ed"></a>

## Self-Discipline


<a id="org568970e"></a>

### Self-Discipline State Machine


<a id="orgee7ba1d"></a>

## Transportation/Shopping/Errands


<a id="org72b2b0b"></a>

## Document Management


<a id="org0e6acc6"></a>

## Financial Planner


<a id="org982c5eb"></a>

## Emergency Preparedness


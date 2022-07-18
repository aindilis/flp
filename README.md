
# Table of Contents

1.  [The Free Life Planner](#org6fdfcae)
    1.  [THIS README IS UNDER CONSTRUCTION](#orgf378795)
2.  [Introduction](#orgf73cbb9)
3.  [Status](#org35e03bd)
4.  [Summary](#org05c7774)
5.  [Overview](#org620b66e)
    1.  [Workflow Manager](#orga4bf9c3)
    2.  [Health](#orgd8f170b)
        1.  [Exercise](#org6673966)
        2.  [Nutrition](#orgdd6d042)
        3.  [Doctor's Visits and Orders](#org1bfc043)
        4.  [Medications](#org219c745)
    3.  [Time Management](#org5c3808d)
        1.  [Recurrences](#orgb384f4b)
        2.  [Calendaring](#org1e38401)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#orgbb78443)
    4.  [Organization](#org4015a38)
        1.  [Inventory Management](#org26b4ba1)
    5.  [Self-Discipline](#org6e63330)
        1.  [Self-Discipline State Machine](#org06b5079)
    6.  [Transportation/Shopping/Errands](#orge2e9890)
        1.  [Transportation](#orgaff91b7)
        2.  [Shopping](#org2a94ad8)
    7.  [Document Management](#orgf2082fd)
    8.  [Financial Planner](#org49a7bb5)
    9.  [Emergency Preparedness](#org4127bfa)
6.  [Technical Overview](#org6d13136)
    1.  [Health](#org0580639)
        1.  [Medications](#orga6c4137)
    2.  [Time Management](#org8c9446d)
        1.  [Recurrences](#org279af57)
        2.  [Calendaring](#orgb9af82e)
        3.  [Planning, Scheduling and Execution](#orgbf1fef8)


<a id="org6fdfcae"></a>

# The Free Life Planner


<a id="orgf378795"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orgf73cbb9"></a>

# Introduction

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="org35e03bd"></a>

# Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org05c7774"></a>

# Summary

-   [Workflow Manager](#orga4bf9c3) (Guides user through all other systems)
-   [Health](#orgd8f170b) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org3b3a6c3) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org5c3808d) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org4015a38) (Inventory Management)
-   [Self-Discipline](#org6e63330) (State Machine)
-   [Paperwork](#orgf2082fd) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org49a7bb5) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org4127bfa) ()


<a id="org620b66e"></a>

# Overview


<a id="orga4bf9c3"></a>

## Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="orgd8f170b"></a>

## Health


<a id="org6673966"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="orgdd6d042"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org6e63330) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="org1bfc043"></a>

### Doctor's Visits and Orders

-   [ ] Tracking visits
-   [ ] Following through on instructions
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system
    -   [ ] Symptom and condition tracker


<a id="org219c745"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="org5c3808d"></a>

## Time Management


<a id="orgb384f4b"></a>

### Recurrences


<a id="org1e38401"></a>

### Calendaring


<a id="orgbb78443"></a>

### Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

1.  Planning

    -   [X] Temporal planning
    -   [X] Contingent planning
    -   [X] Behavior tree reactive planning
    -   [X] [BDI reactive planning](http://jason.sourceforge.net/)

2.  Plan Monitoring

    -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
    -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="org4015a38"></a>

## Organization


<a id="org26b4ba1"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="org6e63330"></a>

## Self-Discipline


<a id="org06b5079"></a>

### Self-Discipline State Machine


<a id="orge2e9890"></a>

## Transportation/Shopping/Errands


<a id="orgaff91b7"></a>

### Transportation

-   [ ] API mashups
    -   [ ] Hours of operation look-ups
    -   [ ] Route planning
-   [-] Location Logic
    -   [X] [Owntracks](https://owntracks.org/) integration
    -   [ ] Reverse geocoding
    -   [ ] Locational Rules
        -   [ ] e.g. Silence my phone when at any movie theater


<a id="org2a94ad8"></a>

### Shopping

-   [ ] Receipt parsers
-   [X] Online order Tracker
    -   [X] Checks against Bank OFX export
-   [X] Online Delivery Tracker
-   [ ] Integration with pantry and inventory management


<a id="orgf2082fd"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="org49a7bb5"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org4127bfa"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="org6d13136"></a>

# Technical Overview


<a id="org0580639"></a>

## Health


<a id="orga6c4137"></a>

### Medications

[PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org8c9446d"></a>

## Time Management


<a id="org279af57"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgb9af82e"></a>

### Calendaring


<a id="orgbf1fef8"></a>

### Planning, Scheduling and Execution

-   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) planning
    -   [X] CLG, Colin2<sub>CLP</sub>, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan<sub>522</sub>
        -   [X] [More than 200 PDDL life planning domains](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/templates)
-   [X] Contingent planning
    -   [X] DNFct
        -   [X] More than 10 contingent life planning domains
-   [ ] Behavior tree reactive planning
    -   [ ] Plan Monitor
        -   [ ] Execution of generated (PDDL/AgentSpeak(L)/BT/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
-   [X] BDI Agent
    -   [X] Jason/AgentSpeak(L) w/ SWIPL integration
        -   [X] [More than 10 BDI domains](https://github.com/aindilis/jason/tree/master/examples)


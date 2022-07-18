
# Table of Contents

1.  [The Free Life Planner](#org9d5f926)
    1.  [THIS README IS UNDER CONSTRUCTION](#org31fb3f5)
2.  [Introduction](#org03ec23e)
3.  [Status](#orgda335f5)
4.  [Summary](#org6622b90)
5.  [Overview](#orgd2e7a4b)
    1.  [Workflow Manager](#org76cb2f2)
    2.  [Health](#org5660c49)
        1.  [Exercise](#org5d57e79)
        2.  [Nutrition](#org05bf125)
        3.  [Doctor's Visits and Orders](#org8a3c8f7)
        4.  [Medications](#orgf22f4e5)
    3.  [Time Management](#org2ff85bf)
        1.  [Recurrences](#org73b4f4b)
        2.  [Calendaring](#org82627c8)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#org13a6113)
    4.  [Organization](#orgd0cc6f4)
        1.  [Inventory Management](#org9f9347b)
    5.  [Self-Discipline](#orgf255738)
        1.  [Self-Discipline State Machine](#org115da46)
    6.  [Transportation/Shopping/Errands](#org9524774)
        1.  [Transportation](#org1477b14)
        2.  [Shopping](#orge68ea3b)
    7.  [Document Management](#org27b6ea4)
    8.  [Financial Planner](#orgf8a5acc)
    9.  [Emergency Preparedness](#orgaa11f54)
6.  [Technical Overview](#org906d813)
    1.  [Health](#org0d8c315)
        1.  [Medications](#orgfa435fb)
    2.  [Time Management](#orgbae6abd)
        1.  [Recurrences](#org16da114)
        2.  [Calendaring](#org8312bc4)
        3.  [Planning, Scheduling and Execution](#org8173a12)


<a id="org9d5f926"></a>

# The Free Life Planner


<a id="org31fb3f5"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org03ec23e"></a>

# Introduction

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="orgda335f5"></a>

# Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org6622b90"></a>

# Summary

-   [Workflow Manager](#org76cb2f2) (Guides user through all other systems)
-   [Health](#org5660c49) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#orgf4c415f) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org2ff85bf) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orgd0cc6f4) (Inventory Management)
-   [Self-Discipline](#orgf255738) (State Machine)
-   [Paperwork](#org27b6ea4) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgf8a5acc) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgaa11f54) ()


<a id="orgd2e7a4b"></a>

# Overview


<a id="org76cb2f2"></a>

## Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org5660c49"></a>

## Health


<a id="org5d57e79"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org05bf125"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#orgf255738) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="org8a3c8f7"></a>

### Doctor's Visits and Orders

-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org27b6ea4)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system
    -   [ ] Symptom and condition tracker


<a id="orgf22f4e5"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="org2ff85bf"></a>

## Time Management


<a id="org73b4f4b"></a>

### Recurrences


<a id="org82627c8"></a>

### Calendaring


<a id="org13a6113"></a>

### Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

1.  Planning

    -   [X] Temporal planning
    -   [X] Contingent planning
    -   [X] Behavior tree reactive planning
    -   [X] [BDI reactive planning](http://jason.sourceforge.net/)

2.  Plan Monitoring

    -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
    -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="orgd0cc6f4"></a>

## Organization


<a id="org9f9347b"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="orgf255738"></a>

## Self-Discipline


<a id="org115da46"></a>

### Self-Discipline State Machine


<a id="org9524774"></a>

## Transportation/Shopping/Errands


<a id="org1477b14"></a>

### Transportation

-   [ ] API mashups
    -   [ ] Hours of operation look-ups
    -   [ ] Route planning
-   [-] Location Logic
    -   [X] [Owntracks](https://owntracks.org/) integration
    -   [ ] Reverse geocoding
    -   [ ] Locational Rules
        -   [ ] e.g. Silence my phone when at any movie theater


<a id="orge68ea3b"></a>

### Shopping

-   [ ] Receipt parsers
-   [X] Online order Tracker
    -   [X] Checks against Bank OFX export
-   [X] Online Delivery Tracker
-   [ ] Integration with pantry and inventory management


<a id="org27b6ea4"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgf8a5acc"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="orgaa11f54"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="org906d813"></a>

# Technical Overview


<a id="org0d8c315"></a>

## Health


<a id="orgfa435fb"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="orgbae6abd"></a>

## Time Management


<a id="org16da114"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org8312bc4"></a>

### Calendaring


<a id="org8173a12"></a>

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



# Table of Contents

1.  [The Free Life Planner](#orge00de93)
    1.  [THIS README IS UNDER CONSTRUCTION](#orgdfba7a3)
2.  [Introduction](#orgfc80e91)
3.  [Status](#org86ff1ae)
4.  [Summary](#org96305d4)
5.  [Overview](#org66d1b11)
    1.  [Workflow Manager](#org83e488b)
    2.  [Health](#org58c5550)
        1.  [Exercise](#orga552198)
        2.  [Nutrition](#org2392af7)
        3.  [Doctor's Visits and Orders](#org03f4592)
        4.  [Medications](#orgb8f03ec)
    3.  [Time Management](#org6a431e3)
        1.  [Recurrences](#orgd9f6570)
        2.  [Calendaring](#org36c3b19)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#orgca78683)
    4.  [Organization](#org5206ab8)
        1.  [Inventory Management](#org7f7533c)
    5.  [Self-Discipline](#orgf2e5a03)
        1.  [Self-Discipline State Machine](#orga3289b5)
    6.  [Transportation/Shopping/Errands](#org9b449e6)
        1.  [Transportation](#org801394c)
        2.  [Shopping](#org0e484bb)
    7.  [Document Management](#org47b70e8)
    8.  [Financial Planner](#orge43d35c)
    9.  [Emergency Preparedness](#org1d85a8c)


<a id="orge00de93"></a>

# The Free Life Planner


<a id="orgdfba7a3"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orgfc80e91"></a>

# Introduction

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="org86ff1ae"></a>

# Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org96305d4"></a>

# Summary

-   [Workflow Manager](#org83e488b) (Guides user through all other systems)
-   [Health](#org58c5550) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org04814a7) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org6a431e3) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org5206ab8) (Inventory Management)
-   [Self-Discipline](#orgf2e5a03) (State Machine)
-   [Paperwork](#org47b70e8) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orge43d35c) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org1d85a8c) ()


<a id="org66d1b11"></a>

# Overview


<a id="org83e488b"></a>

## Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org58c5550"></a>

## Health


<a id="orga552198"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org2392af7"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#orgf2e5a03) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="org03f4592"></a>

### Doctor's Visits and Orders

-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org47b70e8)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system
    -   [ ] Symptom and condition tracker


<a id="orgb8f03ec"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="org6a431e3"></a>

## Time Management


<a id="orgd9f6570"></a>

### Recurrences


<a id="org36c3b19"></a>

### Calendaring


<a id="orgca78683"></a>

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


<a id="org5206ab8"></a>

## Organization


<a id="org7f7533c"></a>

### Inventory Management

-   Pantry management


<a id="orgf2e5a03"></a>

## Self-Discipline


<a id="orga3289b5"></a>

### Self-Discipline State Machine


<a id="org9b449e6"></a>

## Transportation/Shopping/Errands


<a id="org801394c"></a>

### Transportation

-   [ ] API look-up mashups
    -   [ ] Hours of operation
        -   [ ] Stores/offices/etc
    -   [ ] Weather
    -   [ ] Route planning
-   [-] Location Logic
    -   [X] [Owntracks](https://owntracks.org/) integration
    -   [ ] Reverse geocoding
    -   [ ] Locational Rules
        -   [ ] e.g. [Silence my phone when at any movie theater](http://frdcsa.org/~andrewdo/projects/ll-rules.pl)


<a id="org0e484bb"></a>

### Shopping

-   [ ] Receipts
    -   [ ] Parsers and storage for online store receipts
    -   [ ] Parsers for brick and mortar store receipts
        -   [ ] OCR for physical receipts
-   [X] Online order Tracker
    -   [X] Check against OFX export
-   [X] Online Delivery Tracker
-   [ ] Integration with pantry and inventory management


<a id="org47b70e8"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="orge43d35c"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org1d85a8c"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


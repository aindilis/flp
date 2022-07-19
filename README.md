
# Table of Contents

1.  [The Free Life Planner](#orgfd77af1)
    1.  [THIS README IS UNDER CONSTRUCTION](#orgfc83fea)
2.  [Introduction](#org037a900)
3.  [Status](#org51a8eee)
4.  [Summary](#org860002a)
5.  [Overview](#orga260353)
    1.  [Workflow Manager](#org95394c8)
    2.  [Health](#org021f333)
        1.  [Exercise](#org979b623)
        2.  [Nutrition](#org021f8eb)
        3.  [Doctor's Visits and Orders](#org2bdedad)
        4.  [Medications](#orga616c0e)
    3.  [Time Management](#orgd2ad4ae)
        1.  [Recurrences](#orgbf1f98b)
        2.  [Calendaring](#orgd219828)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#org26084e8)
    4.  [Organization](#org5832cb3)
        1.  [Inventory Management](#orge22cf64)
    5.  [Self-Discipline](#org744be2a)
        1.  [Self-Discipline State Machine](#org2955e62)
    6.  [Transportation/Shopping/Errands](#org55238e8)
        1.  [Transportation](#org63f479d)
        2.  [Shopping](#org899cd37)
    7.  [Document Management](#org440a8bb)
    8.  [Financial Planner](#orgd3055d0)
    9.  [Emergency Preparedness](#org415aea0)


<a id="orgfd77af1"></a>

# The Free Life Planner


<a id="orgfc83fea"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org037a900"></a>

# Introduction

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="org51a8eee"></a>

# Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org860002a"></a>

# Summary

-   [Workflow Manager](#org95394c8) (Guides user through all other systems)
-   [Health](#org021f333) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org4a48dfe) (Nutrition, Taste, Cost, etc)
-   [Time Management](#orgd2ad4ae) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org5832cb3) (Inventory Management)
-   [Self-Discipline](#org744be2a) (State Machine)
-   [Paperwork](#org440a8bb) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgd3055d0) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org415aea0) ()


<a id="orga260353"></a>

# Overview


<a id="org95394c8"></a>

## Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org021f333"></a>

## Health


<a id="org979b623"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org021f8eb"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org744be2a) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="org2bdedad"></a>

### Doctor's Visits and Orders

-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org440a8bb)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system
    -   [ ] Symptom and condition tracker


<a id="orga616c0e"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="orgd2ad4ae"></a>

## Time Management


<a id="orgbf1f98b"></a>

### Recurrences


<a id="orgd219828"></a>

### Calendaring


<a id="org26084e8"></a>

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


<a id="org5832cb3"></a>

## Organization


<a id="orge22cf64"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="org744be2a"></a>

## Self-Discipline


<a id="org2955e62"></a>

### Self-Discipline State Machine


<a id="org55238e8"></a>

## Transportation/Shopping/Errands


<a id="org63f479d"></a>

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


<a id="org899cd37"></a>

### Shopping

-   [ ] Receipts
    -   [ ] Parsers and storage for online store receipts
    -   [ ] Parsers for brick and mortar store receipts
        -   [ ] OCR for physical receipts
-   [X] Online order Tracker
    -   [X] Check against OFX export
-   [X] Online Delivery Tracker
-   [ ] Integration with pantry and inventory management


<a id="org440a8bb"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="orgd3055d0"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org415aea0"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


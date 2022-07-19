
# Table of Contents

1.  [The Free Life Planner](#orgb2f6998)
    1.  [THIS README IS UNDER CONSTRUCTION](#org46537aa)
2.  [Introduction](#orgd8a8397)
3.  [Status](#org5a4e6f3)
4.  [Summary](#orgd2b0ab4)
5.  [Overview](#orgc4eac32)
    1.  [Workflow Manager](#org6fcd7a7)
    2.  [Health](#org35d1033)
        1.  [Exercise](#orgaff4a44)
        2.  [Nutrition](#org60439a7)
        3.  [Doctor's Visits and Orders](#orga181520)
        4.  [Medications](#orgfc5b338)
    3.  [Time Management](#org1e2ca74)
        1.  [Recurrences](#org170faa5)
        2.  [Calendaring](#orgb81df16)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#orgd069885)
    4.  [Organization](#orgc45ab30)
        1.  [Inventory Management](#orgd276aa7)
    5.  [Self-Discipline](#org14b1db9)
        1.  [Self-Discipline State Machine](#orgfd78111)
    6.  [Transportation/Shopping/Errands](#orgcfb23bd)
        1.  [Transportation](#orgfb312f5)
        2.  [Shopping](#orgccdc98a)
    7.  [Document Management](#org002697c)
    8.  [Financial Planner](#orgbb5c51a)
    9.  [Emergency Preparedness](#orgdbef188)


<a id="orgb2f6998"></a>

# The Free Life Planner


<a id="org46537aa"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orgd8a8397"></a>

# Introduction

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="org5a4e6f3"></a>

# Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgd2b0ab4"></a>

# Summary

-   [Workflow Manager](#org6fcd7a7) (Guides user through all other systems)
-   [Health](#org35d1033) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org19fe469) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org1e2ca74) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orgc45ab30) (Inventory Management)
-   [Self-Discipline](#org14b1db9) (State Machine)
-   [Paperwork](#org002697c) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgbb5c51a) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgdbef188) ()


<a id="orgc4eac32"></a>

# Overview


<a id="org6fcd7a7"></a>

## Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org35d1033"></a>

## Health


<a id="orgaff4a44"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org60439a7"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org14b1db9) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="orga181520"></a>

### Doctor's Visits and Orders

-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org002697c)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system
    -   [ ] Symptom and condition tracker


<a id="orgfc5b338"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="org1e2ca74"></a>

## Time Management


<a id="org170faa5"></a>

### Recurrences


<a id="orgb81df16"></a>

### Calendaring


<a id="orgd069885"></a>

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

3.  Some domains

    -   [ ] Planning ahead for inclement weather
        -   [ ] e.g. Stock up on groceries before a major storm hits
        -   [ ] Household emergency preparedness


<a id="orgc45ab30"></a>

## Organization


<a id="orgd276aa7"></a>

### Inventory Management

-   Pantry management


<a id="org14b1db9"></a>

## Self-Discipline


<a id="orgfd78111"></a>

### Self-Discipline State Machine


<a id="orgcfb23bd"></a>

## Transportation/Shopping/Errands


<a id="orgfb312f5"></a>

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


<a id="orgccdc98a"></a>

### Shopping

-   [ ] Receipts
    -   [ ] Parsers and storage for online store receipts
    -   [ ] Parsers for brick and mortar store receipts
        -   [ ] OCR for physical receipts
-   [X] Online order Tracker
    -   [X] Check against OFX export
-   [X] Online Delivery Tracker
-   [ ] Integration with pantry and inventory management


<a id="org002697c"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="orgbb5c51a"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="orgdbef188"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


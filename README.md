
# Table of Contents

1.  [The Free Life Planner](#org611e319)
    1.  [THIS README IS UNDER CONSTRUCTION](#orgbb09728)
    2.  [Overview](#org69e4595)
    3.  [Status](#org1b25d59)
    4.  [Some Things that the Free Life Planner helps with:](#org98bb207)
    5.  [In-Depth Overview](#org0759052)
        1.  [Workflow Manager](#orga3d6003)
        2.  [Health](#org80e64e1)
        3.  [Time Management](#org60ca3c5)
        4.  [Organization](#org9b188e6)
        5.  [Self-Discipline](#orgd26c722)
        6.  [Transportation/Shopping/Errands](#orgdc0ceb6)
        7.  [Document Management](#org8aae22a)
        8.  [Financial Planner](#orgea4c29e)
        9.  [Emergency Preparedness](#orgc519b2d)


<a id="org611e319"></a>

# The Free Life Planner


<a id="orgbb09728"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org69e4595"></a>

## Overview

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="org1b25d59"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org98bb207"></a>

## Some Things that the Free Life Planner helps with:

-   [Workflow Manager](#orga3d6003) (Guides user through all other systems)
-   [Health](#org80e64e1) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#orga5551e6) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org60ca3c5) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org9b188e6) (Inventory Management)
-   [Self-Discipline](#orgd26c722) (State Machine)
-   [Paperwork](#org8aae22a) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgea4c29e) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgc519b2d) ()


<a id="org0759052"></a>

## In-Depth Overview


<a id="orga3d6003"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org80e64e1"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#orgd26c722) for dieting
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


<a id="org60ca3c5"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planners
    
        -   9 [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) temporal planners
            -   [X] CLG, Colin2<sub>CLP</sub>, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan522
        -   1 contingent planner
            -   [X] DNFct
        -   [X] More than 200 life planning domains
    
    2.  Plan Monitoring
    
        -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org9b188e6"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">
    
    -   Pantry management


<a id="orgd26c722"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="orgdc0ceb6"></a>

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


<a id="org8aae22a"></a>

### Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgea4c29e"></a>

### Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="orgc519b2d"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


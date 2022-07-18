
# Table of Contents

1.  [The Free Life Planner](#org6e5ae79)
    1.  [THIS README IS UNDER CONSTRUCTION](#org236279e)
    2.  [Overview](#orga7d85fd)
    3.  [Status](#orgceb3fe3)
    4.  [Some Things that the Free Life Planner helps with:](#orgfd5bbe4)
    5.  [Nontechnical Overview](#org03e740b)
        1.  [Workflow Manager](#orga2a3ce9)
        2.  [Health](#orgfbfbadd)
        3.  [Time Management](#orgbb4ece5)
        4.  [Organization](#orgc701734)
        5.  [Self-Discipline](#org13c4357)
        6.  [Transportation/Shopping/Errands](#org6802dff)
        7.  [Document Management](#org4252700)
        8.  [Financial Planner](#orgf24399a)
        9.  [Emergency Preparedness](#org20b8159)
    6.  [Technical Overview](#orgb7b359d)
        1.  [Planning](#orgdc55ccb)


<a id="org6e5ae79"></a>

# The Free Life Planner


<a id="org236279e"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orga7d85fd"></a>

## Overview

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function
-   Sample use cases
    -   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
    -   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)


<a id="orgceb3fe3"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgfd5bbe4"></a>

## Some Things that the Free Life Planner helps with:

-   [Workflow Manager](#orga2a3ce9) (Guides user through all other systems)
-   [Health](#orgfbfbadd) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org5a40934) (Nutrition, Taste, Cost, etc)
-   [Time Management](#orgbb4ece5) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orgc701734) (Inventory Management)
-   [Self-Discipline](#org13c4357) (State Machine)
-   [Paperwork](#org4252700) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgf24399a) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org20b8159) ()


<a id="org03e740b"></a>

## Nontechnical Overview


<a id="orga2a3ce9"></a>

### Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="orgfbfbadd"></a>

### Health

1.  Exercise

    -   [X] Fitness Manager
    -   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"

2.  Nutrition

    1.  Meal Planner
    
        -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] Improves nutrition and taste
        -   [ ] Reduces cost and prep time 4X
        -   [ ] [Self-Discipline](#org13c4357) for dieting
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


<a id="orgbb4ece5"></a>

### Time Management

1.  Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

    1.  Planning
    
        -   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) planning
        -   [X] Contingent planning
        -   [X] Behavior tree reactive planning
        -   [X] [BDI Agent](http://jason.sourceforge.net/)
    
    2.  Plan Monitoring
    
        -   [ ] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
            -   [ ] Behavior trees
                -   [ ] Execution of generated (PDDL/AgentSpeak(L)/BT/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
        -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)

2.  Recurrence System

    How to schedule something for the last day of every month:
    
        hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgc701734"></a>

### Organization

1.  Inventory Management

    <img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">
    
    -   Pantry management


<a id="org13c4357"></a>

### Self-Discipline

1.  Self-Discipline State Machine


<a id="org6802dff"></a>

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


<a id="org4252700"></a>

### Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3) and integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [ ] Integration of document-related tasks into Workflow Manager


<a id="orgf24399a"></a>

### Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org20b8159"></a>

### Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="orgb7b359d"></a>

## Technical Overview


<a id="orgdc55ccb"></a>

### Planning

-   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) planning
    -   [X] CLG, Colin2<sub>CLP</sub>, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan<sub>522</sub>
        -   [X] [More than 200 PDDL life planning domains](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/templates)
-   [X] Contingent planning
    -   [X] DNFct
        -   [X] More than 10 contingent life planning domains
-   [X] Behavior tree reactive planning
    -   [X] Plan Monitor
-   [X] [BDI Agent](https://github.com/aindilis/jason/tree/master/examples)
    -   [X] Jason/AgentSpeak(L) w/ SWIPL integration
        -   [X] [More than 10 BDI domains](https://github.com/aindilis/jason/tree/master/examples)


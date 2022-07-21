
# Table of Contents

1.  [The Free Life Planner](#org4e2c71e)
    1.  [THIS README IS UNDER CONSTRUCTION](#org0f68f72)
2.  [Introduction](#org7a65e40)
    1.  [Purpose](#org6eca506)
    2.  [Sample use cases](#org1b22dfc)
    3.  [Status](#org3ad4c25)
    4.  [Summary](#orgcf720f7)
3.  [General Overview](#org37d82d1)
    1.  [Workflow Manager](#orgadf18ae)
    2.  [Health](#org93220e1)
        1.  [Exercise](#orgd748759)
        2.  [Nutrition](#orge9a489f)
        3.  [Doctor's Visits and Orders](#org22ed5ae)
        4.  [Medications](#org31d3bce)
    3.  [Time Management](#org151f202)
        1.  [Recurrences](#orga4ffcdf)
        2.  [Calendaring](#org623b9a6)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#orgea38aff)
    4.  [Organization](#org7890c03)
        1.  [Inventory Management](#orgec92f92)
        2.  [Communication Management](#org2e25d4c)
        3.  [Chore Charting](#org1ffcc16)
    5.  [Self-Discipline](#orgc67252f)
        1.  [Self-Discipline State Machine](#org15f58da)
        2.  [Gamification](#org6c2d3e6)
        3.  [Movement Discipline](#orgc610a6e)
    6.  [Transportation/Shopping/Errands](#org16f087e)
        1.  [Transportation](#org29a7355)
        2.  [Shopping/Errands](#orge3464ae)
    7.  [Document Management](#org7810c2f)
    8.  [Financial Planner](#orgb87ebd5)
    9.  [Emergency Preparedness](#org8c78829)
4.  [More Info](#orgdd1256f)
    1.  [More Use Cases](#orgc6e3922)
    2.  [User Base](#orgc8f6f2f)
    3.  [Links](#orgd8374bd)
5.  [Technical Overview](#org36f331e)
    1.  [Workflow Manager](#org1008501)
    2.  [Health](#org95d50a5)
        1.  [Exercise](#org34c0684)
        2.  [Nutrition](#org06aedc1)
        3.  [Medications](#org30ec2fd)
    3.  [Time Management](#org5c82330)
        1.  [Recurrences](#org089dbb4)
        2.  [Calendaring](#org0d856e5)
        3.  [Planning, Scheduling and Execution](#org0c4288c)
    4.  [Organization](#org4328cba)
        1.  [Inventory Management](#orgd52cf1f)
    5.  [Self-Discipline](#orge19977d)
        1.  [Self-Discipline State Machine](#orgf2459b4)
    6.  [Transportation/Shopping/Errands](#org57e8311)
        1.  [Transportation](#orgccccb9b)
        2.  [Shopping/Errands](#org95ac6a5)
    7.  [Document Management](#org1810338)
    8.  [Financial Planner](#org8a849a8)
    9.  [Emergency Preparedness](#orga6d6486)
6.  [Technologies Most Used](#orgf6583b1)


<a id="org4e2c71e"></a>

# The Free Life Planner


<a id="org0f68f72"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org7a65e40"></a>

# Introduction


<a id="org6eca506"></a>

## Purpose

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org1b22dfc"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#orgc6e3922)


<a id="org3ad4c25"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgcf720f7"></a>

## Summary

-   [Workflow Manager](#orgadf18ae) (Guides user through all other systems)
-   [Health](#org93220e1) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org9acbee6) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org151f202) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org7890c03) (Inventory Management)
-   [Self-Discipline](#orgc67252f) (State Machine)
-   [Paperwork](#org7810c2f) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgb87ebd5) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org8c78829) ()


<a id="org37d82d1"></a>

# General Overview


<a id="orgadf18ae"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks


<a id="org93220e1"></a>

## Health


<a id="orgd748759"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="orge9a489f"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#orgc67252f) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="org22ed5ae"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] Patient advocate
-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org7810c2f)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="org31d3bce"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="org151f202"></a>

## Time Management


<a id="orga4ffcdf"></a>

### Recurrences


<a id="org623b9a6"></a>

### Calendaring


<a id="orgea38aff"></a>

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


<a id="org7890c03"></a>

## Organization


<a id="orgec92f92"></a>

### Inventory Management

-   Pantry management


<a id="org2e25d4c"></a>

### Communication Management

-   Pantry management


<a id="org1ffcc16"></a>

### Chore Charting


<a id="orgc67252f"></a>

## Self-Discipline


<a id="org15f58da"></a>

### Self-Discipline State Machine


<a id="org6c2d3e6"></a>

### Gamification


<a id="orgc610a6e"></a>

### Movement Discipline


<a id="org16f087e"></a>

## Transportation/Shopping/Errands


<a id="org29a7355"></a>

### Transportation


<a id="orge3464ae"></a>

### Shopping/Errands


<a id="org7810c2f"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="orgb87ebd5"></a>

## Financial Planner


<a id="org8c78829"></a>

## Emergency Preparedness


<a id="orgdd1256f"></a>

# More Info


<a id="orgc6e3922"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to your doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on your taxes, and to change your air filter
-   Telling you that a particular plan of yours violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="orgc8f6f2f"></a>

## User Base

-   Everyone
-   People with disabilities such as pervasive developmental disorders
-   People in poverty who are one misstep from disaster
-   People with unwieldy illnesses
-   People who are homeless


<a id="orgd8374bd"></a>

## Links

-   Here is the main FLP code site:

<https://github.com/aindilis/free-life-planner>

-   Here is the release of FRDCSA Panoply Git VM (containing older and stripped down versions of FRDCSA and Free Life Planner):

<https://github.com/aindilis/frdcsa-panoply-git-20200329>

-   Here is a story describing the Free Life Planner:

<https://frdcsa.org/~andrewdo/writings/homeless-story.html>

-   Here is the most recent talk on FLP.

<https://ontologforum.org/index.php/ConferenceCall_2022_04_20>

-   Here is the beginning of the release of FRDCSA (marking the Panoply release the official public release and deeming the last five years of work the "private" version of FRDCSA, and backporting from private to public as able):

<https://github.com/aindilis/frdcsa-installer>

-   Here is a recent talk from EmacsConf2019 about FRDCSA/FLP/Panoply:

<https://frdcsa.org/~andrewdo/frdcsa-emacsconf2019-final.webm>

-   Here is an independent codebase (no dependencies on FRDCSA) for interactive plan monitoring:

<https://github.com/aindilis/plan-monitor>

-   Here is some more recent work on the Interactive Execution Monitor:

<https://frdcsa.org/~andrewdo/iem2-2.mp4>
<https://frdcsa.org/~andrewdo/iem2-3.mp4>

-   Here is a video of an older, much smaller and simpler version of the FLP booting up (be careful, noisy):

<https://www.youtube.com/watch?v=t_dCAlf26LE>

-   Here is the beginning of a paper on FLP:

<https://frdcsa.org/~andrewdo/pioneer/wk1/flp.pdf>

-   and one on FRDCSA:

<https://frdcsa.org/~andrewdo/pioneer/wk1/frdcsa.pdf>

-   Here is a paper on the SPSE2 subsystem, an early planning system for FRDCSA which inspired parts of FLP:

<https://frdcsa.org/visual-aid/pdf/Temporal-Planning-and-Inferencing-for-Personal-Task-Management-with-SPSE2.pdf>

-   Here is a link to the financial planning submodule:

<https://github.com/aindilis/financial-planning#projected-transactions-for-florence-tucker>

-   Here is a link to the meal planning submodule:

<https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html>

-   Here is a video which shows some progress on the planner systems and also later the meal planner:

<https://www.youtube.com/watch?v=XZh_tHNboCI&t=15s>

-   Here are some earlier documents about the FLP:

<https://frdcsa.org/~andrewdo/writings/News-Challenge-2.html>
<https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanningCoachSoftware.html>
<https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanningCoachSoftwareUpdate.html>
<https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanner.html>

-   Here is the README for Panoply/FRDCSA:

<https://frdcsa.org/~andrewdo/writings/README.html>

-   Here is the project blog:

<https://facebook.com/frdcsa>

-   Here is the LogicMOO system mentioned in the EmacsConf video, which FLP draws heavily upon and intends to integrate with eventually:

<https://github.com/TeamSPoon/prologmud/wiki>

-   And here the design docs for LogicMOO:

<https://drive.google.com/drive/#folders/0B0QA19UX0ehlV1ZEaXEzc3hjTWM>


<a id="org36f331e"></a>

# Technical Overview


<a id="org1008501"></a>

## Workflow Manager

-   [ ] e.g.
    
        'move-to-page'(begin,'user-agenda').  
        'complete-task'('mark-off-all-completed-from-agenda').  
        'complete-task'('sort-agenda').  
        'finish-page'('user-agenda').


<a id="org95d50a5"></a>

## Health


<a id="org34c0684"></a>

### Exercise


<a id="org06aedc1"></a>

### Nutrition

1.  Meal Planner


<a id="org30ec2fd"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org5c82330"></a>

## Time Management


<a id="org089dbb4"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org0d856e5"></a>

### Calendaring

1.  Integrations

    -   [X] Import from
        -   [X] Org-agenda
        -   [X] SPSE2
        -   [X] Google Calendar
        -   [X] ICS
    -   [ ] Export to
        -   [ ] Org-agenda
        -   [ ] SPSE2
        -   [ ] Google Calendar
        -   [ ] ICS


<a id="org0c4288c"></a>

### Planning, Scheduling and Execution

1.  Planners

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

2.  Additional Planning System

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

3.  Some domains

    -   [ ] Plan cycles (cycle)
    -   [X] Standard domain library (BASEKB)
        -   [X] agent, biomaintenance, chores, deontic, economic, food, hygiene, misc, security, space, tool, work
    -   [ ] Household emergency preparedness
        -   [ ] Planning ahead for inclement weather
            -   [ ] e.g. Stock up on groceries before a major storm hits


<a id="org4328cba"></a>

## Organization


<a id="orgd52cf1f"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="orge19977d"></a>

## Self-Discipline


<a id="orgf2459b4"></a>

### Self-Discipline State Machine


<a id="org57e8311"></a>

## Transportation/Shopping/Errands


<a id="orgccccb9b"></a>

### Transportation

-   [ ] API look-up mashups
    -   [ ] Hours of operation
        -   [ ] Stores/offices/etc
    -   [ ] Weather
    -   [ ] Route planning
    -   [ ] Reverse geocoding
-   [-] Location Logic
    -   [X] [Owntracks](https://owntracks.org/) integration
    -   [ ] Locational Rules
        -   [ ] e.g. [Silence my phone when at any movie theater](http://frdcsa.org/~andrewdo/projects/ll-rules.pl)
            
                performAction(addToPendingTasks(unsilenceCellPhoneWhenLeavingMovieTheaters)) :-
                	leaving(Agent,Location),
                	isa(Location,movieTheater),
                	hasPerformedAction(Agent,silenceCellPhoneAtMovieTheater).

-   [X] Movement Discipline


<a id="org95ac6a5"></a>

### Shopping/Errands

-   [X] Shopping List Management
-   [X] Integration with financial management
    -   [X] OFX cross-referencing
-   [ ] Integration with inventory and pantry management
-   [-] Buying
    -   [ ] Broker - Purchase Decision Support System
        -   [ ] Argumentation
            -   [ ] Decide what to purchase
            -   [ ] Decide whether to purchase
    -   [X] Online Shopping
        -   [X] Receipts
            -   [X] Parsers and storage for online store receipts
        -   [X] Online order tracker
        -   [X] Online delivery tracker
    -   [-] Brick and Mortar Shopping
        -   [X] Receipts
            -   [X] Parsers for brick and mortar store receipts
            -   [X] OCR for physical receipts
        -   [ ] "Traveling Salesmen" route planning
            -   [ ] [Open Route Service API (optimization) integration](https://openrouteservice.org/)
-   [-] Selling
    -   [ ] Broker - personal selling system
        -   [ ] Argumentation
            -   [ ] Decide what to sell
            -   [ ] Decide whether to sell
    -   [X] [SHOPS](https://frdcsa.org/frdcsa/internal/shops) point of sale system (for businesses)


<a id="org1810338"></a>

## Document Management


<a id="org8a849a8"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
        -   [ ] Specify recurring transactions
        -   [ ] Automatically detect recurring transactions from OFX exports and plan for them
            -   e.g. promiseToPayForSpec('ELEC',andrewDougherty,'<ELECTRICCOMPANY>',dollars(93.00),[can([1]),not(onTime([3])))).
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="orga6d6486"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="orgf6583b1"></a>

# Technologies Most Used

-   [X] SWI-Prolog
    -   Julian time library
-   [X] Perl    
    -   [X] YASWI Perl<->SWI-Prolog Interface
    -   [X] Catalyst CMS
        -   [X] ShinyCMS
-   [X] Java
    -   [X] JavaPengines (Java<->SWI-Prolog)
    -   [X] Jason/AgentSpeak(L)
        -   [X] JPL Java<->SWI-Prolog
    -   [X] Alexa voice skill interface
-   [X] PDDL 2.2 temporal metric planning
    -   [X] LPG-td-1.0
    -   [X] OPTIC<sub>CLP</sub>


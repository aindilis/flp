
# Table of Contents

1.  [The Free Life Planner](#org1b58cf4)
    1.  [THIS README IS UNDER CONSTRUCTION](#orgbc80bbc)
2.  [Introduction](#orgc227da4)
    1.  [Purpose](#org1f8e4fa)
    2.  [Sample use cases](#org803fa5a)
    3.  [Status](#org21b981e)
    4.  [Summary](#orgcd5f707)
3.  [General Overview](#org1f43ef3)
    1.  [Workflow Manager](#org5509cde)
    2.  [Health](#org0f9e4f1)
        1.  [Exercise](#org22c7ea4)
        2.  [Nutrition](#org3abda36)
        3.  [Doctor's Visits and Orders](#org06aee75)
        4.  [Medications](#org00f2daa)
    3.  [Time Management](#orgc80f704)
        1.  [Recurrences](#org25f1648)
        2.  [Calendaring](#org1027a73)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#org6e389cb)
    4.  [Organization](#org00a4e90)
        1.  [Inventory Management](#org9296f66)
        2.  [Communication Management](#org694ad88)
    5.  [Self-Discipline](#org188f81b)
        1.  [Self-Discipline State Machine](#orgf8b3bee)
        2.  [Gamification](#orgf96d26a)
        3.  [Movement Discipline](#orgbd966f5)
    6.  [Transportation/Shopping/Errands](#orgfe30319)
        1.  [Transportation](#org992433c)
        2.  [Shopping/Errands](#org104bced)
    7.  [Document Management](#org3f3b037)
    8.  [Financial Planner](#org90b6026)
    9.  [Emergency Preparedness](#orgbf87275)
4.  [More Info](#orgfcd71f8)
    1.  [More Use Cases](#org8869419)
    2.  [User Base](#org950266f)
    3.  [Links](#orgd1610e8)
5.  [Technical Overview](#org7a85101)
    1.  [Workflow Manager](#orga8d3190)
    2.  [Health](#org32829d9)
        1.  [Medications](#org6586238)
    3.  [Time Management](#org24933d7)
        1.  [Recurrences](#org8faf097)
        2.  [Calendaring](#org6e48188)
        3.  [Planning, Scheduling and Execution](#org175a004)
    4.  [Organization](#org1337c33)
        1.  [Inventory Management](#org001e712)
    5.  [Self-Discipline](#orgda891ec)
        1.  [Self-Discipline State Machine](#orgfe10c61)
    6.  [Transportation/Shopping/Errands](#org5e9e16f)
        1.  [Transportation](#org3e67354)
        2.  [Shopping/Errands](#org8d1d48d)
    7.  [Document Management](#org0e1c43c)
    8.  [Financial Planner](#orge4cb0bc)
    9.  [Emergency Preparedness](#org9634ee1)
6.  [Technologies Most Used](#org81b8bc2)


<a id="org1b58cf4"></a>

# The Free Life Planner


<a id="orgbc80bbc"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orgc227da4"></a>

# Introduction


<a id="org1f8e4fa"></a>

## Purpose

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org803fa5a"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#org8869419)


<a id="org21b981e"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgcd5f707"></a>

## Summary

-   [Workflow Manager](#org5509cde) (Guides user through all other systems)
-   [Health](#org0f9e4f1) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org71b3716) (Nutrition, Taste, Cost, etc)
-   [Time Management](#orgc80f704) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org00a4e90) (Inventory Management)
-   [Self-Discipline](#org188f81b) (State Machine)
-   [Paperwork](#org3f3b037) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org90b6026) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgbf87275) ()


<a id="org1f43ef3"></a>

# General Overview


<a id="org5509cde"></a>

## Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org0f9e4f1"></a>

## Health


<a id="org22c7ea4"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org3abda36"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org188f81b) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="org06aee75"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] Patient advocate
-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org3f3b037)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="org00f2daa"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="orgc80f704"></a>

## Time Management


<a id="org25f1648"></a>

### Recurrences


<a id="org1027a73"></a>

### Calendaring


<a id="org6e389cb"></a>

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


<a id="org00a4e90"></a>

## Organization


<a id="org9296f66"></a>

### Inventory Management

-   Pantry management


<a id="org694ad88"></a>

### Communication Management

-   Pantry management


<a id="org188f81b"></a>

## Self-Discipline


<a id="orgf8b3bee"></a>

### Self-Discipline State Machine


<a id="orgf96d26a"></a>

### Gamification


<a id="orgbd966f5"></a>

### Movement Discipline


<a id="orgfe30319"></a>

## Transportation/Shopping/Errands


<a id="org992433c"></a>

### Transportation


<a id="org104bced"></a>

### Shopping/Errands


<a id="org3f3b037"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="org90b6026"></a>

## Financial Planner


<a id="orgbf87275"></a>

## Emergency Preparedness


<a id="orgfcd71f8"></a>

# More Info


<a id="org8869419"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives.
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need.
-   Remembering that when you finish filling out some particular paperwork, to send a copy to your doctor.
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them.
-   Reminding you to work on your taxes, and to change your air filter.
-   Telling you that a particular plan of yours violates various moral and ethical constraints.
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through.


<a id="org950266f"></a>

## User Base

-   Everyone
-   People with disabilities such as pervasive developmental disorders.
-   People in poverty who are one misstep from disaster.
-   People with unwieldy illnesses.
-   People who are homeless.


<a id="orgd1610e8"></a>

## Links

-   [Technical Overview](https://github.com/aindilis/flp/blob/main/Manual.md)

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


<a id="org7a85101"></a>

# Technical Overview


<a id="orga8d3190"></a>

## Workflow Manager


<a id="org32829d9"></a>

## Health


<a id="org6586238"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org24933d7"></a>

## Time Management


<a id="org8faf097"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org6e48188"></a>

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


<a id="org175a004"></a>

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


<a id="org1337c33"></a>

## Organization


<a id="org001e712"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="orgda891ec"></a>

## Self-Discipline


<a id="orgfe10c61"></a>

### Self-Discipline State Machine


<a id="org5e9e16f"></a>

## Transportation/Shopping/Errands


<a id="org3e67354"></a>

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
-   [X] Movement Discipline


<a id="org8d1d48d"></a>

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


<a id="org0e1c43c"></a>

## Document Management


<a id="orge4cb0bc"></a>

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


<a id="org9634ee1"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="org81b8bc2"></a>

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


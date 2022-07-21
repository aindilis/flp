
# Table of Contents

1.  [The Free Life Planner](#orgcb1a5f5)
    1.  [THIS README IS UNDER CONSTRUCTION](#org6618d87)
2.  [Introduction](#org8bf03f7)
    1.  [Purpose](#org8ef1e06)
    2.  [Sample use cases](#org2249432)
    3.  [Status](#orgb720640)
    4.  [Summary](#org1cd2285)
3.  [General Overview](#orgf6810fd)
    1.  [Workflow Manager](#orgb39dbfa)
    2.  [Health](#org52d183e)
        1.  [Exercise](#org7c31db0)
        2.  [Nutrition](#org587909c)
        3.  [Doctor's Visits and Orders](#org0a49df7)
        4.  [Medications](#orgbe14fc9)
    3.  [Time Management](#org811c02e)
        1.  [Recurrences](#org81ccef0)
        2.  [Calendaring](#orgb01cf0b)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#org2b774cd)
    4.  [Organization](#orgd322a25)
        1.  [Inventory Management](#orgfe8fc35)
        2.  [Communication Management](#orgecc1607)
        3.  [Chore Charting](#orgd1201bb)
    5.  [Self-Discipline](#org60443de)
        1.  [Self-Discipline State Machine](#orgfa84bc4)
        2.  [Gamification](#orgb96c8d2)
        3.  [Movement Discipline](#orgc824e8b)
    6.  [Transportation/Shopping/Errands](#org79b110b)
        1.  [Transportation](#org5e70c3a)
        2.  [Shopping/Errands](#org6539620)
    7.  [Document Management](#orgc6ea06f)
    8.  [Financial Planner](#orgea2cb11)
    9.  [Emergency Preparedness](#org230d89a)
4.  [More Info](#org547557b)
    1.  [More Use Cases](#orga592c6e)
    2.  [User Base](#org35a84ec)
    3.  [Links](#orgdad8bd0)
5.  [Technical Overview](#orgc3cc39f)
    1.  [Workflow Manager](#orgf3dca9c)
    2.  [Health](#orgb0dfe09)
        1.  [Medications](#org8b90aec)
    3.  [Time Management](#orga4d0494)
        1.  [Recurrences](#org85cee09)
        2.  [Calendaring](#org9aab852)
        3.  [Planning, Scheduling and Execution](#org8b9bac1)
    4.  [Organization](#orgda32092)
        1.  [Inventory Management](#org598b64a)
    5.  [Self-Discipline](#orge788b1c)
        1.  [Self-Discipline State Machine](#orgebd8a23)
    6.  [Transportation/Shopping/Errands](#orgf0fca28)
        1.  [Transportation](#org4470780)
        2.  [Shopping/Errands](#org50275ea)
    7.  [Document Management](#org08bc9a3)
    8.  [Financial Planner](#org0fddeb8)
    9.  [Emergency Preparedness](#org68a7a8f)
6.  [Technologies Most Used](#orga6b049f)


<a id="orgcb1a5f5"></a>

# The Free Life Planner


<a id="org6618d87"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org8bf03f7"></a>

# Introduction


<a id="org8ef1e06"></a>

## Purpose

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org2249432"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#orga592c6e)


<a id="orgb720640"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org1cd2285"></a>

## Summary

-   [Workflow Manager](#orgb39dbfa) (Guides user through all other systems)
-   [Health](#org52d183e) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org454f570) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org811c02e) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orgd322a25) (Inventory Management)
-   [Self-Discipline](#org60443de) (State Machine)
-   [Paperwork](#orgc6ea06f) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgea2cb11) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org230d89a) ()


<a id="orgf6810fd"></a>

# General Overview


<a id="orgb39dbfa"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks


<a id="org52d183e"></a>

## Health


<a id="org7c31db0"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org587909c"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org60443de) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="org0a49df7"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] Patient advocate
-   [ ] Tracking visits
-   [ ] [Following through on instructions](#orgc6ea06f)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="orgbe14fc9"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="org811c02e"></a>

## Time Management


<a id="org81ccef0"></a>

### Recurrences


<a id="orgb01cf0b"></a>

### Calendaring


<a id="org2b774cd"></a>

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


<a id="orgd322a25"></a>

## Organization


<a id="orgfe8fc35"></a>

### Inventory Management

-   Pantry management


<a id="orgecc1607"></a>

### Communication Management

-   Pantry management


<a id="orgd1201bb"></a>

### Chore Charting


<a id="org60443de"></a>

## Self-Discipline


<a id="orgfa84bc4"></a>

### Self-Discipline State Machine


<a id="orgb96c8d2"></a>

### Gamification


<a id="orgc824e8b"></a>

### Movement Discipline


<a id="org79b110b"></a>

## Transportation/Shopping/Errands


<a id="org5e70c3a"></a>

### Transportation


<a id="org6539620"></a>

### Shopping/Errands


<a id="orgc6ea06f"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="orgea2cb11"></a>

## Financial Planner


<a id="org230d89a"></a>

## Emergency Preparedness


<a id="org547557b"></a>

# More Info


<a id="orga592c6e"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives.
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need.
-   Remembering that when you finish filling out some particular paperwork, to send a copy to your doctor.
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them.
-   Reminding you to work on your taxes, and to change your air filter.
-   Telling you that a particular plan of yours violates various moral and ethical constraints.
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through.


<a id="org35a84ec"></a>

## User Base

-   Everyone
-   People with disabilities such as pervasive developmental disorders.
-   People in poverty who are one misstep from disaster.
-   People with unwieldy illnesses.
-   People who are homeless.


<a id="orgdad8bd0"></a>

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


<a id="orgc3cc39f"></a>

# Technical Overview


<a id="orgf3dca9c"></a>

## Workflow Manager

-   [ ] e.g.
    
        'move-to-page'(begin,'user-agenda').  
        'complete-task'('mark-off-all-completed-from-agenda').  
        'complete-task'('sort-agenda').  
        'finish-page'('user-agenda').


<a id="orgb0dfe09"></a>

## Health


<a id="org8b90aec"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="orga4d0494"></a>

## Time Management


<a id="org85cee09"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org9aab852"></a>

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


<a id="org8b9bac1"></a>

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


<a id="orgda32092"></a>

## Organization


<a id="org598b64a"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="orge788b1c"></a>

## Self-Discipline


<a id="orgebd8a23"></a>

### Self-Discipline State Machine


<a id="orgf0fca28"></a>

## Transportation/Shopping/Errands


<a id="org4470780"></a>

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


<a id="org50275ea"></a>

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


<a id="org08bc9a3"></a>

## Document Management


<a id="org0fddeb8"></a>

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


<a id="org68a7a8f"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="orga6b049f"></a>

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



# Table of Contents

1.  [The Free Life Planner](#org1b81f9b)
    1.  [THIS README IS UNDER CONSTRUCTION](#orgae6540e)
2.  [Introduction](#org33f48cb)
    1.  [Purpose](#orgf5566b8)
    2.  [Sample use cases](#orgf6df216)
    3.  [Status](#orgc5ff5e5)
    4.  [Summary](#org2e5e70d)
3.  [General Overview](#org2d6ca71)
    1.  [Workflow Manager](#org2915b7b)
    2.  [Health](#orgdaf47fc)
        1.  [Exercise](#org98de20e)
        2.  [Nutrition](#org57d9b22)
        3.  [Doctor's Visits and Orders](#orgf884a04)
        4.  [Medications](#orgb659ec2)
    3.  [Time Management](#orgcfea923)
        1.  [Recurrences](#org4362389)
        2.  [Calendaring](#org712f016)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#orgc8be3d7)
    4.  [Organization](#org20449ac)
        1.  [Inventory Management](#orgcb260e2)
        2.  [Communication Management](#orgcfab269)
        3.  [Chore Charting](#orgf505a4a)
    5.  [Self-Discipline](#orge19feeb)
        1.  [Self-Discipline State Machine](#org812ea83)
        2.  [Gamification](#org2212206)
        3.  [Movement Discipline](#org194f610)
    6.  [Transportation/Shopping/Errands](#org14ec893)
        1.  [Transportation](#org5afa923)
        2.  [Shopping/Errands](#orgacb6b13)
    7.  [Document Management](#org49a5abd)
    8.  [Financial Planner](#orgc5a181f)
    9.  [Emergency Preparedness](#org68562b3)
4.  [More Info](#orgf07d63b)
    1.  [More Use Cases](#org9957cdd)
    2.  [User Base](#org079b0d4)
    3.  [Links](#orga3d3d35)
5.  [Technical Overview](#orga08217a)
    1.  [Workflow Manager](#orgc208b75)
    2.  [Health](#org33bbb24)
        1.  [Exercise](#orga7e9c85)
        2.  [Nutrition](#org80d8cdb)
        3.  [Medications](#org990a295)
    3.  [Time Management](#orgf52f962)
        1.  [Recurrences](#orga9ad523)
        2.  [Calendaring](#org8ca3a97)
        3.  [Planning, Scheduling and Execution](#orgb055022)
    4.  [Organization](#org3594e65)
        1.  [Inventory Management](#org9562592)
    5.  [Self-Discipline](#orgc7d646a)
        1.  [Self-Discipline State Machine](#org85734d7)
    6.  [Transportation/Shopping/Errands](#orgcb8d0ec)
        1.  [Transportation](#orgd7d7098)
        2.  [Shopping/Errands](#org5ad746b)
    7.  [Document Management](#org6ef2cab)
    8.  [Financial Planner](#org93046a8)
    9.  [Emergency Preparedness](#org48ec931)
6.  [Technologies Most Used](#orgbe0672c)


<a id="org1b81f9b"></a>

# The Free Life Planner


<a id="orgae6540e"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org33f48cb"></a>

# Introduction


<a id="orgf5566b8"></a>

## Purpose

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="orgf6df216"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#org9957cdd)


<a id="orgc5ff5e5"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org2e5e70d"></a>

## Summary

-   [Workflow Manager](#org2915b7b) (Guides user through all other systems)
-   [Health](#orgdaf47fc) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org52f638b) (Nutrition, Taste, Cost, etc)
-   [Time Management](#orgcfea923) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org20449ac) (Inventory Management)
-   [Self-Discipline](#orge19feeb) (State Machine)
-   [Paperwork](#org49a5abd) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgc5a181f) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org68562b3) ()


<a id="org2d6ca71"></a>

# General Overview


<a id="org2915b7b"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks


<a id="orgdaf47fc"></a>

## Health


<a id="org98de20e"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org57d9b22"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#orge19feeb) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="orgf884a04"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] Patient advocate
-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org49a5abd)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="orgb659ec2"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="orgcfea923"></a>

## Time Management


<a id="org4362389"></a>

### Recurrences


<a id="org712f016"></a>

### Calendaring


<a id="orgc8be3d7"></a>

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


<a id="org20449ac"></a>

## Organization


<a id="orgcb260e2"></a>

### Inventory Management

-   Pantry management


<a id="orgcfab269"></a>

### Communication Management

-   Pantry management


<a id="orgf505a4a"></a>

### Chore Charting


<a id="orge19feeb"></a>

## Self-Discipline


<a id="org812ea83"></a>

### Self-Discipline State Machine


<a id="org2212206"></a>

### Gamification


<a id="org194f610"></a>

### Movement Discipline


<a id="org14ec893"></a>

## Transportation/Shopping/Errands


<a id="org5afa923"></a>

### Transportation


<a id="orgacb6b13"></a>

### Shopping/Errands


<a id="org49a5abd"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="orgc5a181f"></a>

## Financial Planner


<a id="org68562b3"></a>

## Emergency Preparedness


<a id="orgf07d63b"></a>

# More Info


<a id="org9957cdd"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to your doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on your taxes, and to change your air filter
-   Telling you that a particular plan of yours violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="org079b0d4"></a>

## User Base

-   Everyone
-   People with disabilities such as pervasive developmental disorders
-   People in poverty who are one misstep from disaster
-   People with unwieldy illnesses
-   People who are homeless


<a id="orga3d3d35"></a>

## Links

-   Here is the main FLP code site:
    -   <https://github.com/aindilis/free-life-planner>

-   Here is the release of FRDCSA Panoply Git VM (containing older and stripped down versions of FRDCSA and Free Life Planner):
    -   <https://github.com/aindilis/frdcsa-panoply-git-20200329>

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


<a id="orga08217a"></a>

# Technical Overview


<a id="orgc208b75"></a>

## Workflow Manager

-   [ ] e.g.
    
        'move-to-page'(begin,'user-agenda').  
        'complete-task'('mark-off-all-completed-from-agenda').  
        'complete-task'('sort-agenda').  
        'finish-page'('user-agenda').


<a id="org33bbb24"></a>

## Health


<a id="orga7e9c85"></a>

### Exercise


<a id="org80d8cdb"></a>

### Nutrition

1.  Meal Planner


<a id="org990a295"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="orgf52f962"></a>

## Time Management


<a id="orga9ad523"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org8ca3a97"></a>

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


<a id="orgb055022"></a>

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


<a id="org3594e65"></a>

## Organization


<a id="org9562592"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="orgc7d646a"></a>

## Self-Discipline


<a id="org85734d7"></a>

### Self-Discipline State Machine


<a id="orgcb8d0ec"></a>

## Transportation/Shopping/Errands


<a id="orgd7d7098"></a>

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


<a id="org5ad746b"></a>

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


<a id="org6ef2cab"></a>

## Document Management


<a id="org93046a8"></a>

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


<a id="org48ec931"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="orgbe0672c"></a>

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


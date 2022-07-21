
# Table of Contents

1.  [The Free Life Planner](#orgb27b19c)
    1.  [THIS README IS UNDER CONSTRUCTION](#org38f84e8)
2.  [Introduction](#org82410f1)
    1.  [Purpose](#org6013b53)
    2.  [Sample use cases](#orgfaec547)
    3.  [Status](#org84ea439)
    4.  [Summary](#org5fb22fd)
3.  [General Overview](#org9d6bf0d)
    1.  [Workflow Manager](#org0871686)
    2.  [Health](#orga56d3e5)
        1.  [Exercise](#org658ea99)
        2.  [Nutrition](#orgecb76d7)
        3.  [Doctor's Visits and Orders](#orge1eaddc)
        4.  [Medications](#org739b483)
    3.  [Time Management](#org16296ed)
        1.  [Recurrences](#org377a416)
        2.  [Calendaring](#orgdf3381a)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#orgcaed3ee)
    4.  [Organization](#orge0666a8)
        1.  [Inventory Management](#org08503b4)
        2.  [Communication Management](#org0a1624f)
        3.  [Chore Charting](#org74b4c40)
    5.  [Self-Discipline](#org5c68ff2)
        1.  [Self-Discipline State Machine](#orgc4ed432)
        2.  [Gamification](#orga8ecda2)
        3.  [Movement Discipline](#org41367e8)
    6.  [Transportation/Shopping/Errands](#orgb49d3bf)
        1.  [Transportation](#org092c8eb)
        2.  [Shopping/Errands](#orge053833)
    7.  [Document Management](#org9869934)
    8.  [Financial Planner](#org8c22d7a)
    9.  [Emergency Preparedness](#org20c95a4)
4.  [More Info](#org3201f8b)
    1.  [More Use Cases](#org8003cbf)
    2.  [User Base](#orgab7a9b7)
    3.  [Links](#org5f04838)
5.  [Technical Overview](#orgd45260d)
    1.  [Workflow Manager](#org4347ff6)
    2.  [Health](#orgf0cfa03)
        1.  [Exercise](#org6186140)
        2.  [Nutrition](#org43e5c7d)
        3.  [Medications](#orgc702ede)
    3.  [Time Management](#org55e0342)
        1.  [Recurrences](#org66d0a2f)
        2.  [Calendaring](#org80f1500)
        3.  [Planning, Scheduling and Execution](#org6bedfa9)
    4.  [Organization](#org7bc6acf)
        1.  [Inventory Management](#org310712d)
    5.  [Self-Discipline](#org54a59d1)
        1.  [Self-Discipline State Machine](#org1011f4a)
    6.  [Transportation/Shopping/Errands](#orgcb95cfd)
        1.  [Transportation](#org3473d00)
        2.  [Shopping/Errands](#orgad4809e)
    7.  [Document Management](#orgfb02017)
    8.  [Financial Planner](#orgb134f45)
    9.  [Emergency Preparedness](#org70477e2)
6.  [Major Technologies Used](#org878586f)


<a id="orgb27b19c"></a>

# The Free Life Planner


<a id="org38f84e8"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org82410f1"></a>

# Introduction


<a id="org6013b53"></a>

## Purpose

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="orgfaec547"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#org8003cbf)


<a id="org84ea439"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org5fb22fd"></a>

## Summary

-   [Workflow Manager](#org0871686) (Guides user through all other systems)
-   [Health](#orga56d3e5) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org4686e47) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org16296ed) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orge0666a8) (Inventory Management)
-   [Self-Discipline](#org5c68ff2) (State Machine)
-   [Paperwork](#org9869934) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org8c22d7a) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org20c95a4) ()


<a id="org9d6bf0d"></a>

# General Overview


<a id="org0871686"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks


<a id="orga56d3e5"></a>

## Health


<a id="org658ea99"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="orgecb76d7"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org5c68ff2) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="orge1eaddc"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] Patient advocate
-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org9869934)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="org739b483"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="org16296ed"></a>

## Time Management


<a id="org377a416"></a>

### Recurrences


<a id="orgdf3381a"></a>

### Calendaring


<a id="orgcaed3ee"></a>

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


<a id="orge0666a8"></a>

## Organization


<a id="org08503b4"></a>

### Inventory Management

-   Pantry management


<a id="org0a1624f"></a>

### Communication Management

-   Pantry management


<a id="org74b4c40"></a>

### Chore Charting


<a id="org5c68ff2"></a>

## Self-Discipline


<a id="orgc4ed432"></a>

### Self-Discipline State Machine


<a id="orga8ecda2"></a>

### Gamification


<a id="org41367e8"></a>

### Movement Discipline


<a id="orgb49d3bf"></a>

## Transportation/Shopping/Errands


<a id="org092c8eb"></a>

### Transportation


<a id="orge053833"></a>

### Shopping/Errands


<a id="org9869934"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="org8c22d7a"></a>

## Financial Planner


<a id="org20c95a4"></a>

## Emergency Preparedness


<a id="org3201f8b"></a>

# More Info


<a id="org8003cbf"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to your doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on your taxes, and to change your air filter
-   Telling you that a particular plan of yours violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="orgab7a9b7"></a>

## User Base

-   Everyone
-   People with disabilities such as pervasive developmental disorders
-   People in poverty who are one misstep from disaster
-   People with unwieldy illnesses
-   People who are homeless


<a id="org5f04838"></a>

## Links

-   Here is the main FLP code site:
    -   <https://github.com/aindilis/free-life-planner>

-   Here is the release of FRDCSA Panoply Git VM (containing older and stripped down versions of FRDCSA and Free Life Planner):
    -   <https://github.com/aindilis/frdcsa-panoply-git-20200329>

-   Here is a story describing the Free Life Planner:
    -   <https://frdcsa.org/~andrewdo/writings/homeless-story.html>

-   Here is the most recent talk on FLP.
    -   <https://ontologforum.org/index.php/ConferenceCall_2022_04_20>

-   Here is the beginning of the release of FRDCSA (marking the Panoply release the official public release and deeming the last five years of work the "private" version of FRDCSA, and backporting from private to public as able):
    -   <https://github.com/aindilis/frdcsa-installer>

-   Here is a recent talk from EmacsConf2019 about FRDCSA/FLP/Panoply:
    -   <https://frdcsa.org/~andrewdo/frdcsa-emacsconf2019-final.webm>

-   Here is an independent codebase (no dependencies on FRDCSA) for interactive plan monitoring:
    -   <https://github.com/aindilis/plan-monitor>

-   Here is some more recent work on the Interactive Execution Monitor:
    -   <https://frdcsa.org/~andrewdo/iem2-2.mp4>
    -   <https://frdcsa.org/~andrewdo/iem2-3.mp4>

-   Here is a video of an older, much smaller and simpler version of the FLP booting up (be careful, noisy):
    -   <https://www.youtube.com/watch?v=t_dCAlf26LE>

-   Here is the beginning of a paper on FLP:
    -   <https://frdcsa.org/~andrewdo/pioneer/wk1/flp.pdf>

-   and one on FRDCSA:
    -   <https://frdcsa.org/~andrewdo/pioneer/wk1/frdcsa.pdf>

-   Here is a paper on the SPSE2 subsystem, an early planning system for FRDCSA which inspired parts of FLP:
    -   <https://frdcsa.org/visual-aid/pdf/Temporal-Planning-and-Inferencing-for-Personal-Task-Management-with-SPSE2.pdf>

-   Here is a link to the financial planning submodule:
    -   <https://github.com/aindilis/financial-planning#projected-transactions-for-florence-tucker>

-   Here is a link to the meal planning submodule:
    -   <https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html>

-   Here is a video which shows some progress on the planner systems and also later the meal planner:
    -   <https://www.youtube.com/watch?v=XZh_tHNboCI&t=15s>

-   Here are some earlier documents about the FLP:
    -   <https://frdcsa.org/~andrewdo/writings/News-Challenge-2.html>
    -   <https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanningCoachSoftware.html>
    -   <https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanningCoachSoftwareUpdate.html>
    -   <https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanner.html>

-   Here is the README for Panoply/FRDCSA:
    -   <https://frdcsa.org/~andrewdo/writings/README.html>

-   Here is the project blog:
    -   <https://facebook.com/frdcsa>

-   Here is the LogicMOO system mentioned in the EmacsConf video, which FLP draws heavily upon and intends to integrate with eventually:
    -   <https://github.com/TeamSPoon/prologmud/wiki>

-   And here the design docs for LogicMOO:
    -   <https://drive.google.com/drive/#folders/0B0QA19UX0ehlV1ZEaXEzc3hjTWM>


<a id="orgd45260d"></a>

# Technical Overview


<a id="org4347ff6"></a>

## Workflow Manager

-   [ ] e.g.
    
        'move-to-page'(begin,'user-agenda').  
        'complete-task'('mark-off-all-completed-from-agenda').  
        'complete-task'('sort-agenda').  
        'finish-page'('user-agenda').


<a id="orgf0cfa03"></a>

## Health


<a id="org6186140"></a>

### Exercise


<a id="org43e5c7d"></a>

### Nutrition

1.  Meal Planner


<a id="orgc702ede"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org55e0342"></a>

## Time Management


<a id="org66d0a2f"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org80f1500"></a>

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


<a id="org6bedfa9"></a>

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


<a id="org7bc6acf"></a>

## Organization


<a id="org310712d"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="org54a59d1"></a>

## Self-Discipline


<a id="org1011f4a"></a>

### Self-Discipline State Machine


<a id="orgcb95cfd"></a>

## Transportation/Shopping/Errands


<a id="org3473d00"></a>

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


<a id="orgad4809e"></a>

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


<a id="orgfb02017"></a>

## Document Management


<a id="orgb134f45"></a>

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


<a id="org70477e2"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="org878586f"></a>

# Major Technologies Used

-   [X] [SWI-Prolog](https://www.swi-prolog.org/)
    -   [Julian](https://fifth-postulate.nl/julian/) time library
-   [X] Perl    
    -   [X] [YASWI](https://metacpan.org/pod/Language::Prolog::Yaswi) Perl<->SWI-Prolog Interface
    -   [X] [Catalyst CMS](http://catalyst.perl.org/Catalyst)
        -   [X] [ShinyCMS](https://shinycms.org/)
    -   [X] [Mojolicious](https://www.mojolicious.org/)
-   [X] Java
    -   [X] [JavaPengine](https://github.com/aindilis/JavaPengine) (Java<->SWI-Prolog)
    -   [X] [Jason/AgentSpeak(L)](http://jason.sourceforge.net/wp/)
        -   [X] [JPL](https://jpl7.org/) Java<->SWI-Prolog
    -   [X] [Alexa](https://github.com/alexa/alexa-skills-kit-sdk-for-java) voice skill interface
-   [X] PDDL 2.2 temporal metric planning
    -   [X] [LPG-td-1.0](https://lpg.unibs.it/lpg/)
    -   [X] [OPTIC<sub>CLP</sub>](https://nms.kcl.ac.uk/planning/software/optic.html)


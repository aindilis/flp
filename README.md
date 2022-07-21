
# Table of Contents

1.  [The Free Life Planner](#org83743f1)
    1.  [THIS README IS UNDER CONSTRUCTION](#orga3cdd39)
2.  [Introduction](#org85bc774)
    1.  [Purpose](#orgeba1336)
    2.  [Sample use cases](#org052db6a)
    3.  [Status](#org2c1fb88)
    4.  [Summary](#orgbedfdf9)
3.  [General Overview](#org3b7cd92)
    1.  [Workflow Manager](#org8a2de0f)
    2.  [Health](#orgb95f7a1)
        1.  [Exercise](#org7175c4b)
        2.  [Nutrition](#orgac39e62)
        3.  [Doctor's Visits and Orders](#org26b3d49)
        4.  [Medications](#orgd5003e5)
    3.  [Time Management](#org9239c75)
        1.  [Recurrences](#orga291d88)
        2.  [Calendaring](#orge33eca8)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#orgf849926)
    4.  [Organization](#orge87f52a)
        1.  [Inventory Management](#org3a7c4f2)
        2.  [Communication Management](#org8921a5e)
        3.  [Chore Charting](#orgbd73b6f)
    5.  [Self-Discipline](#org44221df)
        1.  [Self-Discipline State Machine](#org3353da2)
        2.  [Gamification](#org8db4ddb)
        3.  [Movement Discipline](#org4d5015f)
    6.  [Transportation/Shopping/Errands](#orgf2a3958)
        1.  [Transportation](#org9b052d8)
        2.  [Shopping/Errands](#org0915691)
    7.  [Document Management](#org31af73a)
    8.  [Financial Planner](#orgea68563)
    9.  [Emergency Preparedness](#org09c2661)
4.  [More Info](#org3054fe8)
    1.  [More Use Cases](#org1278e45)
    2.  [User Base](#org99b0545)
    3.  [Links](#org15fa42a)
5.  [Technical Overview](#org96621a3)
    1.  [Workflow Manager](#org9afd382)
    2.  [Health](#orgb8f8d72)
        1.  [Medications](#orgc089848)
    3.  [Time Management](#org5df52dc)
        1.  [Recurrences](#org94291a4)
        2.  [Calendaring](#org4d0e242)
        3.  [Planning, Scheduling and Execution](#org5e66955)
    4.  [Organization](#org3795d81)
        1.  [Inventory Management](#orgc7df026)
    5.  [Self-Discipline](#orgd6d887d)
        1.  [Self-Discipline State Machine](#orgf25e79e)
    6.  [Transportation/Shopping/Errands](#org86928b0)
        1.  [Transportation](#orgb0b31ec)
        2.  [Shopping/Errands](#orgaed5af5)
    7.  [Document Management](#orgd3d36c4)
    8.  [Financial Planner](#orgddb75be)
    9.  [Emergency Preparedness](#org4cc800b)
6.  [Technologies Most Used](#org6c54197)


<a id="org83743f1"></a>

# The Free Life Planner


<a id="orga3cdd39"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org85bc774"></a>

# Introduction


<a id="orgeba1336"></a>

## Purpose

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org052db6a"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#org1278e45)


<a id="org2c1fb88"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgbedfdf9"></a>

## Summary

-   [Workflow Manager](#org8a2de0f) (Guides user through all other systems)
-   [Health](#orgb95f7a1) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#org1eb039a) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org9239c75) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orge87f52a) (Inventory Management)
-   [Self-Discipline](#org44221df) (State Machine)
-   [Paperwork](#org31af73a) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orgea68563) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org09c2661) ()


<a id="org3b7cd92"></a>

# General Overview


<a id="org8a2de0f"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks


<a id="orgb95f7a1"></a>

## Health


<a id="org7175c4b"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="orgac39e62"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org44221df) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="org26b3d49"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] Patient advocate
-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org31af73a)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="orgd5003e5"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="org9239c75"></a>

## Time Management


<a id="orga291d88"></a>

### Recurrences


<a id="orge33eca8"></a>

### Calendaring


<a id="orgf849926"></a>

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


<a id="orge87f52a"></a>

## Organization


<a id="org3a7c4f2"></a>

### Inventory Management

-   Pantry management


<a id="org8921a5e"></a>

### Communication Management

-   Pantry management


<a id="orgbd73b6f"></a>

### Chore Charting


<a id="org44221df"></a>

## Self-Discipline


<a id="org3353da2"></a>

### Self-Discipline State Machine


<a id="org8db4ddb"></a>

### Gamification


<a id="org4d5015f"></a>

### Movement Discipline


<a id="orgf2a3958"></a>

## Transportation/Shopping/Errands


<a id="org9b052d8"></a>

### Transportation


<a id="org0915691"></a>

### Shopping/Errands


<a id="org31af73a"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="orgea68563"></a>

## Financial Planner


<a id="org09c2661"></a>

## Emergency Preparedness


<a id="org3054fe8"></a>

# More Info


<a id="org1278e45"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives.
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need.
-   Remembering that when you finish filling out some particular paperwork, to send a copy to your doctor.
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them.
-   Reminding you to work on your taxes, and to change your air filter.
-   Telling you that a particular plan of yours violates various moral and ethical constraints.
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through.


<a id="org99b0545"></a>

## User Base

-   Everyone
-   People with disabilities such as pervasive developmental disorders.
-   People in poverty who are one misstep from disaster.
-   People with unwieldy illnesses.
-   People who are homeless.


<a id="org15fa42a"></a>

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


<a id="org96621a3"></a>

# Technical Overview


<a id="org9afd382"></a>

## Workflow Manager

-   [ ] e.g.
    
        'move-to-page'(begin,'user-agenda').  
        'complete-task'('mark-off-all-completed-from-agenda').  
        'complete-task'('sort-agenda').  
        'finish-page'('user-agenda').


<a id="orgb8f8d72"></a>

## Health


<a id="orgc089848"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org5df52dc"></a>

## Time Management


<a id="org94291a4"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org4d0e242"></a>

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


<a id="org5e66955"></a>

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


<a id="org3795d81"></a>

## Organization


<a id="orgc7df026"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="orgd6d887d"></a>

## Self-Discipline


<a id="orgf25e79e"></a>

### Self-Discipline State Machine


<a id="org86928b0"></a>

## Transportation/Shopping/Errands


<a id="orgb0b31ec"></a>

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


<a id="orgaed5af5"></a>

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


<a id="orgd3d36c4"></a>

## Document Management


<a id="orgddb75be"></a>

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


<a id="org4cc800b"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="org6c54197"></a>

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


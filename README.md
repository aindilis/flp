
# Table of Contents

1.  [The Free Life Planner](#org9c086e6)
    1.  [THIS README IS UNDER CONSTRUCTION](#orgc066b15)
2.  [Introduction](#org4360576)
    1.  [Purpose](#orgd3e02e5)
    2.  [Sample use cases](#org8ee7ff2)
    3.  [Status](#orgf18cde1)
3.  [General Overview](#orgbd5dec6)
    1.  [Workflow Manager](#org0f882de)
    2.  [Health](#org86ec806)
        1.  [Exercise](#orga5d013e)
        2.  [Nutrition](#orgc814f7f)
        3.  [Doctor's Visits and Orders](#org4dd6f05)
        4.  [Medications](#org993ccf2)
        5.  [Mental Health](#orgf449b35)
    3.  [Time Management](#org976fa1c)
        1.  [Recurrences](#orgdc84e82)
        2.  [Calendaring](#org488bb18)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#orgd8a2f98)
    4.  [Organization](#org6d469b1)
        1.  [Inventory Management](#orgc98f8e9)
        2.  [Communication Management](#orgd4ad966)
        3.  [Chore Charting](#orgcdfa28b)
        4.  [Maintenance](#org0b63980)
    5.  [Self-Discipline](#org354dbd3)
        1.  [Todo](#orgc931886)
        2.  [Note-Taking](#org7ecab26)
        3.  [Scheduling](#org1cf4a44)
        4.  [Self-Discipline State Machine](#org357f650)
        5.  [Gamification](#org0e614b9)
        6.  [Movement Discipline](#org40a82dc)
    6.  [Transportation/Shopping/Errands](#org7641b9a)
        1.  [Transportation](#org4b41bd8)
        2.  [Shopping/Errands](#orge476252)
    7.  [Document Management](#org8ef83a1)
    8.  [Financial Planner](#org5bd4d9e)
    9.  [Emergency Preparedness](#org0c06841)
4.  [Technical Overview](#org6d26467)
    1.  [Workflow Manager](#org9801b35)
    2.  [Health](#org7ff0dcf)
        1.  [Exercise](#org1b7e468)
        2.  [Nutrition](#orgf362591)
        3.  [Medications](#org0a920ab)
    3.  [Time Management](#org666d926)
        1.  [Recurrences](#orga39fe4a)
        2.  [Calendaring](#orge933881)
        3.  [Planning, Scheduling and Execution](#orgdc3f8d3)
    4.  [Organization](#orgb104e3f)
        1.  [Inventory Management](#orgec443ba)
        2.  [Research and Development](#org6d73417)
    5.  [Self-Discipline](#org2e2796b)
        1.  [Self-Discipline State Machine](#org77ff2ea)
    6.  [Transportation/Shopping/Errands](#org9175b6c)
        1.  [Transportation](#org8fbe523)
        2.  [Shopping/Errands](#orgeac8224)
    7.  [Document Management](#orgc86707f)
    8.  [Financial Planner](#orgdd0de9e)
    9.  [Emergency Preparedness](#org98bbd23)
5.  [Major Techniques Used](#orga67c06c)
6.  [Major Technologies Used](#orgf124e59)
7.  [More Info](#org52bdff3)
    1.  [More Use Cases](#org1722315)
    2.  [User Base](#org96c8555)
    3.  [Links](#org3c0f398)


<a id="org9c086e6"></a>

# The Free Life Planner


<a id="orgc066b15"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org4360576"></a>

# Introduction


<a id="orgd3e02e5"></a>

## Purpose

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="org8ee7ff2"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#org1722315)


<a id="orgf18cde1"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgbd5dec6"></a>

# General Overview


<a id="org0f882de"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks


<a id="org86ec806"></a>

## Health


<a id="orga5d013e"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="orgc814f7f"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
        -   [ ] Macros planning and counting
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org354dbd3) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] Recipe manager
    -   [ ] Recommender system


<a id="org4dd6f05"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] Patient advocate
-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org8ef83a1)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="org993ccf2"></a>

### Medications

-   [ ] Refill tracker
-   [ ] Medication management


<a id="orgf449b35"></a>

### Mental Health

-   [ ] Emotional security
    -   [ ] Managing triggers
    -   [ ] Reframing self-talk
-   [ ] Planning for optimal productivity by meeting needs
    -   [ ] Pre/pro-active planning
    -   [ ] Root cause analysis for low-productivity
    -   [ ] Task tracking and MTTC
-   [ ] Psychometric reporting
    -   [ ] Identifying factors


<a id="org976fa1c"></a>

## Time Management


<a id="orgdc84e82"></a>

### Recurrences


<a id="org488bb18"></a>

### Calendaring


<a id="orgd8a2f98"></a>

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


<a id="org6d469b1"></a>

## Organization


<a id="orgc98f8e9"></a>

### Inventory Management

-   Pantry management


<a id="orgd4ad966"></a>

### Communication Management

-   Proxy all communications
    -   [-] Team building
        -   [ ] [Teamcore/STEAM](https://teamcore.seas.harvard.edu/publications/towards-flexible-teamwork)
        -   [ ] [Horn-TeamLog](https://www.mimuw.edu.pl/~nguyen/HornTeamLog-long.pdf)
        -   [ ] [NL<sub>MAMS</sub>](https://link.springer.com/book/10.1007/978-3-319-39972-0)
        -   [X] [Social Network Analysis](http://www.casos.cs.cmu.edu/projects/ora/software.php)
    -   [-] Dossier system
        -   [-] Relationship management
            -   [ ] Access Control Lists
            -   [X] Talking points
        -   [X] Memcons
        -   [ ] Commitments extraction
        -   [ ] Goal/Interest/Ability extraction
    -   [-] Persuasion
        -   [ ] A/B Testing
        -   [X] [Argument mapping](https://argdown.org/)


<a id="orgcdfa28b"></a>

### Chore Charting

-   Track who/what/where/when regarding chores
-   Track birthdays, anniversaries, etc


<a id="org0b63980"></a>

### Maintenance

-   Home
-   Automotive
-   Equipment
-   Computer systems


<a id="org354dbd3"></a>

## Self-Discipline


<a id="orgc931886"></a>

### Todo


<a id="org7ecab26"></a>

### Note-Taking

-   [X] Org-mode
-   [ ] Cyc-Zettelkasten
-   [X] Do todo-list system


<a id="org1cf4a44"></a>

### Scheduling

-   [X] PDDL
-   [ ] Optaplanner


<a id="org357f650"></a>

### Self-Discipline State Machine

-   [ ] Use the digital twin and plan to choose from possible things to do


<a id="org0e614b9"></a>

### Gamification

-   [X] Rewards for completing recurrent tasks
-   [X] Daily penalty for leaving any recurrent tasks incomplete
-   [X] Penalties for lack of movement discipline
-   [ ] Rewards for staying productive


<a id="org40a82dc"></a>

### Movement Discipline


<a id="org7641b9a"></a>

## Transportation/Shopping/Errands


<a id="org4b41bd8"></a>

### Transportation


<a id="orge476252"></a>

### Shopping/Errands


<a id="org8ef83a1"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders
    -   [X] Digital library system
        -   [X] Equipment manuals
    -   [X] [Book reader](https://frdcsa.org/frdcsa/internal/clear)
    -   [X] [Information search management](#org6d73417)


<a id="org5bd4d9e"></a>

## Financial Planner


<a id="org0c06841"></a>

## Emergency Preparedness


<a id="org6d26467"></a>

# Technical Overview


<a id="org9801b35"></a>

## Workflow Manager

-   [ ] e.g.
    
        'move-to-page'(begin,'user-agenda').  
        'complete-task'('mark-off-all-completed-from-agenda').  
        'complete-task'('sort-agenda').  
        'finish-page'('user-agenda').


<a id="org7ff0dcf"></a>

## Health


<a id="org1b7e468"></a>

### Exercise


<a id="orgf362591"></a>

### Nutrition

1.  Meal Planner

    -   [ ] Rotating emergency food and water provisions
    -   [ ] Food pantries


<a id="org0a920ab"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org666d926"></a>

## Time Management


<a id="orga39fe4a"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orge933881"></a>

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


<a id="orgdc3f8d3"></a>

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

    -   [-] Do system (todo lists)
        -   [ ] Task duration estimation
        -   [X] Task classification
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
    -   [X] Standard domain library (basekb)
        -   [X] agent, biomaintenance, chores, deontic, economic, food, hygiene, misc, security, space, tool, work
    -   [ ] Household emergency preparedness
        -   [ ] Planning ahead for inclement weather
            -   [ ] e.g. Stock up on groceries before a major storm hits
            -   [ ] Weather control rules


<a id="orgb104e3f"></a>

## Organization


<a id="orgec443ba"></a>

### Inventory Management

-   [ ] Supplier tracking
-   [ ] Automatic reordering

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="org6d73417"></a>

### Research and Development

-   [X] Academician system
-   [X] Study system
-   [ ] ITS system
-   [X] Seeker system


<a id="org2e2796b"></a>

## Self-Discipline


<a id="org77ff2ea"></a>

### Self-Discipline State Machine


<a id="org9175b6c"></a>

## Transportation/Shopping/Errands


<a id="org8fbe523"></a>

### Transportation

-   [ ] API look-up mashups
    -   [ ] Hours of operation
        -   [ ] Stores/offices/etc
    -   [ ] Weather
    -   [ ] Route planning
        -   [ ] Point to point
        -   [ ] "Traveling Salesmen"
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


<a id="orgeac8224"></a>

### Shopping/Errands

-   [X] Shopping list management
-   [X] Integration with financial management
    -   [X] OFX cross-referencing
-   [ ] Integration with inventory and pantry management
-   [-] Buying
    -   [ ] Broker - Purchase/Financial Decision Support Systems
        -   [ ] Argumentation
            -   [ ] Decide what to purchase
            -   [ ] Decide whether to purchase
    -   [ ] Ethical consumerism
        -   [ ] Boycott management using Prolog representation
            -   [ ] Collective action trap avoidance
                -   [ ] Using Koordinator
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


<a id="orgc86707f"></a>

## Document Management


<a id="orgdd0de9e"></a>

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


<a id="org98bbd23"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)
    -   [ ] Recurrences for reminders to maintain equipment, supplies, plans and drills
    -   [ ] Safety plans
        -   [ ] Fire
        -   [ ] Pandemic
        -   [ ] Food and water


<a id="orga67c06c"></a>

# Major Techniques Used

-   [ ] Dialog-interface
    
        hasDialogEntry('tell <PERSON> <THING>').
        dialogInterfaceQuery(Entry)  --> ([tell];[talk,to]),grabber(Person,person),([about];[]),oneOrMore(token,Tokens),
        	{getCurrentDateTime(Now),
        	 currentAgent(Agent),
        	 Entry = assert(atTime(Now,tell(Agent,Person,Tokens)))}.
        
        curGaeilgeArSeo(tell(Agent,TokenizedStatement),Gaeilge) :-
        	getGloss(Agent,AgentGloss),
        	atomic_list_concat(TokenizedStatement,' ',Statement),
        	atomic_list_concat(['I',told,AgentGloss,Statement],' ',Gaeilge).


<a id="orgf124e59"></a>

# Major Technologies Used

-   [X] [SWI-Prolog](https://www.swi-prolog.org/)
    -   [Julian](https://fifth-postulate.nl/julian/) time library
    -   [CLP(fd)](https://www.swi-prolog.org/man/clpfd.html) Constraint Logic Programming
    -   [Quick Load Format](https://www.swi-prolog.org/pldoc/man?section=qlf)
-   [X] Perl    
    -   [X] [YASWI](https://metacpan.org/pod/Language::Prolog::Yaswi) Perl<->SWI-Prolog Interface
    -   [X] [Catalyst MVC](http://catalyst.perl.org/Catalyst)
        -   [X] [ShinyCMS](https://shinycms.org/)
    -   [X] [Mojolicious](https://www.mojolicious.org/)
-   [X] Java
    -   [X] [JavaPengine](https://github.com/aindilis/JavaPengine) (Java<->SWI-Prolog)
    -   [X] [Jason/AgentSpeak(L)](http://jason.sourceforge.net/wp/)
        -   [X] [JPL](https://jpl7.org/) Java<->SWI-Prolog
    -   [X] [Alexa](https://github.com/alexa/alexa-skills-kit-sdk-for-java) voice skill interface
-   [X] [Emacs integration](https://www.youtube.com/watch?v=0l3K__C9Dkc)
-   [X] Bash scripting
-   [X] PDDL 2.2 temporal metric planning
    -   [X] [LPG-td-1.0](https://lpg.unibs.it/lpg/)
    -   [X] [OPTIC<sub>CLP</sub>](https://nms.kcl.ac.uk/planning/software/optic.html)
-   [X] Vampire-KIF ATP system
-   [X] OpenCyc
-   [-] MySQL persistence
    -   [X] Through UniLang/FreeKBS2
    -   [ ] Directly from SWI-Prolog using ODBC
-   [ ] [Inform7](https://github.com/ganelson/inform)


<a id="org52bdff3"></a>

# More Info


<a id="org1722315"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to your doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on your taxes, and to change your air filter
-   Telling you that a particular plan of yours violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="org96c8555"></a>

## User Base

-   Everyone
-   People
    -   with disabilities such as pervasive developmental disorders
    -   in poverty who are one misstep from disaster
    -   with unwieldy illnesses
    -   who are homeless
    -   who experience relationship violence
    -   etc


<a id="org3c0f398"></a>

## Links

-   Here is the main FLP code site:
    -   <https://github.com/aindilis/free-life-planner>

-   Here is the release of FRDCSA Panoply Git VM (containing older and stripped down versions of FRDCSA and Free Life Planner):
    -   <https://github.com/aindilis/frdcsa-panoply-git-20200329>

-   Here is a story describing the Free Life Planner:
    -   <https://frdcsa.org/~andrewdo/writings/homeless-story.html>

-   Here is the most recent talk on FLP:
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


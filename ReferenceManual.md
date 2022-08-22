- [Technical Overview](#org20a324a)
  - [THIS REFERENCE MANUAL IS UNDER CONSTRUCTION](#org35b1cf4)
- [[README](https://github.com/aindilis/flp/blob/main/README.md)](#orgc509dbd)
  - [Broad overview of FLP](#orgb53e67e)
  - [Workflow Manager](#org8a2648b)
  - [Health](#orgc8a194f)
    - [Exercise](#org6308654)
    - [Nutrition](#org5678c2f)
    - [Doctor's Visits and Orders](#orgb36fdab)
    - [Medications](#orgadda5da)
    - [Mental Health](#org418bb38)
  - [Time Management](#orgbfb1317)
    - [Recurrences](#orgc955e93)
    - [Calendaring](#orgf5b2fab)
    - [Planning, Scheduling and Execution](#org6aa3ac2)
  - [Organization](#orgb9c042e)
    - [Inventory Management](#org1e6a8e3)
    - [Communication Management](#org8e4d335)
    - [Chore Charting](#orgc66d8e1)
    - [Maintenance](#orgf41fa4b)
    - [Research and Development](#org3526a82)
  - [Self-Discipline](#org20d7861)
    - [To-Do](#org4b9bd68)
    - [Note-Taking](#org6d34159)
    - [Scheduling](#orgf004373)
    - [Self-Discipline State Machine](#org0e17214)
    - [Gamification](#org0db8e43)
    - [Movement Discipline](#orgc1cbe50)
  - [Transportation/Shopping/Errands](#org1ea9f7d)
    - [Transportation](#org3c48b6f)
    - [Shopping/Errands](#org32f4d27)
  - [Document Management](#org5879be8)
  - [Financial Planner](#org606d62a)
  - [Emergency Preparedness](#org3a041f1)
- [Major Techniques Used](#org4ee2e48)
- [Major Technologies Used](#orgfa5a393)
  - [[README](https://github.com/aindilis/flp/blob/main/README.md)](#org0b4796f)
    - [Broad overview of FLP](#org8bf3a00)


<a id="org20a324a"></a>

# Technical Overview


<a id="org35b1cf4"></a>

## THIS REFERENCE MANUAL IS UNDER CONSTRUCTION


<a id="orgc509dbd"></a>

# [README](https://github.com/aindilis/flp/blob/main/README.md)


<a id="orgb53e67e"></a>

## Broad overview of FLP


<a id="org8a2648b"></a>

## Workflow Manager

-   [ ] <code>[35%]</code> e.g.
    
    ```Prolog
    'move-to-page'(begin,'user-agenda').  
    'complete-task'('mark-off-all-completed-from-agenda').  
    'complete-task'('sort-agenda').  
    'finish-page'('user-agenda').  
    ```
-   [ ] <code>[33%]</code> [Jason/AgentSpeak "metaplanning" system](https://github.com/aindilis/jason/tree/master/examples/linux-remote-control-2-adapter)
    -   [ ] Dynamically add/remove goals and replan
    -   [ ] <code>[10%]</code> Contingency planning

```Jason/AgentSpeak(L)
+!quarantine(Person) <-
	?hasRoom(Person,Room);
	!atLocation(Person,Room);
	+prohibited((move(Person,Location),Location \= Room));
	...
```


<a id="orgc8a194f"></a>

## Health


<a id="org6308654"></a>

### Exercise

-   [ ] <code>[33%]</code> Interactive plan monitoring of exercises
-   [ ] <code>[66%]</code> Track daily progress w/ Alexa interface


<a id="org5678c2f"></a>

### Nutrition

1.  Meal Planner

    -   [-] [Multiple meal planning and preparation systems](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] <code>[50%]</code> [Gourmet-Formalog-Standalone](https://github.com/aindilis/gourmet-formalog-standalone/)
        -   [ ] [st0opkid's MealSolver](https://github.com/aindilis/mealsolver)
        -   [ ] [<code>[66%]</code> PDDL-based mealplanner](https://frdcsa.org/%7eandrewdo/projects/mealplanning/)
        -   [ ] [<code>[25%]</code> Interactive cooking assistant](https://frdcsa.org/%7eandrewdo/WebWiki/CookingAssistant.html)
        -   [X] [PGourmet](https://altruisticsoftware.org/frdcsa/internal/pgourmet/)
        -   [ ] [Gourmet](https://altruisticsoftware.org/frdcsa/internal/gourmet)
        -   [ ] etc
    -   [ ] Rotating emergency food and water provisions
        -   [ ] Stock enough provisions to survive n-months
        -   [ ] Consuming the oldest staples first to prevent victuals from expiring
    -   [ ] Food pantries


<a id="orgb36fdab"></a>

### Doctor's Visits and Orders

-   [ ] [Medical diagnostics](https://github.com/timhannifan/symptom-tree/issues/1)
-   [ ] Following orders using [Machine Reading Comprehension](https://paperswithcode.com/task/machine-reading-comprehension)


<a id="orgadda5da"></a>

### Medications

-   [ ] <code>[30%]</code> [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)
    -   [ ] <code>[30%]</code> Manage time-dependent effects of medication dosages and half-lives
-   [ ] <code>[33%]</code> Medication refill tracking
-   [X] Medication reminders and recording


<a id="org418bb38"></a>

### Mental Health


<a id="orgbfb1317"></a>

## Time Management


<a id="orgc955e93"></a>

### Recurrences

How to schedule something for the last day of every month:

```Prolog
hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
	deltaTime([_Year-_Month-1],days(-1),YMD).
```


<a id="orgf5b2fab"></a>

### Calendaring

1.  Integrations

    -   With different agenda, calendaring, and planning / scheduling systems
        -   [X] Import from
            -   [X] Org-agenda
            -   [X] SPSE2 (Shared Priority System Editor v2)
            -   [X] Google Calendar
            -   [X] ICS (Internet Calendar Scheduling)
        -   [-] Export to
            -   [X] Org-agenda
            -   [X] SPSE2
            -   [ ] <code>[33%]</code> Google Calendar
            -   [X] ICS


<a id="org6aa3ac2"></a>

### Planning, Scheduling and Execution

1.  Planners

    -   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) planning
        -   [X] CLG, Colin2<sub>CLP</sub>, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan<sub>522</sub>
            -   [X] [More than 200 PDDL life planning domains](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/templates)
        -   [X] [SPSE2](https://frdcsa.org/visual-aid/pdf/Temporal-Planning-and-Inferencing-for-Personal-Task-Management-with-SPSE2.pdf)
        -   [X] [PDDL plan interactive execution monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)
    -   [X] Contingent planning
        -   [X] DNFct
            -   [X] More than 10 contingent life planning domains
        -   [ ] <code>[33%]</code> [AP/3T](https://github.com/aindilis/3t-frdcsa)
    -   [ ] <code>[90%]</code> Behavior tree reactive planning
        -   [ ] <code>[90%]</code> [Plan Monitor](https://github.com/aindilis/plan-monitor)
            -   [ ] <code>[40%]</code> Execution of generated (PDDL/AgentSpeak(L)/Behavior Tree/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
    -   [X] BDI Agent
        -   [X] Jason/AgentSpeak(L) w/ SWIPL integration (SWI-Prolog)
            -   [X] [More than 10 BDI domains](https://github.com/aindilis/jason/tree/master/examples)

2.  Additional Planning System

    -   [-] Do system (to-do lists)
        -   [ ] <code>[20%]</code> Task duration estimation
        -   [X] Task classification
    -   [-] Do-Convert system
        -   [X] Unique IDs for goals
        -   [ ] <code>[50%]</code> [Track changes to goals](https://github.com/aindilis/do-convert-logic)
        -   [X] Export to SPSE2/Verb/PDDL
    -   [ ] Factored planning
    -   [X] Planning systems
        -   [X] Verber
        -   [X] SPSE2
        -   [X] SPSE2-Formalog
    -   [-] Digital twin
        -   [X] WSM (World State Monitor)
        -   [X] Fitness Manager
        -   [ ] <code>[50%]</code> Checklists
    -   [ ] <code>[33%]</code> Kanban
    -   [ ] <code>[33%]</code> Goalban
    -   [X] User Agenda (for recurrences)
    -   [X] Habit tracker
    -   [ ] <code>[60%]</code> Resource Manager (plans over inventory/etc)
        -   [ ] <code>[80%]</code> Productivity Requirements
    -   [ ] <code>[25%]</code> Subsystem monitoring
        -   [ ] <code>[25%]</code> Mission Control
        -   [ ] <code>[35%]</code> Normal Form
    -   [-] Gamification
        -   [X] [Score](https://github.com/aindilis/score)
        -   [ ] Rewards/Penalties
        -   [X] [Manager](https://github.com/aindilis/manager)

3.  Some domains

    -   [ ] <code>[25%]</code> Plan cycles (cycle)
    -   [X] Standard domain library (basekb)
        -   [X] [agent, biomaintenance, chores, deontic, economic, food, hygiene, misc, security, space, tool, work](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/worlds/basekb)
    -   [ ] <code>[10%]</code> Household emergency preparedness
        -   [ ] Planning ahead for bad weather
            -   [ ] e.g. Stock up on groceries before a major storm hits
            -   [ ] <code>[50%]</code> Weather control rules


<a id="orgb9c042e"></a>

## Organization


<a id="org1e6a8e3"></a>

### Inventory Management

-   [ ] <code>[66%]</code> Pantry management
    -   [ ] <code>[75%]</code> Barcoded and un-barcoded food items
    -   [ ] <code>[10%]</code> Manage expected expiration dates
        -   [ ] Prevent food loss
            -   [ ] <code>[25%]</code> Help to schedule cooking before food expires
        -   [ ] Know how long it can stay out, or in fridge/freezer
            -   [ ] <code>[25%]</code> Know when to move it
-   [ ] <code>[15%]</code> Executable product manuals
    -   [ ] <code>[90%]</code> Automatically schedule maintenance
    -   [ ] <code>[10%]</code> Interactively perform maintenance
-   [ ] Executable product warranties
    -   [ ] Integration with planning and scheduling

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">


<a id="org8e4d335"></a>

### Communication Management

-   Proxy all communications
    -   [-] <code>[100%]</code> Dossier system
        -   [-] Relationship management
            -   [ ] <code>[25%]</code> ACLs (Access Control Lists)
            -   [X] Talking points
        -   [X] Memcons (Memorandum of Conversation)
        -   [ ] <code>[33%]</code> Commitments extraction
        -   [ ] <code>[33%]</code> Goal/Interest/Ability extraction
    -   [-] Persuasion
        -   [ ] <code>[10%]</code> A/B Testing
        -   [X] [Argument mapping](https://argdown.org/)
    -   [-] Team building
        -   [ ] [Teamcore/STEAM](https://teamcore.seas.harvard.edu/publications/towards-flexible-teamwork) (a Shell for TEAMwork)
        -   [ ] [Horn-TeamLog](https://www.mimuw.edu.pl/~nguyen/HornTeamLog-long.pdf)
        -   [ ] [NL<sub>MAMS</sub>](https://link.springer.com/book/10.1007/978-3-319-39972-0) (Natural Language MultiAgent Mental Simulator)
        -   [X] [SNA](http://www.casos.cs.cmu.edu/projects/ora/software.php) (Social Network Analysis)


<a id="orgc66d8e1"></a>

### Chore Charting


<a id="orgf41fa4b"></a>

### Maintenance


<a id="org3526a82"></a>

### Research and Development

-   [X] Academician system
-   [X] Study system
-   [ ] ITS system (Intelligent Tutoring System)
-   [X] Seeker system


<a id="org20d7861"></a>

## Self-Discipline


<a id="org4b9bd68"></a>

### To-Do


<a id="org6d34159"></a>

### Note-Taking

-   [X] Org-mode
-   [ ] <code>[10%]</code> Cyc-Zettelkasten
-   [X] Do to-do list system


<a id="orgf004373"></a>

### Scheduling

-   [X] PDDL (Planning Domain Definition Language)
-   [ ] PDDL+ (Planning Domain Definition Language Plus)
-   [ ] <code>[05%]</code> Optaplanner


<a id="org0e17214"></a>

### Self-Discipline State Machine

-   [ ] <code>[33%]</code> Use the digital twin and plan to choose from possible things to do


<a id="org0db8e43"></a>

### Gamification

-   [X] Rewards for completing recurrent tasks
-   [X] Daily penalty for leaving any recurrent tasks incomplete
-   [X] Penalties for lack of movement discipline
-   [ ] <code>[50%]</code> Rewards for staying productive


<a id="orgc1cbe50"></a>

### Movement Discipline


<a id="org1ea9f7d"></a>

## Transportation/Shopping/Errands


<a id="org3c48b6f"></a>

### Transportation

-   [ ] <code>[33%]</code> API look-up mashups (Application Programming Interface)
    -   [ ] <code>[90%]</code> Hours of operation
        -   [ ] <code>[90%]</code> Stores/offices/etc
    -   [ ] <code>[30%]</code> Weather
    -   [ ] <code>[30%]</code> Route planning
        -   [ ] Point to point
        -   [ ] "Traveling Salesmen"
    -   [ ] <code>[90%]</code> Reverse geocoding
-   [-] <code>[66%]</code> Location Logic
    -   [X] [Owntracks](https://owntracks.org/) integration
    -   [ ] <code>[50%]</code> Locational Rules
        -   [ ] <code>[75%]</code> e.g. [Silence my phone when at any movie theater](http://frdcsa.org/~andrewdo/projects/ll-rules.pl)
            
            ```Prolog
            performAction(addToPendingTasks(unsilenceCellPhoneWhenLeavingMovieTheaters)) :-
            	leaving(Agent,Location),
            	isa(Location,movieTheater),
            	hasPerformedAction(Agent,silenceCellPhoneAtMovieTheater).
            ```

-   [X] Movement Discipline


<a id="org32f4d27"></a>

### Shopping/Errands

-   [X] Shopping list management
-   [X] Integration with [financial management](#org606d62a)
    -   [X] OFX cross-referencing (Open Financial eXchange)
-   [ ] <code>[33%]</code> Integration with inventory and pantry management
-   [-] Buying
    -   [ ] Broker - Purchase/Financial Decision Support Systems
        -   [ ] <code>[10%]</code> Argumentation
            -   [ ] <code>[10%]</code> Decide what to purchase
            -   [ ] <code>[10%]</code> Decide whether to purchase
    -   [ ] Ethical consumerism
        -   [ ] <code>[25%]</code> Boycott management using Prolog representation
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


<a id="org5879be8"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork (Optical Character Recognition)
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ Git
    -   [X] Export selected documents and folders
    -   [X] Digital library system
        -   [X] Equipment manuals
    -   [X] [Book reader](https://frdcsa.org/frdcsa/internal/clear)
    -   [X] [Information search management](#org3526a82)


<a id="org606d62a"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
        -   [X] Specify recurring transactions
        -   [X] Automatically detect recurring transactions from OFX exports and plan for them
            -   e.g.
                
                ```Prolog
                promiseToPayForSpec('ELEC',andrewDougherty,'<ELECTRICCOMPANY>',dollars(93.00),[can([1]),not(onTime([3])))).
                ```
    
    -   [-] Metaplanners help develop contingency plans for different financial problems
        -   [X] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships
-   [ ] [(Personal) Accounting](http://xbrlsite.azurewebsites.net/2021/reporting-scheme/pfs/documentation/Index.html)
    -   [ ] [XBRL](http://xbrl.squarespace.com/) bookkeeping
        -   [ ] Loan and debt management
        -   [ ] Budgeting
            -   [ ] Classifying (OFX) transactions
        -   [ ] Financial reporting
            -   [ ] Regulatory compliance (say, to Social Security rules)
-   [ ] Debt tracking


<a id="org3a041f1"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)
    -   [ ] <code>[50%]</code> Recurrences for reminders to maintain equipment, supplies, plans and drills
    -   [ ] Safety plans
        -   [ ] <code>[05%]</code> Fire
        -   [ ] <code>[80%]</code> [Pandemic](https://frdcsa.org/~andrewdo/writings/behavior-tree-task-manager-for-covid-19.pdf)
        -   [ ] <code>[10%]</code> Food and water


<a id="org4ee2e48"></a>

# Major Techniques Used

-   [ ] Dialog-interface
    
    ```Prolog
    hasDialogEntry('tell <PERSON> <THING>').
    dialogInterfaceQuery(Entry)  --> ([tell];[talk,to]),grabber(Person,person),([about];[]),oneOrMore(token,Tokens),
    	{getCurrentDateTime(Now),
    	 currentAgent(Agent),
    	 Entry = assert(atTime(Now,tell(Agent,Person,Tokens)))}.
    
    curGaeilgeArSeo(tell(Agent,Person,TokenizedStatement),Gaeilge) :-
    	getGloss(Agent,AgentGloss),
    	getGloss(Person,PersonGloss),
    	atomic_list_concat(TokenizedStatement,' ',Statement),
    	atomic_list_concat([AgentGloss,told,PersonGloss,Statement],' ',Gaeilge).
    ```


<a id="orgfa5a393"></a>

# Major Technologies Used

-   [X] [SWI-Prolog](https://www.swi-prolog.org/) (Sociaal-Wetenschappelijke Informatica)
    -   [Julian](https://fifth-postulate.nl/julian/) time library
    -   [CLP(fd)](https://www.swi-prolog.org/man/clpfd.html) (Constraint Logic Programming)
    -   [QLF](https://www.swi-prolog.org/pldoc/man?section=qlf) (Quick Load Format)
-   [X] [Perl](https://www.perl.org/)
    -   [X] [YASWI](https://metacpan.org/pod/Language::Prolog::Yaswi) (Yet Another interface to SWI-Prolog) Perl<->SWI-Prolog Interface
    -   [X] [Catalyst MVC](http://catalyst.perl.org/Catalyst) (Model/View/Controller)
        -   [X] [ShinyCMS](https://shinycms.org/) (Content Management System)
    -   [X] [Mojolicious](https://www.mojolicious.org/)
-   [X] [Java](https://www.java.com/en/)
    -   [X] [JavaPengine](https://github.com/aindilis/JavaPengine) (Java<->SWI-Prolog)
    -   [X] [Jason/AgentSpeak(L)](http://jason.sourceforge.net/wp/)
        -   [X] [JPL](https://jpl7.org/) (Java Prolog Library?) Java<->SWI-Prolog
    -   [X] [Alexa](https://github.com/alexa/alexa-skills-kit-sdk-for-java) voice skill interface
-   [X] [Bash](https://www.gnu.org/software/bash/) scripting
-   [X] [Emacs integration](https://www.youtube.com/watch?v=0l3K__C9Dkc)
-   [X] [PDDL 2.2](https://planning.wiki/ref/pddl22/domain) temporal metric planning
    -   [X] [LPG-td-1.0](https://lpg.unibs.it/lpg/)
    -   [X] [OPTIC<sub>CLP</sub>](https://nms.kcl.ac.uk/planning/software/optic.html) (Optimizing Preferences and Time-Dependent Costs) (Coin-or Linear Programming)
-   [X] [Vampire-KIF](https://en.wikipedia.org/wiki/Vampire_(theorem_prover)) (Knowledge Interchange Format) ATP (Automated Theorem Proving) system
-   [X] [SUMO](https://github.com/ontologyportal/sumo)
-   [X] [OpenCyc](https://sourceforge.net/projects/opencyc/)
-   [-] [MariaDB/MySQL](https://mariadb.org/) persistence
    -   [X] Through [UniLang](https://github.com/aindilis/unilang)/[FreeKBS2](https://github.com/aindilis/freekbs2) (Universal Language) (Free Knowledge Based System v2)
    -   [ ] [Directly from SWI-Prolog using ODBC](https://github.com/aindilis/data-integration) (Open DataBase Connectivity)
-   [ ] [Inform7](https://github.com/ganelson/inform)


<a id="org0b4796f"></a>

## [README](https://github.com/aindilis/flp/blob/main/README.md)


<a id="org8bf3a00"></a>

### Broad overview of FLP

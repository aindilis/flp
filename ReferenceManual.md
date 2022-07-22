
# Table of Contents

1.  [Technical Overview](#org5bae09d)
    1.  [Workflow Manager](#org049bacf)
    2.  [Health](#org5b7008c)
        1.  [Exercise](#org0f36e0d)
        2.  [Nutrition](#orgdb67d9d)
        3.  [Medications](#org7bd65ff)
    3.  [Time Management](#org565937a)
        1.  [Recurrences](#org7503c6a)
        2.  [Calendaring](#orgb77e06b)
        3.  [Planning, Scheduling and Execution](#org3cf5a92)
    4.  [Organization](#orgaa4079f)
        1.  [Inventory Management](#org77e2be4)
        2.  [Communication](#orgdc7d44d)
        3.  [Research and Development](#org4419441)
    5.  [Self-Discipline](#org1ea9c00)
        1.  [To-Do](#orgf457e52)
        2.  [Note-Taking](#org6c4602e)
        3.  [Scheduling](#org08b5b45)
        4.  [Self-Discipline State Machine](#org8da14ec)
        5.  [Gamification](#org0f58ba5)
        6.  [Movement Discipline](#orgee3afc6)
    6.  [Transportation/Shopping/Errands](#org2013322)
        1.  [Transportation](#orga3a1f96)
        2.  [Shopping/Errands](#org33327a0)
    7.  [Document Management](#org69d5afd)
    8.  [Financial Planner](#orgba02447)
    9.  [Emergency Preparedness](#org1323427)
2.  [Major Techniques Used](#org8004c00)
3.  [Major Technologies Used](#org11812f0)


<a id="org5bae09d"></a>

# Technical Overview


<a id="org049bacf"></a>

## Workflow Manager

-   [ ] e.g.
    
        'move-to-page'(begin,'user-agenda').  
        'complete-task'('mark-off-all-completed-from-agenda').  
        'complete-task'('sort-agenda').  
        'finish-page'('user-agenda').


<a id="org5b7008c"></a>

## Health


<a id="org0f36e0d"></a>

### Exercise


<a id="orgdb67d9d"></a>

### Nutrition

1.  Meal Planner

    -   [ ] Rotating emergency food and water provisions
        -   [ ] Stock enough provisions to survive n-months
        -   [ ] Consuming the oldest staples first to prevent victuals from expiring
    -   [ ] Food pantries


<a id="org7bd65ff"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)
    -   [ ] Manage time-dependent effects of medication dosages and half-lives


<a id="org565937a"></a>

## Time Management


<a id="org7503c6a"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgb77e06b"></a>

### Calendaring

1.  Integrations

    -   With different agenda, calendaring, and planning / scheduling systems
        -   [X] Import from
            -   [X] Org-agenda
            -   [X] SPSE2 (Shared Priority System Editor v2)
            -   [X] Google Calendar
            -   [X] ICS (Internet Calendar Scheduling)
        -   [ ] Export to
            -   [ ] Org-agenda
            -   [ ] SPSE2
            -   [ ] Google Calendar
            -   [ ] ICS


<a id="org3cf5a92"></a>

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
            -   [ ] Execution of generated (PDDL/AgentSpeak(L)/Behavior Tree/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
    -   [X] BDI Agent
        -   [X] Jason/AgentSpeak(L) w/ SWIPL integration (SWI-Prolog)
            -   [X] [More than 10 BDI domains](https://github.com/aindilis/jason/tree/master/examples)

2.  Additional Planning System

    -   [-] Do system (to-do lists)
        -   [ ] Task duration estimation
        -   [X] Task classification
    -   [ ] Do-Convert system
    -   [ ] Factored planning
    -   [X] Planning systems
        -   [X] Verber
        -   [X] SPSE2
        -   [X] SPSE2-Formalog
    -   [-] Digital twin
        -   [X] WSM (World State Monitor)
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
        -   [ ] Planning ahead for bad weather
            -   [ ] e.g. Stock up on groceries before a major storm hits
            -   [ ] Weather control rules


<a id="orgaa4079f"></a>

## Organization


<a id="org77e2be4"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="orgdc7d44d"></a>

### Communication

-   Proxy all communications
    -   [-] Dossier system
        -   [-] Relationship management
            -   [ ] ACLs (Access Control Lists)
            -   [X] Talking points
        -   [X] Memcons (Memorandum of Conversation)
        -   [ ] Commitments extraction
        -   [ ] Goal/Interest/Ability extraction
    -   [-] Persuasion
        -   [ ] A/B Testing
        -   [X] [Argument mapping](https://argdown.org/)
    -   [-] Team building
        -   [ ] [Teamcore/STEAM](https://teamcore.seas.harvard.edu/publications/towards-flexible-teamwork) (a Shell for TEAMwork)
        -   [ ] [Horn-TeamLog](https://www.mimuw.edu.pl/~nguyen/HornTeamLog-long.pdf)
        -   [ ] [NL<sub>MAMS</sub>](https://link.springer.com/book/10.1007/978-3-319-39972-0) (Natural Language MultiAgent Mental Simulator)
        -   [X] [SNA](http://www.casos.cs.cmu.edu/projects/ora/software.php) (Social Network Analysis)


<a id="org4419441"></a>

### Research and Development

-   [X] Academician system
-   [X] Study system
-   [ ] ITS system (Intelligent Tutoring System)
-   [X] Seeker system


<a id="org1ea9c00"></a>

## Self-Discipline


<a id="orgf457e52"></a>

### To-Do


<a id="org6c4602e"></a>

### Note-Taking

-   [X] Org-mode
-   [ ] Cyc-Zettelkasten
-   [X] Do to-do list system


<a id="org08b5b45"></a>

### Scheduling

-   [X] PDDL (Planning Domain Definition Language)
-   [ ] Optaplanner


<a id="org8da14ec"></a>

### Self-Discipline State Machine

-   [ ] Use the digital twin and plan to choose from possible things to do


<a id="org0f58ba5"></a>

### Gamification

-   [X] Rewards for completing recurrent tasks
-   [X] Daily penalty for leaving any recurrent tasks incomplete
-   [X] Penalties for lack of movement discipline
-   [ ] Rewards for staying productive


<a id="orgee3afc6"></a>

### Movement Discipline


<a id="org2013322"></a>

## Transportation/Shopping/Errands


<a id="orga3a1f96"></a>

### Transportation

-   [ ] API look-up mashups (Application Programming Interface)
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


<a id="org33327a0"></a>

### Shopping/Errands

-   [X] Shopping list management
-   [X] Integration with financial management
    -   [X] OFX cross-referencing (Open Financial eXchange)
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


<a id="org69d5afd"></a>

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
    -   [X] [Information search management](#org4419441)


<a id="orgba02447"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
        -   [ ] Specify recurring transactions
        -   [ ] Automatically detect recurring transactions from OFX exports and plan for them
            -   e.g.
                
                    promiseToPayForSpec('ELEC',andrewDougherty,'<ELECTRICCOMPANY>',dollars(93.00),[can([1]),not(onTime([3])))).
    
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org1323427"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)
    -   [ ] Recurrences for reminders to maintain equipment, supplies, plans and drills
    -   [ ] Safety plans
        -   [ ] Fire
        -   [ ] Pandemic
        -   [ ] Food and water


<a id="org8004c00"></a>

# Major Techniques Used

-   [ ] Dialog-interface
    
        hasDialogEntry('tell <PERSON> <THING>').
        dialogInterfaceQuery(Entry)  --> ([tell];[talk,to]),grabber(Person,person),([about];[]),oneOrMore(token,Tokens),
        	{getCurrentDateTime(Now),
        	 currentAgent(Agent),
        	 Entry = assert(atTime(Now,tell(Agent,Person,Tokens)))}.
        
        curGaeilgeArSeo(tell(Agent,Person,TokenizedStatement),Gaeilge) :-
        	getGloss(Agent,AgentGloss),
        	getGloss(Person,PersonGloss),
        	atomic_list_concat(TokenizedStatement,' ',Statement),
        	atomic_list_concat([AgentGloss,told,Person,Statement],' ',Gaeilge).


<a id="org11812f0"></a>

# Major Technologies Used

-   [X] [SWI-Prolog](https://www.swi-prolog.org/) (Sociaal-Wetenschappelijke Informatica)
    -   [Julian](https://fifth-postulate.nl/julian/) time library
    -   [CLP(fd)](https://www.swi-prolog.org/man/clpfd.html) (Constraint Logic Programming)
    -   [QLF](https://www.swi-prolog.org/pldoc/man?section=qlf) (Quick Load Format)
-   [X] Perl    
    -   [X] [YASWI](https://metacpan.org/pod/Language::Prolog::Yaswi) (Yet Another interface to SWI-Prolog) Perl<->SWI-Prolog Interface
    -   [X] [Catalyst MVC](http://catalyst.perl.org/Catalyst) (Model/View/Controller)
        -   [X] [ShinyCMS](https://shinycms.org/) (Content Management System)
    -   [X] [Mojolicious](https://www.mojolicious.org/)
-   [X] Java
    -   [X] [JavaPengine](https://github.com/aindilis/JavaPengine) (Java<->SWI-Prolog)
    -   [X] [Jason/AgentSpeak(L)](http://jason.sourceforge.net/wp/)
        -   [X] [JPL](https://jpl7.org/) (Java Prolog Library?) Java<->SWI-Prolog
    -   [X] [Alexa](https://github.com/alexa/alexa-skills-kit-sdk-for-java) voice skill interface
-   [X] Bash scripting
-   [X] [Emacs integration](https://www.youtube.com/watch?v=0l3K__C9Dkc)
-   [X] PDDL 2.2 temporal metric planning
    -   [X] [LPG-td-1.0](https://lpg.unibs.it/lpg/)
    -   [X] [OPTIC<sub>CLP</sub>](https://nms.kcl.ac.uk/planning/software/optic.html) (Optimizing Preferences and Time-Dependent Costs) (Coin-or Linear Programming)
-   [X] Vampire-KIF (Knowledge Interchange Format) ATP (Automated Theorem Proving) system
-   [X] OpenCyc
-   [-] MySQL persistence
    -   [X] Through UniLang/FreeKBS2 (Universal Language) (Free Knowledge Based System v2)
    -   [ ] Directly from SWI-Prolog using ODBC (Open DataBase Connectivity)
-   [ ] [Inform7](https://github.com/ganelson/inform)


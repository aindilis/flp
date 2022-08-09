- [Technical Overview](#orga584eeb)
  - [THIS REFERENCE MANUAL IS UNDER CONSTRUCTION](#org03c9d02)
  - [Workflow Manager](#org05de443)
  - [Health](#org7c82fcd)
    - [Exercise](#orgbaf0b59)
    - [Nutrition](#orgaec23ac)
    - [Doctor's Visits and Orders](#org0f2c422)
    - [Medications](#orged835ee)
    - [Mental Health](#org1493006)
  - [Time Management](#orgca1cd2d)
    - [Recurrences](#orge30cb17)
    - [Calendaring](#org7b07439)
    - [Planning, Scheduling and Execution](#org8a8d120)
  - [Organization](#orgc12f17a)
    - [Inventory Management](#orgd7cbae5)
    - [Communication Management](#org1e808e1)
    - [Chore Charting](#org29c1498)
    - [Maintenance](#org85d1e2c)
    - [Research and Development](#org8d6692d)
  - [Self-Discipline](#org4778913)
    - [To-Do](#org6a27934)
    - [Note-Taking](#org65357a8)
    - [Scheduling](#orgf44d2d5)
    - [Self-Discipline State Machine](#org2300496)
    - [Gamification](#org4ec40bf)
    - [Movement Discipline](#org5f89184)
  - [Transportation/Shopping/Errands](#org6b5795a)
    - [Transportation](#orgac493e4)
    - [Shopping/Errands](#orgbae365f)
  - [Document Management](#orgf5f9da9)
  - [Financial Planner](#org835344b)
  - [Emergency Preparedness](#org34a7f8c)
- [Major Techniques Used](#org8821c53)
- [Major Technologies Used](#orgda8078c)
  - [[README](https://github.com/aindilis/flp/blob/main/README.md)](#org978518d)


<a id="orga584eeb"></a>

# Technical Overview


<a id="org03c9d02"></a>

## THIS REFERENCE MANUAL IS UNDER CONSTRUCTION


<a id="org05de443"></a>

## Workflow Manager

-   [ ] e.g.
    
    ```Prolog
    'move-to-page'(begin,'user-agenda').  
    'complete-task'('mark-off-all-completed-from-agenda').  
    'complete-task'('sort-agenda').  
    'finish-page'('user-agenda').  
    ```


<a id="org7c82fcd"></a>

## Health


<a id="orgbaf0b59"></a>

### Exercise


<a id="orgaec23ac"></a>

### Nutrition

1.  Meal Planner

    -   [ ] Rotating emergency food and water provisions
        -   [ ] Stock enough provisions to survive n-months
        -   [ ] Consuming the oldest staples first to prevent victuals from expiring
    -   [ ] Food pantries


<a id="org0f2c422"></a>

### Doctor's Visits and Orders


<a id="orged835ee"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)
    -   [ ] Manage time-dependent effects of medication dosages and half-lives


<a id="org1493006"></a>

### Mental Health


<a id="orgca1cd2d"></a>

## Time Management


<a id="orge30cb17"></a>

### Recurrences

How to schedule something for the last day of every month:

```Prolog
hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
	deltaTime([_Year-_Month-1],days(-1),YMD).
```


<a id="org7b07439"></a>

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


<a id="org8a8d120"></a>

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


<a id="orgc12f17a"></a>

## Organization


<a id="orgd7cbae5"></a>

### Inventory Management

-   [ ] Pantry management
-   [ ] Executable product manuals and warranties
    -   [ ] Automatically schedule maintenance

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">


<a id="org1e808e1"></a>

### Communication Management

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


<a id="org29c1498"></a>

### Chore Charting


<a id="org85d1e2c"></a>

### Maintenance


<a id="org8d6692d"></a>

### Research and Development

-   [X] Academician system
-   [X] Study system
-   [ ] ITS system (Intelligent Tutoring System)
-   [X] Seeker system


<a id="org4778913"></a>

## Self-Discipline


<a id="org6a27934"></a>

### To-Do


<a id="org65357a8"></a>

### Note-Taking

-   [X] Org-mode
-   [ ] Cyc-Zettelkasten
-   [X] Do to-do list system


<a id="orgf44d2d5"></a>

### Scheduling

-   [X] PDDL (Planning Domain Definition Language)
-   [ ] Optaplanner


<a id="org2300496"></a>

### Self-Discipline State Machine

-   [ ] Use the digital twin and plan to choose from possible things to do


<a id="org4ec40bf"></a>

### Gamification

-   [X] Rewards for completing recurrent tasks
-   [X] Daily penalty for leaving any recurrent tasks incomplete
-   [X] Penalties for lack of movement discipline
-   [ ] Rewards for staying productive


<a id="org5f89184"></a>

### Movement Discipline


<a id="org6b5795a"></a>

## Transportation/Shopping/Errands


<a id="orgac493e4"></a>

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
            
            ```Prolog
            performAction(addToPendingTasks(unsilenceCellPhoneWhenLeavingMovieTheaters)) :-
            	leaving(Agent,Location),
            	isa(Location,movieTheater),
            	hasPerformedAction(Agent,silenceCellPhoneAtMovieTheater).
            ```

-   [X] Movement Discipline


<a id="orgbae365f"></a>

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


<a id="orgf5f9da9"></a>

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
    -   [X] [Information search management](#org8d6692d)


<a id="org835344b"></a>

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


<a id="org34a7f8c"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)
    -   [ ] Recurrences for reminders to maintain equipment, supplies, plans and drills
    -   [ ] Safety plans
        -   [ ] Fire
        -   [ ] Pandemic
        -   [ ] Food and water


<a id="org8821c53"></a>

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


<a id="orgda8078c"></a>

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


<a id="org978518d"></a>

## [README](https://github.com/aindilis/flp/blob/main/README.md)

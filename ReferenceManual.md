- [Technical Overview](#org807e165)
  - [THIS REFERENCE MANUAL IS UNDER CONSTRUCTION](#orged068b2)
  - [[README](https://github.com/aindilis/flp/blob/main/README.md)](#orgfff8e25)
  - [Workflow Manager](#org7d5ccfc)
  - [Health](#org6c4caab)
    - [Exercise](#org0aeda21)
    - [Nutrition](#org748ad97)
    - [Doctor's Visits and Orders](#orgc7a8c57)
    - [Medications](#orgcd439d4)
    - [Mental Health](#orgb121017)
  - [Time Management](#org9b3bd2c)
    - [Recurrences](#orgba60ac2)
    - [Calendaring](#org55a1730)
    - [Planning, Scheduling and Execution](#org2b2aca8)
  - [Organization](#orgc87b597)
    - [Inventory Management](#org21bc376)
    - [Communication Management](#org0824fb6)
    - [Chore Charting](#org5a8fc60)
    - [Maintenance](#orgd902b57)
    - [Research and Development](#orgaa32824)
  - [Self-Discipline](#org7591279)
    - [To-Do](#org3eb4ae6)
    - [Note-Taking](#orgba8644d)
    - [Scheduling](#org9977e94)
    - [Self-Discipline State Machine](#orgf52dddf)
    - [Gamification](#orgb7c75c5)
    - [Movement Discipline](#org8b9bb7b)
  - [Transportation/Shopping/Errands](#orgad3a4d2)
    - [Transportation](#orga9474e3)
    - [Shopping/Errands](#org8b03ead)
  - [Document Management](#orga046200)
  - [Financial Planner](#orgbc6be2e)
  - [Emergency Preparedness](#orgee26e65)
- [Major Techniques Used](#orge7f157f)
- [Major Technologies Used](#org0d0d701)
  - [[README](https://github.com/aindilis/flp/blob/main/README.md)](#orga4ae439)


<a id="org807e165"></a>

# Technical Overview


<a id="orged068b2"></a>

## THIS REFERENCE MANUAL IS UNDER CONSTRUCTION


<a id="orgfff8e25"></a>

## [README](https://github.com/aindilis/flp/blob/main/README.md)


<a id="org7d5ccfc"></a>

## Workflow Manager

-   [ ] e.g.
    
    ```Prolog
    'move-to-page'(begin,'user-agenda').  
    'complete-task'('mark-off-all-completed-from-agenda').  
    'complete-task'('sort-agenda').  
    'finish-page'('user-agenda').  
    ```
-   [ ] Jason/AgentSpeak "metaplanning" system
    -   [ ] Dynamically add/remove goals and replan
    -   [ ] Contingency planning

```Jason/AgentSpeak(L)
+!quarantine(Person) <-
	?hasRoom(Person,Room);
	!atLocation(Person,Room);
	+obligation(doNotLeave(Person,Room));
	...
```


<a id="org6c4caab"></a>

## Health


<a id="org0aeda21"></a>

### Exercise

-   [ ] Interactive plan monitoring of exercises
-   [ ] Track daily progress w/ Alexa interface


<a id="org748ad97"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Multiple meal planning and preparation systems](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] [Gourmet-Formalog-Standalone](https://github.com/aindilis/gourmet-formalog-standalone/)
        -   [ ] [st0opkid's MealSolver](https://github.com/aindilis/mealsolver)
        -   [ ] [PDDL-based mealplanner](https://frdcsa.org/%7eandrewdo/projects/mealplanning/)
        -   [ ] [Interactive cooking assistant](https://frdcsa.org/%7eandrewdo/WebWiki/CookingAssistant.html)
        -   [ ] PGourmet, Gourmet, etc
    -   [ ] Rotating emergency food and water provisions
        -   [ ] Stock enough provisions to survive n-months
        -   [ ] Consuming the oldest staples first to prevent victuals from expiring
    -   [ ] Food pantries


<a id="orgc7a8c57"></a>

### Doctor's Visits and Orders


<a id="orgcd439d4"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)
    -   [ ] Manage time-dependent effects of medication dosages and half-lives
-   [ ] Medication refill tracking


<a id="orgb121017"></a>

### Mental Health


<a id="org9b3bd2c"></a>

## Time Management


<a id="orgba60ac2"></a>

### Recurrences

How to schedule something for the last day of every month:

```Prolog
hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
	deltaTime([_Year-_Month-1],days(-1),YMD).
```


<a id="org55a1730"></a>

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
            -   [ ] Google Calendar
            -   [X] ICS


<a id="org2b2aca8"></a>

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
    -   [-] Do-Convert system
        -   [X] Unique IDs for goals
        -   [ ] Track changes to goals
        -   [X] Export to SPSE2/Verb/PDDL
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


<a id="orgc87b597"></a>

## Organization


<a id="org21bc376"></a>

### Inventory Management

-   [ ] Pantry management
    -   [ ] Barcoded and un-barcoded food items
    -   [ ] Manage expected expiration dates
        -   [ ] Prevent food loss
            -   [ ] Help to schedule cooking before food expires
        -   [ ] Know how long it can stay out, or in fridge/freezer
            -   [ ] Know when to move it
-   [ ] Executable product manuals
    -   [ ] Automatically schedule maintenance
    -   [ ] Interactively perform maintenance
-   [ ] Executable product warranties
    -   [ ] Integration with planning and scheduling

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">


<a id="org0824fb6"></a>

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


<a id="org5a8fc60"></a>

### Chore Charting


<a id="orgd902b57"></a>

### Maintenance


<a id="orgaa32824"></a>

### Research and Development

-   [X] Academician system
-   [X] Study system
-   [ ] ITS system (Intelligent Tutoring System)
-   [X] Seeker system


<a id="org7591279"></a>

## Self-Discipline


<a id="org3eb4ae6"></a>

### To-Do


<a id="orgba8644d"></a>

### Note-Taking

-   [X] Org-mode
-   [ ] Cyc-Zettelkasten
-   [X] Do to-do list system


<a id="org9977e94"></a>

### Scheduling

-   [X] PDDL (Planning Domain Definition Language)
-   [ ] PDDL+ (Planning Domain Definition Language Plus)
-   [ ] Optaplanner


<a id="orgf52dddf"></a>

### Self-Discipline State Machine

-   [ ] Use the digital twin and plan to choose from possible things to do


<a id="orgb7c75c5"></a>

### Gamification

-   [X] Rewards for completing recurrent tasks
-   [X] Daily penalty for leaving any recurrent tasks incomplete
-   [X] Penalties for lack of movement discipline
-   [ ] Rewards for staying productive


<a id="org8b9bb7b"></a>

### Movement Discipline


<a id="orgad3a4d2"></a>

## Transportation/Shopping/Errands


<a id="orga9474e3"></a>

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


<a id="org8b03ead"></a>

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


<a id="orga046200"></a>

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
    -   [X] [Information search management](#orgaa32824)


<a id="orgbc6be2e"></a>

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


<a id="orgee26e65"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)
    -   [ ] Recurrences for reminders to maintain equipment, supplies, plans and drills
    -   [ ] Safety plans
        -   [ ] Fire
        -   [ ] Pandemic
        -   [ ] Food and water


<a id="orge7f157f"></a>

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


<a id="org0d0d701"></a>

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


<a id="orga4ae439"></a>

## [README](https://github.com/aindilis/flp/blob/main/README.md)

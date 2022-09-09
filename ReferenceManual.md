- [Technical Overview](#org9251141)
  - [THIS REFERENCE MANUAL IS UNDER CONSTRUCTION](#org695b69c)
- [[README](https://github.com/aindilis/flp/blob/main/README.md)](#org508629a)
  - [[Broad overview of FLP](https://github.com/aindilis/flp/blob/main/README.md)](#orgb94f941)
- [Reference Manual Contents](#org433c7fc)
  - [Workflow Manager](#org6219963)
  - [Health](#org2c076d7)
    - [Evidence-Based Wellness](#org0bc38c1)
    - [Exercise](#orgf252f96)
    - [Nutrition](#org03ac8e2)
    - [Doctor's Visits and Orders](#orgda4f23e)
    - [Medications](#org4d7573d)
    - [Mental Health](#org14319d2)
  - [Time Manapgement](#orgd95f646)
    - [Recurrences](#org67686e0)
    - [Calendaring](#org1a4b890)
    - [Planning, Scheduling and Execution](#org710edae)
  - [Organization](#orge2014bb)
    - [Inventory Management](#orga7736d2)
    - [Communication Management](#org40cfa28)
    - [Chore Charting](#org174925c)
    - [Maintenance](#org765e5db)
    - [Research and Development](#org4f69563)
  - [Self-Discipline](#org9eaf367)
    - [To-Do](#org924459b)
    - [Note-Taking](#orgca478b6)
    - [Scheduling](#orgd299cd3)
    - [Self-Discipline State Machine](#orgc35dc6a)
    - [Gamification](#org75cadda)
    - [Movement Discipline](#orgea1d056)
  - [Transportation/Shopping/Errands](#orgd482d61)
    - [Transportation](#orgf4cf865)
    - [Shopping/Errands](#orgdb4b52a)
  - [Document Management](#orge15a66a)
  - [Financial Planner](#orge6f2745)
  - [Emergency Preparedness](#orgfd6387f)
- [Major Techniques Used](#orgdf67c5d)
- [Major Technologies Used](#org5b74115)
  - [[README](https://github.com/aindilis/flp/blob/main/README.md)](#org1ea669c)
    - [[Broad overview of FLP](https://github.com/aindilis/flp/blob/main/README.md)](#org5ec1d0d)


<a id="org9251141"></a>

# Technical Overview


<a id="org695b69c"></a>

## THIS REFERENCE MANUAL IS UNDER CONSTRUCTION


<a id="org508629a"></a>

# [README](https://github.com/aindilis/flp/blob/main/README.md)


<a id="orgb94f941"></a>

## [Broad overview of FLP](https://github.com/aindilis/flp/blob/main/README.md)


<a id="org433c7fc"></a>

# Reference Manual Contents


<a id="org6219963"></a>

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


<a id="org2c076d7"></a>

## Health


<a id="org0bc38c1"></a>

### Evidence-Based Wellness

1.  Data collection

    -   [ ] Opt-in anonymized data sharing
        -   [ ] With users' fine-grained consent
        -   [ ] With secure multiparty computation

2.  Prevention / early detection

    -   [ ] Users' known conditions/symptoms, sorted by probable conditions/symptoms by conditional probability, impact/severity
        -   [ ] Observations substantiated by FLP data collection
        -   [ ] Medical KBS integrations, possibly: MedDRA, LEX, OpenGALEN, RxNorm, UMLS, etc


<a id="orgf252f96"></a>

### Exercise

-   [ ] <code>[33%]</code> Interactive plan monitoring of exercises
-   [ ] <code>[66%]</code> Track daily progress w/ Alexa interface


<a id="org03ac8e2"></a>

### Nutrition

1.  Meal Planner

    -   [-] [Multiple meal planning and preparation systems](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] <code>[50%]</code> [Gourmet-Formalog-Standalone](https://github.com/aindilis/gourmet-formalog-standalone/)
            -   [ ] Using MM recipe archive ([SOAR](https://www.recipesource.com/), etc), [FDC](https://fdc.nal.usda.gov/), [OpenFoodTox](https://www.efsa.europa.eu/en/data-report/chemical-hazards-database-openfoodtox), [Basket](https://github.com/fodmap-diet/basket) (Meal Master, Searchable Online Archive of Recipes, Food Data Central)
        -   [ ] [st0opkid's MealSolver](https://github.com/aindilis/mealsolver)
        -   [ ] <code>[66%]</code> [PDDL-based mealplanner](https://frdcsa.org/%7eandrewdo/projects/mealplanning/)
        -   [ ] <code>[25%]</code> [Interactive cooking assistant](https://frdcsa.org/%7eandrewdo/WebWiki/CookingAssistant.html)
        -   [X] [PGourmet](https://altruisticsoftware.org/frdcsa/internal/pgourmet/)
        -   [ ] [Gourmet](https://altruisticsoftware.org/frdcsa/internal/gourmet)
        -   [ ] etc
    -   [ ] Rotating emergency food and water provisions
        -   [ ] Stock enough provisions to survive n-months
        -   [ ] Consuming the oldest staples first to prevent victuals from expiring
    -   [ ] Food pantries


<a id="orgda4f23e"></a>

### Doctor's Visits and Orders

-   [ ] [Medical diagnostics](https://github.com/timhannifan/symptom-tree/issues/1)
-   [ ] Following orders
    -   [ ] Using [Machine Reading Comprehension](https://paperswithcode.com/task/machine-reading-comprehension)
    -   [ ] Converting orders into an SPSE2 planning context


<a id="org4d7573d"></a>

### Medications

-   [ ] <code>[30%]</code> [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)
    -   [ ] <code>[30%]</code> Manage time-dependent effects of medication dosages and half-lives
-   [ ] <code>[33%]</code> Medication refill tracking
-   [X] Medication reminders and recording


<a id="org14319d2"></a>

### Mental Health

-   [ ] Symptoms for symptoms
    -   [ ] [Executive Function](https://frdcsa.org/~andrewdo/projects/some-humanitarian-systems.html)
    -   [ ] Negative self talk
        -   [ ] <code>[25%]</code> Rewrites negative self talk using LLM prompts (Large Language Models)
    -   [ ] Low productivity
        -   [ ] <code>[100%]</code> Elicits how the user is feeling
        -   [ ] <code>[75%]</code> Uses NLI/RTE to fetch from treatment DB (Natural Language Inference / Recognizing Textual Entailment)
-   [ ] Systems for conditions
    -   [ ] ADHD
        -   [ ] Distraction ontology
            -   [ ] <code>[40%]</code> (Pre/re)active planning using [WOPR](https://github.com/aindilis/free-life-planner/blob/master/data-git/systems/planning/free_wopr.pl) to minimize or mitigate distractions
        -   [ ] <code>[30%]</code> different FLP modes using environmental anchors
        -   [X] Automatic priming and transitions
            -   [X] Change smart lighting colors for different modes, like working, relaxing, etc
            -   [X] Managing music for different modes (using Audacious playlists)
    -   [ ] Autism
        -   [ ] Using different tools for and from [Computational Autism](https://link.springer.com/book/10.1007/978-3-319-39972-0)
            -   [ ] [Supplemental materials](https://storage.googleapis.com/springer-extras/zip/2016/978-3-319-39972-0.zip) like NL<sub>MAMS</sub>
        -   [ ] Social reasoning prostheses
            -   [ ] [Audience](https://github.com/aindilis/audience), Mach, SocBot, [IRC-KB](https://github.com/aindilis/irc-kb), [POSI](https://frdcsa.org/~andrewdo/writings/flourish-2009.pdf), PPOSI, Social Intelligence, etc
    -   [ ] Schizophrenia
    -   [ ] etc


<a id="orgd95f646"></a>

## Time Manapgement


<a id="org67686e0"></a>

### Recurrences

How to schedule something for the last day of every month:

```Prolog
hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
	deltaTime([_Year-_Month-1],days(-1),YMD).
```


<a id="org1a4b890"></a>

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

2.  Financial Calendar

    -   [X] Show on calendar possible date and time ranges for recurring transactions


<a id="org710edae"></a>

### Planning, Scheduling and Execution

1.  Planners

    -   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) planning
        -   [X] LPG<sub>TD</sub><sub>1</sub><sub>0</sub>, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, OPTIC<sub>CLP</sub>, CLG, Colin2<sub>CLP</sub>, HSPS, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, SGPlan<sub>522</sub>
            -   [X] [More than 200 PDDL life planning domains](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/templates)
        -   [X] [SPSE2](https://frdcsa.org/visual-aid/pdf/Temporal-Planning-and-Inferencing-for-Personal-Task-Management-with-SPSE2.pdf)
        -   [X] [PDDL plan interactive execution monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)
        -   [X] PSEx3 integrated tasks and finances system
    -   [X] Contingent planning
        -   [X] [DNFct](https://github.com/aindilis/dnfct-frdcsa/)
            -   [X] [More than 10 contingent life planning domains](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/templates/contingent/dnfct)
        -   [ ] <code>[33%]</code> [AP/3T](https://github.com/aindilis/3t-frdcsa)
    -   [ ] <code>[90%]</code> [Behavior tree reactive planning](https://frdcsa.org/~andrewdo/writings/behavior-tree-task-manager-for-covid-19.pdf)
        -   [ ] <code>[90%]</code> [Plan Monitor](https://github.com/aindilis/plan-monitor)
            -   [ ] <code>[40%]</code> Execution of generated (PDDL/AgentSpeak(L)/Behavior Tree/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
    -   [X] BDI Agent
        -   [X] Jason/AgentSpeak(L) w/ SWIPL integration (SWI-Prolog)
            -   [X] [More than 10 BDI domains](https://github.com/aindilis/jason/tree/master/examples)

2.  Additional Planning System

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
        -   [X] Tracks from a growing list of elicited habits, records when engaging in / avoiding behaviors
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
    -   <code>[33%]</code> PDDL Standard domain library (basekb)
        -   [X] [agent, biomaintenance, chores, deontic, economic, food, hygiene, misc, security, space, tool, work](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/worlds/basekb)
    -   <code>[33%]</code> Behavior Tree standard library
        -   [X] deliveries, electrical, errands, exercise, financial, food-pantries, groceries, hospitalization, hygiene, meal-planning, medication, movement-discipline, paperwork, plumbing, security, sickness, sleep, trip-planning
    -   [ ] <code>[10%]</code> Household emergency preparedness
        -   [ ] Planning ahead for bad weather
            -   [ ] e.g. Stock up on groceries before a major storm hits
            -   [ ] <code>[50%]</code> Weather control rules


<a id="orge2014bb"></a>

## Organization


<a id="orga7736d2"></a>

### Inventory Management

-   [ ] <code>[66%]</code> Pantry management
    -   [ ] <code>[75%]</code> Barcoded and un-barcoded food items
    -   [ ] <code>[10%]</code> Manage expected expiration dates
        -   [ ] Prevent food loss
            -   [ ] <code>[25%]</code> Help to schedule cooking before food expires
        -   [ ] [Know how long it can stay out, or in fridge/freezer](https://frdcsa.org/~andrewdo/projects/mealplanning/freezer_cooking.pl.txt)
            -   [ ] <code>[25%]</code> Know when to move it
-   [ ] <code>[15%]</code> Executable product manuals
    -   [ ] <code>[90%]</code> Automatically schedule maintenance
    -   [ ] <code>[10%]</code> Interactively perform maintenance
-   [ ] Executable product warranties
    -   [ ] Integration with planning and scheduling

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">


<a id="org40cfa28"></a>

### Communication Management

-   [Proxy all communications](https://github.com/aindilis/audience)
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
        -   [ ] [Teamwork via Collective Intention](https://github.com/QuMuLab/teamwork-via-collective-intention)
        -   [X] [SNA](http://www.casos.cs.cmu.edu/projects/ora/software.php) (Social Network Analysis)


<a id="org174925c"></a>

### Chore Charting


<a id="org765e5db"></a>

### Maintenance


<a id="org4f69563"></a>

### Research and Development

-   [X] Academician system
-   [X] Study system
-   [ ] ITS system (Intelligent Tutoring System)
-   [X] Seeker system


<a id="org9eaf367"></a>

## Self-Discipline


<a id="org924459b"></a>

### To-Do

-   [ ] <code>[50%]</code> Org and Org-agenda
-   [ ] <code>[75%]</code> [Do system (to-do lists)](https://github.com/aindilis/do)
    -   [ ] <code>[50%]</code> Do-convert
        -   [X] Track millions of goals
        -   [ ] <code>[90%]</code> Convert sexps to Prolog w/ QLF-persistence
    -   [ ] <code>[50%]</code> [Do-convert-logic](//github.com/aindilis/do-convert-logic)
        -   [X] Unique IDs for goals
        -   [X] [Track changes to goals](https://github.com/aindilis/do-convert-logic)
        -   [X] Export to SPSE2/Verb/PDDL
    -   [ ] <code>[33%]</code> Task classification, commitment extraction, dependency elicitation, duration estimation, ontology, prioritization, tagging
-   [ ] Miscellaneous other partially completed to-do systems
    -   [ ] ([Score](https://github.com/aindilis/score), Lightspeed, [Normal-Form](https://github.com/aindilis/normal-form)/Spark Todo, PSE, Agenda, System-Planning, crontab, Task-Manager, PSE-x, todo-list-processor, SPSE2, SPSE2-Formalog, FLP, Do-Cyc, Do-Pl)


<a id="orgca478b6"></a>

### Note-Taking

-   [X] Org-mode
-   [ ] <code>[10%]</code> Cyc-Zettelkasten


<a id="orgd299cd3"></a>

### Scheduling

-   [X] PDDL (Planning Domain Definition Language)
-   [ ] PDDL+ (Planning Domain Definition Language Plus)
-   [ ] <code>[05%]</code> Optaplanner


<a id="orgc35dc6a"></a>

### Self-Discipline State Machine

-   [ ] <code>[33%]</code> Use the digital twin and plan to choose from possible things to do


<a id="org75cadda"></a>

### Gamification

-   [X] Rewards for completing recurrent tasks
-   [X] Daily penalty for leaving any recurrent tasks incomplete
-   [X] Penalties for lack of movement discipline
-   [ ] <code>[50%]</code> Rewards for staying productive


<a id="orgea1d056"></a>

### Movement Discipline


<a id="orgd482d61"></a>

## Transportation/Shopping/Errands


<a id="orgf4cf865"></a>

### Transportation

-   [ ] <code>[33%]</code> API look-up mashups (Application Programming Interface)
    -   [ ] <code>[90%]</code> Hours of operation
        -   [ ] <code>[90%]</code> Stores/offices/etc
    -   [ ] <code>[30%]</code> Weather
    -   [ ] <code>[30%]</code> Route planning
        -   [ ] Point to point
        -   [ ] "Traveling Salesman"
    -   [ ] <code>[90%]</code> Reverse geocoding
-   [-] <code>[66%]</code> Location Logic
    -   [X] [Owntracks](https://owntracks.org/) integration
    -   [ ] <code>[50%]</code> Locational Rules
        -   [ ] <code>[75%]</code> e.g. [Silence my phone when at any movie theater](http://frdcsa.org/~andrewdo/projects/ll-rules.pl)
            
            ```Prolog
            performAction(addToPendingTasks(Agent,unsilenceCellPhoneWhenLeavingMovieTheaters)) :-
            	currentAgent(Agent),
            	leaving(Agent,Location),
            	isa(Location,movieTheater),
            	hasPerformedAction(Agent,silenceCellPhoneAtMovieTheater).
            ```

-   [X] Movement Discipline


<a id="orgdb4b52a"></a>

### Shopping/Errands

-   [X] Shopping list management
-   [X] Integration with [financial management](#orge6f2745)
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


<a id="orge15a66a"></a>

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
    -   [X] [Information search management](#org4f69563)


<a id="orge6f2745"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
        -   [X] Specify recurring transactions
        -   [X] Automatically detect recurring transactions from OFX exports and plan for them
            -   e.g.
                
                ```Prolog
                promiseToPayForSpec('ELEC',andrewDougherty,'<ELECTRICCOMPANY>',dollars(93.00),[can([1]),not(onTime([3])))).
                ```
        
        -   [X] View expected financial transactions along with primary agenda on a calendar
    -   [-] Metaplanners help develop contingency plans for different financial problems
        -   [X] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships
    -   <code>[75%]</code> SPSE2->PSEx3 export (Planning, Scheduling and Execution System (Extended), version 3)
        -   <code>[75%]</code> Integrating financial reasoning and other domains, with SPSE's to-do dependency graph
-   [ ] [(Personal) Accounting](http://xbrlsite.azurewebsites.net/2021/reporting-scheme/pfs/documentation/Index.html)
    -   [ ] [XBRL](http://xbrl.squarespace.com/) bookkeeping
        -   [ ] Loan and debt management
        -   [ ] Budgeting
            -   [ ] Classifying (OFX) transactions
        -   [ ] Financial reporting
            -   [ ] Regulatory compliance (say, to Social Security rules)
-   [ ] Debt tracking


<a id="orgfd6387f"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)
    -   [ ] <code>[50%]</code> Recurrences for reminders to maintain equipment, supplies, plans and drills
    -   [ ] Safety plans
        -   [ ] <code>[05%]</code> Fire
        -   [ ] <code>[80%]</code> [Pandemic](https://frdcsa.org/~andrewdo/writings/behavior-tree-task-manager-for-covid-19.pdf)
        -   [ ] <code>[10%]</code> Food and water


<a id="orgdf67c5d"></a>

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


<a id="org5b74115"></a>

# Major Technologies Used

-   [-] [SWI-Prolog](https://www.swi-prolog.org/) (Sociaal-Wetenschappelijke Informatica)
    -   [X] [Julian](https://fifth-postulate.nl/julian/) time library
    -   [X] [CLP(fd)](https://www.swi-prolog.org/man/clpfd.html) (Constraint Logic Programming)
    -   [ ] <code>[50%]</code> [QLF](https://www.swi-prolog.org/pldoc/man?section=qlf) (Quick Load Format)
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
    -   [ ] [<code>[50%]</code> Directly from SWI-Prolog using ODBC](https://github.com/aindilis/data-integration) (Open DataBase Connectivity)
-   [ ] <code>[33%]</code> [Inform7](https://github.com/ganelson/inform)


<a id="org1ea669c"></a>

## [README](https://github.com/aindilis/flp/blob/main/README.md)


<a id="org5ec1d0d"></a>

### [Broad overview of FLP](https://github.com/aindilis/flp/blob/main/README.md)


# Table of Contents

1.  [Technical Overview](#org49192db)
    1.  [THIS REFERENCE MANUAL IS UNDER CONSTRUCTION](#org7a9b7cf)
2.  [Links](#orgd6b78fd)
3.  [You are at the ReferenceManual.md](#orgf6ce10d)
4.  [Reference Manual Contents](#orgab2cc80)
    1.  [Workflow Manager](#orgda0a291)
    2.  [Health](#orgc6f0ad6)
        1.  [Evidence-Based Wellness](#orgf52ffcf)
        2.  [Exercise](#orgdb51c75)
        3.  [Nutrition](#orgb402331)
        4.  [Doctor's Visits and Orders](#org1926a29)
        5.  [Medications](#orgde751c3)
        6.  [Mental Health](#org4517598)
    3.  [Time Management](#orga723652)
        1.  [Recurrences](#org2dba14c)
        2.  [Calendaring](#orgb0419fa)
        3.  [Planning, Scheduling and Execution](#orgf09d916)
    4.  [Organization](#orgc29a353)
        1.  [Inventory Management](#org8516921)
        2.  [Communication Management](#orgfdfb239)
        3.  [Chore Charting](#org39e8bcd)
        4.  [Maintenance](#org066e1a5)
        5.  [Smart Home](#org1819d32)
        6.  [Research and Development](#org10c6e15)
    5.  [Self-Discipline](#org77893b6)
        1.  [To-Do](#org8511aab)
        2.  [Note-Taking](#orga682196)
        3.  [Scheduling](#org4d2238d)
        4.  [Self-Discipline State Machine](#org0c2133e)
        5.  [Gamification](#org0f2ffe2)
        6.  [Movement Discipline](#org9194323)
    6.  [Transportation/Shopping/Errands](#org9ef4493)
        1.  [Transportation](#org59d3408)
        2.  [Shopping/Errands](#org648e373)
    7.  [Document Management](#org713d9e1)
    8.  [Financial Planner](#orgb282d40)
    9.  [Emergency Preparedness](#org976f688)
5.  [Major Techniques Used](#orgdc43b1f)
6.  [Major Technologies Used](#org855bdd5)
    1.  [README](#org1fb583b)
        1.  [Broad overview of FLP](#org9c423d6)
        2.  [Finish elaboration of finance and health planner capabilities](#org2ff5086)


<a id="org49192db"></a>

# Technical Overview


<a id="org7a9b7cf"></a>

## THIS REFERENCE MANUAL IS UNDER CONSTRUCTION


<a id="orgd6b78fd"></a>

# Links

-   Please note that for now there are (rather confusingly) four
    important documents to see:
    -   The [original deprecated Free Life Planner repo](https://github.com/aindilis/free-life-planner#readme) (including screenshots and links)
    
    -   The new [ReferenceManual.md](https://github.com/aindilis/flp/blob/main/ReferenceManual.md) (the most detailed overview of FLP)
    
    -   The new [README.md](https://github.com/aindilis/flp/blob/main/README.md) (a less detailed summary and links)

-   I am going to condense these into a single document real soon now.
    -   The paper - "The Free Life Planner: A Virtual Secondary Social Safety Net" (will link to when it becomes available)


<a id="orgf6ce10d"></a>

# You are at the ReferenceManual.md


<a id="orgab2cc80"></a>

# Reference Manual Contents


<a id="orgda0a291"></a>

## Workflow Manager

-   [ ] <code>[35%]</code> e.g.
    
        'move-to-page'(begin,'user-agenda').
        'complete-task'('mark-off-all-completed-from-agenda').
        'complete-task'('sort-agenda').  'finish-page'('user-agenda').
-   [ ] <code>[60%]</code> [JASWIPL "metaplanning" systems integration](https://github.com/aindilis/jason/tree/master/examples/executive-function-adapter) (Jason/AgentSpeak(L)<->SWIPL)
-   [ ] <code>[30%]</code> [Jason/AgentSpeak(L)<->Python<->(SuperAGI|BabyAGI|AutoGPT|MetaGPT|BeeBot) LLM-based autonomous agents](https://github.com/aindilis/jason/tree/master/examples/python-adapter)
    
    -   [ ] <code>[20%]</code> Dynamically add/remove goals and replan
    -   [ ] <code>[60%]</code> Contingency planning
        -   [X] WebUI to select ground or unground contingency triggers
            -   [X] Code Llama generation of NL contingency plans for triggers (Natural Language)
    
        +!quarantine(Person) <-
        	?hasRoom(Person,Room);
        	!atLocation(Person,Room);
        	+prohibited((move(Person,Location),Location \= Room));
        	...


<a id="orgc6f0ad6"></a>

## Health


<a id="orgf52ffcf"></a>

### Evidence-Based Wellness

1.  Data collection

    -   [ ] Opt-in anonymized data sharing
        -   [ ] With users' fine-grained consent
        -   [ ] With secure multiparty computation

2.  Prevention / early detection

    -   [ ] Take users' known conditions/symptoms, estimate conditional probabilities of additional conditions/symptoms
        -   [ ] Sorted by a norm on or MCDA for likelihood and impact/severity (multi-criteria decision analysis)
        -   [ ] Observations substantiated by FLP data collection
        -   [ ] Medical KBS integrations, possibly: MedDRA, LEX, OpenGALEN, RxNorm, UMLS, etc
        -   [ ] Medical KG integrations, possibly: [Hetionet](https://het.io), [PDT](https://patternslanguage.com/articles/f/a-personal-digital-twin-forhealthcare) (Personal Digital Twin)


<a id="orgdb51c75"></a>

### Exercise

-   [ ] <code>[33%]</code> Interactive plan monitoring of exercises
-   [ ] <code>[66%]</code> Track daily progress w/ Alexa interface


<a id="orgb402331"></a>

### Nutrition

1.  Meal Planner

    -   [ ] <code>[40%]</code> Seamless integration with FLP's generalized action planning systems
    -   [ ] Many [meal planning resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] [Multiple meal planning and preparation systems](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] <code>[50%]</code> [Gourmet-Formalog-Standalone](https://github.com/aindilis/gourmet-formalog-standalone/)
            -   [ ] Using [OpenFoodTox](https://www.efsa.europa.eu/en/data-report/chemical-hazards-database-openfoodtox), [Basket](https://github.com/fodmap-diet/basket)
        -   [ ] [st0opkid's MealSolver](https://github.com/aindilis/mealsolver)
        -   [ ] <code>[66%]</code> [PDDL-based mealplanner](https://frdcsa.org/%7eandrewdo/projects/mealplanning/)
        -   [ ] <code>[25%]</code> [Interactive cooking assistant](https://frdcsa.org/%7eandrewdo/WebWiki/CookingAssistant.html)
        -   [X] [PGourmet](https://altruisticsoftware.org/frdcsa/internal/pgourmet/)
        -   [ ] [Gourmet](https://altruisticsoftware.org/frdcsa/internal/gourmet)
    -   [ ] <code>[85%]</code> Nutrition lookup
        -   [X] Using [FDC](https://fdc.nal.usda.gov/) csvs converted to Prolog KB (Food Data Central)
        -   [X] Using Nutritionix
            -   [ ] Working (but offline due to air-gapping development server)
    -   [ ] [Inventory Management](#org8516921)
        -   [ ] User modeling
            -   [ ] Self-discipline coach software
                -   [ ] Understanding psychology of users' relationships to food
            -   [X] Helping w/ Portion control
                -   [X] Door sensor alerts on fridge and freezer
                -   [ ] <code>[20%]</code> Follow up dialog regarding intent when fridge and freezer accessed
                -   [ ] [Gamification](#org0f2ffe2)
            -   [ ] Specifically checking for common symptoms known to affect the user, like gerd, lactose intolerance, etc
                -   [ ] Inference existence of food sensitivities
            -   [ ] Nutritional temporal records
                -   [ ] Privacy preserving
                -   [ ] Integration with health temporal records
                    -   [ ] Empirical analysis of nutritional factors associated with medical conditions
                        -   [ ] [Hetionet](https://het.io)
                    -   [ ] Detection and allowance for genetic factors affecting diet and heatlh
    -   [ ] Ensuring food safety
        -   [ ] Semi-automatic RKF of textual knowledge bases regarding food safety (Rapid Knowledge Formation)
    -   [ ] <code>[20%]</code> Logging and planning of macros
    -   [ ] Specialty Diets
        -   [ ] <code>[33%]</code> Food ontology
            -   [ ] Food properties encoded into Prolog factbase
                -   [ ] Medical properties such as allergies
                -   [ ] Food storage duration (in various conditions, such as freezer) knowledge
                -   [ ] Using word embeddings for food similarity
            -   [ ] Food substitutions (changing, adding or canceling)
            -   [ ] Normalization / mapping NL descriptions to entities in a KB (Natural Language)
                -   [ ] Parsers
                    -   [ ] NL recipes to planning problems
                    -   [ ] Normalizing parsers
                        -   [ ] Ingredients to food
                        -   [ ] Food data to food
                        -   [ ] Branded foods to ingredients
            -   [ ] Integration with knowledge sources
                -   [X] WordNet
                -   [X] OpenCyc
        -   [ ] Help with ethical diets like vegan, pescatarian, etc
        -   [ ] Help with medical diets like diabetic, missing gall bladder, etc
    -   [ ] Recipe manager
        -   [ ] <code>[95%]</code> Using MM recipe archive of 150,000 recipes from [SOAR](https://www.recipesource.com/), (Meal Master, Searchable Online Archive of Recipes,)
        -   [ ] Integration of a separate list of recipe archives containing an additional 150,000 recipes
        -   [ ] [Recommender system / collaborative filtering](https://frdcsa.org/~andrewdo/WebWiki/RecipeRecommendationSystem.html) of recipes
    -   [ ] Freezer cooking
        -   [ ] Reduces by >= 4X both cost and prep time
    -   [ ] <code>[50%]</code> Cooking Assistant
        -   [ ] <code>[50%]</code> Automatic conversion of recipes to BTs (Behavior Trees)
            -   [ ] CURD (Carnegie Mellon University Recipe Database)
            -   [ ] Semafor parser
        -   [ ] Walking the user through resultant BTs using [Plan-Monitor](https://github.com/aindilis/plan-monitor)
    -   [ ] Food style and preference learning
        -   [ ] Estimate when the user is likely to get tired of some recipe or ingredient(s)
    -   [ ] Comprehensive meal contingent plan generation
    -   [ ] Planning tool to avoid food spoilage and expiration in various storage conditions
        -   [X] Door sensor alerts on fridge and freezer       
            -   [ ] <code>[20%]</code> Follow up dialog regarding intent when fridge and freezer accessed
                -   [X] Ask user why they triggered door sensors
        -   [ ] Calculate remaining time before spoilage based on storage condition temporal history
    -   [ ] Rotating emergency food and water provisions
        -   [ ] Stock enough provisions to survive n-months
        -   [ ] Consuming the oldest staples first to prevent victuals from expiring
    -   [ ] Food pantries
    -   [ ] <code>[50%]</code> Receipt tracker
        -   [ ] <code>[25%]</code> Bill splitter


<a id="org1926a29"></a>

### Doctor's Visits and Orders

-   [ ] [Medical diagnostics](https://github.com/timhannifan/symptom-tree/issues/1)
-   [ ] Following orders
    -   [ ] Scan into [Document Management System](#org713d9e1)
    -   [ ] <code>[90%]</code> Ensuring compliance via [Machine Reading Comprehension](https://paperswithcode.com/task/machine-reading-comprehension)
        -   [X] Using WizardLM to extract instructions from documents
        -   [X] Converting orders into an BT (Behavior Tree)
        -   [ ] Converting orders into an SPSE2 planning context


<a id="orgde751c3"></a>

### Medications

-   [ ] <code>[30%]</code> [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)
    -   [ ] <code>[30%]</code> Manage time-dependent effects of medication dosages and half-lives
-   [ ] <code>[33%]</code> Medication refill tracking
-   [X] Medication reminders and recording


<a id="org4517598"></a>

### Mental Health

-   [ ] Systems for symptoms
    -   [ ] [Executive function](https://github.com/aindilis/jason/tree/master/examples/executive-function-adapter)
    -   [ ] Negative self talk
        -   [ ] <code>[50%]</code> Rewrites negative self talk using LLM prompts (Large Language Models)
    -   [ ] Low productivity
        -   [X] Elicits how the user is feeling
        -   [ ] <code>[75%]</code> Uses NLI/RTE to fetch from treatment DB (Natural Language Inference / Recognizing Textual Entailment)
-   [ ] Systems for conditions
    -   [ ] ADHD (Attention-Deficit/Hyperactivity Disorder)
        -   [ ] Distraction ontology
            -   [ ] <code>[40%]</code> (Pre/re)active planning using [WOPR](https://github.com/aindilis/free-life-planner/blob/master/data-git/systems/planning/free_wopr.pl) to minimize or mitigate distractions (War Operation Plan Response)
        -   [ ] <code>[30%]</code> different FLP modes using environmental anchors
        -   [X] Automatic priming and transitions
            -   [X] Change smart lighting colors for different modes, like working, relaxing, etc
                -   [X] Auto detection of working, relaxing, etc
            -   [X] Managing music for different modes (using playlists)
    -   [ ] Autism
        -   [ ] Using different tools for and from [Computational Autism](https://link.springer.com/book/10.1007/978-3-319-39972-0)
            -   [ ] [Supplemental materials](https://storage.googleapis.com/springer-extras/zip/2016/978-3-319-39972-0.zip) like NL<sub>MAMS</sub>
        -   [ ] Social reasoning prostheses
            -   [ ] [Audience](https://github.com/aindilis/audience), Mach, SocBot, [IRC-KB](https://github.com/aindilis/irc-kb), [POSI](https://frdcsa.org/~andrewdo/writings/flourish-2009.pdf), PPOSI, Social Intelligence, etc
    -   [ ] Schizophrenia
    -   [ ] etc


<a id="orga723652"></a>

## Time Management


<a id="org2dba14c"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgb0419fa"></a>

### Calendaring

1.  Integrations

    -   [ ] With different agenda, calendaring, and planning / scheduling systems
        -   [X] Import from
            -   [X] Org-agenda
            -   [X] SPSE2 (Shared Priority System Editor v2)
            -   [X] Google Calendar
            -   [X] ICS (Internet Calendar Scheduling)
        -   [ ] Export to
            -   [X] Org-agenda
            -   [ ] <code>[85%]</code> SPSE2
            -   [ ] <code>[33%]</code> Google Calendar
            -   [X] ICS

2.  Financial Calendar

    -   [X] Show on calendar possible date and time ranges for recurring transactions


<a id="orgf09d916"></a>

### Planning, Scheduling and Execution

1.  Planners

    -   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) planning
        -   [X] LPG<sub>TD</sub><sub>1</sub><sub>0</sub>, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, OPTIC<sub>CLP</sub>, CLG, Colin2<sub>CLP</sub>, HSPS, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, SGPlan<sub>522</sub>
            -   [X] [More than 200 PDDL life planning domains](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/templates)
        -   [X] [SPSE2](https://frdcsa.org/visual-aid/pdf/Temporal-Planning-and-Inferencing-for-Personal-Task-Management-with-SPSE2.pdf)
        -   [X] [PDDL plan interactive execution monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)
        -   [X] PSEx3 integrated tasks and finances system
    -   [X] Contingent planning
        -   [X] [DNFct](https://github.com/aindilis/dnfct-frdcsa/) (Disjunctive Normal Form: Contingent)
            -   [X] [More than 10 contingent life planning domains](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/templates/contingent/dnfct)
        -   [ ] <code>[33%]</code> [AP/3T](https://github.com/aindilis/3t-frdcsa) (Adversarial Planner)
    -   [ ] <code>[90%]</code> [Behavior tree reactive planning](https://frdcsa.org/~andrewdo/writings/behavior-tree-task-manager-for-covid-19.pdf)
        -   [ ] <code>[90%]</code> [Plan Monitor](https://github.com/aindilis/plan-monitor)
            -   [ ] <code>[33%]</code> [More than 15 BT domains](#orgce2a390)
            -   [ ] <code>[40%]</code> Execution of generated (PDDL/AgentSpeak(L)/Behavior Tree/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
    -   [X] BDI Agent (Belief-Desire-Intention)
        -   [X] Jason/AgentSpeak(L) w/ SWIPL integration (SWI-Prolog)
            -   [X] [More than 10 BDI domains](https://github.com/aindilis/jason/tree/master/examples)
        -   [ ] <code>[30%]</code> [Jason/AgentSpeak(L)<->Python<->(SuperAGI|BabyAGI|AutoGPT|MetaGPT|BeeBot) LLM-based autonomous agents](https://github.com/aindilis/jason/tree/master/examples/python-adapter)
    -   [ ] LLM-based autonomous agents
        -   [ ] [SuperAGI<->Jason/AgentSpeak(L)<->SWIPL<->FLP<->FRDCSA<->OpenCyc integration](https://lablab.ai/event/autonomous-agents-hackathon/frdcsa/agent-speak-toolkitbuilder-and-autopacker)

2.  Additional Planning System

    -   [ ] Factored planning
    -   [X] Planning systems
        -   [X] Verber
        -   [X] SPSE2
        -   [X] SPSE2-Formalog
    -   [ ] Digital twin
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
    -   [ ] Gamification
        -   [X] [Score](https://github.com/aindilis/score)
        -   [ ] Rewards/Penalties
        -   [X] [Manager](https://github.com/aindilis/manager)
        -   [ ] <code>[50%]</code> Adherence tracker
            -   [ ] Color coded labelled rectangles indicating the last accessed time of various FLP systems
                -   [ ] Determine which systems are not being used correctly
                -   [ ] Determine which sensors have stopped working (e.g. dead battery)

3.  Some domains

    -   [ ] <code>[25%]</code> Plan cycles (cycle)
    -   [ ] <code>[33%]</code> PDDL Standard domain library (basekb)
        -   [X] [agent, biomaintenance, chores, deontic, economic, food, hygiene, misc, security, space, tool, work](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/worlds/basekb)
    -   [ ] <code>[33%]</code> Behavior Tree standard library
        -   [X] deliveries, electrical, errands, exercise, financial, food-pantries, groceries, hospitalization, hygiene, meal-planning, medication, movement-discipline, paperwork, plumbing, security, sickness, sleep, trip-planning
    -   [ ] <code>[10%]</code> Household emergency preparedness
        -   [ ] Planning ahead for bad weather
            -   [ ] e.g. Stock up on groceries before a major storm hits
            -   [ ] <code>[50%]</code> Weather control rules


<a id="orgc29a353"></a>

## Organization


<a id="org8516921"></a>

### Inventory Management

-   [ ] <code>[66%]</code> Pantry management
    -   [ ] <code>[75%]</code> A Mermaid diagram for inventory addition and removal control flow
        -   [ ] <code>[15%]</code> The Platinum dynamic WebUI for walking through the Mermaid graph, and properly processing food inventory addition and removal
        -   [ ] <code>[75%]</code> Barcoded and un-barcoded food items
            -   [ ] <code>[50%]</code> Barcode scanning of food products
                -   [X] Wireless USB barcode scanner hidraw agent
    -   [ ] <code>[10%]</code> Manage expected expiration dates
        -   [ ] Prevent food loss
            -   [ ] <code>[25%]</code> Help to schedule cooking before food expires
        -   [ ] [Know how long it can stay out, or in fridge/freezer](https://frdcsa.org/~andrewdo/projects/mealplanning/freezer_cooking.pl.txt)
            -   [ ] <code>[25%]</code> Know when to move it
    -   [ ] Physical layout assistant
    -   [ ] Helping to reorder from preferred vendor types, like organic, local, etc
    -   [ ] Automatic shopping list generation and reordering
    -   [ ] Tracking food recalls or warnings
        -   [ ] Crypto signatures and source-monitoring
    -   [ ] Kitchen and appliance cleaning and maintenance tips
-   [ ] <code>[15%]</code> Executable product manuals
    -   [ ] <code>[60%]</code> Interactively use products
        -   [X] Use coffeemaker using plan monitor
    -   [ ] <code>[90%]</code> Automatically schedule maintenance
    -   [ ] <code>[10%]</code> Interactively perform maintenance
-   [ ] Executable product warranties
    -   [ ] Integration with planning and scheduling

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">


<a id="orgfdfb239"></a>

### Communication Management

-   [Proxy all communications](https://github.com/aindilis/audience)
    -   [X] Dossier system
        -   [ ] Relationship management
            -   [ ] <code>[25%]</code> ACLs (Access Control Lists)
            -   [X] Talking points
        -   [X] Memcons (Memorandum of Conversation)
        -   [ ] <code>[33%]</code> Commitments extraction
        -   [ ] <code>[33%]</code> Goal/Interest/Ability extraction
    -   [ ] Persuasion
        -   [ ] <code>[10%]</code> A/B Testing
        -   [X] [Argument mapping](https://argdown.org/)
    -   [ ] Team building
        -   [ ] [Teamcore/STEAM](https://teamcore.seas.harvard.edu/publications/towards-flexible-teamwork) (a Shell for TEAMwork)
        -   [ ] [TeamLog](https://www.amazon.com/Teamwork-Multi-Agent-Systems-Formal-Approach/dp/0470699884)
        -   [ ] [Horn-TeamLog](https://www.mimuw.edu.pl/~nguyen/HornTeamLog-long.pdf)
        -   [ ] [NL<sub>MAMS</sub>](https://link.springer.com/book/10.1007/978-3-319-39972-0) (Natural Language MultiAgent Mental Simulator)
        -   [ ] [Teamwork via Collective Intention](https://github.com/QuMuLab/teamwork-via-collective-intention)
        -   [X] [SNA](http://www.casos.cs.cmu.edu/projects/ora/software.php) (Social Network Analysis)


<a id="org39e8bcd"></a>

### Chore Charting

-   [ ] <code>[60%]</code> Chore ontology
    -   [X] Comprehensive chore lists
    -   [ ] <code>[50%]</code> Household chores
    -   [ ] <code>[80%]</code> Caregiving chores
-   [ ] <code>[66%]</code> Chore logic
    -   [ ] <code>[66%]</code> Scheduling, reminders, tracking and gamification
    -   [ ] <code>[66%]</code> Interactive plan execution using library of chore BTs (behavior trees)


<a id="org066e1a5"></a>

### Maintenance

-   [ ] <code>[33%]</code> Household maintenance
    -   [ ] <code>[50%]</code> Complete list of scheduled home maintenance tasks
        -   [ ] <code>[10%]</code> Test fire alarms
        -   [X] Furnace maintenance
        -   [ ] etc
-   [X] Automotive maintenance schedule


<a id="org1819d32"></a>

### Smart Home

-   [ ] SVRS Integrated shelter management
    -   [ ] Sensor network
        -   [X] Security and surveillance
            -   [X] [SDR](https://github.com/merbanan/rtl_433) sensor monitoring (Software Defined Radio)
            -   [X] Home defense preparations and contingency planning
            -   [X] Video cameras and perimeter defense sensors
                -   [ ] <code>[20%]</code> Video understanding (similar to [VSAM](http://www.cs.cmu.edu/~vsam/))
                    -   [X] Object recognition
                    -   [ ] Activity detection
                        -   [ ] <code>[25%]</code> Suspicious/anomalous activity detection
        -   [ ] <code>[50%]</code> Smart lighting control
            -   [ ] <code>[50%]</code>  For managing moods (such as, red - during work) for productivity, relaxation, etc
            -   [X] Indicating availability to housemates (red - do not disturb, etc)
        -   [X] [Event logging and inference](https://github.com/aindilis/elog2)
            -   [X] Action triggers
                -   [ ] <code>[60%]</code> Changing smart lighting based on detected work activity
                -   [ ] <code>[50%]</code> Penalization for lack of movement discipline (e.g. left room without plan)
                -   [ ] Reactive systems
                    -   [ ] <code>[33%]</code> Climate/temperature control
                        -   [ ] <code>[33%]</code> Open windows, Turn the AC/heater on/off, etc
                    -   [ ] <code>[20%]</code> Weather monitoring
                        -   [ ] Warnings to prepare for storms, extreme weather
            -   [ ] <code>[10%]</code> Complex event detection
                -   [ ] <code>[20%]</code> [RTEC](https://github.com/aartikis/RTEC) (Run Time Event Calculus)
    -   [ ] [Home maintenance](#org066e1a5)
    -   [ ] [Emergency preparedness](#org976f688)
    -   [ ] SVRE
        -   [ ] <code>[30%]</code> IPSVRE
            -   [ ] <code>[90%]</code> Management of many aspects of individual environments including: lighting, climate, distractions, productivity, etc.


<a id="org10c6e15"></a>

### Research and Development

-   [X] [Academician system](https://github.com/aindilis/academician)
-   [X] [Study system](https://github.com/aindilis/study)
-   [ ] ITS system (Intelligent Tutoring System)
-   [X] Seeker system


<a id="org77893b6"></a>

## Self-Discipline


<a id="org8511aab"></a>

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
    -   [ ] <code>[33%]</code> Task classification, commitment extraction, dependency elicitation, duration estimation, ontology, prioritization, tagging, inferring completed tasks from changelogs using [LangPro](https://github.com/kovvalsky/LangPro)
-   [ ] Miscellaneous other partially completed to-do systems
    -   [ ] ([Score](https://github.com/aindilis/score), Lightspeed, [Normal-Form](https://github.com/aindilis/normal-form)/[Spark](https://github.com/aindilis/spark-frdcsa), Todo, PSE, Agenda, System-Planning, crontab, Task-Manager, PSE-x, todo-list-processor, [SPSE2](https://github.com/aindilis/spse), [SPSE2-Formalog](https://github.com/aindilis/spse2-formalog/), [FLP](https://github.com/aindilis/free-life-planner), [Do-Cyc](https://github.com/aindilis/do-cyc), Do-Pl)


<a id="orga682196"></a>

### Note-Taking

-   [X] Org-mode
-   [ ] <code>[10%]</code> Cyc-ZK (Zettelkasten)


<a id="org4d2238d"></a>

### Scheduling

-   [X] PDDL-2.2 (Planning Domain Definition Language)
-   [ ] <code>[20%]</code> PDDL+ (Planning Domain Definition Language Plus)
-   [ ] <code>[05%]</code> [Optaplanner](https://www.optaplanner.org/)


<a id="org0c2133e"></a>

### Self-Discipline State Machine

-   [ ] <code>[33%]</code> Use the digital twin and plan to choose from possible things to do


<a id="org0f2ffe2"></a>

### Gamification

-   [X] Rewards for completing recurrent tasks
-   [X] Daily penalty for leaving any recurrent tasks incomplete
-   [X] Penalties for lack of [movement discipline](#org9194323)
-   [ ] <code>[50%]</code> Rewards for staying productive


<a id="org9194323"></a>

### Movement Discipline

-   [ ] <code>[33%]</code> Optional mode where one must premeditate before moving to a different location


<a id="org9ef4493"></a>

## Transportation/Shopping/Errands


<a id="org59d3408"></a>

### Transportation

-   [ ] <code>[33%]</code> API look-up mashups (Application Programming Interface)
    -   [ ] <code>[90%]</code> Hours of operation
        -   [ ] <code>[90%]</code> Stores/offices/etc
    -   [ ] <code>[30%]</code> Weather
    -   [ ] <code>[30%]</code> Route planning
        -   [ ] Point to point
        -   [ ] "Traveling Salesman"
    -   [ ] <code>[90%]</code> Reverse geocoding
-   [ ] <code>[66%]</code> Location logic
    -   [X] [Owntracks](https://owntracks.org/) integration
    -   [ ] <code>[50%]</code> Locational rules
        -   [ ] <code>[75%]</code> e.g. [Silence my phone when at any movie theater](http://frdcsa.org/~andrewdo/projects/ll-rules.pl)
            
                performAction(addToPendingTasks(Agent,unsilenceCellPhone(Agent,Phone))) :-
                	currentAgent(Agent),
                	hasMobilePhone(Agent,Phone),
                	leaving(Agent,Location),
                	isa(Location,movieTheater),
                	hasRecentlyPerformedAction(Agent,silenceCellPhone(Agent,Phone)).

-   [X] [Movement discipline](#org9194323)


<a id="org648e373"></a>

### Shopping/Errands

-   [X] Shopping list management
-   [X] Integration with [financial management](#orgb282d40)
    -   [X] OFX cross-referencing (Open Financial eXchange)
-   [ ] <code>[33%]</code> Integration with inventory and pantry management
-   [ ] Buying
    -   [ ] Broker - Purchase/Financial Decision Support Systems
        -   [ ] <code>[10%]</code> Argumentation (Possibly using [MARGO](https://sourceforge.net/projects/margo/) or similar (Multiattribute ARGumentation framework for Opinion explanation))
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
    -   [ ] Brick and Mortar Shopping
        -   [X] Receipts
            -   [X] Parsers for brick and mortar store receipts
            -   [X] OCR for physical receipts
        -   [ ] "Traveling Salesman" route planning
            -   [ ] [Open Route Service API (optimization) integration](https://openrouteservice.org/)
-   [ ] Selling
    -   [ ] Broker - personal selling system
        -   [ ] Argumentation
            -   [ ] Decide what to sell
            -   [ ] Decide whether to sell


<a id="org713d9e1"></a>

## Document Management

-   [ ] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork (Optical Character Recognition)
    -   [ ] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ Git
    -   [X] Export selected documents and folders
    -   [X] Digital library system
        -   [X] Equipment manuals
    -   [X] [Book reader](https://frdcsa.org/frdcsa/internal/clear)
    -   [X] [Information search management](#org10c6e15)


<a id="orgb282d40"></a>

## Financial Planner

-   [ ] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
        -   [X] Specify recurring transactions
        -   [X] Automatically detect recurring transactions from OFX exports and plan for them
            -   e.g.
                
                    promiseToPayForSpec('ELEC',andrewDougherty,'<ELECTRICCOMPANY>',dollars(93.00),[can([1]),not(onTime([3])))).
        
        -   [X] View expected financial transactions along with primary agenda on a calendar
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [X] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships
    -   [ ] <code>[75%]</code> SPSE2->PSEx3 export (Planning, Scheduling and Execution System (Extended), version 3)
        -   [ ] <code>[75%]</code> Integrating financial reasoning and other domains, with SPSE's to-do dependency graph
-   [ ] [(Personal) Accounting](http://xbrlsite.azurewebsites.net/2021/reporting-scheme/pfs/documentation/Index.html)
    -   [ ] [XBRL](http://xbrl.squarespace.com/) bookkeeping
        -   [ ] Loan and debt management
        -   [ ] Budgeting
            -   [ ] Classifying (OFX) transactions
        -   [ ] Financial reporting
            -   [ ] Regulatory compliance (say, to Social Security rules)
-   [ ] Debt tracking


<a id="org976f688"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)
    -   [ ] <code>[50%]</code> Recurrences for reminders to maintain equipment, supplies, plans and drills
    -   [ ] Safety plans
        -   [ ] <code>[05%]</code> Fire
        -   [ ] <code>[80%]</code> [Pandemic](https://frdcsa.org/~andrewdo/writings/behavior-tree-task-manager-for-covid-19.pdf)
        -   [ ] <code>[10%]</code> Food and water


<a id="orgdc43b1f"></a>

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
        	atomic_list_concat([AgentGloss,told,PersonGloss,Statement],' ',Gaeilge).


<a id="org855bdd5"></a>

# Major Technologies Used

-   [ ] [SWI-Prolog](https://www.swi-prolog.org/) (Sociaal-Wetenschappelijke Informatica)
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
    -   [X] Cyc Java API<->Inline Perl
-   [X] [Bash](https://www.gnu.org/software/bash/) scripting
-   [X] [Emacs integration](https://www.youtube.com/watch?v=0l3K__C9Dkc)
-   [X] [PDDL 2.2](https://planning.wiki/ref/pddl22/domain) temporal metric planning
    -   [X] [LPG-td-1.0](https://lpg.unibs.it/lpg/)
    -   [X] [OPTIC<sub>CLP</sub>](https://nms.kcl.ac.uk/planning/software/optic.html) (Optimizing Preferences and Time-Dependent Costs) (Coin-or Linear Programming)
-   [X] [Vampire-KIF](https://en.wikipedia.org/wiki/Vampire_(theorem_prover)) (Knowledge Interchange Format) ATP (Automated Theorem Proving) system
-   [X] [SUMO](https://github.com/ontologyportal/sumo)
-   [X] [OpenCyc](https://sourceforge.net/projects/opencyc/)
-   [ ] [MariaDB/MySQL](https://mariadb.org/) persistence
    -   [X] Through [UniLang](https://github.com/aindilis/unilang)/[FreeKBS2](https://github.com/aindilis/freekbs2) (Universal Language) (Free Knowledge Based System v2)
    -   [ ] [<code>[50%]</code> Directly from SWI-Prolog using ODBC](https://github.com/aindilis/data-integration) (Open DataBase Connectivity)
-   [ ] <code>[33%]</code> [Inform7](https://github.com/ganelson/inform)
-   [X] LLMs (Large Language Models)
    -   [X] Code Llama 34B
    -   [X] WizardLM


<a id="org1fb583b"></a>

## [README](https://github.com/aindilis/flp/blob/main/README.md)


<a id="org9c423d6"></a>

### [Broad overview of FLP](https://github.com/aindilis/flp/blob/main/README.md)


<a id="org2ff5086"></a>

### TODO Finish elaboration of finance and health planner capabilities


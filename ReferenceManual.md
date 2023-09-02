
# Table of Contents

1.  [Technical Overview](#org4b97e0d)
    1.  [THIS REFERENCE MANUAL IS UNDER CONSTRUCTION](#org1d34b27)
2.  [Links](#org99195d6)
3.  [You are at the ReferenceManual.md](#org2d01545)
4.  [Reference Manual Contents](#org3e4e793)
    1.  [Workflow Manager](#orga424a6c)
    2.  [Health](#org54f0b00)
        1.  [Evidence-Based Wellness](#orgd3ee086)
        2.  [Exercise](#org4c3c354)
        3.  [Nutrition](#orge2a2f8d)
        4.  [Doctor's Visits and Orders](#orgf029f78)
        5.  [Medications](#orgc9ff946)
        6.  [Mental Health](#org10e3186)
    3.  [Time Management](#org188368f)
        1.  [Recurrences](#orgd112ca2)
        2.  [Calendaring](#orgc4f8d5c)
        3.  [Planning, Scheduling and Execution](#org3e5fa55)
    4.  [Organization](#orgf2e778e)
        1.  [Inventory Management](#orgef82c4d)
        2.  [Communication Management](#orga3a3209)
        3.  [Chore Charting](#org0689c0c)
        4.  [Maintenance](#org3e4dce8)
        5.  [Smart Home](#orge4e6abf)
        6.  [Research and Development](#org8a71bba)
    5.  [Self-Discipline](#org4d70cb2)
        1.  [To-Do](#org7a97756)
        2.  [Note-Taking](#orge3646ca)
        3.  [Scheduling](#orgbf7f4d9)
        4.  [Self-Discipline State Machine](#org82d951f)
        5.  [Gamification](#org5f5460d)
        6.  [Movement Discipline](#org0057ef3)
    6.  [Transportation/Shopping/Errands](#orgfb5193d)
        1.  [Transportation](#org8e12648)
        2.  [Shopping/Errands](#org88ec821)
    7.  [Document Management](#org16331c9)
    8.  [Financial Planner](#org2f690fe)
    9.  [Emergency Preparedness](#org782d157)
    10. [Employment](#orga18eea6)
    11. [Executive Function](#org0963306)
    12. [Smart home](#org6067169)
        1.  [Home Maintenance](#org00eb551)
        2.  [Equipment Maintenance](#org33a8100)
    13. [Relationship Management](#orge781a3c)
5.  [Major Techniques Used](#org5418995)
6.  [Major Technologies Used](#org82b716a)
    1.  [README](#org01793e7)
        1.  [Broad overview of FLP](#orgc847ef4)
        2.  [Finish elaboration of finance and health planner capabilities](#org2d21d02)


<a id="org4b97e0d"></a>

# Technical Overview


<a id="org1d34b27"></a>

## THIS REFERENCE MANUAL IS UNDER CONSTRUCTION


<a id="org99195d6"></a>

# Links

-   Please note that for now there are (rather confusingly) four
    important documents to see:
    -   The [original deprecated Free Life Planner repo](https://github.com/aindilis/free-life-planner#readme) (including screenshots and links)
    
    -   The new [ReferenceManual.md](https://github.com/aindilis/flp/blob/main/ReferenceManual.md) (the most detailed overview of FLP)
    
    -   The new [README.md](https://github.com/aindilis/flp/blob/main/README.md) (a less detailed summary and links)

-   I am going to condense these into a single document real soon now.
    -   The paper - "The Free Life Planner: A Virtual Secondary Social Safety Net" (will link to when it becomes available)


<a id="org2d01545"></a>

# You are at the ReferenceManual.md


<a id="org3e4e793"></a>

# Reference Manual Contents


<a id="orga424a6c"></a>

## Workflow Manager

-   [ ] <code>[35%]</code> e.g.
    
        'move-to-page'(begin,'user-agenda').
        'complete-task'('mark-off-all-completed-from-agenda').
        'complete-task'('sort-agenda').  'finish-page'('user-agenda').
-   [ ] <code>[60%]</code> [JASWIPL "metaplanning" systems integration](https://github.com/aindilis/jason/tree/master/examples/executive-function-adapter) (Jason/AgentSpeak(L)<->SWIPL)
-   [ ] <code>[30%]</code> [Jason/AgentSpeak(L)<->Python<->(SuperAGI|BabyAGI|AutoGPT|MetaGPT|BeeBot) LLM-based autonomous agents](https://github.com/aindilis/jason/tree/master/examples/python-adapter)
    -   [ ] <code>[60%]</code> Contingency planning
        -   [X] WebUI to select ground or unground contingency triggers
            -   [X] Code Llama generation of NL contingency plans for triggers (Natural Language)
    -   [ ] <code>[20%]</code> Dynamically add/remove goals and replan

<pre>
+!quarantine(Person) <-
	?hasRoom(Person,Room);
	!atLocation(Person,Room);
	+prohibited((move(Person,Location),Location \\= Room));
	&#x2026;
</pre>


<a id="org54f0b00"></a>

## Health


<a id="orgd3ee086"></a>

### Evidence-Based Wellness

1.  General

    -   [ ] Medical Q&A using [DoctorGPT](https://github.com/llSourcell/DoctorGPT) or a successor LLM

2.  Data Collection and User Modeling

    -   [ ] <code>[50%]</code> Record / create an inventory of all user's medical symptoms
        -   [ ] List conditions, [medications](#orgc9ff946) and their effects
        -   [ ] Inventory medication effects, side-effects and risks
    -   [ ] SNA of providers (Social Network Analysis)
        -   [ ] Who they they are, what they do, what they advise and how often we need to visit
    -   [ ] Empirically determine effectiveness of treatments
        -   [ ] Opt-in anonymized data sharing
            -   [ ] With users' fine-grained consent
            -   [ ] With secure multiparty computation
            -   [ ] For use with data mining, ML

3.  Prevention / Early Detection

    -   [ ] Achieve and maintain medical situational awareness
        -   [ ] Take users' known conditions/symptoms, estimate conditional probabilities of additional conditions/symptoms
            -   [ ] Similar to the probabilistic techniques behind SLAM algorithms from autonomous robotics (Simultaneous Localization and Mapping)
                -   [ ] Propagating conditional densities
            -   [ ] Sorted by a norm on or MCDA for likelihood and impact/severity (multi-criteria decision analysis)
            -   [ ] Observations substantiated by FLP data collection
            -   [ ] Medical KBS integrations, possibly: MedDRA, LEX, OpenGALEN, RxNorm, UMLS, etc
            -   [ ] Medical KG integrations, possibly: [Hetionet](https://het.io), [PDT](https://patternslanguage.com/articles/f/a-personal-digital-twin-forhealthcare) (Personal Digital Twin)
        -   [ ] Help with prophylaxis for known risks
        -   [ ] Help to administer treatments (preventative, ongoing and restorative)

4.  Diagnostics and Treatments

    -   [ ] Expert system for diagnosis of medical problems and treatment
        -   [ ] Application of otherwise unavailable medical knowledge (in the absence of a medical professional
        -   [ ] Argumentation-based synchronization and reconciliation when able to see medical professional
            -   [ ] Either in person
            -   [ ] Telemedicine / remote doctor
        -   [ ] [WOPR](https://frdcsa.org/frdcsa/minor/wopr/index.html) contingency plans, represented in Prolog, fulfilled by Code Llama or GPT-4
            -   [ ] Library of COAs/SOPs (Courses Of Action, Standard Operating Procedures)
                -   [ ] Instructions for CPR, Heimlich, etc
                    -   [ ] Just in time
                    -   [ ] Ahead of time, studying administered by an ITS (Intelligent Tutoring System)
            -   [ ] Upon activation of contingency trigger:
                -   [ ] Executed using interactive execution system
                    -   [ ] JASWIPL (Jason/AgentSpeak(L)<->SWI-Prolog integration)
                    -   [ ] IEM2 (Interactive Execution Monitor verson 2)
                    -   [ ] Plan-Monitor
            -   [ ] <code>[30%]</code> [Flowcharts](https://online.visual-paradigm.com/digrams/templates/flowchart) for determining best professional treatment options
                -   [ ] ER, Urgent care, phone on-call doctor/nurse, telemedicine, etc (Emergency Room)
                    -   [ ] <code>[20%]</code> Hospital packing list including all necessary supplies for ER visit
        -   [ ] Medical fact checking
            -   [ ] Visual library of images for diagnosis and explanation
                -   [ ] CV-based algorithms trained to identify conditions (such as skin conditions or lesions) (Computer Vision)
        -   [ ] Integration with financial planner and inventory manager for ensuring all (potentially) necessary medical supplies kept in stock and not expired
        -   [ ] Argumentation-based deliberation regarding the validation of planned treatments


<a id="org4c3c354"></a>

### Exercise

-   [ ] <code>[33%]</code> Interactive plan monitoring of exercises
-   [ ] <code>[66%]</code> Track daily progress
    -   [ ] <code>[100%]</code> Using Alexa interface (please note, we are switching to either Rhasspy or MyCroft ASAP, due to need to airgap)


<a id="orge2a2f8d"></a>

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
    -   [ ] [Inventory Management](#orgef82c4d)
        -   [ ] User modeling
            -   [ ] <code>[40%]</code> [Self-discipline](#org4d70cb2) coach software
                -   [ ] Understanding psychology of users' relationships to food
            -   [X] Helping w/ Portion control
                -   [X] Door sensor alerts on fridge and freezer
                -   [ ] <code>[20%]</code> Follow up dialog regarding intent when fridge and freezer accessed
                -   [ ] [Gamification](#org5f5460d)
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


<a id="orgf029f78"></a>

### Doctor's Visits and Orders

-   [X] Appointment calendar
    -   [ ] Track appointments and avoid double-booking and overbooking
    -   [X] Verbal and User-Agenda reminders
    -   [X] Q&A system for asking things like when is my next appointment
-   [ ] [Medical diagnostics](https://github.com/timhannifan/symptom-tree/issues/1)
-   [ ] <code>[40%]</code> Following doctors' orders
    -   [X] Scan into [Document Management System](#org16331c9) for managing (among other things) medical records
    -   [ ] <code>[90%]</code> Ensuring compliance via [Machine Reading Comprehension](https://paperswithcode.com/task/machine-reading-comprehension)
        -   [X] Using WizardLM to extract instructions from documents
        -   [X] Converting orders into an BT (Behavior Tree)
        -   [ ] Converting orders into an SPSE2 planning context
    -   [ ] Medical question answering in absence of medical professionals using software such as [DoctorGPT](https://github.com/llSourcell/DoctorGPT)
-   [ ] Medical adherence tracking
    -   [ ] Ensuring follow-through with doctor's orders
        -   [ ] LLM-based and E2C representation (PrologCyc) (Large Language Model, English to CycL)
-   [ ] Medical record management
    -   [ ] Tracking nutrition, exercise, medications, supplements, doctor's visits, immunizations, hygiene, etc
-   [ ] Sanity and triple checking for potentially valid health concerns that were missed
    -   [ ] Patient advocate to detect potential confusion or foul-ups due to communication breakdowns between patients, doctors and other doctors


<a id="orgc9ff946"></a>

### Medications

-   [X] Medication reminders and recording
-   [ ] Planning, tracking and monitoring of medication and supplement usage
    -   [ ] Complete CLP-based medication manager that understands time management (Constraint Logic Programming)
        -   [ ] Predict when we will run out of various medications
            -   [ ] Logistically ensure stable access to necessary medications
                -   [ ] Accounting for factors such as medical professional turnover, weather phenomenon, etc
                -   [ ] Securing medications that are logistically difficult to access
                    -   [ ] Hours of operation of pharmacy, clinics
    -   [ ] Domain specific knowledge regarding factors like whether a med cannot be skipped, or if necessary, for how long
    -   [ ] <code>[30%]</code> [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)
        -   [ ] <code>[30%]</code> Manage time-dependent effects of medication dosages and half-lives
    -   [ ] <code>[33%]</code> Medication refill tracking
        -   [ ] Ensure cannot be removed from the user's agenda, cannot be postponed
        -   [ ] Store relevant contact information
        -   [ ] Recurrent sanity checks
        -   [ ] Infer when user forgot to refill or track medications
    -   [ ] Note start of medication run
        -   [ ] Close monitoring of potential symptoms, associated conditions, side-effects, etc
            -   [ ] <code>[50%]</code> Recent medical history and significant data automatically added to report for doctor
                -   [ ] Talking points for next associated visit with a medical professional
                -   [ ] <code>[20%]</code> Interactive dialog manager (similar to but much improved over [Audience Dialog subsystem](https://frdcsaorg/~andrewdo/WebWiki/AudienceDialog.html))
                    -   [ ] Recording of doctor's responses, answers and orders
                    -   [ ] <code>[75%]</code> Dialog execution monitoring using cell-phone


<a id="org10e3186"></a>

### Mental Health

-   [ ] Systems for tracking symptoms
    -   [ ] [Executive function](https://github.com/aindilis/jason/tree/master/examples/executive-function-adapter)
    -   [ ] Negative self talk
        -   [ ] <code>[50%]</code> Rewrites negative self talk using LLM prompts (Large Language Models)
    -   [ ] Planning to achieve and maintain [human flourishing](https://arxiv.org/pdf/2302.09248.pdf)
        -   [ ] Low mood and/or productivity amelioration
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


<a id="org188368f"></a>

## Time Management


<a id="orgd112ca2"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgc4f8d5c"></a>

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


<a id="org3e5fa55"></a>

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
    -   [ ] Temporally-contingent planning
        -   [ ] [TraCE-lite](https://pure.hw.ac.uk/ws/portalfiles/portal/63630796/ICAPS_PlanRob_2021_TCP_.pdf)
    -   [ ] <code>[90%]</code> [Behavior tree reactive planning](https://frdcsa.org/~andrewdo/writings/behavior-tree-task-manager-for-covid-19.pdf)
        -   [ ] <code>[90%]</code> [Plan Monitor](https://github.com/aindilis/plan-monitor)
            -   [ ] <code>[33%]</code> [More than 15 BT domains](#org1288a5d)
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
        -   [ ] <code>[50%]</code> Allow installation and uninstallation of habits
        -   [X] Tracks from a growing list of elicited habits, records when engaging in / avoiding behaviors
    -   [ ] <code>[60%]</code> Resource Manager (plans over inventory/etc)
        -   [ ] <code>[80%]</code> Productivity Requirements
    -   [ ] <code>[25%]</code> Subsystem monitoring
        -   [ ] <code>[25%]</code> Mission Control
        -   [ ] <code>[35%]</code> Normal Form
    -   [ ] Gamification

3.  Some domains

    -   [ ] <code>[50%]</code> Plan cycles (cycle)
        -   [X] Toy plan cycle
        -   [ ] Real-world plan cycle
    -   [ ] <code>[33%]</code> PDDL Standard domain library (basekb)
        -   [X] [agent, biomaintenance, chores, deontic, economic, food, hygiene, misc, security, space, tool, work](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/worlds/basekb)
    -   [ ] <code>[33%]</code> Behavior Tree standard library
        -   [X] deliveries, electrical, errands, exercise, financial, food-pantries, groceries, hospitalization, hygiene, meal-planning, medication, movement-discipline, paperwork, plumbing, security, sickness, sleep, trip-planning
    -   [ ] <code>[10%]</code> Household emergency preparedness
        -   [ ] Planning ahead for bad weather
            -   [ ] e.g. Stock up on groceries before a major storm hits
            -   [ ] <code>[50%]</code> Weather control rules


<a id="orgf2e778e"></a>

## Organization


<a id="orgef82c4d"></a>

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


<a id="orga3a3209"></a>

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


<a id="org0689c0c"></a>

### Chore Charting

-   [ ] <code>[60%]</code> Chore ontology
    -   [X] Comprehensive chore lists
    -   [ ] <code>[50%]</code> Household chores
    -   [ ] <code>[80%]</code> Caregiving chores
-   [ ] <code>[66%]</code> Chore logic
    -   [ ] <code>[66%]</code> Scheduling, reminders, tracking and gamification
    -   [ ] <code>[66%]</code> Interactive plan execution using library of chore BTs (behavior trees)


<a id="org3e4dce8"></a>

### Maintenance

-   [ ] <code>[33%]</code> Household maintenance
    -   [ ] <code>[50%]</code> Complete list of scheduled home maintenance tasks
        -   [ ] <code>[10%]</code> Test fire alarms
        -   [X] Furnace maintenance
        -   [ ] etc
-   [X] Automotive maintenance schedule


<a id="orge4e6abf"></a>

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
    -   [ ] [Home maintenance](#org3e4dce8)
    -   [ ] [Emergency preparedness](#org782d157)
    -   [ ] SVRE
        -   [ ] <code>[30%]</code> IPSVRE
            -   [ ] <code>[90%]</code> Management of many aspects of individual environments including: lighting, climate, distractions, productivity, etc.


<a id="org8a71bba"></a>

### Research and Development

-   [X] [Academician system](https://github.com/aindilis/academician)
-   [X] [Study system](https://github.com/aindilis/study)
-   [ ] ITS system (Intelligent Tutoring System)
-   [X] Seeker system


<a id="org4d70cb2"></a>

## Self-Discipline


<a id="org7a97756"></a>

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


<a id="orge3646ca"></a>

### Note-Taking

-   [X] Org-mode
-   [ ] <code>[10%]</code> Cyc-ZK (Zettelkasten)


<a id="orgbf7f4d9"></a>

### Scheduling

-   [X] PDDL-2.2 (Planning Domain Definition Language)
-   [ ] <code>[20%]</code> PDDL+ (Planning Domain Definition Language Plus)
-   [ ] <code>[05%]</code> [Optaplanner](https://www.optaplanner.org/)


<a id="org82d951f"></a>

### Self-Discipline State Machine

-   [ ] <code>[33%]</code> Use the digital twin and plan to choose from possible things to do


<a id="org5f5460d"></a>

### Gamification

-   [X] [Score](https://github.com/aindilis/score)
-   [ ] <code>[75%]</code> Rewards/Penalties
-   [X] [Manager](https://github.com/aindilis/manager)
-   [X] Rewards for completing recurrent tasks
-   [X] Daily penalty for leaving any recurrent tasks incomplete
-   [X] Penalties for lack of [movement discipline](#org0057ef3)
-   [ ] <code>[50%]</code> Rewards for staying productive
-   [ ] <code>[50%]</code> Adherence tracker
    -   [X] Color coded labelled rectangles indicating the last accessed time of various FLP systems
        -   [X] Determine which systems are not being used correctly
        -   [X] Determine which sensors have stopped working (e.g. dead battery)


<a id="org0057ef3"></a>

### Movement Discipline

-   [ ] <code>[33%]</code> Optional mode where one must premeditate before moving to a different location


<a id="orgfb5193d"></a>

## Transportation/Shopping/Errands


<a id="org8e12648"></a>

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

-   [X] [Movement discipline](#org0057ef3)


<a id="org88ec821"></a>

### Shopping/Errands

-   [X] Shopping list management
-   [X] Integration with [financial management](#org2f690fe)
    -   [X] OFX cross-referencing (Open Financial eXchange)
-   [ ] <code>[33%]</code> Integration with inventory and pantry management
-   [ ] Buying
    -   [ ] Broker - Purchase/Financial Decision Support Systems
        -   [ ] <code>[10%]</code> Argumentation (Possibly using [MARGO](https://sourceforge.net/projects/margo/) or similar (Multiattribute ARGumentation framework for Opinion explanation))
            -   [ ] <code>[10%]</code> Decide what to purchase
            -   [ ] <code>[10%]</code> Decide whether to purchase
    -   [ ] Ethical consumerism
        -   [ ] <code>[25%]</code> [Boycott management](https://github.com/aindilis/boycott-manager/tree/main/attempts/1) using Prolog representation
            -   [ ] Collective action trap avoidance
                -   [ ] Using [Koordinator](https://github.com/koo5/koordinator2000)
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


<a id="org16331c9"></a>

## Document Management

-   [ ] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork (Optical Character Recognition)
    -   [ ] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [ ] <code>[90%]</code> Backup w/ Git
    -   [X] Export selected documents and folders
    -   [X] Digital library system
        -   [X] Equipment manuals
    -   [X] [Book reader](https://frdcsa.org/frdcsa/internal/clear)
    -   [X] [Information search management](#org8a71bba)


<a id="org2f690fe"></a>

## Financial Planner

-   [ ] <code>[50%]</code> [Financial Planning](https://github.com/aindilis/financial-planning#readme)
-   [X] Quickly forecast finances almost indefinitely into the future
    -   [X] Specify recurring transactions
    -   [X] Automatically detect recurring transactions from OFX exports and plan for them
        -   e.g.
            
                promiseToPayForSpec('ELEC',andrewDougherty,'<ELECTRICCOMPANY>',dollars(93.00),[can([1]),not(onTime([3])))).
    -   [X] View expected financial transactions along with primary agenda on a calendar
        
        -   [X] Calenderical recurrences using CLP (Constraint Logic Programming) 
            -   [ ] <code>[25%]</code> WebUI for editing financial recurrences
        
        -   [X] Predicted transactions' date, description, debit or credit and running balance
            -   [X] As a list
            -   [X] As a chart
-   [X] Temporal metric planning for finances
-   [X] Financial reasoning integrated with general planning
    -   [X] Express expected date ranges of transactions using can, neg(oTime), months, date ranges, etc.
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] [TraCE](https://openreview.net/pdf?id=JJYg8KKLJtL) temporally-contingent planner integration
    -   [X] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships
-   [X] Abduction of recurrences and predicted events from bank statements in OFX or CSV (Open Financial Exchange, Comma-Separated Values)
    -   [ ] Retrospectively analyze prior predictions
        -   [ ] To update or correct financial recurrences
-   [X] [Interactive Execution Monitor v2](https://frdcsa.org/~andrewdo/iem2-3.mp4) for walking user through plans
    -   [ ] <code>[50%]</code> Verify preconditions
    -   [X] Update world state with all effects
        -   [X] Extraction of world state deltas
    -   [ ] <code>[25%]</code> WebUI for IEM2 (using Mock Perl/Tk objects)
-   [ ] <code>[75%]</code> SPSE2->PSEx3 export (Planning, Scheduling and Execution System (Extended), version 3)
    -   [ ] <code>[75%]</code> Integrating financial reasoning and other domains, with SPSE's to-do dependency graph
-   [X] Modification of PDDL/Verb domain/problem and temporal world state
-   [X] Financial alerts
    -   [X] Text-to-speech alerts for recurrent transactions
-   [ ] [Purchase Management](https://frdcsa.org/frdcsa/minor/broker)
    -   [ ] Argumentation-based [PDSS](https://frdcsa.org/frdcsa/minor/purchase-decision-support-system/index.html) (Purchase Deciscion Support System)
        -   [ ] Reasoning over user needs
        -   [ ] Critical questions:
            -   [ ] Is this purchase [ethical](https://frdcsa.org/frdcsa/minor/ethical-consumer-system/index.html)/necessary/within-budget?
                -   [ ] Product and seller comparison
                -   [ ] Payment plan management
    -   [X] Tracking purchases and deliveries
    -   [ ] Inventory/pantry [Inventory Management](#orgef82c4d) integration
    -   [ ] Resource manager (automatic reordering and stock management)
    -   [ ] Receipt tracker
        -   [ ] <code>[50%]</code> Online
        -   [ ] <code>[50%]</code> Brick and mortar
        -   [X] Matching bank records to receipts
-   [ ] Alerts for anticipated upcoming overdrafts
-   [ ] <code>[10%]</code> Displaying live/real-time bank information
    -   [ ] <code>[20%]</code> Check current account balance automatically
    -   [ ] Account history
-   [ ] [(Personal) Accounting](http://xbrlsite.azurewebsites.net/2021/reporting-scheme/pfs/documentation/Index.html)
    -   [ ] [XBRL](http://xbrl.squarespace.com/) bookkeeping
        -   [ ] Loan and debt tracking/management
        -   [ ] Budgeting (monthly)
            -   [ ] Automatic creation of fundraising alerts and deadlines to maintain positive balance
        -   [ ] Classifying (OFX) transactions
        -   [ ] Financial reporting
            -   [ ] Regulatory compliance (say, to Social Security rules)
-   [ ] Bill payment subsystem


<a id="org782d157"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)
    -   [ ] <code>[50%]</code> Recurrences for reminders to maintain equipment, supplies, plans and drills
    -   [ ] Safety plans
        -   [ ] <code>[05%]</code> Fire
        -   [ ] <code>[80%]</code> [Pandemic](https://frdcsa.org/~andrewdo/writings/behavior-tree-task-manager-for-covid-19.pdf)
        -   [ ] <code>[10%]</code> Food and water


<a id="orga18eea6"></a>

## Employment


<a id="org0963306"></a>

## Executive Function


<a id="org6067169"></a>

## Smart home


<a id="org00eb551"></a>

### Home Maintenance


<a id="org33a8100"></a>

### Equipment Maintenance


<a id="orge781a3c"></a>

## Relationship Management


<a id="org5418995"></a>

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


<a id="org82b716a"></a>

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
-   [X] [Python](https://www.python.org/)
    -   [X] [Py4J](https://py4j.org/") Python<->Java integration
    -   [ ] [python-agentspeak](https://github.com/niklasf/python-agentspeak)
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
-   [X] [LLMs](https://en.wikipedia.org/wiki/Large_language_model) (Large Language Models)
    -   [X] [Code Llama](https://ai.meta.com/blog/code-llama-large-language-model-coding/) 34B
        -   [X] Llama.cpp
    -   [X] [WizardLM](https://github.com/nlpxucan/WizardLM)


<a id="org01793e7"></a>

## [README](https://github.com/aindilis/flp/blob/main/README.md)


<a id="orgc847ef4"></a>

### [Broad overview of FLP](https://github.com/aindilis/flp/blob/main/README.md)


<a id="org2d21d02"></a>

### TODO Finish elaboration of finance and health planner capabilities


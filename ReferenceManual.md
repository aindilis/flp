
# Table of Contents

1.  [The Free Life Planner](#org5d497d7)
2.  [Technical Overview](#org258abb5)
    1.  [THIS REFERENCE MANUAL IS UNDER CONSTRUCTION](#org0962875)
3.  [Links](#org19cbc52)
4.  [You are at the ReferenceManual.md](#org7c0b525)
5.  [Reference Manual Contents](#orga49b2c4)
6.  [Introduction](#org1e1878d)
    1.  [Purpose](#org175c250)
    2.  [User Base](#org329ba86)
    3.  [Sample use cases](#orgfb11ee0)
    4.  [Status](#orge63d043)
7.  [Features](#org3d332fc)
    1.  [Voice Assistant](#org37483be)
    2.  [Workflow Manager](#org252b872)
    3.  [Health](#org240c41e)
        1.  [Evidence-Based Wellness](#orga223925)
        2.  [Exercise](#org1f67adf)
        3.  [Nutrition](#org4ebd8c5)
        4.  [Doctor's Visits and Orders](#orgd834ea5)
        5.  [Medications](#orgd5a8628)
        6.  [Mental Health](#org493ba7f)
    4.  [Time Management](#orga9c6293)
        1.  [Recurrences](#orgca8d068)
        2.  [Calendaring](#org829f87d)
        3.  [Planning, Scheduling and Execution](#org1b4c93a)
    5.  [Organization](#orgd23732e)
        1.  [Inventory Management](#org9fdec51)
        2.  [Adulting](#org51f924f)
    6.  [Interpersonal](#org85bc3a2)
        1.  [Communication Management](#orgc2bab91)
        2.  [Chore Charting](#org63a7aa6)
        3.  [Maintenance](#org8923d23)
        4.  [Smart Home](#orgb685ab2)
        5.  [Research and Development](#orgabd92d4)
    7.  [Self-Discipline](#org9fbb993)
        1.  [To-Do](#org454a4f4)
        2.  [Note-Taking](#org9593667)
        3.  [Scheduling](#orgeeac372)
        4.  [Self-Discipline State Machine](#orge718771)
        5.  [Gamification](#org538bf52)
        6.  [Movement Discipline](#orgb5812ee)
    8.  [Transportation/Shopping/Errands](#org2eb46ee)
        1.  [Transportation](#org7017e06)
        2.  [Shopping/Errands](#org2ef82d6)
    9.  [Document Management](#org00e8535)
    10. [Financial Planner](#orgee97b4b)
    11. [Emergency Preparedness](#org9d7e573)
    12. [Employment](#org085cfbd)
    13. [Executive Function](#orgade43cc)
    14. [Smart home](#org2632499)
        1.  [Maintenance](#org59f305a)
8.  [Major Technologies Used](#orgee16618)
9.  [More Info](#org1007c74)
    1.  [More Use Cases](#org81ed2ea)
    2.  [Links](#org2cb9309)


<a id="org5d497d7"></a>

# The Free Life Planner


<a id="org258abb5"></a>

# Technical Overview


<a id="org0962875"></a>

## THIS REFERENCE MANUAL IS UNDER CONSTRUCTION


<a id="org19cbc52"></a>

# Links

-   Please note that for now there are (rather confusingly) three
    important documents to see:
    -   The [original deprecated Free Life Planner repo](https://github.com/aindilis/free-life-planner#readme) (including screenshots and links)
    
    -   This document: the new [ReferenceManual.md](https://github.com/aindilis/flp/blob/main/ReferenceManual.md) (the most detailed overview of FLP (Free Life Planner))
    
    -   The paper ["The Free Life Planner: A Virtual Secondary Social Safety Net"](https://frdcsa.org/~andrewdo/flp-jwas-article-draft-1.pdf)


<a id="org7c0b525"></a>

# You are at the ReferenceManual.md


<a id="orga49b2c4"></a>

# Reference Manual Contents


<a id="org1e1878d"></a>

# Introduction


<a id="org175c250"></a>

## Purpose

-   A free/libre program for helping people with the logistics of
    daily life, helping to plan and secure things like food,
    medicine, finances, transportation, health and so on.
-   A short, medium and long-term life planner
-   Cognitive prosthesis for executive function
    -   Including for people w/ ADHD, autism, schizophrenia, dementia, etc
-   A "life manual" / "skills for living life"


<a id="org329ba86"></a>

## User Base

-   This software is intended to be of general use
-   However, people facing challenges are particularly likely to benefit more
    -   with disabilities such as pervasive developmental disorders
        -   "folks do not realize that they are one fall, auto accident,
            or vascular event away from being a person with a
            disability." - Mary Hart
    -   of limited means who are one misstep from disaster
    -   with disease, illness or medical conditions
    -   who are homeless
    -   returning citizens
    -   who experience relationship violence
    -   victims of persecution and hate
    -   victims of war or political oppression
    -   victims of natural or man-made disasters and climate change
    -   immigrants and refugees
    -   other groups not here accounted for


<a id="orgfb11ee0"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#org81ed2ea)


<a id="orge63d043"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org3d332fc"></a>

# Features


<a id="org37483be"></a>

## Voice Assistant

-   [X] Interactive Voice Assistant
    -   [X] Using [Alexa](https://alexa.amazon.com)
        -   [X] Networked/online access only
        -   [X] "Alexa, tell David, Andrew drank another glass of water"
    -   [X] Using [Rhasspy](https://rhasspy.readthedocs.io)
        -   [X] Both Air-gapped/offline access oand networked/online access
        -   [X] "Porcupine, How many glasses of water did Andrew drink today?"
        -   [X] ASR/STT (Automatic Speech Recognition, Speech To Text)
            -   [X] Using [tiemajor/whisper-rhasspy-http](https://github.com/seifane/whisper-rhasspy-http)
        -   [X] TTS
            -   [X] Using [coqui-ai/TTS](https://github.com/coqui-ai/TTS) server (Text To Speech)
            -   [ ] <code>[50%]</code> Using [Bark](https://github.com/suno-ai/bark) (Text To Speech)
-   [ ] <code>[60%]</code> Dialog manager
-   [X] Dialog manager
    -   [X] For single-step dialogues

<pre>
hasDialogEntry('tell <PERSON> <THING>').
dialogInterfaceQuery(Entry)  &#x2013;> ([tell];[talk,to]),grabber(Person,person),([about];[]),oneOrMore(token,Tokens),
	{getCurrentDateTime(Now),
	 currentAgent(Agent),
	 Entry = assert(atTime(Now,tell(Agent,Person,Tokens)))}.

curGaeilgeArSeo(tell(Agent,Person,TokenizedStatement),Gaeilge) :-
	getGloss(Agent,AgentGloss),
	getGloss(Person,PersonGloss),
	atomic<sub>list</sub><sub>concat</sub>(TokenizedStatement,' ',Statement),
	atomic<sub>list</sub><sub>concat</sub>([AgentGloss,told,PersonGloss,Statement],' ',Gaeilge).
</pre>

-   <code>[10%]</code> For multi-step dialogues
    -   [ ] <code>[10%]</code> [DIT](https://dit.uvt.nl), [Regulus](https://sf.net/p/regulus), [Trindikit](https://sf.net/p/trindikit), etc


<a id="org252b872"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks
    -   [X] PDDL based planner, which creates a (for now, linear) path through FLP to accomplish all objectives (Planning Domain Description Language)
        -   [ ] <code>[20%]</code> Generating constraints for Workflow Manager's PDDL planner

<pre>
'move-to-page'(begin,'user-agenda').
'complete-task'('mark-off-all-completed-from-agenda').
'complete-task'('sort-agenda').  'finish-page'('user-agenda').
</pre>

-   [ ] <code>[50%]</code> AgentSpeak integration
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


<a id="org240c41e"></a>

## Health


<a id="orga223925"></a>

### Evidence-Based Wellness

1.  General

    -   [ ] Medical Q&A using [DoctorGPT](https://github.com/llSourcell/DoctorGPT) or a successor LLM

2.  Data Collection and User Modeling

    -   [ ] <code>[50%]</code> Record / create an inventory of all user's medical symptoms
        -   [ ] List conditions, [medications](#orgd5a8628) and their effects
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
        -   [ ] Application of otherwise unavailable medical knowledge (in the absence of a medical professional)
        -   [ ] Argumentation-based synchronization and reconciliation when able to see medical professional
            -   [ ] Either in person
            -   [ ] Telemedicine / remote doctor
        -   [ ] [WOPR](https://github.com/aindilis/free-life-planner/blob/master/data-git/systems/planning/free_wopr.pl) contingency plans, represented in Prolog, fulfilled by Code Llama or GPT-4
            -   [ ] Library of COAs/SOPs (Courses Of Action, Standard Operating Procedures)
                -   [ ] Instructions for CPR, Heimlich, etc
                    -   [ ] Just in time
                    -   [ ] Ahead of time, studying administered by an ITS (Intelligent Tutoring System)
            -   [ ] Upon activation of contingency trigger:
                -   [ ] Executed using interactive execution system
                    -   [ ] JASWIPL (Jason/AgentSpeak(L)<->SWI-Prolog integration)
                    -   [ ] IEM2 (Interactive Execution Monitor verson 2)
                    -   [ ] Plan-Monitor
            -   [ ] <code>[30%]</code> [Flowcharts](https://online.visual-paradigm.com/diagrams/templates/flowchart/) / workflows for determining best professional treatment options
                -   [ ] ER, Urgent care, phone on-call doctor/nurse, telemedicine, etc (Emergency Room)
                    -   [ ] <code>[20%]</code> Hospital packing list including all necessary supplies for ER visit
        -   [ ] Medical fact checking
            -   [ ] Visual library of images for diagnosis and explanation
                -   [ ] CV-based algorithms trained to identify conditions (such as skin conditions or lesions) (Computer Vision)
        -   [ ] Integration with financial planner and inventory manager for ensuring all (potentially) necessary medical supplies kept in stock and not expired
        -   [ ] Argumentation-based deliberation regarding the validation of planned treatments


<a id="org1f67adf"></a>

### Exercise

-   [X] Fitness Manager
    -   [ ] <code>[33%]</code> Interactive plan monitoring of exercises
        -   [X] [exercise.bt](file:///var/lib/myfrdcsa/private/systems/behavior-trees/data-git/bts/p/exercise.bt)
    -   [ ] <code>[66%]</code> Track daily progress
        -   [X] Using Rhasspy Voice Assistant
            -   [X] "Porcupine, Andrew finished daily exercises"
        -   [X] Using legacy Alexa interface
            -   [X] "Alexa, tell David - Andrew did his morning exercises"


<a id="org4ebd8c5"></a>

### Nutrition

1.  Meal Planner

    -   [ ] Improves nutrition and taste
    -   [ ] <code>[40%]</code> Seamless integration with FLP's generalized action planning systems
    -   [ ] Many [meal planning resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] [Multiple meal planning and preparation systems](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
        -   [ ] <code>[50%]</code> [Gourmet-Formalog-Standalone](https://github.com/aindilis/gourmet-formalog-standalone/)
            -   [ ] Using [OpenFoodTox](https://www.efsa.europa.eu/en/data-report/chemical-hazards-database-openfoodtox), [Basket](https://github.com/fodmap-diet/basket)
        -   [ ] <code>[66%]</code> [PDDL-based mealplanner](https://frdcsa.org/%7eandrewdo/projects/mealplanning/)
        -   [ ] <code>[25%]</code> [Interactive cooking assistant](https://frdcsa.org/%7eandrewdo/WebWiki/CookingAssistant.html)
        -   [X] [PGourmet](https://altruisticsoftware.org/frdcsa/internal/pgourmet/)
        -   [ ] [Gourmet](https://altruisticsoftware.org/frdcsa/internal/gourmet)
        -   [ ] [st0opkid's MealSolver](https://github.com/aindilis/mealsolver)
    -   [ ] <code>[85%]</code> Nutrition lookup
        -   [X] Using [FDC](https://fdc.nal.usda.gov/) csvs converted to Prolog KB (Food Data Central)
        -   [X] Using Nutritionix
            -   [ ] Working (but offline due to air-gapping development server)
    -   [ ] [Inventory Management](#org9fdec51)
        -   [ ] User modeling
            -   [ ] <code>[40%]</code> [Self-discipline](#org9fbb993) coach software
                -   [ ] For hitting macros
                -   [ ] Understanding psychology of users' relationships to food
            -   [X] Helping w/ Portion control
                -   [X] Door sensor alerts on fridge and freezer
                -   [ ] <code>[20%]</code> Follow up dialog regarding intent when fridge and freezer accessed
                -   [ ] [Gamification](#org538bf52)
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
            -   [ ] [CURD](https://cs.cmu.edu/~ark/CURD) (Carnegie Mellon University Recipe Database)
            -   [ ] [Open-SESAME](https://github.com/swabhs/open-sesame) parser
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


<a id="orgd834ea5"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [X] Appointment calendar
    -   [ ] Track appointments and avoid double-booking and overbooking
    -   [X] Verbal and User-Agenda reminders
    -   [X] Q&A system for asking things like when is my next appointment
-   [ ] [Medical diagnostics](https://github.com/timhannifan/symptom-tree/issues/1)
-   [ ] <code>[40%]</code> Following doctors' orders
    -   [X] Scan into [Document Management System](#org00e8535) for managing (among other things) medical records
    -   [ ] <code>[90%]</code> Ensuring compliance via [Machine Reading Comprehension](https://paperswithcode.com/task/machine-reading-comprehension)
        -   [X] Using [WizardLM](https://github.com/nlpxucan/WizardLM) to extract instructions from documents
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
-   [ ] For when a physician is unavailable
    -   [ ] Diagnostic expert system
        -   [ ] [Diagnostics and Treatments](#org44019d5)
    -   [ ] First aid course of action system


<a id="orgd5a8628"></a>

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


<a id="org493ba7f"></a>

### Mental Health

-   [ ] Emotional security
    -   [ ] Managing triggers
    -   [ ] <code>[25%]</code> Reframing self-talk
-   [ ] Psychometric reporting
    -   [ ] Identifying factors
-   [ ] Systems for tracking symptoms
    -   [ ] [Executive function](https://github.com/aindilis/jason/tree/master/examples/executive-function-adapter)
    -   [ ] Negative self talk
        -   [ ] <code>[50%]</code> Rewrites negative self talk using LLM prompts (Large Language Models)
    -   [ ] Planning to achieve and maintain [human flourishing](https://arxiv.org/pdf/2302.09248.pdf)
        -   [ ] Planning for optimal productivity by meeting needs
            -   [ ] Pre/pro-active planning
            -   [ ] Root cause analysis for low-productivity
            -   [ ] <code>[75%]</code> Responses to low mood and low productivity
                -   [X] Elicits how the user is feeling
                -   [ ] <code>[75%]</code> Uses NLI/RTE to fetch from treatment DB (Natural Language Inference / Recognizing Textual Entailment)
            -   [ ] Task tracking and MTTC (Mean Time To Completion)
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


<a id="orga9c6293"></a>

## Time Management


<a id="orgca8d068"></a>

### Recurrences

-   [X] Dates
    -   [X] On a given date
    -   [X] On a given day of week
    -   [X] Through given days of week
    -   [X] Every n-th week/month/year
-   [ ] Times
    -   [X] Multiple specific time points
    -   [ ] Durations

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org829f87d"></a>

### Calendaring

1.  Capabilities

    -   [X] Scheduling appointments
    -   [X] Scheduling of chores
    -   [ ] Detect double-booking

2.  Integrations

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

3.  Financial Calendar

    -   [X] Show on calendar possible date and time ranges for recurring transactions


<a id="org1b4c93a"></a>

### Planning, Scheduling and Execution

1.  Planning

    -   [ ] <code>[25%]</code> Workflow Manager
    -   [ ] <code>[45%]</code> Metaplanning
    -   [X] Temporal planning
    -   [X] Contingent planning
    -   [ ] <code>[05%]</code> Temporally-contingent (metric) planning
    -   [X] Behavior tree reactive planning
    -   [X] [BDI reactive planning](http://jason.sourceforge.net/) (Belief-Desire-Intention)

2.  Planners

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
        -   [ ] Temporally-contingent (metric) planning
            -   [ ] [TraCE-lite](https://cgi.cse.unsw.edu.au/~eptcs/paper.cgi?AREA2022.6.pdf)
    -   [ ] <code>[90%]</code> [Behavior tree reactive planning](https://frdcsa.org/~andrewdo/writings/behavior-tree-task-manager-for-covid-19.pdf)
        -   [ ] <code>[90%]</code> [Plan Monitor](https://github.com/aindilis/plan-monitor)
            -   [ ] <code>[33%]</code> [More than 15 BT domains](#orga0317da)
            -   [ ] <code>[40%]</code> Execution of generated (PDDL/AgentSpeak(L)/Behavior Tree/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
    -   [X] BDI Agent (Belief-Desire-Intention)
        -   [X] Jason/AgentSpeak(L) w/ SWIPL integration (SWI-Prolog)
            -   [X] [More than 10 BDI domains](https://github.com/aindilis/jason/tree/master/examples)
        -   [ ] <code>[30%]</code> [Jason/AgentSpeak(L)<->Python<->(SuperAGI|BabyAGI|AutoGPT|MetaGPT|BeeBot) LLM-based autonomous agents](https://github.com/aindilis/jason/tree/master/examples/python-adapter)
    -   [ ] LLM-based autonomous agents
        -   [ ] [SuperAGI<->Jason/AgentSpeak(L)<->SWIPL<->FLP<->FRDCSA<->OpenCyc integration](https://lablab.ai/event/autonomous-agents-hackathon/frdcsa/agent-speak-toolkitbuilder-and-autopacker)

3.  Additional Planning System

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

4.  Some domains

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

5.  Plan Monitoring

    -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
    -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="orgd23732e"></a>

## Organization


<a id="org9fdec51"></a>

### Inventory Management

-   [ ] <code>[10%]</code> Supplier tracking
    -   [ ] <code>[25%]</code> Integration with cashflow tracking
    -   [ ] <code>[10%]</code> Semiautomatic reordering
        -   [ ] Helping to reorder from preferred vendor types, like organic, local, etc
-   [ ] <code>[66%]</code> Pantry management
    -   [ ] <code>[80%]</code> Nutrition lookup
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


<a id="org51f924f"></a>

### Adulting

-   [ ] ADLs
    -   [ ] Daily Self Care
-   [ ] IADLs
    -   [ ] Chore charting
        -   [ ] <code>[35%]</code> Track who/what/where/when regarding chores
        -   [X] Implement rewards via [Gamification](#org538bf52)


<a id="org85bc3a2"></a>

## Interpersonal

-   [ ] Team building


<a id="orgc2bab91"></a>

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
    -   [ ] Relationship management
        -   [ ] Friendships
        -   [ ] Family
        -   [ ] Groups
            -   [ ] Social advocacy/interest groups
        -   [X] Track birthdays, anniversaries, etc
    -   [ ] Team building
        -   [ ] Networking
        -   [ ] Colleagues
        -   [ ] [Teamcore/STEAM](https://teamcore.seas.harvard.edu/publications/towards-flexible-teamwork) (a Shell for TEAMwork)
        -   [ ] [TeamLog](https://www.amazon.com/Teamwork-Multi-Agent-Systems-Formal-Approach/dp/0470699884)
        -   [ ] [Horn-TeamLog](https://www.mimuw.edu.pl/~nguyen/HornTeamLog-long.pdf)
        -   [ ] [NL<sub>MAMS</sub>](https://link.springer.com/book/10.1007/978-3-319-39972-0) (Natural Language MultiAgent Mental Simulator)
        -   [ ] [Teamwork via Collective Intention](https://github.com/QuMuLab/teamwork-via-collective-intention)
        -   [X] [SNA](http://www.casos.cs.cmu.edu/projects/ora/software.php) (Social Network Analysis)


<a id="org63a7aa6"></a>

### Chore Charting

-   [ ] <code>[60%]</code> Chore ontology
    -   [X] Comprehensive chore lists
    -   [ ] <code>[50%]</code> Household chores
    -   [ ] <code>[80%]</code> Caregiving chores
-   [ ] <code>[66%]</code> Chore logic
    -   [ ] <code>[66%]</code> Scheduling, reminders, tracking and gamification
    -   [ ] <code>[66%]</code> Interactive plan execution using library of chore BTs (behavior trees)


<a id="org8923d23"></a>

### Maintenance

-   [ ] <code>[33%]</code> Household maintenance
    -   [ ] <code>[50%]</code> Complete list of scheduled home maintenance tasks
        -   [ ] <code>[10%]</code> Test fire alarms
        -   [X] Furnace maintenance
        -   [ ] etc
-   [X] Automotive maintenance schedule


<a id="orgb685ab2"></a>

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
    -   [ ] [Home maintenance](#org8923d23)
    -   [ ] [Emergency preparedness](#org9d7e573)
    -   [ ] SVRE
        -   [ ] <code>[30%]</code> IPSVRE
            -   [ ] <code>[90%]</code> Management of many aspects of individual environments including: lighting, climate, distractions, productivity, etc.


<a id="orgabd92d4"></a>

### Research and Development

-   [X] [Academician system](https://github.com/aindilis/academician)
-   [X] [Study system](https://github.com/aindilis/study)
-   [ ] ITS system (Intelligent Tutoring System)
-   [X] Seeker system


<a id="org9fbb993"></a>

## Self-Discipline


<a id="org454a4f4"></a>

### To-Do

-   [ ] <code>[50%]</code> Org and Org-agenda
-   [ ] <code>[75%]</code> [Do system (to-do lists)](https://github.com/aindilis/do)
    -   [ ] <code>[50%]</code> Do-convert
        -   [X] Track millions of goals
            -   [ ] <code>[60%]</code> Including their interdependencies
            -   [X] In a logical language
        -   [ ] <code>[90%]</code> Convert sexps to Prolog w/ QLF-persistence
    -   [ ] <code>[50%]</code> [Do-convert-logic](//github.com/aindilis/do-convert-logic)
        -   [X] Unique IDs for goals
        -   [X] [Track changes to goals](https://github.com/aindilis/do-convert-logic)
        -   [X] Export to SPSE2/Verb/PDDL
    -   [ ] <code>[33%]</code> Task classification, commitment extraction, dependency elicitation, duration estimation, ontology, prioritization, tagging, inferring completed tasks from changelogs using [LangPro](https://github.com/kovvalsky/LangPro)
-   [ ] Miscellaneous other partially completed to-do systems
    -   [ ] ([Score](https://github.com/aindilis/score), Lightspeed, [Normal-Form](https://github.com/aindilis/normal-form)/[Spark](https://github.com/aindilis/spark-frdcsa), Todo, PSE, Agenda, System-Planning, crontab, Task-Manager, PSE-x, todo-list-processor, [SPSE2](https://github.com/aindilis/spse), [SPSE2-Formalog](https://github.com/aindilis/spse2-formalog/), [FLP](https://github.com/aindilis/free-life-planner), [Do-Cyc](https://github.com/aindilis/do-cyc), Do-Pl)


<a id="org9593667"></a>

### Note-Taking

-   [X] Org-mode
-   [ ] <code>[10%]</code> Cyc-ZK (Zettelkasten)


<a id="orgeeac372"></a>

### Scheduling

-   [X] PDDL-2.2 (Planning Domain Definition Language)
-   [ ] <code>[20%]</code> PDDL+ (Planning Domain Definition Language Plus)
-   [ ] <code>[05%]</code> [Optaplanner](https://www.optaplanner.org/)
-   [ ] <code>[50%]</code> Automatically schedule tasks using (temporal) planning algorithms
    -   [ ] <code>[10%]</code> A taxonomy of task properties
-   [X] Schedule important tasks
-   [X] Set deadlines


<a id="orge718771"></a>

### Self-Discipline State Machine

-   [ ] Make sure the user is up to any task
-   [ ] Assist with follow-through on things like dieting, exercise, etc
-   [ ] <code>[33%]</code> Use the digital twin and plan to choose from possible things to do


<a id="org538bf52"></a>

### Gamification

-   [X] [Score](https://github.com/aindilis/score)
-   [ ] <code>[75%]</code> Rewards/Penalties
-   [X] [Manager](https://github.com/aindilis/manager)
-   [X] Rewards for completing recurrent tasks
-   [X] Daily penalty for leaving any recurrent tasks incomplete
-   [X] Penalties for lack of [movement discipline](#orgb5812ee)
-   [ ] <code>[50%]</code> Rewards for staying productive
-   [ ] <code>[60%]</code> Adherence tracker
    -   [X] Color coded labelled rectangles indicating the last accessed time of various FLP systems
        -   [X] Determine which systems are not being used correctly
        -   [X] Determine which sensors have stopped working (e.g. dead battery)


<a id="orgb5812ee"></a>

### Movement Discipline

-   [ ] Ensure we think before we move
    -   [ ] <code>[33%]</code> Optional mode where one must premeditate before moving to a different location


<a id="org2eb46ee"></a>

## Transportation/Shopping/Errands


<a id="org7017e06"></a>

### Transportation

-   [ ] <code>[25%]</code> Develop proper transportation plans
-   [ ] <code>[33%]</code> API look-up mashups (Application Programming Interface)
    -   [ ] <code>[90%]</code> Hours of operation
        -   [ ] <code>[90%]</code> Stores/offices/etc
    -   [ ] <code>[30%]</code> Weather
    -   [ ] <code>[30%]</code> Route planning
        -   [ ] Point to point
        -   [ ] "Traveling Salesman"
    -   [ ] <code>[90%]</code> Reverse geocoding
-   [ ] <code>[66%]</code> [Location logic](https://frdcsa.org/~andrewdo/projects/ll-rules.pl)
    -   [X] [Owntracks](https://owntracks.org/) integration
    -   [ ] <code>[75%]</code> Use "Location Logic" to provide reminders
        -   [ ] <code>[50%]</code> Locational rules
            -   [ ] <code>[75%]</code> e.g. Don't forget to bring this with you when you leave
            -   [ ] <code>[75%]</code> e.g. Silence one's cell phone in certain types of locations

<pre>
performAction(addToPendingTasks(Agent,unsilenceCellPhone(Agent,Phone))) :-
	currentAgent(Agent),
	hasMobilePhone(Agent,Phone),
	leaving(Agent,Location),
	isa(Location,movieTheater),
	hasRecentlyPerformedAction(Agent,silenceCellPhone(Agent,Phone)).
</pre>

-   [X] [Movement discipline](#orgb5812ee)


<a id="org2ef82d6"></a>

### Shopping/Errands

-   [X] Shopping list management
    -   [X] Integration with [financial management](#orgee97b4b)
        -   [X] OFX cross-referencing (Open Financial eXchange)
    -   [ ] <code>[33%]</code> Integration with inventory and pantry management
-   [ ] Buy/sell things as necessary
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
            -   [ ] <code>[25%]</code> Track all types of receipts
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


<a id="org00e8535"></a>

## Document Management

-   [ ] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork (Optical Character Recognition)
        -   [X] Cross reference with schedule
        -   [X] Ensure confidentiality of information
    -   [ ] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
        -   [ ] Track and help the user implement doctors orders
    -   [ ] <code>[90%]</code> Backup w/ Git
    -   [X] Export selected documents and folders
    -   [X] Digital library system
        -   [X] Equipment manuals
    -   [X] [Book reader](https://frdcsa.org/frdcsa/internal/clear)
    -   [X] [Information search management](#orgabd92d4)


<a id="orgee97b4b"></a>

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
        -   [X] Tell us when we're going to run out of money
            -   [X] Tell us how much we need to raise by when
-   [X] Temporal metric planning for finances
-   [X] Financial reasoning integrated with general planning
    -   [X] Adds financial reasoning to life-planning problems
    -   [X] Express expected date ranges of transactions using can, neg(oTime), months, date ranges, etc.
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] [TraCE](https://openreview.net/pdf?id=JJYg8KKLJtL) temporally-contingent (metric) planner integration
    -   [X] Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships
        -   [X] Help manage cash flow in tight situations
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
    -   [ ] Inventory/pantry [Inventory Management](#org9fdec51) integration
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


<a id="org9d7e573"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)
    -   [ ] <code>[10%]</code> Help the user stay on top of emergency preparedness
    -   [ ] Analyze which kinds of emergencies are particular to the users situation
    -   [ ] Prepare a "bug-out bag," emergency food and water supply, etc
    -   [ ] Help the user maintain a ready posture
    -   [ ] Safety plans and drills
    -   [ ] <code>[50%]</code> Recurrences for reminders to maintain equipment, supplies, plans and drills
    -   [ ] Safety plans
        -   [ ] <code>[05%]</code> Fire
        -   [ ] <code>[80%]</code> [Pandemic](https://frdcsa.org/~andrewdo/writings/behavior-tree-task-manager-for-covid-19.pdf)
        -   [ ] <code>[10%]</code> Food and water


<a id="org085cfbd"></a>

## Employment

-   [X] [Time tracking](https://altruisticsoftware.org/frdcsa/minor/consultant-support/)
-   [ ] Acquiring income
-   [ ] Job search
    -   [X] [Semi-automatic job applications](https://www.youtube.com/watch?v=qFRSwRVFuhE&feature=youtu.be)
    -   [ ] [<code>[90%]</code> Resume generation](https://github.com/aindilis/job-search)
        -   [ ] <code>[30%]</code> Dynamic resumes tailored to specific job posts
    -   [X] [Negotiation trainer](https://frdcsa.org/~andrewdo/WebWiki/AudienceDialog.html)


<a id="orgade43cc"></a>

## Executive Function

-   [ ] Intelligence Augmentation
    -   [ ] Learning
        -   [ ] Education
        -   [ ] Empirical
    -   [ ] Cognitive Prosthesis
    -   [ ] Nootropics
-   [ ] Problem-Solving
    -   [ ] Goal setting


<a id="org2632499"></a>

## Smart home


<a id="org59f305a"></a>

### Maintenance

-   [ ] Equipment
-   [ ] Computer systems

1.  Home Maintenance

    -   [X] Home

2.  Equipment Maintenance

    -   [X] Automotive


<a id="orgee16618"></a>

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
    -   [X] [Py4J](https://py4j.org/") Python<->Java integration (Python For Java)
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
        -   [X] [Llama.cpp](https://github.com/ggerganov/llama.cpp)
    -   [X] [WizardLM](https://github.com/nlpxucan/WizardLM)
-   [X] [Rhasspy](https://rhasspy.readthedocs.io/en/latest/) Voice Assistant integration
    -   [X] [whisper-rhasspy-http](https://github.com/tiemajor/whisper-rhasspy-http) plugin
        -   [X] [Whisper](https://openai.com/research/whisper) ASR/STT plugin (Automatic Speech Recognition, Speech To Text)
    -   [X] [coqui-ai/TTS](https://github.com/coqui-ai/TTS) (Text To Speech)
        -   [X] [Bark](https://github.com/suno-ai/bark) TTS (Text To Speech)


<a id="org1007c74"></a>

# More Info


<a id="org81ed2ea"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to one's doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on one's taxes, and to change one's air filter
-   Telling you that a particular plan of one's violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="org2cb9309"></a>

## Links

-   Here is the best paper on FLP:
    -   <https://frdcsa.org/~andrewdo/flp-jwas-article-draft-1.pdf>

-   Here is the main FLP (Free Life Planner) code site:
    -   <https://github.com/aindilis/free-life-planner>
    
    -   Screenshots
        -   <https://github.com/aindilis/free-life-planner#a-few-screenshots>
    
    -   Subsystems
        -   <https://github.com/aindilis/free-life-planner#flp-subsystems>

-   Here is the release of FRDCSA (Formalized Research Database: Cluster, Study and Apply) Panoply Git VM (Virtual Machine) (containing older and stripped down versions of FRDCSA and Free Life Planner):
    -   <https://github.com/aindilis/frdcsa-panoply-git-20200329>

-   Here is a story describing the Free Life Planner:
    -   <https://frdcsa.org/~andrewdo/writings/homeless-story.html>

-   Here is the most recent talk on FLP:
    -   <https://ontologforum.org/index.php/ConferenceCall_2022_04_20>
    -   <https://frdcsa.org/~andrewdo/ontolog-2022010-reduced.mp4>

-   Here is the beginning of the release of FRDCSA (marking the Panoply release the official public release and deeming the last five years of work the "private" version of FRDCSA, and backporting from private to public as able):
    -   <https://github.com/aindilis/frdcsa-installer>

-   Here is a recent talk from EmacsConf2019 about FRDCSA/FLP/Panoply:
    -   <https://frdcsa.org/~andrewdo/frdcsa-emacsconf2019-final.webm>

-   Here is an independent codebase (no dependencies on FRDCSA) for interactive plan monitoring:
    -   <https://github.com/aindilis/plan-monitor>

-   Here is some more recent work on the IEM (Interactive Execution Monitor):
    -   <https://frdcsa.org/~andrewdo/iem2-2.mp4>
    -   <https://frdcsa.org/~andrewdo/iem2-3.mp4>

-   Here is a video of an older, much smaller and simpler version of the FLP booting up (be careful, noisy):
    -   <https://www.youtube.com/watch?v=t_dCAlf26LE>

-   Here is an incomplete paper on FRDCSA:
    -   <https://frdcsa.org/~andrewdo/pioneer/wk1/frdcsa.pdf>

-   Here is an outdated and incomplete paper on FLP:
    -   <https://frdcsa.org/~andrewdo/pioneer/wk1/flp.pdf>

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

-   Here is the Logicmoo (Logic Multi-User Dungeon - Object Oriented) system mentioned in the EmacsConf video, which FLP draws heavily upon and intends to integrate with eventually:
    -   <https://github.com/TeamSPoon/prologmud/wiki>

-   And here the design docs for Logicmoo:
    -   <https://drive.google.com/drive/#folders/0B0QA19UX0ehlV1ZEaXEzc3hjTWM>


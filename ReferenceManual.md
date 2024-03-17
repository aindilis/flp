
# Table of Contents

1.  [Technical Overview](#orge46999d)
    1.  [THIS REFERENCE MANUAL IS UNDER CONSTRUCTION](#orgffe3882)
2.  [Links](#org4dfea1b)
3.  [You are at the ReferenceManual.md](#org65f3974)
4.  [Reference Manual Contents](#org4ada07d)
5.  [Introduction](#orgfe14406)
    1.  [Purpose](#orgad3899a)
    2.  [User Base](#org7f80e4c)
    3.  [Sample Use Cases](#org9f21846)
    4.  [Status](#org540c664)
6.  [Features](#org361b422)
    1.  [Voice Assistant](#orga2d05a3)
    2.  [Workflow Manager](#orgaf08aa9)
    3.  [Health](#org02206b8)
        1.  [Evidence-Based Wellness](#org47e794f)
        2.  [Exercise](#orgb3fe7c4)
        3.  [Nutrition](#org177f4df)
        4.  [Doctor's Visits and Orders](#orgd760240)
        5.  [Medications](#org42ec1d8)
        6.  [Mental Health](#org488f490)
    4.  [Time Management](#orgf344e3a)
        1.  [Recurrences](#org7f8a967)
        2.  [Calendaring](#org747c555)
        3.  [Planning, Scheduling and Execution](#org822eb07)
    5.  [Organization](#org18e0c72)
        1.  [Inventory Management](#org5c252fc)
        2.  [Adulting](#orgab29cdc)
        3.  [Communication Management](#org6932ed4)
        4.  [Chore Charting](#org6b6b829)
        5.  [Maintenance](#org3e3c3a0)
        6.  [Smart Home](#org5b0de8a)
        7.  [Research and Development](#org8add76f)
    6.  [Self-Discipline](#orgd10b28a)
        1.  [To-Do](#org44118ce)
        2.  [Checklists](#orgcb0e9d9)
        3.  [Note-Taking](#org3782950)
        4.  [Scheduling](#org03ea38b)
        5.  [Self-Discipline State Machine](#org91438bb)
        6.  [Gamification](#org0ac19e1)
        7.  [Movement Discipline](#org7be2a6d)
    7.  [Transportation/Shopping/Errands](#orgc0d0c43)
        1.  [Transportation](#orgc4893b3)
        2.  [Shopping/Errands](#orgccc27a6)
    8.  [Document Management](#org3ec204b)
    9.  [Financial Planner](#org4fed8ae)
    10. [Emergency Preparedness](#orga732622)
    11. [Employment](#orgcce44a7)
    12. [Executive Function](#orgcb18567)
7.  [Future Work](#orgb0a186b)
    1.  [Integrations](#orga593c9d)
8.  [Special Use Cases](#org0218dda)
    1.  [Homelessness](#org24097b4)
    2.  [Illness](#org8076662)
    3.  [Insolvency](#orgd008c2a)
    4.  [Abuse](#orgdcec5ac)
    5.  [Climate Change and Disaster Management](#org6e6d768)
9.  [Major Technologies Used](#orgc95c72b)
10. [More Info](#org499290e)
    1.  [More Use Cases](#org12cba62)
    2.  [Recognition](#org7becf39)
    3.  [Links](#org9d46ae8)
        1.  [Screenshots](#org105e2d2)
        2.  [Subsystems](#orgffcd9e3)
        3.  [More Links](#org0ac9635)


<a id="orge46999d"></a>

# Technical Overview


<a id="orgffe3882"></a>

## THIS REFERENCE MANUAL IS UNDER CONSTRUCTION


<a id="org4dfea1b"></a>

# Links

-   Please note that for now there are (rather confusingly) three
    important documents to see:
    -   The [original deprecated Free Life Planner repo](https://github.com/aindilis/free-life-planner#readme) (including screenshots and links)
    
    -   This document: the new [ReferenceManual.md](https://github.com/aindilis/flp/blob/main/ReferenceManual.md) (the most detailed overview of FLP (Free Life Planner))
    
    -   The paper ["The Free Life Planner: A Virtual Secondary Social Safety Net"](https://frdcsa.org/~andrewdo/flp-jwas-article-draft-1.pdf)


<a id="org65f3974"></a>

# You are at the ReferenceManual.md


<a id="org4ada07d"></a>

# Reference Manual Contents


<a id="orgfe14406"></a>

# Introduction


<a id="orgad3899a"></a>

## Purpose

-   A free/libre program for helping people with the logistics of
    daily life, helping to plan and secure things like food,
    medicine, finances, transportation, health and so on.
-   A short, medium and long-term life planner
-   Cognitive prosthesis for executive function
    -   Including for people w/ ADHD, autism, schizophrenia, dementia, etc
-   A "life manual" / "skills for living life"


<a id="org7f80e4c"></a>

## User Base

-   This software is intended to be of general use
-   However, people facing challenges are particularly likely to benefit more
    -   With disabilities such as pervasive developmental disorders
        -   "Folks do not realize that they are one fall, auto accident,
            or vascular event away from being a person with a
            disability." - Mary Hart
    -   Of limited means who are one misstep from disaster
    -   With disease, illness or medical conditions
    -   Who are unhoused
    -   Returning citizens
    -   Victims of:
        -   Relationship violence
        -   Persecution and hate
        -   War or political oppression
        -   Natural or man-made disasters and climate change
    -   Immigrants and refugees
    -   Other demographics not here accounted for


<a id="org9f21846"></a>

## Sample Use Cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#org12cba62)


<a id="org540c664"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org361b422"></a>

# Features


<a id="orga2d05a3"></a>

## Voice Assistant

-   ✅ Interactive Voice Assistant
    -   ✅ Using [Alexa](https://alexa.amazon.com)
        
        -   ✅ Networked/online access only
        
        -   ✅ "Alexa, tell David, Andrew drank another glass of water"
    -   ✅ Using [Rhasspy](https://rhasspy.readthedocs.io)
        -   ✅ Both Air-gapped/offline access and networked/online access
        -   ✅ "Porcupine, How many glasses of water did Andrew drink today?"
        -   ✅ ASR/STT (Automatic Speech Recognition, Speech To Text)
            -   ✅ Using [tiemajor/whisper-rhasspy-http](https://github.com/seifane/whisper-rhasspy-http)
        -   ✅ TTS
            -   ✅ Using [coqui-ai/TTS](https://github.com/coqui-ai/TTS) server (Text To Speech)
            -   [ ] <code>[50%]</code> Using [Bark](https://github.com/suno-ai/bark) (Text To Speech)
-   [ ] <code>[60%]</code> Dialog manager
-   ✅ Dialog manager
    -   ✅ For single-step dialogues
-   ✅ Latest LLM models for Question Answering (Large Language Models)

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


<a id="orgaf08aa9"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks
    -   ✅ PDDL based planner, which creates a (for now, linear) path through FLP to accomplish all objectives (Planning Domain Description Language)
        -   [ ] <code>[20%]</code> Generating constraints for Workflow Manager's PDDL planner

<pre>
'move-to-page'(begin,'user-agenda').
'complete-task'('mark-off-all-completed-from-agenda').
'complete-task'('sort-agenda').  'finish-page'('user-agenda').
</pre>

-   [ ] <code>[55%]</code> AgentSpeak integration
    -   [ ] <code>[60%]</code> [JASWIPL "metaplanning" systems integration](https://github.com/aindilis/jason/tree/master/examples/executive-function-adapter) (Jason/AgentSpeak(L)<->SWI-Prolog integration)
    -   [ ] <code>[30%]</code> [Jason/AgentSpeak(L)<->Python<->(SuperAGI|BabyAGI|AutoGPT|MetaGPT|BeeBot) LLM-based autonomous agents](https://github.com/aindilis/jason/tree/master/examples/python-adapter)
        -   ✅ [Video about integrating AgentSpeak(L) with LLM-based Autonomous Agents](https://youtube.com/watch?v=8vsQzTD3Qfk)
            -   (Please note, the above video shows an outdated way of connecting all these systems. The new method uses SPAMI)
    -   [ ] <code>[30%]</code> [SPAMI](https://github.com/aindilis/agentspeak-l-swi-prolog-meta-interpreter) (SWI-Prolog AgentSpeak(L) Meta-Interpreter)
        -   [ ] <code>[20%]</code> Prolog Jason-like event/control-loop
    -   [ ] <code>[65%]</code> Contingency planning
        -   ✅ [WOPR NL-based Contingency Planner](https://frdcsa.org/~andrewdo/wopr-heavily-redacted-20231107.tgz) (War Operation Plan Response, Natural Language)
            -   ✅ Using NL for KRR and generating contingency plans via BFS (Knowledge Representation and Reasoning, Breadth First Search)
                -   ✅ Exports current fluents from WSM (World State Monitor)
                -   ✅ Prompts Mistral Instruct 7B to generate:
                    -   ✅ Threats for the initial situation
                    -   ✅ Potential contingency plans for those threats
                    -   ✅ Effects of the contingency plans
                    -   ✅ New world state by applying the effects to the parent situation
                    -   ✅ Then recurse
            -   <code>[50%]</code> Draft paper on contingency planning with WOPR
        -   ✅ WebUI to select ground or unground contingency triggers
            -   ✅ Latest LLM models for generation of NL contingency plans for triggers (Natural Language)
    -   [ ] <code>[30%]</code> Dynamically add/remove goals and replan

<pre>
+!quarantine(Person) <-
        ?hasRoom(Person,Room);
        !atLocation(Person,Room);
        +prohibited((move(Person,Location),Location \\= Room));
        &#x2026;
</pre>


<a id="org02206b8"></a>

## Health


<a id="org47e794f"></a>

### Evidence-Based Wellness

1.  General

    -   [ ] Medical Q&A using [DoctorGPT](https://github.com/llSourcell/DoctorGPT) or a successor LLM

2.  Data Collection and User Modeling

    -   [ ] <code>[50%]</code> Record / create an inventory of all user's medical symptoms
        -   [ ] List conditions, [medications](#org42ec1d8) and their effects
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
                    -   [ ] SPAMI or JASWIPL
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


<a id="orgb3fe7c4"></a>

### Exercise

-   ✅ Fitness Manager
    -   [ ] <code>[33%]</code> Interactive plan monitoring of exercises
        -   ✅ [exercise.bt](file:///var/lib/myfrdcsa/private/systems/behavior-trees/data-git/bts/p/exercise.bt)
    -   [ ] <code>[66%]</code> Track daily progress
        -   ✅ Using Rhasspy Voice Assistant
            -   ✅ "Porcupine, Andrew finished daily exercises"
        -   ✅ Using legacy Alexa interface
            -   ✅ "Alexa, tell David - Andrew did his morning exercises"


<a id="org177f4df"></a>

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
        -   ✅ [PGourmet](https://altruisticsoftware.org/frdcsa/internal/pgourmet/)
        -   [ ] [Gourmet](https://altruisticsoftware.org/frdcsa/internal/gourmet)
        -   [ ] [st0opkid's MealSolver](https://github.com/aindilis/mealsolver)
    -   [ ] <code>[85%]</code> Nutrition lookup
        -   ✅ Using [FDC](https://fdc.nal.usda.gov/) csvs converted to Prolog KB (Food Data Central)
        -   ✅ Using Nutritionix
            -   [ ] Working (but offline due to air-gapping development server)
    -   [ ] [Inventory Management](#org5c252fc)
        -   [ ] User modeling
            -   [ ] <code>[40%]</code> [Self-discipline](#orgd10b28a) coach software
                -   [ ] For hitting macros
                -   [ ] Understanding psychology of users' relationships to food
            -   ✅ Helping w/ Portion control
                -   ✅ Door sensor alerts on fridge and freezer
                -   [ ] <code>[20%]</code> Follow up dialog regarding intent when fridge and freezer accessed
                -   [ ] [Gamification](#org0ac19e1)
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
                -   ✅ WordNet
                -   ✅ OpenCyc
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
        -   ✅ Walking the user through resultant BTs using [Plan-Monitor](https://github.com/aindilis/plan-monitor)
    -   [ ] Food style and preference learning
        -   [ ] Estimate when the user is likely to get tired of some recipe or ingredient(s)
    -   [ ] Comprehensive meal contingent plan generation
    -   [ ] Planning tool to avoid food spoilage and expiration in various storage conditions
        -   ✅ Door sensor alerts on fridge and freezer       
            -   [ ] <code>[20%]</code> Follow up dialog regarding intent when fridge and freezer accessed
                -   ✅ Ask user why they triggered door sensors
        -   [ ] Calculate remaining time before spoilage based on storage condition temporal history
    -   [ ] Rotating emergency food and water provisions
        -   [ ] Stock enough provisions to survive n-months
        -   [ ] Consuming the oldest staples first to prevent victuals from expiring
    -   [ ] Food pantries
    -   [ ] <code>[50%]</code> Receipt tracker
        -   [ ] <code>[25%]</code> Bill splitter


<a id="orgd760240"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   ✅ Appointment calendar
    -   [ ] Track appointments and avoid double-booking and overbooking
    -   ✅ Verbal and User-Agenda reminders
    -   ✅ Q&A system for asking things like when is my next appointment
-   [ ] [Medical diagnostics](https://github.com/timhannifan/symptom-tree/issues/1)
-   [ ] <code>[40%]</code> Following doctors' orders
    -   ✅ Scan into [Document Management System](#org3ec204b) for managing (among other things) medical records
    -   [ ] <code>[90%]</code> Ensuring compliance via [Machine Reading Comprehension](https://paperswithcode.com/task/machine-reading-comprehension)
        -   ✅ Using [WizardLM](https://github.com/nlpxucan/WizardLM) to extract instructions from documents
        -   ✅ Converting orders into an BT (Behavior Tree)
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
        -   [ ] [Diagnostics and Treatments](#org218ea61)
    -   [ ] First aid course of action system


<a id="org42ec1d8"></a>

### Medications

-   ✅ Medication reminders and recording
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


<a id="org488f490"></a>

### Mental Health

-   [ ] Techniques
    -   [ ] <code>[15%]</code> Psychotherapy aid using [Carl-Llama-2 Therapy LLM](https://huggingface.co/TheBloke/Carl-Llama-2-13B-GGUF)
        -   [ ] Potential commentator for Audience communications proxy
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
                -   ✅ Elicits how the user is feeling
                -   [ ] <code>[75%]</code> Uses NLI/RTE to fetch from treatment DB (Natural Language Inference / Recognizing Textual Entailment)
            -   [ ] Task tracking and MTTC (Mean Time To Completion)
-   [ ] Systems for conditions
    -   [ ] ADHD (Attention-Deficit/Hyperactivity Disorder)
        -   [ ] Distraction ontology
            -   [ ] <code>[40%]</code> (Pre/re)active planning using [WOPR](https://github.com/aindilis/free-life-planner/blob/master/data-git/systems/planning/free_wopr.pl) to minimize or mitigate distractions (War Operation Plan Response)
        -   [ ] <code>[30%]</code> different FLP modes using environmental anchors
            -   ✅ Automatic priming and transitions
            -   ✅ Change smart lighting colors for different modes, like working, relaxing, etc
                -   ✅ Auto detection of working, relaxing, etc
            -   ✅ Managing music for different modes (using playlists)
    -   [ ] Autism
        -   [ ] Using different tools for and from [Computational Autism](https://link.springer.com/book/10.1007/978-3-319-39972-0)
            -   [ ] [Supplemental materials](https://storage.googleapis.com/springer-extras/zip/2016/978-3-319-39972-0.zip) like NL<sub>MAMS</sub>
        -   [ ] Social reasoning prostheses
            -   [ ] [Audience](https://github.com/aindilis/audience), Mach, SocBot, [IRC-KB](https://github.com/aindilis/irc-kb), [POSI](https://frdcsa.org/~andrewdo/writings/flourish-2009.pdf), PPOSI, Social Intelligence, etc
    -   [ ] Schizophrenia
    -   [ ] etc


<a id="orgf344e3a"></a>

## Time Management


<a id="org7f8a967"></a>

### Recurrences

-   ✅ Dates
    -   ✅ On a given date
    -   ✅ On a given day of week
    -   ✅ Through given days of week
    -   ✅ Every n-th week/month/year
-   [ ] Times
    -   ✅ Multiple specific time points
    -   [ ] Durations

How to schedule something for the last day of every month:

<pre>
hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
        deltaTime([<sub>Year</sub>-<sub>Month</sub>-1],days(-1),YMD).
</pre>


<a id="org747c555"></a>

### Calendaring

1.  Capabilities

    -   ✅ Scheduling appointments
    -   ✅ Scheduling of chores
    -   [ ] Detect double-booking

2.  Integrations

    -   [ ] With different agenda, calendaring, and planning / scheduling systems
        -   ✅ Import from
            -   ✅ Org-agenda
            -   ✅ SPSE2 (Shared Priority System Editor v2)
            -   ✅ Google Calendar
            -   ✅ ICS (Internet Calendar Scheduling)
        -   [ ] Export to
            -   ✅ Org-agenda
            -   [ ] <code>[85%]</code> SPSE2
            -   [ ] <code>[33%]</code> Google Calendar
            -   ✅ ICS

3.  Financial Calendar

    -   ✅ Show on calendar possible date and time ranges for recurring transactions


<a id="org822eb07"></a>

### Planning, Scheduling and Execution

1.  Planning

    -   [ ] <code>[25%]</code> Workflow Manager
    -   [ ] <code>[55%]</code> Metaplanning
        -   [ ] <code>[50%]</code> Jason/AgentSpeak(L)
        -   [ ] <code>[50%]</code> SPAMI (SWI-Prolog AgentSpeak(L) Meta-Interpreter)
    -   ✅ Temporal planning
    -   ✅ Contingent planning
    -   [ ] <code>[05%]</code> Temporally-contingent (metric) planning
    -   [ ] <code>[15%]</code> OSP (Oversubscription planning)
    -   ✅ Behavior tree reactive planning
    -   ✅ [BDI reactive planning](http://jason.sourceforge.net/) (Belief-Desire-Intention)

2.  Planners

    -   ✅ [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) planning
        -   ✅ LPG<sub>TD</sub><sub>1</sub><sub>0</sub>, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, OPTIC<sub>CLP</sub>, CLG, Colin2<sub>CLP</sub>, HSPS, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, SGPlan<sub>522</sub>
            -   ✅ [More than 200 PDDL life planning domains](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/templates)
        -   ✅ [SPSE2](https://frdcsa.org/visual-aid/pdf/Temporal-Planning-and-Inferencing-for-Personal-Task-Management-with-SPSE2.pdf)
        -   ✅ [PDDL plan interactive execution monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)
        -   ✅ PSEx3 integrated tasks and finances system
    -   ✅ Contingent planning
        -   ✅ [DNFct](https://github.com/aindilis/dnfct-frdcsa/) (Disjunctive Normal Form: Contingent)
            -   ✅ [More than 10 contingent life planning domains](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/templates/contingent/dnfct)
        -   [ ] <code>[33%]</code> [AP/3T](https://github.com/aindilis/3t-frdcsa) (Adversarial Planner)
        -   [ ] Temporally-contingent (metric) planning
            -   [ ] [TraCE](https://cgi.cse.unsw.edu.au/~eptcs/paper.cgi?AREA2022.6.pdf)-lite
                -   [Explaining Temporal Plans with Incomplete Knowledge and Sensing Information](https://openreview.net/pdf?id=JJYg8KKLJtL)
                -   [Compiling Contingent Planning into Temporal Planning for Robust AUV Deployments](https://pure.hw.ac.uk/ws/portalfiles/portal/63630796/ICAPS_PlanRob_2021_TCP_.pdf)
    -   [ ] Oversubscription planning
        -   [ ] <code>[20%]</code> [Symbolic-OSP](https://github.com/speckdavid/symbolic-osp)
    -   [ ] <code>[90%]</code> [Behavior tree reactive planning](https://frdcsa.org/~andrewdo/writings/behavior-tree-task-manager-for-covid-19.pdf)
        -   [ ] <code>[90%]</code> [Plan Monitor](https://github.com/aindilis/plan-monitor)
            -   [ ] <code>[33%]</code> [More than 15 BT domains](#prolog-agent-agents)
            -   [ ] <code>[40%]</code> Execution of generated (PDDL/AgentSpeak(L)/Behavior Tree/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
    -   ✅ BDI Agent (Belief-Desire-Intention)
        -   ✅ JASWIPL: Jason/AgentSpeak(L) w/ SWIPL integration (SWI-Prolog)
            -   ✅ [More than 10 BDI domains](https://github.com/aindilis/jason/tree/master/examples)
        -   [ ] <code>[30%]</code> [Jason/AgentSpeak(L)<->Python<->(SuperAGI|BabyAGI|AutoGPT|MetaGPT|BeeBot) LLM-based autonomous agents](https://github.com/aindilis/jason/tree/master/examples/python-adapter)
        -   [ ] <code>[30%]</code> SPAMI: Pure Prolog AgentSpeak(L)
            -   [ ] <code>[15%]</code> [27 BDI agents/domain](#prolog-agent-agents)
    -   [ ] LLM-based autonomous agents
        -   [ ] [SuperAGI<->Jason/AgentSpeak(L)<->SWIPL<->FLP<->FRDCSA<->OpenCyc integration](https://lablab.ai/event/autonomous-agents-hackathon/frdcsa/agent-speak-toolkitbuilder-and-autopacker)

3.  Additional Planning System

    -   [ ] Factored planning
    -   ✅ Planning systems
        -   ✅ Verber
        -   ✅ SPSE2
        -   ✅ SPSE2-Formalog
    -   [ ] Digital twin
        -   ✅ WSM (World State Monitor)
        -   ✅ Fitness Manager
        -   [ ] <code>[55%]</code> Nested checklists
    -   [ ] <code>[33%]</code> Kanban
    -   [ ] <code>[33%]</code> Goalban
    -   ✅ User Agenda (for recurrences)
    -   ✅ Habit tracker
        -   [ ] <code>[50%]</code> Allow installation and uninstallation of habits
        -   ✅ Tracks from a growing list of elicited habits, records when engaging in / avoiding behaviors
    -   [ ] <code>[60%]</code> Resource Manager (plans over inventory/etc)
        -   [ ] <code>[80%]</code> Productivity Requirements
    -   [ ] <code>[25%]</code> Subsystem monitoring
        -   [ ] <code>[25%]</code> Mission Control
        -   [ ] <code>[35%]</code> Normal Form
    -   [ ] Gamification

4.  Some domains

    -   [ ] <code>[50%]</code> Plan cycles (cycle)
        -   ✅ Toy plan cycle
        -   [ ] Real-world plan cycle
    -   [ ] <code>[33%]</code> PDDL Standard domain library (basekb)
        -   ✅ [agent, biomaintenance, chores, deontic, economic, food, hygiene, misc, security, space, tool, work](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/worlds/basekb)
    -   [ ] <code>[33%]</code> Behavior Tree standard library
        -   ✅ deliveries, electrical, errands, exercise, financial, food-pantries, groceries, hospitalization, hygiene, meal-planning, medication, movement-discipline, paperwork, plumbing, security, sickness, sleep, trip-planning
    -   [ ] <code>[10%]</code> Household emergency preparedness
        -   [ ] Planning ahead for bad weather
            -   [ ] e.g. Stock up on groceries before a major storm hits
            -   [ ] <code>[50%]</code> Weather control rules
    -   [ ] <code>[15%]</code> [27 Prolog-Agent/SPAMI/Autonomous LLM agents](https://github.com/aindilis/autonomous-ai-agent/tree/main/agents)
        -   [ ] <code>[15%]</code> Academician - Research topics completely on its own.
        -   [ ] <code>[15%]</code> Agent Smith - Install FRDCSA on a remote system.
        -   [ ] <code>[15%]</code> API Learner - Maps APIs by reading API documentation and examples.
        -   [ ] <code>[15%]</code> Architect - Curate software collections and matchmake capabilities with feature requests.
        -   [ ] <code>[15%]</code> Argument - Develop arguments for an against a position, using LLMs, and reason them out.
        -   [ ] <code>[15%]</code> Audience - Proxy all communications and make sure they are appropriate and act accordingly if not.
        -   [ ] <code>[15%]</code> Executive Function - Take our large to-do list systems and help us to achieve them, and set new goals.
        -   [ ] <code>[15%]</code> IAEC2 - Analyze files and other digital objects and figure out what they are and act accordingly with them.
        -   [ ] <code>[15%]</code> IAEC - Analyze files and other digital objects and figure out what they are and act accordingly with them.
        -   [ ] <code>[15%]</code> Manager - Track me down if I am not available, and ensure I received given messages.
        -   [ ] <code>[15%]</code> Metaplanner - Metaplan with sub-planners, for instance the financial planner, moving things around like expected dates of certain payments.
        -   [ ] <code>[15%]</code> MUSH - Analyze error messages and research how to resolve them.
        -   [ ] <code>[15%]</code> Neo - Control subagents properly.
        -   [ ] <code>[15%]</code> Packager - Figure out what software we have and need, and go about packaging it for Debian.
        -   [ ] <code>[15%]</code> Praise Bot - Generate compliments and otherwise reward the user for productivity, encouraging them to stay motivated and productive.
        -   [ ] <code>[15%]</code> Sentinel - Monitor and housekeep the computer, making sure that all files get moved to their intended locations, and extract information useful to FRDCSA/FLP/Prolog-Agent.
        -   [ ] <code>[15%]</code> Setanta Agent - Administer machines, map networks, read manpages and write code, etc.
        -   [ ] <code>[15%]</code> Setup Debian - Bring a vanilla Debian machine up to speed, ready to have FRDCSA installed on it.
        -   [ ] <code>[15%]</code> SIEVE - Work with what it knows about software systems, and use previously mentioned agents to help it create large repositories of packaged software.
        -   [ ] <code>[15%]</code> Softbot1 - Act as a software robot, moving around on a system and doing intelligent things with it.
        -   [ ] <code>[15%]</code> Suasion - Persuade people of the truth of some conclusion.
        -   [ ] <code>[15%]</code> SVRS - Monitor all sensors and behave accordingly.
        -   [ ] <code>[15%]</code> System Implementor - Take research papers and attempt to reimplement when necessary.
        -   [ ] <code>[15%]</code> Vger2 - Tool to create a massive software collection, using various techniques to build an ontology of systems, and determine their availability.
        -   [ ] <code>[15%]</code> Web Agent - Read, understand and navigate websites, helping with research.
        -   [ ] <code>[15%]</code> WOPR - Develop continency plans for a given situation.
        -   [ ] <code>[15%]</code> Workflow Manager - Help the user to make use of FLP by walking them throw what they need to do.

5.  Plan Monitoring

    -   ✅ [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
    -   ✅ [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="org18e0c72"></a>

## Organization


<a id="org5c252fc"></a>

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
                -   ✅ Wireless USB barcode scanner hidraw agent
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
        -   ✅ Use coffeemaker using plan monitor
    -   [ ] <code>[90%]</code> Automatically schedule maintenance
    -   [ ] <code>[10%]</code> Interactively perform maintenance
-   [ ] Executable product warranties
    -   [ ] Integration with planning and scheduling


<a id="orgab29cdc"></a>

### Adulting

-   [ ] ADLs
    -   [ ] Daily Self Care
-   [ ] IADLs
    -   [ ] Chore charting
        -   [ ] <code>[35%]</code> Track who/what/where/when regarding chores
        -   ✅ Implement rewards via [Gamification](#org0ac19e1)


<a id="org6932ed4"></a>

### Communication Management

-   [Proxy all communications](https://github.com/aindilis/audience)
    -   ✅ Dossier system
        -   [ ] Relationship management
            -   [ ] <code>[25%]</code> ACLs (Access Control Lists)
            -   ✅ Talking points
        -   ✅ Memcons (Memorandum of Conversation)
        -   [ ] <code>[33%]</code> Commitments extraction
        -   [ ] <code>[33%]</code> Goal/Interest/Ability extraction
    -   [ ] Persuasion
        -   [ ] <code>[10%]</code> A/B Testing
        -   ✅ [Argument mapping](https://argdown.org/)
    -   [ ] Relationship management
        -   [ ] Friendships
        -   [ ] Family
        -   [ ] Groups
            -   [ ] Social advocacy/interest groups
        -   ✅ Track birthdays, anniversaries, etc
    -   [ ] Team building
        -   [ ] Networking
        -   [ ] Colleagues
        -   [ ] [Teamcore/STEAM](https://teamcore.seas.harvard.edu/publications/towards-flexible-teamwork) (a Shell for TEAMwork)
        -   [ ] [TeamLog](https://www.amazon.com/Teamwork-Multi-Agent-Systems-Formal-Approach/dp/0470699884)
        -   [ ] [Horn-TeamLog](https://www.mimuw.edu.pl/~nguyen/HornTeamLog-long.pdf)
        -   [ ] [NL<sub>MAMS</sub>](https://link.springer.com/book/10.1007/978-3-319-39972-0) (Natural Language MultiAgent Mental Simulator)
        -   [ ] [Teamwork via Collective Intention](https://github.com/QuMuLab/teamwork-via-collective-intention)
        -   ✅ [SNA](http://www.casos.cs.cmu.edu/projects/ora/software.php) (Social Network Analysis)


<a id="org6b6b829"></a>

### Chore Charting

-   [ ] <code>[60%]</code> Chore ontology
    -   ✅ Comprehensive chore lists
    -   [ ] <code>[50%]</code> Household chores
    -   [ ] <code>[80%]</code> Caregiving chores
-   [ ] <code>[66%]</code> Chore logic
    -   [ ] <code>[66%]</code> Scheduling, reminders, tracking and gamification
    -   [ ] <code>[66%]</code> Interactive plan execution using library of chore BTs (behavior trees)


<a id="org3e3c3a0"></a>

### Maintenance

-   [ ] <code>[33%]</code> Household maintenance
    -   [ ] <code>[50%]</code> Complete list of scheduled home maintenance tasks
        -   [ ] <code>[10%]</code> Test fire alarms
        -   ✅ Furnace maintenance
        -   [ ] etc
-   ✅ Automotive maintenance schedule


<a id="org5b0de8a"></a>

### Smart Home

-   [ ] SVRS Integrated shelter management
    -   [ ] Sensor network
        -   ✅ Security and surveillance
            -   [ ] Cyberphysical Security
                -   [ ] Network Monitoring
                    -   [ ] Setanta, Setanta-Agent, jnettop
                -   [ ] Remote Execution
                    -   [ ] Prolog-Agent
                        -   [ ] SPAMI
                -   [ ] Tools for updating Air Gapped systems
                -   [ ] HIPAA rules implemented in a logic program
            -   ✅ [SDR](https://github.com/merbanan/rtl_433) sensor monitoring (Software Defined Radio)
            -   ✅ Home defense preparations and contingency planning
            -   ✅ Video cameras and perimeter defense sensors
                -   [ ] <code>[20%]</code> Video understanding (similar to [VSAM](http://www.cs.cmu.edu/~vsam/))
                    -   ✅ Object recognition
                    -   [ ] Activity detection
                        -   [ ] <code>[25%]</code> Suspicious/anomalous activity detection
        -   [ ] <code>[50%]</code> Smart lighting control
            -   [ ] <code>[50%]</code>  For managing moods (such as, red - during work) for productivity, relaxation, etc
            -   ✅ Indicating availability to housemates (red - do not disturb, etc)
        -   ✅ [Event logging and inference](https://github.com/aindilis/elog2)
            
            -   ✅ Action triggers
                -   [ ] <code>[60%]</code> Changing smart lighting based on detected work activity
                -   [ ] <code>[50%]</code> Penalization for lack of movement discipline (e.g. left room without plan)
                -   [ ] Reactive systems
                    -   [ ] <code>[33%]</code> Climate/temperature control
                        -   [ ] <code>[33%]</code> Open windows, Turn the AC/heater on/off, etc
                    -   [ ] <code>[20%]</code> Weather monitoring
                        -   [ ] Warnings to prepare for storms, extreme weather
            
            -   [ ] <code>[10%]</code> Complex event detection
                -   [ ] <code>[20%]</code> [RTEC](https://github.com/aartikis/RTEC) (Run Time Event Calculus)
    -   [ ] [Home maintenance](#org3e3c3a0)
    -   [ ] [Emergency preparedness](#orga732622)
    -   [ ] SVRE
        -   [ ] <code>[30%]</code> IPSVRE
            -   [ ] <code>[90%]</code> Management of many aspects of individual environments including: lighting, climate, distractions, productivity, etc.
    -   [ ] <code>[66%]</code> PDDL+ based pest control planners

1.  Maintenance

    -   [ ] Equipment
    -   [ ] Computer systems

2.  Home Maintenance

    -   ✅ Home

3.  Equipment Maintenance

    -   ✅ Automotive


<a id="org8add76f"></a>

### Research and Development

-   ✅ [Academician system](https://github.com/aindilis/academician)
-   ✅ [Study system](https://github.com/aindilis/study)
-   [ ] ITS system (Intelligent Tutoring System)
-   ✅ Seeker system
    -   KSAs (Knowledge Seeking Agents)
-   Automatic Arugument Mining and Construction


<a id="orgd10b28a"></a>

## Self-Discipline


<a id="org44118ce"></a>

### To-Do

-   [ ] <code>[50%]</code> Org and Org-agenda
-   [ ] <code>[75%]</code> [Do system (to-do lists)](https://github.com/aindilis/do)
    -   [ ] <code>[50%]</code> Do-convert
        -   ✅ Track millions of goals
            -   [ ] <code>[60%]</code> Including their interdependencies
            -   ✅ In a logical language
        -   [ ] <code>[90%]</code> Convert sexps to Prolog w/ QLF-persistence
    -   [ ] <code>[50%]</code> [Do-convert-logic](//github.com/aindilis/do-convert-logic)
        -   ✅ Unique IDs for goals
        -   ✅ [Track changes to goals](https://github.com/aindilis/do-convert-logic)
        -   ✅ Export to SPSE2/Verb/PDDL
    -   [ ] <code>[33%]</code> Task classification, commitment extraction, dependency elicitation, duration estimation, ontology, prioritization, tagging, inferring completed tasks from changelogs using [LangPro](https://github.com/kovvalsky/LangPro)
-   [ ] Miscellaneous other partially completed to-do systems
    -   [ ] ([Score](https://github.com/aindilis/score), Lightspeed, [Normal-Form](https://github.com/aindilis/normal-form)/[Spark](https://github.com/aindilis/spark-frdcsa), Todo, PSE, Agenda, System-Planning, crontab, Task-Manager, PSE-x, todo-list-processor, [SPSE2](https://github.com/aindilis/spse), [SPSE2-Formalog](https://github.com/aindilis/spse2-formalog/), [FLP](https://github.com/aindilis/free-life-planner), [Do-Cyc](https://github.com/aindilis/do-cyc), Do-Pl)


<a id="orgcb0e9d9"></a>

### Checklists

-   [Disciple](https://github.com/aindilis/disciple)
    -   <code>[70%]</code> Checklists for daily activities
    -   <code>[70%]</code> Interfaces for marking off items from checklist
        -   <code>[80%]</code> Alexa/Rhasspy voice interface
        -   <code>[80%]</code> FCMS WebUI log


<a id="org3782950"></a>

### Note-Taking

-   ✅ Org-mode
-   [ ] <code>[10%]</code> Cyc-ZK (Zettelkasten)


<a id="org03ea38b"></a>

### Scheduling

-   ✅ PDDL-2.2 (Planning Domain Definition Language)
-   [ ] <code>[20%]</code> PDDL+ (Planning Domain Definition Language Plus)
-   [ ] <code>[05%]</code> [Optaplanner](https://www.optaplanner.org/)
-   [ ] <code>[50%]</code> Automatically schedule tasks using (temporal) planning algorithms
    -   [ ] <code>[10%]</code> A taxonomy of task properties
-   ✅ Schedule important tasks
-   ✅ Set deadlines


<a id="org91438bb"></a>

### Self-Discipline State Machine

-   [ ] Make sure the user is up to any task
-   [ ] Assist with follow-through on things like dieting, exercise, etc
-   [ ] <code>[33%]</code> Use the digital twin and plan to choose from possible things to do


<a id="org0ac19e1"></a>

### Gamification

-   ✅ [Score](https://github.com/aindilis/score)
-   [ ] <code>[75%]</code> Rewards/Penalties
-   ✅ [Manager](https://github.com/aindilis/manager)
-   ✅ Rewards for completing recurrent tasks
-   ✅ Daily penalty for leaving any recurrent tasks incomplete
-   ✅ Penalties for lack of [movement discipline](#org7be2a6d)
-   [ ] <code>[50%]</code> Rewards for staying productive
-   [ ] <code>[60%]</code> Adherence tracker
    -   ✅ Color coded labelled rectangles indicating the last accessed time of various FLP systems
        -   ✅ Determine which systems are not being used correctly
        -   ✅ Determine which sensors have stopped working (e.g. dead battery)


<a id="org7be2a6d"></a>

### Movement Discipline

-   [ ] Ensure we think before we move
    -   [ ] <code>[33%]</code> Optional mode where one must premeditate before moving to a different location


<a id="orgc0d0c43"></a>

## Transportation/Shopping/Errands


<a id="orgc4893b3"></a>

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
    -   ✅ [Owntracks](https://owntracks.org/) integration
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

-   ✅ [Movement discipline](#org7be2a6d)


<a id="orgccc27a6"></a>

### Shopping/Errands

-   ✅ Shopping list management
    -   ✅ Integration with [financial management](#org4fed8ae)
        -   ✅ OFX cross-referencing (Open Financial eXchange)
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
    -   ✅ Online Shopping
        -   ✅ Receipts
            -   [ ] <code>[25%]</code> Track all types of receipts
            -   ✅ Parsers and storage for online store receipts
        -   ✅ Online order tracker
        -   ✅ Online delivery tracker
    -   [ ] Brick and Mortar Shopping
        -   ✅ Receipts
            -   ✅ Parsers for brick and mortar store receipts
            -   ✅ OCR for physical receipts
        -   [ ] "Traveling Salesman" route planning
            -   [ ] [Open Route Service API (optimization) integration](https://openrouteservice.org/)
-   [ ] Selling
    -   [ ] Broker - personal selling system
        -   [ ] Argumentation
            -   [ ] Decide what to sell
            -   [ ] Decide whether to sell


<a id="org3ec204b"></a>

## Document Management

-   [ ] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   ✅ Scan and OCR all paperwork (Optical Character Recognition)
        -   ✅ Cross reference with schedule
        -   ✅ Ensure confidentiality of information
    -   [ ] Integration of document-related tasks into Workflow Manager
        -   ✅ [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
        -   [ ] Track and help the user implement doctors orders
    -   [ ] <code>[90%]</code> Backup w/ Git
    -   ✅ Export selected documents and folders
    -   ✅ Digital library system
        -   ✅ Equipment manuals
    -   ✅ [Book reader](https://frdcsa.org/frdcsa/internal/clear)
    -   ✅ [Information search management](#org8add76f)


<a id="org4fed8ae"></a>

## Financial Planner

-   [ ] <code>[50%]</code> [Financial Planning](https://github.com/aindilis/financial-planning#readme)
-   ✅ Quickly forecast finances almost indefinitely into the future
    -   ✅ Specify recurring transactions
    -   ✅ Automatically detect recurring transactions from OFX exports and plan for them
        -   e.g.

<pre>
promiseToPayForSpec('ELEC',andrewDougherty,'<ELECTRICCOMPANY>',dollars(93.00),[can([1]),not(onTime([3])))).
</pre>

-   ✅ View expected financial transactions along with primary agenda on a calendar
    -   ✅ Calenderical recurrences using CLP (Constraint Logic Programming) 
        -   [ ] <code>[25%]</code> WebUI for editing financial recurrences
    -   ✅ Predicted transactions' date, description, debit or credit and running balance
        -   ✅ As a list
        -   ✅ As a chart
    -   ✅ Tell us when we're going to run out of money
        -   ✅ Tell us how much we need to raise by when

-   ✅ Temporal metric planning for finances
-   [ ] Purchase Decision Support System / Broker Buy/Sell System
    -   [ ] Oversubscription planning
        -   [ ] Planning for maximizing utility given a cost bound, when can't accomplish all goals
-   ✅ Financial reasoning integrated with general planning
    -   ✅ Adds financial reasoning to life-planning problems
    -   ✅ Express expected date ranges of transactions using can, neg(onTime), months, date ranges, etc.
-   [ ] Metaplanners help develop contingency plans for different financial problems
    -   [ ] [TraCE](https://openreview.net/pdf?id=JJYg8KKLJtL) temporally-contingent (metric) planner integration
    -   ✅ Unexpected delays
    -   [ ] Overcharges and unapproved charges
    -   [ ] Cash flow problems and hardships
        -   ✅ Help manage cash flow in tight situations
-   ✅ Abduction of recurrences and predicted events from bank statements in OFX or CSV (Open Financial Exchange, Comma-Separated Values)
    -   [ ] Retrospectively analyze prior predictions
        -   [ ] To update or correct financial recurrences
-   ✅ [IEM2](https://frdcsa.org/~andrewdo/iem2-3.mp4) for walking user through plans
    -   [ ] <code>[50%]</code> Verify preconditions
    -   ✅ Update world state with all effects
        -   ✅ Extraction of world state deltas
    -   [ ] <code>[25%]</code> WebUI for IEM2 (using Mock Perl/Tk objects)
-   [ ] <code>[75%]</code> SPSE2->PSEx3 export (Planning, Scheduling and Execution System (Extended), version 3)
    -   [ ] <code>[75%]</code> Integrating financial reasoning and other domains, with SPSE's to-do dependency graph
-   ✅ Modification of PDDL/Verb domain/problem and temporal world state
-   ✅ Financial alerts
    -   ✅ Text-to-speech alerts for recurrent transactions
-   [ ] [Purchase Management](https://frdcsa.org/frdcsa/minor/broker)
    -   [ ] [PDSS](https://frdcsa.org/frdcsa/minor/purchase-decision-support-system/index.html) (Purchase Decision Support System)
        -   [ ] <code>[05%]</code> Oversubscription Planning using [Sym-Osp](https://github.com/speckdavid/symbolic-osp)
        -   [ ] Argumentation-based [PDSS](https://frdcsa.org/frdcsa/minor/purchase-decision-support-system/index.html) (Purchase Deciscion Support System)
            -   [ ] Reasoning over user needs
            -   [ ] Critical questions:
                -   [ ] Is this purchase [ethical](https://frdcsa.org/frdcsa/minor/ethical-consumer-system/index.html)/necessary/within-budget?
                    -   The assumption is "do not purchase," which must be soundly defeated to gain permission
                    -   [ ] Product and seller comparison
                    -   [ ] Payment plan management
    -   ✅ Tracking purchases and deliveries
    -   [ ] Inventory/pantry [Inventory Management](#org5c252fc) integration
    -   [ ] Resource manager (automatic reordering and stock management)
    -   [ ] Receipt tracker
        -   [ ] <code>[50%]</code> Online
        -   [ ] <code>[50%]</code> Brick and mortar
        -   ✅ Matching bank records to receipts
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


<a id="orga732622"></a>

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


<a id="orgcce44a7"></a>

## Employment

-   ✅ [Time tracking](https://altruisticsoftware.org/frdcsa/minor/consultant-support/)
-   [ ] Acquiring income
-   [ ] Job search
    -   ✅ [Semi-automatic job applications](https://www.youtube.com/watch?v=qFRSwRVFuhE&feature=youtu.be)
    -   [ ] [<code>[90%]</code> Resume generation](https://github.com/aindilis/job-search)
        -   [ ] <code>[30%]</code> Dynamic resumes tailored to specific job posts
    -   ✅ [Negotiation trainer](https://frdcsa.org/~andrewdo/WebWiki/AudienceDialog.html)


<a id="orgcb18567"></a>

## Executive Function

-   [ ] Intelligence Augmentation
    -   [ ] Learning
        -   [ ] Education
        -   [ ] Empirical
    -   [ ] Cognitive Prosthesis
        -   [ ] Prolog-Agent Intelligent Situated Agent / Softbot
    -   [ ] Nootropics
-   [ ] Problem-Solving
    -   [ ] Goal setting


<a id="orgb0a186b"></a>

# Future Work


<a id="orga593c9d"></a>

## Integrations

-   [ ] FLP-2.0 automatic refactoring/rewrite using [MetaGPT](https://github.com/geekan/MetaGPT)-like program synthesis
-   [ ] <code>[15%]</code> [Eurisko](https://white-flame.com/am-eurisko.html) for [IAEC](https://github.com/aindilis/iaec-notes)
-   [ ] <code>[20%]</code> [am-utexas](https://github.com/aindilis/am-utexas) for IAEC
-   [ ] [TraCE](https://cgi.cse.unsw.edu.au/~eptcs/paper.cgi?AREA2022.6.pdf)-lite
-   [ ] <code>[15%]</code> Symbolic-OSP
-   [ ] [s(CASP)](https://utdallas.edu/~gupta/csr-scasp.pfd)<->FLP(SWIProlog) integration for Event Calculus/commonsense reasoning
-   [ ] FreeKBS2/Prolog context/microtheory support
-   [ ] Privacy
    -   [ ] [HIPAA](http://code.google.com/archive/p/hipaa/) compliance
    -   [ ] Encryption
        -   [ ] Data-at-rest encryption
        -   [ ] In-memory encryption
        -   [ ] Full-disk encryption
    -   [ ] Various security methodologies:
        -   [ ] Principle of least privilege
        -   [ ] Additional security partitioning


<a id="org0218dda"></a>

# Special Use Cases


<a id="org24097b4"></a>

## Homelessness

-   [ ] [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [ ] [Helping the Homeless](https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanner.html)
-   [ ] [Pioneer Contest Week 4 Update](https://frdcsa.org/~andrewdo/writings/flp-update-4.html)
-   [ ] [Pioneer Application](https://frdcsa.org/~andrewdo/writings/pioneer.app/Application.html)


<a id="org8076662"></a>

## Illness

-   [ ] [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [ ] <code>[10%]</code> [Akahige](https://frdcsa.org/frdcsa/internal/akahige)


<a id="orgd008c2a"></a>

## Insolvency

-   [ ] <code>[25%]</code> [Financial Planner](#org4fed8ae)


<a id="orgdcec5ac"></a>

## Abuse

-   [ ] <code>[25%]</code> <https://github.com/RescueSocialTech/Domestic_Abuse_Simulations>


<a id="org6e6d768"></a>

## Climate Change and Disaster Management

-   [ ] <code>[10%]</code> [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="orgc95c72b"></a>

# Major Technologies Used

-   [ ] [SWI-Prolog](https://www.swi-prolog.org/) (Sociaal-Wetenschappelijke Informatica)
    -   ✅ [Julian](https://fifth-postulate.nl/julian/) time library
    -   ✅ [CLP(fd)](https://www.swi-prolog.org/man/clpfd.html) (Constraint Logic Programming)
    -   [ ] <code>[50%]</code> [QLF](https://www.swi-prolog.org/pldoc/man?section=qlf) (Quick Load Format)
-   ✅ [Perl](https://www.perl.org/)
    -   ✅ [YASWI](https://metacpan.org/pod/Language::Prolog::Yaswi) (Yet Another interface to SWI-Prolog) Perl<->SWI-Prolog Interface
    -   ✅ [Catalyst MVC](http://catalyst.perl.org/Catalyst) (Model/View/Controller)
        -   ✅ [ShinyCMS](https://shinycms.org/) (Content Management System)
    -   ✅ [Mojolicious](https://www.mojolicious.org/)
-   ✅ [Java](https://www.java.com/en/)
    -   ✅ [JavaPengine](https://github.com/aindilis/JavaPengine) (Java<->SWI-Prolog)
    -   ✅ [Jason/AgentSpeak(L)](http://jason.sourceforge.net/wp/)
        -   ✅ [JPL](https://jpl7.org/) (Java Prolog Library?) Java<->SWI-Prolog
    -   ✅ [Alexa](https://github.com/alexa/alexa-skills-kit-sdk-for-java) voice skill interface
    -   ✅ Cyc Java API<->Inline Perl
-   ✅ [Python](https://www.python.org/)
    -   ✅ [Py4J](https://py4j.org/") Python<->Java integration (Python For Java)
    -   [ ] [python-agentspeak](https://github.com/niklasf/python-agentspeak)
-   ✅ [Bash](https://www.gnu.org/software/bash/) scripting
-   ✅ [Emacs integration](https://www.youtube.com/watch?v=0l3K__C9Dkc)
-   ✅ [PDDL 2.2](https://planning.wiki/ref/pddl22/domain) temporal metric planning
    -   ✅ [LPG-td-1.0](https://lpg.unibs.it/lpg/)
    -   ✅ [OPTIC<sub>CLP</sub>](https://nms.kcl.ac.uk/planning/software/optic.html) (Optimizing Preferences and Time-Dependent Costs) (Coin-or Linear Programming)
-   ✅ [Vampire-KIF](https://en.wikipedia.org/wiki/Vampire_(theorem_prover)) (Knowledge Interchange Format) ATP (Automated Theorem Proving) system
-   ✅ [SUMO](https://github.com/ontologyportal/sumo)
-   ✅ [OpenCyc](https://sourceforge.net/projects/opencyc/)
-   [ ] [MariaDB/MySQL](https://mariadb.org/) persistence
    -   ✅ Through [UniLang](https://github.com/aindilis/unilang)/[FreeKBS2](https://github.com/aindilis/freekbs2) (Universal Language) (Free Knowledge Based System v2)
    -   [ ] [<code>[50%]</code> Directly from SWI-Prolog using ODBC](https://github.com/aindilis/data-integration) (Open DataBase Connectivity)
-   [ ] <code>[33%]</code> [Inform7](https://github.com/ganelson/inform)
-   ✅ [LLMs](https://en.wikipedia.org/wiki/Large_language_model) (Large Language Models)
    -   ✅ [Mistral Instruct 7B](https://huggingface.com/TheBloke/Mistral-7B-Instruct-v0.1-GGUF)
    -   ✅ [WizardLM](https://github.com/nlpxucan/WizardLM)
    -   ✅ [Code Llama](https://ai.meta.com/blog/code-llama-large-language-model-coding/) 34B
        -   ✅ [Llama.cpp](https://github.com/ggerganov/llama.cpp)
    -   LLEMMA 7B
-   ✅ [Rhasspy](https://rhasspy.readthedocs.io/en/latest/) Voice Assistant integration
    -   ✅ [whisper-rhasspy-http](https://github.com/tiemajor/whisper-rhasspy-http) plugin
        -   ✅ [Whisper](https://openai.com/research/whisper) ASR/STT plugin (Automatic Speech Recognition, Speech To Text)
    -   ✅ [coqui-ai/TTS](https://github.com/coqui-ai/TTS) (Text To Speech)
        -   ✅ [Bark](https://github.com/suno-ai/bark) TTS (Text To Speech)


<a id="org499290e"></a>

# More Info


<a id="org12cba62"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to one's doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on one's taxes, and to change one's air filter
-   Telling you that a particular plan of one's violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="org7becf39"></a>

## Recognition

-   [Pioneer Results](https://frdcsa.org/~andrewdo/projects/1stPlace.jpg)
-   [Pioneer Email](https://frdcsa.org/~andrewdo/projects/pioneer-email.txt)
-   [Testimonials](https://altruisticsoftware.org/frdcsa/#testimonials)


<a id="org9d46ae8"></a>

## Links


<a id="org105e2d2"></a>

### Screenshots

-   <https://github.com/aindilis/free-life-planner#a-few-screenshots>


<a id="orgffcd9e3"></a>

### Subsystems

-   <https://github.com/aindilis/free-life-planner#flp-subsystems>


<a id="org0ac9635"></a>

### More Links

-   Here is the best paper on FLP:
    -   <https://frdcsa.org/~andrewdo/flp-jwas-article-draft-1.pdf>

-   Here is the main FLP (Free Life Planner) code site:
    -   <https://github.com/aindilis/free-life-planner>

-   Here is the release of FRDCSA (Formalized Research Database: Cluster, Study and Apply) Panoply Git VM (Virtual Machine) (containing older and stripped down versions of FRDCSA and Free Life Planner):
    -   <https://github.com/aindilis/frdcsa-panoply-git-20200329>

-   Here is a story describing the Free Life Planner:
    -   <https://frdcsa.org/~andrewdo/writings/homeless-story.html>

-   Here is the most recent talk on FLP:
    -   <https://ontologforum.org/index.php/ConferenceCall_2022_04_20>
    -   <https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4>

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


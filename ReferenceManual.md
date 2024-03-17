
# Table of Contents

    1.  [Overview](#orge5ef10d)
        1.  [📖 Table of Contents](#org531b26c)
        2.  [🌟 Introduction <a name="introduction"></a>](#orge0d6493)
        3.  [🏗️ System Architecture <a name="system-architecture"></a>](#org5604758)
        4.  [🧩 Key Components <a name="key-components"></a>](#org0bc7665)
        5.  [🔍 Subsystem Overview <a name="subsystem-overview"></a>](#orga31c113)
        6.  [🛣️ Development Roadmap <a name="development-roadmap"></a>](#org87f833c)
        7.  [🤝 Contributing <a name="contributing"></a>](#org3ea88a7)
        8.  [📜 License <a name="license"></a>](#org0dc6d25)
1.  [Summarized Reference](#org96a306e)
    1.  [Table of Contents](#orgc5c9c04)
    2.  [1. Introduction <a name="introduction"></a>](#orgb927e25)
        1.  [Purpose](#orgf933fef)
        2.  [User Base](#orgd03add7)
        3.  [Sample Use Cases](#orgea52104)
        4.  [Status](#orge72edf5)
    3.  [2. Features <a name="features"></a>](#org637634b)
        1.  [Voice Assistant <a name="voice-assistant"></a>](#org62c21ab)
        2.  [Workflow Manager <a name="workflow-manager"></a>](#orga48f661)
        3.  [Health <a name="health"></a>](#org22159f3)
        4.  [Time Management <a name="time-management"></a>](#org83f6f4e)
        5.  [Organization <a name="organization"></a>](#org6db5320)
        6.  [Self-Discipline <a name="self-discipline"></a>](#orgdb80d94)
        7.  [Transportation, Shopping, and Errands <a name="transportation-shopping-errands"></a>](#orgc6ceeb0)
        8.  [Document Management <a name="document-management"></a>](#orgac082ab)
        9.  [Financial Planner <a name="financial-planner"></a>](#orge603867)
        10. [Emergency Preparedness <a name="emergency-preparedness"></a>](#org97ccb86)
        11. [Employment <a name="employment"></a>](#org8760d5a)
        12. [Executive Function <a name="executive-function"></a>](#org2d7e3e6)
    4.  [3. Future Work <a name="future-work"></a>](#org7a8517d)
    5.  [4. Special Use Cases <a name="special-use-cases"></a>](#orgfa258cb)
    6.  [5. Major Technologies Used <a name="major-technologies"></a>](#org7099caf)
    7.  [6. Additional Resources <a name="additional-resources"></a>](#org0c7bedd)
        1.  [Use Cases <a name="use-cases"></a>](#org5b6eb44)
        2.  [Recognition <a name="recognition"></a>](#org2c7a4ae)
        3.  [Links <a name="links"></a>](#org8f9a501)
2.  [Full Reference](#orgd3a802d)
3.  [Technical Overview](#org253baa1)
    1.  [THIS REFERENCE MANUAL IS UNDER CONSTRUCTION](#org8a72df0)
4.  [Links](#org4672c71)
5.  [You are at the ReferenceManual.md](#org199b08e)
6.  [Reference Manual Contents](#org4951e36)
7.  [Introduction](#org543ea63)
    1.  [Purpose](#org288aa77)
    2.  [User Base](#org9ac14df)
    3.  [Sample Use Cases](#org97976ab)
    4.  [Status](#org47ce553)
8.  [Features](#org5e8f861)
    1.  [Voice Assistant](#orgdc5a670)
    2.  [Workflow Manager](#orga82012a)
    3.  [Health](#org86ad1a4)
        1.  [Evidence-Based Wellness](#org1a2eb13)
        2.  [Exercise](#org16a7dd2)
        3.  [Nutrition](#org83d949b)
        4.  [Doctor's Visits and Orders](#orga829150)
        5.  [Medications](#orga5c1ec3)
        6.  [Mental Health](#orge41ef4e)
    4.  [Time Management](#org18ef72f)
        1.  [Recurrences](#org6c239cd)
        2.  [Calendaring](#orgfcf9ff8)
        3.  [Planning, Scheduling and Execution](#orgbca49a1)
    5.  [Organization](#org604f8be)
        1.  [Inventory Management](#org917f172)
        2.  [Adulting](#orgba766bf)
        3.  [Communication Management](#org6496fc2)
        4.  [Chore Charting](#orgc6efbf8)
        5.  [Maintenance](#orgb6e5fbd)
        6.  [Smart Home](#orgfdf5b18)
        7.  [Research and Development](#org17b2fd3)
    6.  [Self-Discipline](#org8d7c976)
        1.  [To-Do](#org54c233e)
        2.  [Checklists](#orgbbb19d7)
        3.  [Note-Taking](#org04831ca)
        4.  [Scheduling](#org332ed42)
        5.  [Self-Discipline State Machine](#org454cde8)
        6.  [Gamification](#orga101896)
        7.  [Movement Discipline](#org0874241)
    7.  [Transportation/Shopping/Errands](#org15f9f2c)
        1.  [Transportation](#org05b0cd7)
        2.  [Shopping/Errands](#org22b4f0e)
    8.  [Document Management](#org88b86a1)
    9.  [Financial Planner](#org49c546b)
    10. [Emergency Preparedness](#orgcc1767e)
    11. [Employment](#org95119fb)
    12. [Executive Function](#org79d792e)
9.  [Future Work](#org38750f1)
    1.  [Integrations](#org89a61e3)
10. [Special Use Cases](#orgcb8bc8f)
    1.  [Homelessness](#orgda5f06d)
    2.  [Illness](#org605c34f)
    3.  [Insolvency](#org5b8f9ff)
    4.  [Abuse](#org427f65d)
    5.  [Climate Change and Disaster Management](#orgf71f52b)
11. [Major Technologies Used](#org5c40d45)
12. [More Info](#org3ecb8f5)
    1.  [More Use Cases](#orgf0c81b7)
    2.  [Recognition](#orgaf1ed8c)
    3.  [Links](#org87007e1)
        1.  [Screenshots](#orge8937df)
        2.  [Subsystems](#orge7c9170)
        3.  [More Links](#orgbede063)


<a id="orge5ef10d"></a>

## Overview

Welcome to the Free Life Planner (FLP) Reference Manual! This
comprehensive guide is designed to provide a detailed overview of
FLP's architecture, capabilities, and ongoing development. Whether
you're a developer, researcher, or simply curious about the project,
this manual will help you understand the inner workings of FLP and how
it can be leveraged to improve lives.


<a id="org531b26c"></a>

### 📖 Table of Contents

1.  [Introduction](#introduction)
2.  [System Architecture](#system-architecture)
3.  [Key Components](#key-components)
4.  [Subsystem Overview](#subsystem-overview)
5.  [Development Roadmap](#development-roadmap)
6.  [Contributing](#contributing)
7.  [License](#license)


<a id="orge0d6493"></a>

### 🌟 Introduction <a name="introduction"></a>

The Free Life Planner (FLP) is an ambitious artificial intelligence
project aimed at providing a comprehensive, open-source life
management system. By integrating a wide range of AI techniques and
tools, FLP empowers individuals, particularly those facing challenges
or disadvantages, to navigate the complexities of daily life with
greater ease and confidence.

At its core, FLP is driven by the belief that everyone deserves access
to the benefits of cutting-edge technology, regardless of their
background or circumstances. By harnessing the power of AI for social
good, FLP seeks to create a virtual safety net that promotes
self-reliance, improves quality of life, and ultimately saves lives.


<a id="org5604758"></a>

### 🏗️ System Architecture <a name="system-architecture"></a>

FLP is built upon a modular, extensible architecture that allows for
the integration of diverse AI components and the continuous evolution
of the system. The key architectural elements include:

-   **Knowledge Base**: A central repository of structured and
    unstructured data that serves as the foundation for FLP's reasoning
    and decision-making capabilities.

-   **Reasoning Engine**: A suite of AI algorithms and techniques,
    including rule-based systems, machine learning models, and natural
    language processing, that enable FLP to analyze, interpret, and draw
    insights from the knowledge base.

-   **Planning and Scheduling**: Advanced planning and scheduling
    algorithms that allow FLP to generate optimal strategies and action
    sequences for achieving user goals and managing complex tasks.

-   **User Interface**: A multi-modal, intuitive interface that
    facilitates seamless interaction between users and the FLP system,
    including natural language communication, visual displays, and
    mobile accessibility.

-   **Data Integration**: Robust mechanisms for integrating data from
    various sources, such as sensors, databases, and APIs, to ensure
    FLP's knowledge base remains up-to-date and comprehensive.


<a id="org0bc7665"></a>

### 🧩 Key Components <a name="key-components"></a>

FLP comprises several key components that work together to deliver its
powerful capabilities:

1.  **Prolog-Agent**: An intelligent situated agent that can navigate
    computing environments, understand natural language, synthesize
    programs, and learn through experimentation and study.

2.  **Gourmet**: A sophisticated meal planning system that optimizes
    nutrition, taste, cost, and effort using advanced AI techniques.

3.  **Verber**: A powerful contingency planning and crisis management
    system that models potential consequences of actions and generates
    robust, fault-tolerant plans.

4.  **Sayer and Thinker**: Cognitive systems that analyze and interpret
    the meaning of arbitrary data structures and text, integrating
    machine learning, natural language processing, and knowledge
    representation.

5.  **Temporal Reasoning**: Advanced techniques for reasoning about time,
    events, and causality, enabling FLP to make informed decisions in
    dynamic, evolving contexts.


<a id="orga31c113"></a>

### 🔍 Subsystem Overview <a name="subsystem-overview"></a>

FLP encompasses a wide array of subsystems, each focusing on a
specific aspect of life management. Some of the key subsystems
include:

-   **Finance**: Comprehensive tools for financial planning, budgeting,
    and decision support.

-   **Health**: Modules for tracking medications, managing appointments,
    and providing personalized health insights.

-   **Nutrition**: Advanced meal planning and pantry management
    capabilities, powered by Gourmet.

-   **Transportation**: Intelligent tools for optimizing travel,
    scheduling, and route planning.

-   **Home Automation**: Integration with smart home devices and sensors
    for enhanced convenience and efficiency.

-   **Productivity**: Features for task management, goal setting, and
    habit tracking, all designed to boost personal and professional
    productivity.

For a complete list of subsystems and their current development
status, please refer to the [Subsystem
Directory](<https://github.com/aindilis/free-life-planner#flp-subsystems>).


<a id="org87f833c"></a>

### 🛣️ Development Roadmap <a name="development-roadmap"></a>

FLP is an ongoing, evolving project with an ambitious development
roadmap. Some of the key milestones and priorities include:

1.  **Enhanced Natural Language Interaction**: Improving FLP's ability to
    understand and communicate using natural language, making the
    system more accessible and user-friendly.

2.  **Expanded Knowledge Base**: Continuously growing and refining FLP's
    knowledge base to cover a broader range of domains and provide more
    comprehensive support.

3.  **Advanced Learning Capabilities**: Implementing advanced machine
    learning techniques to enable FLP to learn from user interactions
    and adapt to individual needs and preferences.

4.  **Collaborative Planning**: Developing features that allow multiple
    users to collaborate on shared goals and plans, fostering teamwork
    and collective problem-solving.

5.  **Mobile Optimization**: Enhancing FLP's mobile accessibility and
    performance to ensure seamless usage across devices.

For a more detailed breakdown of planned features and enhancements,
please consult the [Development
Roadmap](<https://github.com/aindilis/free-life-planner#development-roadmap>).


<a id="org3ea88a7"></a>

### 🤝 Contributing <a name="contributing"></a>

FLP thrives on collaboration and community involvement. We welcome
contributions from developers, researchers, domain experts, and anyone
passionate about harnessing AI for social good. Some ways to get
involved include:

-   **Code Contributions**: Help us improve FLP's codebase by submitting
    pull requests, fixing bugs, or implementing new features.

-   **Testing and Feedback**: Participate in testing FLP's components and
    provide valuable feedback to help us refine the system.

-   **Documentation**: Assist in creating and maintaining comprehensive
    documentation to make FLP more accessible and understandable.

-   **Research**: Contribute to advancing the underlying AI techniques and
    approaches that power FLP.

-   **Outreach**: Help spread the word about FLP and advocate for its
    adoption in communities that could benefit from its capabilities.

For detailed guidelines on how to contribute, please refer to our
[Contributing
Guide](<https://github.com/aindilis/free-life-planner#contributing>).


<a id="org0dc6d25"></a>

### 📜 License <a name="license"></a>

FLP is released under the [GNU General Public License
v3.0](<https://www.gnu.org/licenses/gpl-3.0.en.html>), ensuring that it
remains free and open-source software. By contributing to FLP, you
agree to release your contributions under the same license.

---

We hope this Reference Manual serves as a valuable resource for
understanding and engaging with the Free Life Planner
project. Together, we can leverage the power of AI to create a more
equitable, supportive, and opportunity-filled world for all.

If you have any questions, ideas, or feedback, please don't hesitate
to reach out to our team. Thank you for your interest in FLP, and we
look forward to collaborating with you!

---


<a id="org96a306e"></a>

# Summarized Reference

🌟 Free Life Planner (FLP) Reference Manual 🌟


<a id="orgc5c9c04"></a>

## Table of Contents

1.  [Introduction](#introduction)
2.  [Features](#features)
    -   [Voice Assistant](#voice-assistant)
    -   [Workflow Manager](#workflow-manager)
    -   [Health](#health)
    -   [Time Management](#time-management)
    -   [Organization](#organization)
    -   [Self-Discipline](#self-discipline)
    -   [Transportation, Shopping, and Errands](#transportation-shopping-errands)
    -   [Document Management](#document-management)
    -   [Financial Planner](#financial-planner)
    -   [Emergency Preparedness](#emergency-preparedness)
    -   [Employment](#employment)
    -   [Executive Function](#executive-function)
3.  [Future Work](#future-work)
4.  [Special Use Cases](#special-use-cases)
5.  [Major Technologies Used](#major-technologies)
6.  [Additional Resources](#additional-resources)
    -   [Use Cases](#use-cases)
    -   [Recognition](#recognition)
    -   [Links](#links)


<a id="orgb927e25"></a>

## 1. Introduction <a name="introduction"></a>

The Free Life Planner (FLP) is a comprehensive, AI-driven life management system designed to help individuals navigate the complexities of daily life. By integrating a wide array of tools and technologies, FLP aims to provide personalized support and guidance across various domains, promoting self-reliance and improving overall quality of life.


<a id="orgf933fef"></a>

### Purpose

-   Assist with the logistics of daily living, such as securing food, medicine, finances, transportation, and health
-   Offer short, medium, and long-term life planning capabilities
-   Serve as a cognitive prosthesis for executive function, particularly for individuals with ADHD, autism, schizophrenia, dementia, and other conditions
-   Function as a "life manual" or "skills for living life" resource


<a id="orgd03add7"></a>

### User Base

While FLP is intended for general use, it is particularly beneficial for individuals facing challenges or disadvantages, such as:

-   People with disabilities or pervasive developmental disorders
-   Those living in poverty or experiencing financial hardship
-   Individuals with chronic illnesses or medical conditions
-   People experiencing homelessness
-   Victims of relationship violence, persecution, hate, war, political oppression, or natural/man-made disasters
-   Immigrants and refugees


<a id="orgea52104"></a>

### Sample Use Cases

For a more detailed look at how FLP can be applied in real-life scenarios, please refer to the following:

-   [Homeless Story](<https://frdcsa.org/~andrewdo/writings/homeless-story.html>)
-   [Health Story](<https://frdcsa.org/~andrewdo/writings/health-story.html>)
-   [More Use Cases](#use-cases)


<a id="orge72edf5"></a>

### Status

The FLP team is currently working on releasing the latest version of the system on GitHub, with a focus on ensuring interoperability between all subsystems.


<a id="org637634b"></a>

## 2. Features <a name="features"></a>


<a id="org62c21ab"></a>

### Voice Assistant <a name="voice-assistant"></a>

FLP includes an interactive voice assistant, powered by both Alexa and Rhasspy, which offers:

-   Networked/online access (Alexa) and air-gapped/offline access (Rhasspy)
-   Automatic speech recognition and speech-to-text capabilities
-   Text-to-speech functionality using coqui-ai/TTS and Bark
-   Support for single-step and multi-step dialogues
-   Integration with large language models for question answering


<a id="orga48f661"></a>

### Workflow Manager <a name="workflow-manager"></a>

The Workflow Manager is an overarching tool that guides users through necessary tasks, featuring:

-   PDDL-based planning for creating linear paths through FLP to achieve objectives
-   Integration with AgentSpeak for metaplanning and contingency planning
-   Support for dynamic addition and removal of goals with replanning capabilities


<a id="org22159f3"></a>

### Health <a name="health"></a>

FLP's health-related features cover a wide range of areas, including:

-   Evidence-based wellness: Medical Q&A, data collection, user modeling, prevention, early detection, diagnostics, and treatments
-   Exercise: Fitness manager, interactive plan monitoring, and progress tracking
-   Nutrition: Comprehensive meal planning system (Gourmet), inventory management, specialty diet support, and recipe management
-   Doctor's visits and orders: Appointment scheduling, medical diagnostics, adherence tracking, and question answering
-   Medications: Reminders, planning, tracking, monitoring, and refill management
-   Mental health: Psychotherapy aid, emotional security, psychometric reporting, symptom tracking, and condition-specific support


<a id="org83f6f4e"></a>

### Time Management <a name="time-management"></a>

FLP offers a suite of tools for effective time management, such as:

-   Recurrences: Support for scheduling tasks and events on specific dates, days of the week, and at regular intervals
-   Calendaring: Appointment scheduling, chore scheduling, and integration with various calendar formats (e.g., Org-agenda, Google Calendar, ICS)
-   Planning, scheduling, and execution: Workflow management, metaplanning, temporal planning, contingent planning, oversubscription planning, behavior tree reactive planning, and BDI reactive planning


<a id="org6db5320"></a>

### Organization <a name="organization"></a>

FLP assists users with various organizational tasks, including:

-   Inventory management: Supplier tracking, pantry management, expiration date tracking, and shopping list generation
-   Adulting: Support for activities of daily living (ADLs) and instrumental activities of daily living (IADLs)
-   Communication management: Proxying communications, dossier system, relationship management, persuasion, and team building
-   Chore charting: Comprehensive chore lists, scheduling, reminders, tracking, and gamification
-   Maintenance: Household and automotive maintenance scheduling and tracking
-   Smart home: Integrated shelter management, sensor networks, security and surveillance, smart lighting control, event logging and inference, and reactive systems
-   Research and development: Academician system, study system, intelligent tutoring, and automatic argument mining and construction


<a id="orgdb80d94"></a>

### Self-Discipline <a name="self-discipline"></a>

FLP includes various tools to help users develop and maintain self-discipline, such as:

-   To-do lists: Org and Org-agenda, the "Do" system, and integration with other task management tools
-   Checklists: Daily activity checklists and interfaces for marking off completed items
-   Note-taking: Org-mode and Zettelkasten (Cyc-ZK) support
-   Scheduling: PDDL-based scheduling, automatic task scheduling using temporal planning algorithms, and deadline management
-   Self-discipline state machine: Ensuring user readiness for tasks and assisting with habit formation
-   Gamification: Rewards, penalties, adherence tracking, and productivity incentives
-   Movement discipline: Optional mode requiring premeditation before changing locations


<a id="orgc6ceeb0"></a>

### Transportation, Shopping, and Errands <a name="transportation-shopping-errands"></a>

FLP offers support for transportation, shopping, and errands, including:

-   Transportation: Developing transportation plans, API mashups for hours of operation, weather, and route planning, reverse geocoding, and location-based reminders
-   Shopping and errands: Shopping list management, financial integration, inventory and pantry management, ethical consumerism, online and brick-and-mortar shopping support, and personal selling system


<a id="orgac082ab"></a>

### Document Management <a name="document-management"></a>

FLP's document management capabilities include:

-   Scanning and OCR for paperwork, with cross-referencing to schedules and confidentiality maintenance
-   Integration of document-related tasks into the Workflow Manager
-   Date and time reference extraction (using TIMEX3)
-   Git-based backup and version control
-   Digital library system for equipment manuals and other documents


<a id="orge603867"></a>

### Financial Planner <a name="financial-planner"></a>

FLP's financial planner offers a wide range of features, such as:

-   Long-term financial forecasting based on recurring transactions and automated detection from OFX exports
-   Integration of expected financial transactions with the primary agenda on a calendar
-   Temporal metric planning for finances
-   Purchase decision support system and broker buy/sell system
-   Contingency planning for various financial problems (e.g., unexpected delays, overcharges, cash flow issues)
-   Abduction of recurrences and predicted events from bank statements
-   Interactive execution monitoring (IEM2) for guiding users through financial plans
-   Integration with SPSE2 and PSEx3 for comprehensive task and finance management
-   Financial alerts and real-time bank information display
-   Personal accounting, budgeting, and bill payment subsystem


<a id="org97ccb86"></a>

### Emergency Preparedness <a name="emergency-preparedness"></a>

FLP assists users with emergency preparedness by:

-   Helping users stay on top of emergency planning and analyzing situation-specific risks
-   Providing guidance on preparing emergency kits, "bug-out bags," and food and water supplies
-   Offering safety plans and drills for various emergencies (e.g., fire, pandemic, food and water shortages)
-   Utilizing recurrences for reminders to maintain equipment, supplies, plans, and drills


<a id="org8760d5a"></a>

### Employment <a name="employment"></a>

FLP's employment-related features include:

-   Time tracking for work-related tasks
-   Job search assistance, including semi-automatic job applications, resume generation, and tailored resumes for specific job postings
-   Negotiation training and support


<a id="org2d7e3e6"></a>

### Executive Function <a name="executive-function"></a>

FLP serves as a cognitive prosthesis for executive function, offering:

-   Intelligence augmentation through learning (educational and empirical)
-   Problem-solving support and goal-setting assistance
-   Integration with the Prolog-Agent intelligent situated agent/softbot for enhanced reasoning and task completion


<a id="org7a8517d"></a>

## 3. Future Work <a name="future-work"></a>

The FLP team is continuously working on improving and expanding the system's capabilities. Some planned future work includes:

-   FLP-2.0 automatic refactoring/rewrite using MetaGPT-like program synthesis
-   Integration with Eurisko and AM-UTEXAS for IAEC (Intelligent Autonomous Exploratory Creativity)
-   Incorporation of TraCE-lite and Symbolic-OSP for enhanced planning capabilities
-   Integration with s(CASP) for Event Calculus and commonsense reasoning
-   FreeKBS2/Prolog context/microtheory support for more efficient knowledge representation
-   Improved privacy features, including HIPAA compliance, encryption (data-at-rest, in-memory, and full-disk), and enhanced security methodologies (principle of least privilege, additional security partitioning)


<a id="orgfa258cb"></a>

## 4. Special Use Cases <a name="special-use-cases"></a>

FLP is designed to be particularly helpful for individuals facing specific challenges, such as:

-   Homelessness: [Homeless Story](<https://frdcsa.org/~andrewdo/writings/homeless-story.html>), [Helping the Homeless](<https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanner.html>), [Pioneer Contest Week 4 Update](<https://frdcsa.org/~andrewdo/writings/flp-update-4.html>), [Pioneer Application](<https://frdcsa.org/~andrewdo/writings/pioneer.app/Application.html>)
-   Illness: [Health Story](<https://frdcsa.org/~andrewdo/writings/health-story.html>), [Akahige](<https://frdcsa.org/frdcsa/internal/akahige>) (10% complete)
-   Insolvency: [Financial Planner](#financial-planner) (25% complete)
-   Abuse: [Domestic Abuse Simulations](<https://github.com/RescueSocialTech/Domestic_Abuse_Simulations>) (25% complete)
-   Climate Change and Disaster Management: [Personal Emergency Management](<https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4>) (10% complete)


<a id="org7099caf"></a>

## 5. Major Technologies Used <a name="major-technologies"></a>

FLP integrates a wide range of technologies, including but not limited to:

-   SWI-Prolog: Julian time library, CLP(fd) (Constraint Logic Programming), QLF (Quick Load Format) (50% complete)
-   Perl: YASWI (Yet Another interface to SWI-Prolog), Catalyst MVC (Model/View/Controller), ShinyCMS (Content Management System), Mojolicious
-   Java: JavaPengine (Java<->SWI-Prolog), Jason/AgentSpeak(L), JPL (Java Prolog Library?), Alexa voice skill interface, Cyc Java API<->Inline Perl
-   Python: Py4J (Python For Java), python-agentspeak
-   Bash scripting
-   Emacs integration
-   PDDL 2.2 temporal metric planning: LPG-td-1.0, OPTICCLP (Optimizing Preferences and Time-Dependent Costs)
-   Vampire-KIF (Knowledge Interchange Format) ATP (Automated Theorem Proving) system
-   SUMO (Suggested Upper Merged Ontology)
-   OpenCyc
-   MariaDB/MySQL persistence: Through UniLang/FreeKBS2 (Universal Language) (Free Knowledge Based System v2), directly from SWI-Prolog using ODBC (Open DataBase Connectivity) (50% complete)
-   Inform7 (33% complete)
-   Large Language Models (LLMs): Mistral Instruct 7B, WizardLM, Code Llama 34B (Llama.cpp), LLEMMA 7B
-   Rhasspy Voice Assistant integration: whisper-rhasspy-http plugin, Whisper ASR/STT plugin (Automatic Speech Recognition, Speech To Text), coqui-ai/TTS (Text To Speech), Bark TTS (Text To Speech)


<a id="org0c7bedd"></a>

## 6. Additional Resources <a name="additional-resources"></a>


<a id="org5b6eb44"></a>

### Use Cases <a name="use-cases"></a>

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of groceries needed
-   Remembering to send a copy of completed paperwork to one's doctor
-   Recalling and adhering to doctor's instructions, aided by machine comprehension software in a paperless office setting
-   Reminders for working on taxes and changing air filters
-   Identifying plans that violate moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and potential income disruptions


<a id="org2c7a4ae"></a>

### Recognition <a name="recognition"></a>

-   [Pioneer Results](![img](https://frdcsa.org/~andrewdo/projects/1stPlace.jpg))
-   [Pioneer Email](<https://frdcsa.org/~andrewdo/projects/pioneer-email.txt>)
-   [Testimonials](<https://altruisticsoftware.org/frdcsa/#testimonials>)


<a id="org8f9a501"></a>

### Links <a name="links"></a>

-   [FLP Paper](<https://frdcsa.org/~andrewdo/flp-jwas-article-draft-1.pdf>)
-   [FLP Code Repository](<https://github.com/aindilis/free-life-planner>)
-   [FRDCSA Panoply Git VM](<https://github.com/aindilis/frdcsa-panoply-git-20200329>)
-   [Homeless Story](<https://frdcsa.org/~andrewdo/writings/homeless-story.html>)
-   [Recent FLP Talk](<https://ontologforum.org/index.php/ConferenceCall_2022_04_20>) ([Video](<https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4>))
-   [FRDCSA Release](<https://github.com/aindilis/frdcsa-installer>)
-   [EmacsConf2019 Talk on FRDCSA/FLP/Panoply](<https://frdcsa.org/~andrewdo/frdcsa-emacsconf2019-final.webm>)
-   [Interactive Plan Monitoring](<https://github.com/aindilis/plan-monitor>)
-   [Interactive Execution Monitor (IEM) Demo 1](<https://frdcsa.org/~andrewdo/iem2-2.mp4>), [IEM Demo 2](<https://frdcsa.org/~andrewdo/iem2-3.mp4>)
-   [Early FLP Demo](<https://www.youtube.com/watch?v=t_dCAlf26LE>)
-   [FRDCSA Paper](<https://frdcsa.org/~andrewdo/pioneer/wk1/frdcsa.pdf>)
-   [FLP Paper (outdated)](<https://frdcsa.org/~andrewdo/pioneer/wk1/flp.pdf>)
-   [SPSE2 Paper](<https://frdcsa.org/visual-aid/pdf/Temporal-Planning-and-Inferencing-for-Personal-Task-Management-with-SPSE2.pdf>)
-   [Financial Planning Submodule](<https://github.com/aindilis/financial-planning#projected-transactions-for-florence-tucker>)
-   [Meal Planning Submodule](<https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html>)

---


<a id="orgd3a802d"></a>

# Full Reference


<a id="org253baa1"></a>

# Technical Overview


<a id="org8a72df0"></a>

## THIS REFERENCE MANUAL IS UNDER CONSTRUCTION


<a id="org4672c71"></a>

# Links

-   Please note that for now there are (rather confusingly) three
    important documents to see:
    -   The [original deprecated Free Life Planner repo](https://github.com/aindilis/free-life-planner#readme) (including screenshots and links)
    
    -   This document: the new [ReferenceManual.md](https://github.com/aindilis/flp/blob/main/ReferenceManual.md) (the most detailed overview of FLP (Free Life Planner))
    
    -   The paper ["The Free Life Planner: A Virtual Secondary Social Safety Net"](https://frdcsa.org/~andrewdo/flp-jwas-article-draft-1.pdf)


<a id="org199b08e"></a>

# You are at the ReferenceManual.md


<a id="org4951e36"></a>

# Reference Manual Contents


<a id="org543ea63"></a>

# Introduction


<a id="org288aa77"></a>

## Purpose

-   A free/libre program for helping people with the logistics of
    daily life, helping to plan and secure things like food,
    medicine, finances, transportation, health and so on.
-   A short, medium and long-term life planner
-   Cognitive prosthesis for executive function
    -   Including for people w/ ADHD, autism, schizophrenia, dementia, etc
-   A "life manual" / "skills for living life"


<a id="org9ac14df"></a>

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


<a id="org97976ab"></a>

## Sample Use Cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#orgf0c81b7)


<a id="org47ce553"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org5e8f861"></a>

# Features


<a id="orgdc5a670"></a>

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


<a id="orga82012a"></a>

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


<a id="org86ad1a4"></a>

## Health


<a id="org1a2eb13"></a>

### Evidence-Based Wellness

1.  General

    -   [ ] Medical Q&A using [DoctorGPT](https://github.com/llSourcell/DoctorGPT) or a successor LLM

2.  Data Collection and User Modeling

    -   [ ] <code>[50%]</code> Record / create an inventory of all user's medical symptoms
        -   [ ] List conditions, [medications](#orga5c1ec3) and their effects
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


<a id="org16a7dd2"></a>

### Exercise

-   ✅ Fitness Manager
    -   [ ] <code>[33%]</code> Interactive plan monitoring of exercises
        -   ✅ [exercise.bt](file:///var/lib/myfrdcsa/private/systems/behavior-trees/data-git/bts/p/exercise.bt)
    -   [ ] <code>[66%]</code> Track daily progress
        -   ✅ Using Rhasspy Voice Assistant
            -   ✅ "Porcupine, Andrew finished daily exercises"
        -   ✅ Using legacy Alexa interface
            -   ✅ "Alexa, tell David - Andrew did his morning exercises"


<a id="org83d949b"></a>

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
    -   [ ] [Inventory Management](#org917f172)
        -   [ ] User modeling
            -   [ ] <code>[40%]</code> [Self-discipline](#org8d7c976) coach software
                -   [ ] For hitting macros
                -   [ ] Understanding psychology of users' relationships to food
            -   ✅ Helping w/ Portion control
                -   ✅ Door sensor alerts on fridge and freezer
                -   [ ] <code>[20%]</code> Follow up dialog regarding intent when fridge and freezer accessed
                -   [ ] [Gamification](#orga101896)
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


<a id="orga829150"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   ✅ Appointment calendar
    -   [ ] Track appointments and avoid double-booking and overbooking
    -   ✅ Verbal and User-Agenda reminders
    -   ✅ Q&A system for asking things like when is my next appointment
-   [ ] [Medical diagnostics](https://github.com/timhannifan/symptom-tree/issues/1)
-   [ ] <code>[40%]</code> Following doctors' orders
    -   ✅ Scan into [Document Management System](#org88b86a1) for managing (among other things) medical records
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
        -   [ ] [Diagnostics and Treatments](#orgb4d5219)
    -   [ ] First aid course of action system


<a id="orga5c1ec3"></a>

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


<a id="orge41ef4e"></a>

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


<a id="org18ef72f"></a>

## Time Management


<a id="org6c239cd"></a>

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


<a id="orgfcf9ff8"></a>

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


<a id="orgbca49a1"></a>

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


<a id="org604f8be"></a>

## Organization


<a id="org917f172"></a>

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


<a id="orgba766bf"></a>

### Adulting

-   [ ] ADLs
    -   [ ] Daily Self Care
-   [ ] IADLs
    -   [ ] Chore charting
        -   [ ] <code>[35%]</code> Track who/what/where/when regarding chores
        -   ✅ Implement rewards via [Gamification](#orga101896)


<a id="org6496fc2"></a>

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


<a id="orgc6efbf8"></a>

### Chore Charting

-   [ ] <code>[60%]</code> Chore ontology
    -   ✅ Comprehensive chore lists
    -   [ ] <code>[50%]</code> Household chores
    -   [ ] <code>[80%]</code> Caregiving chores
-   [ ] <code>[66%]</code> Chore logic
    -   [ ] <code>[66%]</code> Scheduling, reminders, tracking and gamification
    -   [ ] <code>[66%]</code> Interactive plan execution using library of chore BTs (behavior trees)


<a id="orgb6e5fbd"></a>

### Maintenance

-   [ ] <code>[33%]</code> Household maintenance
    -   [ ] <code>[50%]</code> Complete list of scheduled home maintenance tasks
        -   [ ] <code>[10%]</code> Test fire alarms
        -   ✅ Furnace maintenance
        -   [ ] etc
-   ✅ Automotive maintenance schedule


<a id="orgfdf5b18"></a>

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
    -   [ ] [Home maintenance](#orgb6e5fbd)
    -   [ ] [Emergency preparedness](#orgcc1767e)
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


<a id="org17b2fd3"></a>

### Research and Development

-   ✅ [Academician system](https://github.com/aindilis/academician)
-   ✅ [Study system](https://github.com/aindilis/study)
-   [ ] ITS system (Intelligent Tutoring System)
-   ✅ Seeker system
    -   KSAs (Knowledge Seeking Agents)
-   Automatic Arugument Mining and Construction


<a id="org8d7c976"></a>

## Self-Discipline


<a id="org54c233e"></a>

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


<a id="orgbbb19d7"></a>

### Checklists

-   [Disciple](https://github.com/aindilis/disciple)
    -   <code>[70%]</code> Checklists for daily activities
    -   <code>[70%]</code> Interfaces for marking off items from checklist
        -   <code>[80%]</code> Alexa/Rhasspy voice interface
        -   <code>[80%]</code> FCMS WebUI log


<a id="org04831ca"></a>

### Note-Taking

-   ✅ Org-mode
-   [ ] <code>[10%]</code> Cyc-ZK (Zettelkasten)


<a id="org332ed42"></a>

### Scheduling

-   ✅ PDDL-2.2 (Planning Domain Definition Language)
-   [ ] <code>[20%]</code> PDDL+ (Planning Domain Definition Language Plus)
-   [ ] <code>[05%]</code> [Optaplanner](https://www.optaplanner.org/)
-   [ ] <code>[50%]</code> Automatically schedule tasks using (temporal) planning algorithms
    -   [ ] <code>[10%]</code> A taxonomy of task properties
-   ✅ Schedule important tasks
-   ✅ Set deadlines


<a id="org454cde8"></a>

### Self-Discipline State Machine

-   [ ] Make sure the user is up to any task
-   [ ] Assist with follow-through on things like dieting, exercise, etc
-   [ ] <code>[33%]</code> Use the digital twin and plan to choose from possible things to do


<a id="orga101896"></a>

### Gamification

-   ✅ [Score](https://github.com/aindilis/score)
-   [ ] <code>[75%]</code> Rewards/Penalties
-   ✅ [Manager](https://github.com/aindilis/manager)
-   ✅ Rewards for completing recurrent tasks
-   ✅ Daily penalty for leaving any recurrent tasks incomplete
-   ✅ Penalties for lack of [movement discipline](#org0874241)
-   [ ] <code>[50%]</code> Rewards for staying productive
-   [ ] <code>[60%]</code> Adherence tracker
    -   ✅ Color coded labelled rectangles indicating the last accessed time of various FLP systems
        -   ✅ Determine which systems are not being used correctly
        -   ✅ Determine which sensors have stopped working (e.g. dead battery)


<a id="org0874241"></a>

### Movement Discipline

-   [ ] Ensure we think before we move
    -   [ ] <code>[33%]</code> Optional mode where one must premeditate before moving to a different location


<a id="org15f9f2c"></a>

## Transportation/Shopping/Errands


<a id="org05b0cd7"></a>

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

-   ✅ [Movement discipline](#org0874241)


<a id="org22b4f0e"></a>

### Shopping/Errands

-   ✅ Shopping list management
    -   ✅ Integration with [financial management](#org49c546b)
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


<a id="org88b86a1"></a>

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
    -   ✅ [Information search management](#org17b2fd3)


<a id="org49c546b"></a>

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
    -   [ ] Inventory/pantry [Inventory Management](#org917f172) integration
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


<a id="orgcc1767e"></a>

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


<a id="org95119fb"></a>

## Employment

-   ✅ [Time tracking](https://altruisticsoftware.org/frdcsa/minor/consultant-support/)
-   [ ] Acquiring income
-   [ ] Job search
    -   ✅ [Semi-automatic job applications](https://www.youtube.com/watch?v=qFRSwRVFuhE&feature=youtu.be)
    -   [ ] [<code>[90%]</code> Resume generation](https://github.com/aindilis/job-search)
        -   [ ] <code>[30%]</code> Dynamic resumes tailored to specific job posts
    -   ✅ [Negotiation trainer](https://frdcsa.org/~andrewdo/WebWiki/AudienceDialog.html)


<a id="org79d792e"></a>

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


<a id="org38750f1"></a>

# Future Work


<a id="org89a61e3"></a>

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


<a id="orgcb8bc8f"></a>

# Special Use Cases


<a id="orgda5f06d"></a>

## Homelessness

-   [ ] [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [ ] [Helping the Homeless](https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanner.html)
-   [ ] [Pioneer Contest Week 4 Update](https://frdcsa.org/~andrewdo/writings/flp-update-4.html)
-   [ ] [Pioneer Application](https://frdcsa.org/~andrewdo/writings/pioneer.app/Application.html)


<a id="org605c34f"></a>

## Illness

-   [ ] [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [ ] <code>[10%]</code> [Akahige](https://frdcsa.org/frdcsa/internal/akahige)


<a id="org5b8f9ff"></a>

## Insolvency

-   [ ] <code>[25%]</code> [Financial Planner](#org49c546b)


<a id="org427f65d"></a>

## Abuse

-   [ ] <code>[25%]</code> <https://github.com/RescueSocialTech/Domestic_Abuse_Simulations>


<a id="orgf71f52b"></a>

## Climate Change and Disaster Management

-   [ ] <code>[10%]</code> [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="org5c40d45"></a>

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


<a id="org3ecb8f5"></a>

# More Info


<a id="orgf0c81b7"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to one's doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on one's taxes, and to change one's air filter
-   Telling you that a particular plan of one's violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="orgaf1ed8c"></a>

## Recognition

-   [Pioneer Results](https://frdcsa.org/~andrewdo/projects/1stPlace.jpg)
-   [Pioneer Email](https://frdcsa.org/~andrewdo/projects/pioneer-email.txt)
-   [Testimonials](https://altruisticsoftware.org/frdcsa/#testimonials)


<a id="org87007e1"></a>

## Links


<a id="orge8937df"></a>

### Screenshots

-   <https://github.com/aindilis/free-life-planner#a-few-screenshots>


<a id="orge7c9170"></a>

### Subsystems

-   <https://github.com/aindilis/free-life-planner#flp-subsystems>


<a id="orgbede063"></a>

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


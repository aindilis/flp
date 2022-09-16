- [The Free Life Planner](#org4ea3741)
  - [THIS README IS UNDER CONSTRUCTION](#org1f6e5c8)
- [[Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#orgc4793de)
  - [[In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#org4b374b1)
- [Introduction](#org9622f25)
  - [Purpose](#org8ef6289)
  - [User Base](#org9fbca19)
  - [Sample use cases](#org1e5e288)
  - [Status](#org2cb4a4e)
- [General Overview](#orgc54402c)
  - [Workflow Manager](#org97d4933)
  - [Employment](#orgbf2120a)
  - [Health](#orgfd269e8)
    - [Evidence-Based Wellness](#org68ce7d7)
    - [Exercise](#org5ec6dfb)
    - [Nutrition](#org1c12799)
    - [Doctor's Visits and Orders](#org12c2946)
    - [Medications](#org1202a81)
    - [Mental Health](#orgea218e5)
  - [Time Management](#orgc919dcd)
    - [Recurrences](#orgab83bfe)
    - [Calendaring](#orgdf38f60)
    - [Planning, Scheduling, and Execution](#org2e8627e)
  - [Organization](#org96fca7b)
    - [Financial Planner](#org0cb4e8c)
    - [Inventory Management](#org732b9e1)
    - [Document Management](#orgeaf6b8b)
    - [Adulting](#orgb5b0c2e)
    - [Transportation](#org9099110)
    - [Shopping/Errands](#org948b87f)
    - [Maintenance](#orge1b52da)
    - [Research and Development](#orgd373274)
  - [Self-Discipline](#org6722ed7)
    - [To-Do](#orga7c9d0a)
    - [Note-Taking](#orgf1830f8)
    - [Scheduling](#org0c617a1)
    - [Executive Function](#org6c22cda)
    - [Self-Discipline State Machine](#org111fdc2)
    - [Gamification](#orgcb94d14)
    - [Movement Discipline](#org65cf9e1)
  - [Interpersonal](#org923e7f8)
  - [Emergency Preparedness](#orgdcf3c95)
- [More Info](#org457e8c4)
  - [More Use Cases](#orgd84cc67)
  - [Links](#org1065b97)
  - [[Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#org4bd432a)
    - [[In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#orge83b0fa)


<a id="org4ea3741"></a>

# The Free Life Planner


<a id="org1f6e5c8"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orgc4793de"></a>

# [Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="org4b374b1"></a>

## [In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="org9622f25"></a>

# Introduction


<a id="org8ef6289"></a>

## Purpose

-   A free/libre program for helping people with the logistics of daily life, helping to plan and secure things like food, medicine, finances, transportation, health and so on.
-   A short, medium and long-term life planner
-   Cognitive prosthesis for executive function
    -   Including for people w/ ADHD, autism, schizophrenia, dementia, etc
-   A "life manual" / "skills for living life"


<a id="org9fbca19"></a>

## User Base

-   People
    -   with disabilities such as pervasive developmental disorders
    -   in poverty who are one misstep from disaster
    -   with unwieldy illnesses
    -   who are homeless
    -   who experience relationship violence
    -   returning citizens
    -   everyone else


<a id="org1e5e288"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#orgd84cc67)


<a id="org2cb4a4e"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgc54402c"></a>

# General Overview


<a id="org97d4933"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks


<a id="orgbf2120a"></a>

## Employment

-   [X] [Time tracking](https://altruisticsoftware.org/frdcsa/minor/consultant-support/)
-   [ ] Acquiring income
-   [ ] Job search
    -   [X] [Semi-automatic job applications](https://www.youtube.com/watch?v=qFRSwRVFuhE&feature=youtu.be)
    -   [ ] [<code>[90%]</code> Resume generation](https://github.com/aindilis/job-search)
        -   [ ] <code>[30%]</code> Dynamic resumes tailored to specific job posts
    -   [X] [Negotiation trainer](https://frdcsa.org/~andrewdo/WebWiki/AudienceDialog.html)


<a id="orgfd269e8"></a>

## Health


<a id="org68ce7d7"></a>

### Evidence-Based Wellness

-   [ ] Opt-in data collection
-   [ ] Prevention / early detection


<a id="org5ec6dfb"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org1c12799"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
        -   [ ] <code>[25%]</code> Macros planning and counting
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org6722ed7) for hitting macros
    -   [ ] <code>[20%]</code> Specialty diets (medical or ethical)
    -   [ ] [<code>[10%]</code> Recipe manager](https://frdcsa.org/%7eandrewdo/gourmet-frontend.webm)
    -   [ ] <code>[10%]</code> [Recommender system](https://frdcsa.org/%7eandrewdo/WebWiki/RecipeRecommendationSystem.html)


<a id="org12c2946"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] <code>[10%]</code> Patient advocate
-   [ ] [Tracking visits](https://github.com/aindilis/akahige)
-   [ ] [Following through on instructions](#orgeaf6b8b)
-   [ ] For when a physician is unavailable
    -   [ ] Diagnostic expert system
    -   [ ] First aid course of action system


<a id="org1202a81"></a>

### Medications

-   [ ] <code>[33%]</code> Refill tracker
-   [ ] Medication management


<a id="orgea218e5"></a>

### Mental Health

-   [ ] Emotional security
    -   [ ] Managing triggers
    -   [ ] <code>[25%]</code> Reframing self-talk
-   [ ] Planning for optimal productivity by meeting needs
    -   [ ] Pre/pro-active planning
    -   [ ] Root cause analysis for low-productivity
    -   [ ] <code>[75%]</code> Responses to low-productivity
    -   [ ] Task tracking and MTTC (Mean Time To Completion)
-   [ ] Psychometric reporting
    -   [ ] Identifying factors


<a id="orgc919dcd"></a>

## Time Management


<a id="orgab83bfe"></a>

### Recurrences

-   [X] Dates
    -   [X] On a given date
    -   [X] On a given day of week
    -   [X] Through given days of week
    -   [X] Every n-th week/month/year
-   [ ] Times
    -   [X] Multiple specific time points
    -   [ ] Durations


<a id="orgdf38f60"></a>

### Calendaring

-   [X] Scheduling appointments
-   [X] Scheduling of chores
-   [ ] Detect double-booking


<a id="org2e8627e"></a>

### Planning, Scheduling, and Execution

1.  Planning

    -   [ ] <code>[25%]</code> Workflow Manager
    -   [ ] <code>[25%]</code> Metaplanning
    -   [X] Temporal planning
    -   [X] Contingent planning
    -   [X] Behavior tree reactive planning
    -   [X] [BDI reactive planning](http://jason.sourceforge.net/) (Belief-Desire-Intention)

2.  Plan Monitoring

    -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
    -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="org96fca7b"></a>

## Organization


<a id="org0cb4e8c"></a>

### Financial Planner

-   [ ] Budgeting
-   [X] Help manage cash flow in tight situations
    -   [X] Forecast finances
        -   [X] Automatically detect recurring transactions
        -   [X] Tell us when we're going to run out of money
        -   [X] Tell us how much we need to raise by when
-   [X] Adds financial reasoning to life-planning problems


<a id="org732b9e1"></a>

### Inventory Management

-   [ ] <code>[10%]</code> Supplier tracking
-   [ ] <code>[10%]</code> Semiautomatic reordering
    -   [ ] <code>[25%]</code> Integration with cashflow tracking
-   [ ] Pantry management
    -   [ ] <code>[80%]</code> Nutrition lookup


<a id="orgeaf6b8b"></a>

### Document Management

-   [X] Scan and OCR paperwork
    -   [X] Cross reference with schedule
-   [X] Ensure confidentiality of information
-   [X] Backup documents
-   [ ] Track doctors orders
    -   [ ] Help the user implement doctors orders


<a id="orgb5b0c2e"></a>

### Adulting

-   [ ] ADLs
    -   [ ] Daily Self Care
-   [ ] IADLs
    -   [ ] Chore charting
        -   [ ] <code>[35%]</code> Track who/what/where/when regarding chores
        -   [X] Implement rewards via gamification


<a id="org9099110"></a>

### Transportation

-   [ ] <code>[25%]</code> Develop proper transportation plans
    -   [ ] <code>[25%]</code> Incorporating hours of operation, weather and route information
-   [ ] <code>[75%]</code> Use "Location Logic" to provide reminders
    -   [ ] <code>[75%]</code> e.g. Don't forget to bring this with you when you leave
    -   [ ] <code>[75%]</code> e.g. Silence one's cell phone in certain types of locations


<a id="org948b87f"></a>

### Shopping/Errands

-   [ ] Manage one's shopping list
    -   [ ] <code>[15%]</code> Integrate with [financial tracking](#org0cb4e8c)
    -   [ ] <code>[25%]</code> Integrate with [pantry management](#org1c12799)
-   [ ] <code>[25%]</code> Track all types of receipts
-   [ ] Buy/sell things as necessary
-   [ ] <code>[75%]</code> Help boycott products by companies the user doesn't support


<a id="orge1b52da"></a>

### Maintenance

-   [X] Home
-   [X] Automotive
-   [ ] Equipment
-   [ ] Computer systems


<a id="orgd373274"></a>

### Research and Development


<a id="org6722ed7"></a>

## Self-Discipline


<a id="orga7c9d0a"></a>

### To-Do

-   [ ] <code>[80%]</code> [Track hundreds of thousands of (unscheduled) tasks](https://github.com/aindilis/do/tree/master/scripts/convert)
    -   [ ] <code>[60%]</code> Including their interdependencies
    -   [X] In a logical language


<a id="orgf1830f8"></a>

### Note-Taking


<a id="org0c617a1"></a>

### Scheduling

-   [ ] <code>[50%]</code> Automatically schedule tasks using (temporal) planning algorithms
    -   [ ] <code>[10%]</code> A taxonomy of task properties
-   [X] Schedule important tasks
-   [X] Set deadlines


<a id="org6c22cda"></a>

### Executive Function

-   [ ] Intelligence Augmentation
    -   [ ] Learning
        -   [ ] Education
        -   [ ] Empirical
    -   [ ] Cognitive Prosthesis
    -   [ ] Nootropics
-   [ ] Problem-Solving
    -   [ ] Goal setting


<a id="org111fdc2"></a>

### Self-Discipline State Machine

-   [ ] Make sure the user is up to any task
-   [ ] Assist with follow-through on things like dieting, exercise, etc


<a id="orgcb94d14"></a>

### Gamification

-   [ ] <code>[40%]</code> Apply short, medium and long term reward cycles for task accomplishment


<a id="org65cf9e1"></a>

### Movement Discipline

-   [ ] Ensure we think before we move


<a id="org923e7f8"></a>

## Interpersonal

-   [ ] Team building
    -   [ ] Networking
        -   [ ] Colleagues
-   [ ] Relationship management
    -   [ ] Friendships
    -   [ ] Family
    -   [ ] Groups
        -   [ ] Social advocacy/interest groups
    -   [X] Track birthdays, anniversaries, etc


<a id="orgdcf3c95"></a>

## Emergency Preparedness

-   [ ] <code>[10%]</code> Help the user stay on top of emergency preparedness
    -   [ ] Analyze which kinds of emergencies are particular to the users situation
    -   [ ] Prepare a "bug-out bag," emergency food and water supply, etc
    -   [ ] Help the user maintain a ready posture
    -   [ ] Safety plans and drills


<a id="org457e8c4"></a>

# More Info


<a id="orgd84cc67"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to one's doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on one's taxes, and to change one's air filter
-   Telling you that a particular plan of one's violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="org1065b97"></a>

## Links

-   Here is the reference manual, with implementation details for all of the above items:
    -   [https://github.com/aindilis/flp/blob/main/ReferenceManual.md](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)

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

-   Here is the beginning of a paper on FLP:
    -   <https://frdcsa.org/~andrewdo/pioneer/wk1/flp.pdf>

-   and one on FRDCSA:
    -   <https://frdcsa.org/~andrewdo/pioneer/wk1/frdcsa.pdf>

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


<a id="org4bd432a"></a>

## [Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="orge83b0fa"></a>

### [In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)

- [The Free Life Planner](#org749d03d)
  - [THIS README IS UNDER CONSTRUCTION](#org1e9ef81)
- [[Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#orgdbc1723)
- [Introduction](#orgdb1d4c1)
  - [Purpose](#orgc1504ff)
  - [User Base](#orgcbd737a)
  - [Sample use cases](#org18e9ac9)
  - [Status](#orgaa347e2)
- [General Overview](#org1db5c6f)
  - [Workflow Manager](#orgbe353c9)
  - [Health](#orgf7d2f93)
    - [Exercise](#orgc1fa910)
    - [Nutrition](#org4d040c4)
    - [Doctor's Visits and Orders](#org23c2a4d)
    - [Medications](#org54a474c)
    - [Mental Health](#org4cf657f)
  - [Time Management](#org5472e0c)
    - [Recurrences](#orga1f6c4b)
    - [Calendaring](#org4fb49ba)
    - [Planning, Scheduling, and Execution](#orgf46c711)
  - [Organization](#org4881d24)
    - [Inventory Management](#orge86c500)
    - [Communication Management](#org6433d6c)
    - [Chore Charting](#org658fa5d)
    - [Maintenance](#org98ff324)
    - [Research and Development](#org53d839a)
  - [Self-Discipline](#org7b46c37)
    - [To-Do](#org717c096)
    - [Note-Taking](#orgf197e01)
    - [Scheduling](#orga24681c)
    - [Self-Discipline State Machine](#org76156a0)
    - [Gamification](#orgd43d48b)
    - [Movement Discipline](#org9c610d7)
  - [Transportation/Shopping/Errands](#org2670ea4)
    - [Transportation](#org78400d1)
    - [Shopping/Errands](#org5c04c31)
  - [Document Management](#org4fd60c9)
  - [Financial Planner](#org29e083e)
  - [Emergency Preparedness](#org920c539)
- [More Info](#orgd713604)
  - [More Use Cases](#org685e10a)
  - [Links](#org8756e68)
  - [[Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#org12286c3)


<a id="org749d03d"></a>

# The Free Life Planner


<a id="org1e9ef81"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orgdbc1723"></a>

# [Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="orgdb1d4c1"></a>

# Introduction


<a id="orgc1504ff"></a>

## Purpose

-   A life planner that helps automate every aspect of your life
-   A "Life Manual"
-   Cognitive prosthetic for executive function
    -   Including for people w/ ADHD, autism, schizophrenia, dementia, etc


<a id="orgcbd737a"></a>

## User Base

-   People
    -   with disabilities such as pervasive developmental disorders
    -   in poverty who are one misstep from disaster
    -   with unwieldy illnesses
    -   who are homeless
    -   who experience relationship violence
    -   everyone else


<a id="org18e9ac9"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#org685e10a)


<a id="orgaa347e2"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org1db5c6f"></a>

# General Overview


<a id="orgbe353c9"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks


<a id="orgf7d2f93"></a>

## Health


<a id="orgc1fa910"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org4d040c4"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
        -   [ ] Macros planning and counting
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org7b46c37) for hitting macros
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Recipe manager](https://frdcsa.org/%7eandrewdo/gourmet-frontend.webm)
    -   [ ] [Recommender system](https://frdcsa.org/%7eandrewdo/WebWiki/RecipeRecommendationSystem.html)


<a id="org23c2a4d"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] Patient advocate
-   [ ] [Tracking visits](https://github.com/aindilis/akahige)
-   [ ] [Following through on instructions](#org4fd60c9)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="org54a474c"></a>

### Medications

-   [ ] Refill tracker
-   [ ] Medication management


<a id="org4cf657f"></a>

### Mental Health

-   [ ] Emotional security
    -   [ ] Managing triggers
    -   [ ] Reframing self-talk
-   [ ] Planning for optimal productivity by meeting needs
    -   [ ] Pre/pro-active planning
    -   [ ] Root cause analysis for low-productivity
    -   [ ] Responses to low-productivity
    -   [ ] Task tracking and MTTC (Mean Time To Completion)
-   [ ] Psychometric reporting
    -   [ ] Identifying factors


<a id="org5472e0c"></a>

## Time Management


<a id="orga1f6c4b"></a>

### Recurrences

-   [X] Dates
    -   [X] On a given date
    -   [X] On a given day of week
    -   [X] Through given days of week
    -   [X] Every n-th week/month/year
-   [-] Times
    -   [X] Multiple specific time points
    -   [ ] Durations


<a id="org4fb49ba"></a>

### Calendaring

-   [X] Scheduling appointments
-   [X] Scheduling of chores
-   [ ] Detect double-booking


<a id="orgf46c711"></a>

### Planning, Scheduling, and Execution

1.  Planning

    -   [ ] Workflow Manager
    -   [ ] Metaplanning
    -   [X] Temporal planning
    -   [X] Contingent planning
    -   [X] Behavior tree reactive planning
    -   [X] [BDI reactive planning](http://jason.sourceforge.net/) (Belief-Desire-Intention)

2.  Plan Monitoring

    -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
    -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="org4881d24"></a>

## Organization


<a id="orge86c500"></a>

### Inventory Management

-   [ ] Supplier tracking
-   [ ] Semiautomatic reordering
-   [ ] Pantry management
    -   [ ] Nutrition lookup


<a id="org6433d6c"></a>

### Communication Management

-   [ ] Team building
-   [X] Relationship management
    -   [X] Track birthdays, anniversaries, etc


<a id="org658fa5d"></a>

### Chore Charting

-   [ ] Track who/what/where/when regarding chores
-   [X] Implement rewards via gamification


<a id="org98ff324"></a>

### Maintenance

-   [X] Home
-   [X] Automotive
-   [ ] Equipment
-   [ ] Computer systems


<a id="org53d839a"></a>

### Research and Development


<a id="org7b46c37"></a>

## Self-Discipline


<a id="org717c096"></a>

### To-Do

-   [-] Track hundreds of thousands of (unscheduled) tasks
    -   [ ] Including their interdependencies
    -   [X] In a logical language


<a id="orgf197e01"></a>

### Note-Taking


<a id="orga24681c"></a>

### Scheduling

-   [ ] Automatically schedule tasks using (temporal) planning algorithms
    -   [ ] A taxonomy of task properties
-   [X] Schedule important tasks
-   [X] Set deadlines


<a id="org76156a0"></a>

### Self-Discipline State Machine

-   [ ] Make sure the user is up to any task
-   [ ] Assist with follow-through on things like dieting, exercise, etc


<a id="orgd43d48b"></a>

### Gamification

-   [ ] Apply short, medium and long term reward cycles for task accomplishment


<a id="org9c610d7"></a>

### Movement Discipline

-   [ ] Ensure we think before we move


<a id="org2670ea4"></a>

## Transportation/Shopping/Errands


<a id="org78400d1"></a>

### Transportation

-   [ ] Develop proper transportation plans
    -   [ ] Incorporating hours of operation, weather and route information
-   [ ] Use "Location Logic" to provide reminders
    -   [ ] e.g. Don't forget to bring this with you when you leave
    -   [ ] e.g. Silence your cell phone in certain types of locations


<a id="org5c04c31"></a>

### Shopping/Errands

-   [ ] Manage your shopping list
    -   [ ] Integrate with financial tracking
    -   [ ] Integrate with pantry management
-   [ ] Track all types of receipts
-   [ ] Buy/sell things as necessary
-   [ ] Help boycott products by companies the user doesn't support


<a id="org4fd60c9"></a>

## Document Management

-   [X] Scan and OCR paperwork
    -   [X] Cross reference with schedule
-   [X] Ensure confidentiality of information
-   [X] Backup documents
-   [ ] Track doctors orders
    -   [ ] Help the user implement doctors orders


<a id="org29e083e"></a>

## Financial Planner

-   [X] Help manage cash flow in tight situations
    -   [X] Forecast finances
        -   [X] Automatically detect recurring transactions
        -   [X] Tell us when we're going to run out of money
        -   [X] Tell us how much we need to raise by when


<a id="org920c539"></a>

## Emergency Preparedness

-   [ ] Help the user stay on top of emergency preparedness
    -   [ ] Analyze which kinds of emergencies are particular to the users situation
    -   [ ] Prepare a "bug out bag," emergency food and water supply, etc
    -   [ ] Help the user maintain a ready posture
    -   [ ] Safety plans and drills


<a id="orgd713604"></a>

# More Info


<a id="org685e10a"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to your doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on your taxes, and to change your air filter
-   Telling you that a particular plan of yours violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="org8756e68"></a>

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


<a id="org12286c3"></a>

## [Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)

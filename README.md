- [The Free Life Planner](#org114ad7e)
  - [THIS README IS UNDER CONSTRUCTION](#orgd5f0ec8)
- [[Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#org1a3e385)
- [Introduction](#org315e5f2)
  - [Purpose](#org8961c67)
  - [User Base](#org66b702c)
  - [Sample use cases](#orgc12fc9c)
  - [Status](#org9193ff0)
- [General Overview](#orgfe7a666)
  - [Workflow Manager](#org5c667e9)
  - [Employment](#orgd930cd3)
  - [Health](#orgc5d33d5)
    - [Exercise](#org87b555c)
    - [Nutrition](#org0338c30)
    - [Doctor's Visits and Orders](#org3c95141)
    - [Medications](#org59c0f54)
    - [Mental Health](#org6de836c)
  - [Time Management](#org9e58519)
    - [Recurrences](#org29c5663)
    - [Calendaring](#org2a1013d)
    - [Planning, Scheduling, and Execution](#org54625b9)
  - [Organization](#org4a155bd)
    - [Financial Planner](#org063677c)
    - [Inventory Management](#orgbe70d98)
    - [Document Management](#org7632940)
    - [Adulting](#org779810a)
    - [Transportation](#org683dc0d)
    - [Shopping/Errands](#org3653212)
    - [Maintenance](#org847b6e4)
    - [Research and Development](#orgcbc2d30)
  - [Self-Discipline](#org4f7cb41)
    - [To-Do](#org669a567)
    - [Note-Taking](#orgb1622da)
    - [Scheduling](#orgb5a66e9)
    - [Executive Function](#org3b7efd8)
    - [Self-Discipline State Machine](#orgc3f10f6)
    - [Gamification](#orgcf149e8)
    - [Movement Discipline](#org4e70e64)
  - [Interpersonal](#org9adc976)
  - [Emergency Preparedness](#orga4cf4a9)
- [More Info](#org35799f3)
  - [More Use Cases](#orge85f7b0)
  - [Links](#orgf6ba571)
  - [[Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#orgd8546ae)


<a id="org114ad7e"></a>

# The Free Life Planner


<a id="orgd5f0ec8"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org1a3e385"></a>

# [Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="org315e5f2"></a>

# Introduction


<a id="org8961c67"></a>

## Purpose

-   A life planner that helps with many aspects of one's life
-   A "Life Manual" / "Skills for Living Life"
    -   Cognitive prosthetic for executive function
-   Including for people w/ ADHD, autism, schizophrenia, dementia, etc


<a id="org66b702c"></a>

## User Base

-   People
    -   with disabilities such as pervasive developmental disorders
    -   in poverty who are one misstep from disaster
    -   with unwieldy illnesses
    -   who are homeless
    -   who experience relationship violence
    -   returning citizens
    -   everyone else


<a id="orgc12fc9c"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#orge85f7b0)


<a id="org9193ff0"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgfe7a666"></a>

# General Overview


<a id="org5c667e9"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks


<a id="orgd930cd3"></a>

## Employment

-   [X] Time tracking
-   [ ] Acquiring income
-   [-] Job search
    -   [X] Semi-automatic job applications
    -   [ ] Dynamic resumes tailored to specific job posts
    -   [X] Negotiation trainer


<a id="orgc5d33d5"></a>

## Health


<a id="org87b555c"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org0338c30"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
        -   [ ] Macros planning and counting
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org4f7cb41) for hitting macros
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Recipe manager](https://frdcsa.org/%7eandrewdo/gourmet-frontend.webm)
    -   [ ] [Recommender system](https://frdcsa.org/%7eandrewdo/WebWiki/RecipeRecommendationSystem.html)


<a id="org3c95141"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] Patient advocate
-   [ ] [Tracking visits](https://github.com/aindilis/akahige)
-   [ ] [Following through on instructions](#org7632940)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="org59c0f54"></a>

### Medications

-   [ ] Refill tracker
-   [ ] Medication management


<a id="org6de836c"></a>

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


<a id="org9e58519"></a>

## Time Management


<a id="org29c5663"></a>

### Recurrences

-   [X] Dates
    -   [X] On a given date
    -   [X] On a given day of week
    -   [X] Through given days of week
    -   [X] Every n-th week/month/year
-   [-] Times
    -   [X] Multiple specific time points
    -   [ ] Durations


<a id="org2a1013d"></a>

### Calendaring

-   [X] Scheduling appointments
-   [X] Scheduling of chores
-   [ ] Detect double-booking


<a id="org54625b9"></a>

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


<a id="org4a155bd"></a>

## Organization


<a id="org063677c"></a>

### Financial Planner

-   [ ] Budgeting
-   [X] Help manage cash flow in tight situations
    -   [X] Forecast finances
        -   [X] Automatically detect recurring transactions
        -   [X] Tell us when we're going to run out of money
        -   [X] Tell us how much we need to raise by when


<a id="orgbe70d98"></a>

### Inventory Management

-   [ ] Supplier tracking
-   [ ] Semiautomatic reordering
    -   [ ] Integration with cashflow tracking
-   [ ] Pantry management
    -   [ ] Nutrition lookup


<a id="org7632940"></a>

### Document Management

-   [X] Scan and OCR paperwork
    -   [X] Cross reference with schedule
-   [X] Ensure confidentiality of information
-   [X] Backup documents
-   [ ] Track doctors orders
    -   [ ] Help the user implement doctors orders


<a id="org779810a"></a>

### Adulting

-   [ ] ADLs
    -   [ ] Daily Self Care
-   [-] IADLs
    -   [-] Chore charting
        -   [ ] Track who/what/where/when regarding chores
        -   [X] Implement rewards via gamification


<a id="org683dc0d"></a>

### Transportation

-   [ ] Develop proper transportation plans
    -   [ ] Incorporating hours of operation, weather and route information
-   [ ] Use "Location Logic" to provide reminders
    -   [ ] e.g. Don't forget to bring this with you when you leave
    -   [ ] e.g. Silence one's cell phone in certain types of locations


<a id="org3653212"></a>

### Shopping/Errands

-   [ ] Manage one's shopping list
    -   [ ] Integrate with [financial tracking](#org063677c)
    -   [ ] Integrate with [pantry management](#org0338c30)
-   [ ] Track all types of receipts
-   [ ] Buy/sell things as necessary
-   [ ] Help boycott products by companies the user doesn't support


<a id="org847b6e4"></a>

### Maintenance

-   [X] Home
-   [X] Automotive
-   [ ] Equipment
-   [ ] Computer systems


<a id="orgcbc2d30"></a>

### Research and Development


<a id="org4f7cb41"></a>

## Self-Discipline


<a id="org669a567"></a>

### To-Do

-   [-] Track hundreds of thousands of (unscheduled) tasks
    -   [ ] Including their interdependencies
    -   [X] In a logical language


<a id="orgb1622da"></a>

### Note-Taking


<a id="orgb5a66e9"></a>

### Scheduling

-   [ ] Automatically schedule tasks using (temporal) planning algorithms
    -   [ ] A taxonomy of task properties
-   [X] Schedule important tasks
-   [X] Set deadlines


<a id="org3b7efd8"></a>

### Executive Function

-   [ ] Intelligence Augmentation
    -   [ ] Learning
        -   [ ] Education
        -   [ ] Empirical
    -   [ ] Cognitive Prosthetic
    -   [ ] Nootropics
-   [ ] Problem-Solving


<a id="orgc3f10f6"></a>

### Self-Discipline State Machine

-   [ ] Make sure the user is up to any task
-   [ ] Assist with follow-through on things like dieting, exercise, etc


<a id="orgcf149e8"></a>

### Gamification

-   [ ] Apply short, medium and long term reward cycles for task accomplishment


<a id="org4e70e64"></a>

### Movement Discipline

-   [ ] Ensure we think before we move


<a id="org9adc976"></a>

## Interpersonal

-   [ ] Team building
    -   [ ] Networking
        -   [ ] Colleagues
-   [-] Relationship management
    -   [ ] Friendships
    -   [ ] Family
    -   [ ] Groups
        -   [ ] Social advocacy/interest groups
    -   [X] Track birthdays, anniversaries, etc


<a id="orga4cf4a9"></a>

## Emergency Preparedness

-   [ ] Help the user stay on top of emergency preparedness
    -   [ ] Analyze which kinds of emergencies are particular to the users situation
    -   [ ] Prepare a "bug out bag," emergency food and water supply, etc
    -   [ ] Help the user maintain a ready posture
    -   [ ] Safety plans and drills


<a id="org35799f3"></a>

# More Info


<a id="orge85f7b0"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to one's doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on one's taxes, and to change one's air filter
-   Telling you that a particular plan of one's violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="orgf6ba571"></a>

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


<a id="orgd8546ae"></a>

## [Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)

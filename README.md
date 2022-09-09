- [The Free Life Planner](#org26027a8)
  - [THIS README IS UNDER CONSTRUCTION](#org4dfab39)
- [[Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#org8920ae4)
  - [[In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#org5a87dcf)
- [Introduction](#org139e6b8)
  - [Purpose](#orgadaa421)
  - [User Base](#orga07a585)
  - [Sample use cases](#org7aec4b3)
  - [Status](#org669304f)
- [General Overview](#org0a3bb1c)
  - [Workflow Manager](#orgec4c23e)
  - [Employment](#org4b73f02)
  - [Health](#orgf399357)
    - [Exercise](#org804b207)
    - [Nutrition](#org4a56d1d)
    - [Doctor's Visits and Orders](#org0a1af0b)
    - [Medications](#org3345753)
    - [Mental Health](#orgbd7b127)
  - [Time Management](#orgf9a4c66)
    - [Recurrences](#org35f0326)
    - [Calendaring](#orgcaabb23)
    - [Planning, Scheduling, and Execution](#orge4aa65f)
  - [Organization](#org7e369ca)
    - [Financial Planner](#org192fed5)
    - [Inventory Management](#org5db3de6)
    - [Document Management](#org10f93e1)
    - [Adulting](#orgd023003)
    - [Transportation](#orga3dd51a)
    - [Shopping/Errands](#orgbcfdbaf)
    - [Maintenance](#org63bb1dd)
    - [Research and Development](#orgcac5d8f)
  - [Self-Discipline](#org72b484a)
    - [To-Do](#orge07cd37)
    - [Note-Taking](#org9137ef7)
    - [Scheduling](#org9ecc3de)
    - [Executive Function](#orgb4b138d)
    - [Self-Discipline State Machine](#org4e7f87d)
    - [Gamification](#org0304fc9)
    - [Movement Discipline](#org18c0e6d)
  - [Interpersonal](#org483dc0d)
  - [Emergency Preparedness](#org5c465b7)
- [More Info](#orgc4d8ebb)
  - [More Use Cases](#org3a18844)
  - [Links](#orgfeba5c1)
  - [[Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#orgeacd9dd)
    - [[In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#orgecfd7a1)


<a id="org26027a8"></a>

# The Free Life Planner


<a id="org4dfab39"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org8920ae4"></a>

# [Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="org5a87dcf"></a>

## [In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="org139e6b8"></a>

# Introduction


<a id="orgadaa421"></a>

## Purpose

-   A short, medium and long-term life planner that helps with many aspects of one's life
    -   A "life manual" / "skills for living life"
    -   Cognitive prosthesis for executive function
        -   Including for people w/ ADHD, autism, schizophrenia, dementia, etc


<a id="orga07a585"></a>

## User Base

-   People
    -   with disabilities such as pervasive developmental disorders
    -   in poverty who are one misstep from disaster
    -   with unwieldy illnesses
    -   who are homeless
    -   who experience relationship violence
    -   returning citizens
    -   everyone else


<a id="org7aec4b3"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#org3a18844)


<a id="org669304f"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org0a3bb1c"></a>

# General Overview


<a id="orgec4c23e"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks


<a id="org4b73f02"></a>

## Employment

-   [X] [Time tracking](https://altruisticsoftware.org/frdcsa/minor/consultant-support/)
-   [ ] Acquiring income
-   [-] Job search
    -   [X] [Semi-automatic job applications](https://www.youtube.com/watch?v=qFRSwRVFuhE&feature=youtu.be)
    -   [ ] [<code>[90%]</code> Resume generation](https://github.com/aindilis/job-search)
        -   [ ] <code>[30%]</code> Dynamic resumes tailored to specific job posts
    -   [X] [Negotiation trainer](https://frdcsa.org/~andrewdo/WebWiki/AudienceDialog.html)


<a id="orgf399357"></a>

## Health


<a id="org804b207"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org4a56d1d"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
        -   [ ] <code>[25%]</code> Macros planning and counting
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org72b484a) for hitting macros
    -   [ ] <code>[20%]</code> Specialty diets (medical or ethical)
    -   [ ] [<code>[10%]</code> Recipe manager](https://frdcsa.org/%7eandrewdo/gourmet-frontend.webm)
    -   [ ] <code>[10%]</code> [Recommender system](https://frdcsa.org/%7eandrewdo/WebWiki/RecipeRecommendationSystem.html)


<a id="org0a1af0b"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] <code>[10%]</code> Patient advocate
-   [ ] [Tracking visits](https://github.com/aindilis/akahige)
-   [ ] [Following through on instructions](#org10f93e1)
-   [ ] For when a physician is unavailable
    -   [ ] Diagnostic expert system
    -   [ ] First aid course of action system


<a id="org3345753"></a>

### Medications

-   [ ] <code>[33%]</code> Refill tracker
-   [ ] Medication management


<a id="orgbd7b127"></a>

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


<a id="orgf9a4c66"></a>

## Time Management


<a id="org35f0326"></a>

### Recurrences

-   [X] Dates
    -   [X] On a given date
    -   [X] On a given day of week
    -   [X] Through given days of week
    -   [X] Every n-th week/month/year
-   [-] Times
    -   [X] Multiple specific time points
    -   [ ] Durations


<a id="orgcaabb23"></a>

### Calendaring

-   [X] Scheduling appointments
-   [X] Scheduling of chores
-   [ ] Detect double-booking


<a id="orge4aa65f"></a>

### Planning, Scheduling, and Execution

1.  Planning

    -   [ ] <code>[25%]</code> Workflow Manager
    -   [ ] <code>[25%]</code> Metaplanning
    -   [X] Temporal planning
    -   [X] Contingent planning
    -   [X] Behavior tree reactive planning
    -   [X] [BDI reactive plannin ](http://jason.sourceforge.net/) (Belief-Desire-Intention)

2.  Plan Monitoring

    -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
    -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="org7e369ca"></a>

## Organization


<a id="org192fed5"></a>

### Financial Planner

-   [ ] Budgeting
-   [X] Help manage cash flow in tight situations
    -   [X] Forecast finances
        -   [X] Automatically detect recurring transactions
        -   [X] Tell us when we're going to run out of money
        -   [X] Tell us how much we need to raise by when
-   [X] Adds financial reasoning to life-planning problems


<a id="org5db3de6"></a>

### Inventory Management

-   [ ] <code>[10%]</code> Supplier tracking
-   [ ] <code>[10%]</code> Semiautomatic reordering
    -   [ ] <code>[25%]</code> Integration with cashflow tracking
-   [ ] Pantry management
    -   [ ] <code>[80%]</code> Nutrition lookup


<a id="org10f93e1"></a>

### Document Management

-   [X] Scan and OCR paperwork
    -   [X] Cross reference with schedule
-   [X] Ensure confidentiality of information
-   [X] Backup documents
-   [ ] Track doctors orders
    -   [ ] Help the user implement doctors orders


<a id="orgd023003"></a>

### Adulting

-   [ ] ADLs
    -   [ ] Daily Self Care
-   [-] IADLs
    -   [-] Chore charting
        -   [ ] <code>[35%]</code> Track who/what/where/when regarding chores
        -   [X] Implement rewards via gamification


<a id="orga3dd51a"></a>

### Transportation

-   [ ] <code>[25%]</code> Develop proper transportation plans
    -   [ ] <code>[25%]</code> Incorporating hours of operation, weather and route information
-   [ ] <code>[75%]</code> Use "Location Logic" to provide reminders
    -   [ ] <code>[75%]</code> e.g. Don't forget to bring this with you when you leave
    -   [ ] <code>[75%]</code> e.g. Silence one's cell phone in certain types of locations


<a id="orgbcfdbaf"></a>

### Shopping/Errands

-   [ ] Manage one's shopping list
    -   [ ] <code>[15%]</code> Integrate with [financial tracking](#org192fed5)
    -   [ ] <code>[25%]</code> Integrate with [pantry management](#org4a56d1d)
-   [ ] <code>[25%]</code> Track all types of receipts
-   [ ] Buy/sell things as necessary
-   [ ] <code>[75%]</code> Help boycott products by companies the user doesn't support


<a id="org63bb1dd"></a>

### Maintenance

-   [X] Home
-   [X] Automotive
-   [ ] Equipment
-   [ ] Computer systems


<a id="orgcac5d8f"></a>

### Research and Development


<a id="org72b484a"></a>

## Self-Discipline


<a id="orge07cd37"></a>

### To-Do

-   [-] <code>[80%]</code> [Track hundreds of thousands of (unscheduled) tasks](https://github.com/aindilis/do/tree/master/scripts/convert)
    -   [ ] <code>[60%]</code> Including their interdependencies
    -   [X] In a logical language


<a id="org9137ef7"></a>

### Note-Taking


<a id="org9ecc3de"></a>

### Scheduling

-   [ ] <code>[50%]</code> Automatically schedule tasks using (temporal) planning algorithms
    -   [ ] <code>[10%]</code> A taxonomy of task properties
-   [X] Schedule important tasks
-   [X] Set deadlines


<a id="orgb4b138d"></a>

### Executive Function

-   [ ] Intelligence Augmentation
    -   [ ] Learning
        -   [ ] Education
        -   [ ] Empirical
    -   [ ] Cognitive Prosthesis
    -   [ ] Nootropics
-   [ ] Problem-Solving
    -   [ ] Goal setting


<a id="org4e7f87d"></a>

### Self-Discipline State Machine

-   [ ] Make sure the user is up to any task
-   [ ] Assist with follow-through on things like dieting, exercise, etc


<a id="org0304fc9"></a>

### Gamification

-   [ ] <code>[40%]</code> Apply short, medium and long term reward cycles for task accomplishment


<a id="org18c0e6d"></a>

### Movement Discipline

-   [ ] Ensure we think before we move


<a id="org483dc0d"></a>

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


<a id="org5c465b7"></a>

## Emergency Preparedness

-   [ ] <code>[10%]</code> Help the user stay on top of emergency preparedness
    -   [ ] Analyze which kinds of emergencies are particular to the users situation
    -   [ ] Prepare a "bug-out bag," emergency food and water supply, etc
    -   [ ] Help the user maintain a ready posture
    -   [ ] Safety plans and drills


<a id="orgc4d8ebb"></a>

# More Info


<a id="org3a18844"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to one's doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on one's taxes, and to change one's air filter
-   Telling you that a particular plan of one's violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="orgfeba5c1"></a>

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


<a id="orgeacd9dd"></a>

## [Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="orgecfd7a1"></a>

### [In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)

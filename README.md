- [The Free Life Planner](#org55b0780)
  - [THIS README IS UNDER CONSTRUCTION](#org41ef5c6)
- [[Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#orge18f152)
  - [[In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#org83f9ac9)
- [Introduction](#orge64258c)
  - [Purpose](#orgf4399c0)
  - [User Base](#orgbefef21)
  - [Sample use cases](#org742e150)
  - [Status](#orge096431)
- [General Overview](#org307e123)
  - [Workflow Manager](#org58b0d43)
  - [Employment](#orgcf2d794)
  - [Health](#org6b9947f)
    - [Exercise](#orgb30250e)
    - [Nutrition](#orgbc1a24f)
    - [Doctor's Visits and Orders](#orgecf6c55)
    - [Medications](#orgf3b00c3)
    - [Mental Health](#orgd09f8a1)
  - [Time Management](#orgaf2becf)
    - [Recurrences](#org152bb2b)
    - [Calendaring](#org82faa22)
    - [Planning, Scheduling, and Execution](#orge84194f)
  - [Organization](#org3d21020)
    - [Financial Planner](#org84ff763)
    - [Inventory Management](#org062d271)
    - [Document Management](#org883a1fa)
    - [Adulting](#org071b83b)
    - [Transportation](#orgaea0d1a)
    - [Shopping/Errands](#org02fd839)
    - [Maintenance](#orgb3d3d7d)
    - [Research and Development](#org31ce8e2)
  - [Self-Discipline](#orgba2f383)
    - [To-Do](#org7e774f7)
    - [Note-Taking](#orgcfb1757)
    - [Scheduling](#orgafcce38)
    - [Executive Function](#orgc086333)
    - [Self-Discipline State Machine](#org94c9bc7)
    - [Gamification](#org968a826)
    - [Movement Discipline](#org12b9061)
  - [Interpersonal](#org24dc9df)
  - [Emergency Preparedness](#orgfe9edca)
- [More Info](#orgea94596)
  - [More Use Cases](#org4d9c48f)
  - [Links](#org9903098)
  - [[Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#org618e898)
    - [[In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)](#org4362829)


<a id="org55b0780"></a>

# The Free Life Planner


<a id="org41ef5c6"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orge18f152"></a>

# [Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="org83f9ac9"></a>

## [In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="orge64258c"></a>

# Introduction


<a id="orgf4399c0"></a>

## Purpose

-   A short, medium and long-term life planner that helps with many aspects of one's life
    -   A "life manual" / "skills for living life"
    -   Cognitive prosthesis for executive function
        -   Including for people w/ ADHD, autism, schizophrenia, dementia, etc


<a id="orgbefef21"></a>

## User Base

-   People
    -   with disabilities such as pervasive developmental disorders
    -   in poverty who are one misstep from disaster
    -   with unwieldy illnesses
    -   who are homeless
    -   who experience relationship violence
    -   returning citizens
    -   everyone else


<a id="org742e150"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#org4d9c48f)


<a id="orge096431"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org307e123"></a>

# General Overview


<a id="org58b0d43"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks


<a id="orgcf2d794"></a>

## Employment

-   [X] [Time tracking](https://altruisticsoftware.org/frdcsa/minor/consultant-support/)
-   [ ] Acquiring income
-   [-] Job search
    -   [X] [Semi-automatic job applications](https://www.youtube.com/watch?v=qFRSwRVFuhE&feature=youtu.be)
    -   [ ] [<code>[90%]</code> Resume generation](https://github.com/aindilis/job-search)
        -   [ ] <code>[30%]</code> Dynamic resumes tailored to specific job posts
    -   [X] [Negotiation trainer](https://frdcsa.org/~andrewdo/WebWiki/AudienceDialog.html)


<a id="org6b9947f"></a>

## Health


<a id="orgb30250e"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="orgbc1a24f"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
        -   [ ] <code>[25%]</code> Macros planning and counting
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#orgba2f383) for hitting macros
    -   [ ] <code>[20%]</code> Specialty diets (medical or ethical)
    -   [ ] [<code>[10%]</code> Recipe manager](https://frdcsa.org/%7eandrewdo/gourmet-frontend.webm)
    -   [ ] <code>[10%]</code> [Recommender system](https://frdcsa.org/%7eandrewdo/WebWiki/RecipeRecommendationSystem.html)


<a id="orgecf6c55"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] <code>[10%]</code> Patient advocate
-   [ ] [Tracking visits](https://github.com/aindilis/akahige)
-   [ ] [Following through on instructions](#org883a1fa)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="orgf3b00c3"></a>

### Medications

-   [ ] <code>[33%]</code> Refill tracker
-   [ ] Medication management


<a id="orgd09f8a1"></a>

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


<a id="orgaf2becf"></a>

## Time Management


<a id="org152bb2b"></a>

### Recurrences

-   [X] Dates
    -   [X] On a given date
    -   [X] On a given day of week
    -   [X] Through given days of week
    -   [X] Every n-th week/month/year
-   [-] Times
    -   [X] Multiple specific time points
    -   [ ] Durations


<a id="org82faa22"></a>

### Calendaring

-   [X] Scheduling appointments
-   [X] Scheduling of chores
-   [ ] Detect double-booking


<a id="orge84194f"></a>

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


<a id="org3d21020"></a>

## Organization


<a id="org84ff763"></a>

### Financial Planner

-   [ ] Budgeting
-   [X] Help manage cash flow in tight situations
    -   [X] Forecast finances
        -   [X] Automatically detect recurring transactions
        -   [X] Tell us when we're going to run out of money
        -   [X] Tell us how much we need to raise by when
-   [X] Adds financial reasoning to life-planning problems


<a id="org062d271"></a>

### Inventory Management

-   [ ] <code>[10%]</code> Supplier tracking
-   [ ] <code>[10%]</code> Semiautomatic reordering
    -   [ ] <code>[25%]</code> Integration with cashflow tracking
-   [ ] Pantry management
    -   [ ] <code>[80%]</code> Nutrition lookup


<a id="org883a1fa"></a>

### Document Management

-   [X] Scan and OCR paperwork
    -   [X] Cross reference with schedule
-   [X] Ensure confidentiality of information
-   [X] Backup documents
-   [ ] Track doctors orders
    -   [ ] Help the user implement doctors orders


<a id="org071b83b"></a>

### Adulting

-   [ ] ADLs
    -   [ ] Daily Self Care
-   [-] IADLs
    -   [-] Chore charting
        -   [ ] <code>[35%]</code> Track who/what/where/when regarding chores
        -   [X] Implement rewards via gamification


<a id="orgaea0d1a"></a>

### Transportation

-   [ ] <code>[25%]</code> Develop proper transportation plans
    -   [ ] <code>[25%]</code> Incorporating hours of operation, weather and route information
-   [ ] <code>[75%]</code> Use "Location Logic" to provide reminders
    -   [ ] <code>[75%]</code> e.g. Don't forget to bring this with you when you leave
    -   [ ] <code>[75%]</code> e.g. Silence one's cell phone in certain types of locations


<a id="org02fd839"></a>

### Shopping/Errands

-   [ ] Manage one's shopping list
    -   [ ] <code>[15%]</code> Integrate with [financial tracking](#org84ff763)
    -   [ ] <code>[25%]</code> Integrate with [pantry management](#orgbc1a24f)
-   [ ] <code>[25%]</code> Track all types of receipts
-   [ ] Buy/sell things as necessary
-   [ ] <code>[75%]</code> Help boycott products by companies the user doesn't support


<a id="orgb3d3d7d"></a>

### Maintenance

-   [X] Home
-   [X] Automotive
-   [ ] Equipment
-   [ ] Computer systems


<a id="org31ce8e2"></a>

### Research and Development


<a id="orgba2f383"></a>

## Self-Discipline


<a id="org7e774f7"></a>

### To-Do

-   [-] <code>[80%]</code> [Track hundreds of thousands of (unscheduled) tasks](https://github.com/aindilis/do/tree/master/scripts/convert)
    -   [ ] <code>[60%]</code> Including their interdependencies
    -   [X] In a logical language


<a id="orgcfb1757"></a>

### Note-Taking


<a id="orgafcce38"></a>

### Scheduling

-   [ ] <code>[50%]</code> Automatically schedule tasks using (temporal) planning algorithms
    -   [ ] <code>[10%]</code> A taxonomy of task properties
-   [X] Schedule important tasks
-   [X] Set deadlines


<a id="orgc086333"></a>

### Executive Function

-   [ ] Intelligence Augmentation
    -   [ ] Learning
        -   [ ] Education
        -   [ ] Empirical
    -   [ ] Cognitive Prosthetic
    -   [ ] Nootropics
-   [ ] Problem-Solving
    -   [ ] Goal setting


<a id="org94c9bc7"></a>

### Self-Discipline State Machine

-   [ ] Make sure the user is up to any task
-   [ ] Assist with follow-through on things like dieting, exercise, etc


<a id="org968a826"></a>

### Gamification

-   [ ] <code>[40%]</code> Apply short, medium and long term reward cycles for task accomplishment


<a id="org12b9061"></a>

### Movement Discipline

-   [ ] Ensure we think before we move


<a id="org24dc9df"></a>

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


<a id="orgfe9edca"></a>

## Emergency Preparedness

-   [ ] <code>[10%]</code> Help the user stay on top of emergency preparedness
    -   [ ] Analyze which kinds of emergencies are particular to the users situation
    -   [ ] Prepare a "bug-out bag," emergency food and water supply, etc
    -   [ ] Help the user maintain a ready posture
    -   [ ] Safety plans and drills


<a id="orgea94596"></a>

# More Info


<a id="org4d9c48f"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to one's doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on one's taxes, and to change one's air filter
-   Telling you that a particular plan of one's violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="org9903098"></a>

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


<a id="org618e898"></a>

## [Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="org4362829"></a>

### [In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)

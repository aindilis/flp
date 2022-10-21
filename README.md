
# Table of Contents

1.  [The Free Life Planner](#orgc4474b2)
    1.  [THIS README IS UNDER CONSTRUCTION](#org87704fa)
2.  [Reference Manual](#org46d155a)
    1.  [In-depth feature descriptions and implementation details](#orge89a0a9)
3.  [Introduction](#orge90c77a)
    1.  [Purpose](#org20459f5)
    2.  [User Base](#org24bccd3)
    3.  [Sample use cases](#org4af20c0)
    4.  [Status](#orgeea395c)
4.  [General Overview](#orge33c58a)
    1.  [Workflow Manager](#org96f6b35)
    2.  [Employment](#org115eadb)
    3.  [Health](#orgd45d4e4)
        1.  [Evidence-Based Wellness](#org243851d)
        2.  [Exercise](#orga25851e)
        3.  [Nutrition](#org91acc78)
        4.  [Doctor's Visits and Orders](#org2f90872)
        5.  [Medications](#org23876fc)
        6.  [Mental Health](#org4aa5f0c)
    4.  [Time Management](#orgd82977e)
        1.  [Recurrences](#org8853aaf)
        2.  [Calendaring](#orgfa89e8b)
        3.  [Planning, Scheduling, and Execution](#orgf76da0d)
    5.  [Organization](#orgf5a74fd)
        1.  [Financial Planner](#orgecbdf6a)
        2.  [Inventory Management](#orgda83010)
        3.  [Document Management](#org5641f3d)
        4.  [Adulting](#orge3d978f)
        5.  [Transportation](#org912be0a)
        6.  [Shopping/Errands](#orgf539809)
        7.  [Maintenance](#orgdcffc25)
        8.  [Research and Development](#org2893660)
    6.  [Self-Discipline](#org0257648)
        1.  [To-Do](#org709e3ed)
        2.  [Note-Taking](#org19c3912)
        3.  [Scheduling](#orgb1bdb00)
        4.  [Executive Function](#org006941d)
        5.  [Self-Discipline State Machine](#org1617d6f)
        6.  [Gamification](#org0d9271c)
        7.  [Movement Discipline](#org9958e69)
    7.  [Interpersonal](#org79f14e3)
    8.  [Emergency Preparedness](#orgc63596d)
5.  [More Info](#orgc546f62)
    1.  [More Use Cases](#org6ec6db7)
    2.  [Links](#org185935c)
    3.  [Reference Manual](#org81b216b)
        1.  [In-depth feature descriptions and implementation details](#org2bdcf6a)


<a id="orgc4474b2"></a>

# The Free Life Planner


<a id="org87704fa"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org46d155a"></a>

# [Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="orge89a0a9"></a>

## [In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="orge90c77a"></a>

# Introduction


<a id="org20459f5"></a>

## Purpose

-   A free/libre program for helping people with the logistics of
    daily life, helping to plan and secure things like food,
    medicine, finances, transportation, health and so on.
-   A short, medium and long-term life planner
-   Cognitive prosthesis for executive function
    -   Including for people w/ ADHD, autism, schizophrenia, dementia, etc
-   A "life manual" / "skills for living life"


<a id="org24bccd3"></a>

## User Base

-   People
    -   with disabilities such as pervasive developmental disorders
    -   in poverty who are one misstep from disaster
    -   with unwieldy illnesses
    -   who are homeless
    -   who experience relationship violence
    -   returning citizens
    -   everyone else


<a id="org4af20c0"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [More Use Cases](#org6ec6db7)


<a id="orgeea395c"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orge33c58a"></a>

# General Overview


<a id="org96f6b35"></a>

## Workflow Manager

-   [ ] An overarching tool/wizard which pages through and helps complete all necessary tasks


<a id="org115eadb"></a>

## Employment

-   [X] [Time tracking](https://altruisticsoftware.org/frdcsa/minor/consultant-support/)
-   [ ] Acquiring income
-   [ ] Job search
    -   [X] [Semi-automatic job applications](https://www.youtube.com/watch?v=qFRSwRVFuhE&feature=youtu.be)
    -   [ ] [<code>[90%]</code> Resume generation](https://github.com/aindilis/job-search)
        -   [ ] <code>[30%]</code> Dynamic resumes tailored to specific job posts
    -   [X] [Negotiation trainer](https://frdcsa.org/~andrewdo/WebWiki/AudienceDialog.html)


<a id="orgd45d4e4"></a>

## Health


<a id="org243851d"></a>

### Evidence-Based Wellness

-   [ ] Opt-in data collection
-   [ ] Prevention / early detection


<a id="orga25851e"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org91acc78"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste 
        -   [ ] <code>[25%]</code> Macros planning and counting
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org0257648) for hitting macros
    -   [ ] <code>[20%]</code> Specialty diets (medical or ethical)
    -   [ ] [<code>[10%]</code> Recipe manager](https://frdcsa.org/%7eandrewdo/gourmet-frontend.webm)
    -   [ ] <code>[10%]</code> [Recommender system](https://frdcsa.org/%7eandrewdo/WebWiki/RecipeRecommendationSystem.html)


<a id="org2f90872"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] <code>[10%]</code> Patient advocate
-   [ ] [Tracking visits](https://github.com/aindilis/akahige)
-   [ ] [Following through on instructions](#org5641f3d)
-   [ ] For when a physician is unavailable
    -   [ ] Diagnostic expert system
    -   [ ] First aid course of action system


<a id="org23876fc"></a>

### Medications

-   [ ] <code>[33%]</code> Refill tracker
-   [ ] Medication management


<a id="org4aa5f0c"></a>

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


<a id="orgd82977e"></a>

## Time Management


<a id="org8853aaf"></a>

### Recurrences

-   [X] Dates
    -   [X] On a given date
    -   [X] On a given day of week
    -   [X] Through given days of week
    -   [X] Every n-th week/month/year
-   [ ] Times
    -   [X] Multiple specific time points
    -   [ ] Durations


<a id="orgfa89e8b"></a>

### Calendaring

-   [X] Scheduling appointments
-   [X] Scheduling of chores
-   [ ] Detect double-booking


<a id="orgf76da0d"></a>

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


<a id="orgf5a74fd"></a>

## Organization


<a id="orgecbdf6a"></a>

### Financial Planner

-   [ ] Budgeting
-   [X] Help manage cash flow in tight situations
    -   [X] Forecast finances
        -   [X] Automatically detect recurring transactions
        -   [X] Tell us when we're going to run out of money
        -   [X] Tell us how much we need to raise by when
-   [X] Adds financial reasoning to life-planning problems


<a id="orgda83010"></a>

### Inventory Management

-   [ ] <code>[10%]</code> Supplier tracking
-   [ ] <code>[10%]</code> Semiautomatic reordering
    -   [ ] <code>[25%]</code> Integration with cashflow tracking
-   [ ] Pantry management
    -   [ ] <code>[80%]</code> Nutrition lookup


<a id="org5641f3d"></a>

### Document Management

-   [X] Scan and OCR paperwork
    -   [X] Cross reference with schedule
-   [X] Ensure confidentiality of information
-   [X] Backup documents
-   [ ] Track doctors orders
    -   [ ] Help the user implement doctors orders


<a id="orge3d978f"></a>

### Adulting

-   [ ] ADLs
    -   [ ] Daily Self Care
-   [ ] IADLs
    -   [ ] Chore charting
        -   [ ] <code>[35%]</code> Track who/what/where/when regarding chores
        -   [X] Implement rewards via gamification


<a id="org912be0a"></a>

### Transportation

-   [ ] <code>[25%]</code> Develop proper transportation plans
    -   [ ] <code>[25%]</code> Incorporating hours of operation, weather and route information
-   [ ] <code>[75%]</code> Use "Location Logic" to provide reminders
    -   [ ] <code>[75%]</code> e.g. Don't forget to bring this with you when you leave
    -   [ ] <code>[75%]</code> e.g. Silence one's cell phone in certain types of locations


<a id="orgf539809"></a>

### Shopping/Errands

-   [ ] Manage one's shopping list
    -   [ ] <code>[15%]</code> Integrate with [financial tracking](#orgecbdf6a)
    -   [ ] <code>[25%]</code> Integrate with [pantry management](#org91acc78)
-   [ ] <code>[25%]</code> Track all types of receipts
-   [ ] Buy/sell things as necessary
-   [ ] <code>[75%]</code> Help boycott products by companies the user doesn't support


<a id="orgdcffc25"></a>

### Maintenance

-   [X] Home
-   [X] Automotive
-   [ ] Equipment
-   [ ] Computer systems


<a id="org2893660"></a>

### Research and Development


<a id="org0257648"></a>

## Self-Discipline


<a id="org709e3ed"></a>

### To-Do

-   [ ] <code>[80%]</code> [Track hundreds of thousands of (unscheduled) tasks](https://github.com/aindilis/do/tree/master/scripts/convert)
    -   [ ] <code>[60%]</code> Including their interdependencies
    -   [X] In a logical language


<a id="org19c3912"></a>

### Note-Taking


<a id="orgb1bdb00"></a>

### Scheduling

-   [ ] <code>[50%]</code> Automatically schedule tasks using (temporal) planning algorithms
    -   [ ] <code>[10%]</code> A taxonomy of task properties
-   [X] Schedule important tasks
-   [X] Set deadlines


<a id="org006941d"></a>

### Executive Function

-   [ ] Intelligence Augmentation
    -   [ ] Learning
        -   [ ] Education
        -   [ ] Empirical
    -   [ ] Cognitive Prosthesis
    -   [ ] Nootropics
-   [ ] Problem-Solving
    -   [ ] Goal setting


<a id="org1617d6f"></a>

### Self-Discipline State Machine

-   [ ] Make sure the user is up to any task
-   [ ] Assist with follow-through on things like dieting, exercise, etc


<a id="org0d9271c"></a>

### Gamification

-   [ ] <code>[40%]</code> Apply short, medium and long term reward cycles for task accomplishment


<a id="org9958e69"></a>

### Movement Discipline

-   [ ] Ensure we think before we move


<a id="org79f14e3"></a>

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


<a id="orgc63596d"></a>

## Emergency Preparedness

-   [ ] <code>[10%]</code> Help the user stay on top of emergency preparedness
    -   [ ] Analyze which kinds of emergencies are particular to the users situation
    -   [ ] Prepare a "bug-out bag," emergency food and water supply, etc
    -   [ ] Help the user maintain a ready posture
    -   [ ] Safety plans and drills


<a id="orgc546f62"></a>

# More Info


<a id="org6ec6db7"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need
-   Remembering that when you finish filling out some particular paperwork, to send a copy to one's doctor
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them
-   Reminding you to work on one's taxes, and to change one's air filter
-   Telling you that a particular plan of one's violates various moral and ethical constraints
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through


<a id="org185935c"></a>

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


<a id="org81b216b"></a>

## [Reference Manual](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


<a id="org2bdcf6a"></a>

### [In-depth feature descriptions and implementation details](https://github.com/aindilis/flp/blob/main/ReferenceManual.md)


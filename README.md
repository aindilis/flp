
# Table of Contents

1.  [The Free Life Planner](#org1004bf3)
    1.  [THIS README IS UNDER CONSTRUCTION](#orgad39292)
2.  [Introduction](#org87c78ab)
    1.  [Purpose](#org2c13f9e)
    2.  [Sample use cases](#orga0191cf)
    3.  [Status](#orga4e0cde)
    4.  [Summary](#orga49b61c)
3.  [Overview](#org0282c3f)
    1.  [Workflow Manager](#org933fac8)
    2.  [Health](#org763457f)
        1.  [Exercise](#orgf439abf)
        2.  [Nutrition](#orgaf6ce3d)
        3.  [Doctor's Visits and Orders](#orga0d06b1)
        4.  [Medications](#orgee50630)
    3.  [Time Management](#org485c4c3)
        1.  [Recurrences](#org6ad68ca)
        2.  [Calendaring](#org2374e33)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#org86a0b7b)
    4.  [Organization](#org3f1d21c)
        1.  [Inventory Management](#org4139060)
    5.  [Self-Discipline](#org1d0eee1)
        1.  [Self-Discipline State Machine](#org2415d9d)
    6.  [Transportation/Shopping/Errands](#org0eb75e1)
        1.  [Transportation](#org1229560)
        2.  [Shopping](#org992805c)
    7.  [Document Management](#org33bf182)
    8.  [Financial Planner](#orga75119f)
    9.  [Emergency Preparedness](#orgb2afaa8)
4.  [More Info](#orgbd1f037)
    1.  [More Use Cases](#orgb2a67e8)
    2.  [User Base](#orge31598d)
    3.  [Links](#org25fafe9)


<a id="org1004bf3"></a>

# The Free Life Planner


<a id="orgad39292"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org87c78ab"></a>

# Introduction


<a id="org2c13f9e"></a>

## Purpose

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="orga0191cf"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   More Use Cases


<a id="orga4e0cde"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orga49b61c"></a>

## Summary

-   [Workflow Manager](#org933fac8) (Guides user through all other systems)
-   [Health](#org763457f) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#orgdc4324d) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org485c4c3) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org3f1d21c) (Inventory Management)
-   [Self-Discipline](#org1d0eee1) (State Machine)
-   [Paperwork](#org33bf182) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orga75119f) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#orgb2afaa8) ()


<a id="org0282c3f"></a>

# Overview


<a id="org933fac8"></a>

## Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org763457f"></a>

## Health


<a id="orgf439abf"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="orgaf6ce3d"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#org1d0eee1) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="orga0d06b1"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] Patient advocate
-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org33bf182)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="orgee50630"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="org485c4c3"></a>

## Time Management


<a id="org6ad68ca"></a>

### Recurrences


<a id="org2374e33"></a>

### Calendaring


<a id="org86a0b7b"></a>

### Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring

1.  Planning

    -   [ ] Workflow Manager
    -   [ ] Metaplanning
    -   [X] Temporal planning
    -   [X] Contingent planning
    -   [X] Behavior tree reactive planning
    -   [X] [BDI reactive planning](http://jason.sourceforge.net/)

2.  Plan Monitoring

    -   [X] [Plan Monitoring](https://github.com/aindilis/plan-monitor#readme)
    -   [X] [Interactive Execution Monitoring](https://frdcsa.org/~andrewdo/iem2-3.mp4)


<a id="org3f1d21c"></a>

## Organization


<a id="org4139060"></a>

### Inventory Management

-   Pantry management


<a id="org1d0eee1"></a>

## Self-Discipline


<a id="org2415d9d"></a>

### Self-Discipline State Machine


<a id="org0eb75e1"></a>

## Transportation/Shopping/Errands


<a id="org1229560"></a>

### Transportation

-   [ ] API look-up mashups
    -   [ ] Hours of operation
        -   [ ] Stores/offices/etc
    -   [ ] Weather
    -   [ ] Route planning
-   [-] Location Logic
    -   [X] [Owntracks](https://owntracks.org/) integration
    -   [ ] Reverse geocoding
    -   [ ] Locational Rules
        -   [ ] e.g. [Silence my phone when at any movie theater](http://frdcsa.org/~andrewdo/projects/ll-rules.pl)


<a id="org992805c"></a>

### Shopping

-   [ ] Receipts
    -   [ ] Parsers and storage for online store receipts
    -   [ ] Parsers for brick and mortar store receipts
        -   [ ] OCR for physical receipts
-   [X] Online order Tracker
    -   [X] Check against OFX export
-   [X] Online Delivery Tracker
-   [ ] Integration with pantry and inventory management


<a id="org33bf182"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="orga75119f"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="orgb2afaa8"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="orgbd1f037"></a>

# More Info


<a id="orgb2a67e8"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives.
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need.
-   Remembering that when you finish filling out some particular paperwork, to send a copy to your doctor.
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them.
-   Reminding you to work on your taxes, and to change your air filter.
-   Telling you that a particular plan of yours violates various moral and ethical constraints.
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through.


<a id="orge31598d"></a>

## User Base

-   Everyone
-   People with disabilities such as pervasive developmental disorders.
-   People in poverty who are one misstep from disaster.
-   People with unwieldy illnesses.
-   People who are homeless.


<a id="org25fafe9"></a>

## Links

-   [Technical Overview](https://github.com/aindilis/flp/blob/main/Manual.md)

-   Here is the main FLP code site:

<https://github.com/aindilis/free-life-planner>

-   Here is the release of FRDCSA Panoply Git VM (containing older and stripped down versions of FRDCSA and Free Life Planner):

<https://github.com/aindilis/frdcsa-panoply-git-20200329>

-   Here is a story describing the Free Life Planner:

<https://frdcsa.org/~andrewdo/writings/homeless-story.html>

-   Here is the most recent talk on FLP.

<https://ontologforum.org/index.php/ConferenceCall_2022_04_20>

-   Here is the beginning of the release of FRDCSA (marking the Panoply release the official public release and deeming the last five years of work the "private" version of FRDCSA, and backporting from private to public as able):

<https://github.com/aindilis/frdcsa-installer>

-   Here is a recent talk from EmacsConf2019 about FRDCSA/FLP/Panoply:

<https://frdcsa.org/~andrewdo/frdcsa-emacsconf2019-final.webm>

-   Here is an independent codebase (no dependencies on FRDCSA) for interactive plan monitoring:

<https://github.com/aindilis/plan-monitor>

-   Here is some more recent work on the Interactive Execution Monitor:

<https://frdcsa.org/~andrewdo/iem2-2.mp4>
<https://frdcsa.org/~andrewdo/iem2-3.mp4>

-   Here is a video of an older, much smaller and simpler version of the FLP booting up (be careful, noisy):

<https://www.youtube.com/watch?v=t_dCAlf26LE>

-   Here is the beginning of a paper on FLP:

<https://frdcsa.org/~andrewdo/pioneer/wk1/flp.pdf>

-   and one on FRDCSA:

<https://frdcsa.org/~andrewdo/pioneer/wk1/frdcsa.pdf>

-   Here is a paper on the SPSE2 subsystem, an early planning system for FRDCSA which inspired parts of FLP:

<https://frdcsa.org/visual-aid/pdf/Temporal-Planning-and-Inferencing-for-Personal-Task-Management-with-SPSE2.pdf>

-   Here is a link to the financial planning submodule:

<https://github.com/aindilis/financial-planning#projected-transactions-for-florence-tucker>

-   Here is a link to the meal planning submodule:

<https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html>

-   Here is a video which shows some progress on the planner systems and also later the meal planner:

<https://www.youtube.com/watch?v=XZh_tHNboCI&t=15s>

-   Here are some earlier documents about the FLP:

<https://frdcsa.org/~andrewdo/writings/News-Challenge-2.html>
<https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanningCoachSoftware.html>
<https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanningCoachSoftwareUpdate.html>
<https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanner.html>

-   Here is the README for Panoply/FRDCSA:

<https://frdcsa.org/~andrewdo/writings/README.html>

-   Here is the project blog:

<https://facebook.com/frdcsa>

-   Here is the LogicMOO system mentioned in the EmacsConf video, which FLP draws heavily upon and intends to integrate with eventually:

<https://github.com/TeamSPoon/prologmud/wiki>

-   And here the design docs for LogicMOO:

<https://drive.google.com/drive/#folders/0B0QA19UX0ehlV1ZEaXEzc3hjTWM>


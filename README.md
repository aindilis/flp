
# Table of Contents

1.  [The Free Life Planner](#orga41a7e9)
    1.  [THIS README IS UNDER CONSTRUCTION](#orgfe3d556)
2.  [Introduction](#orgd24b145)
    1.  [Purpose](#orga05f7df)
    2.  [Sample use cases](#orgd8f9827)
    3.  [Status](#org4be1d68)
    4.  [Summary](#org9580610)
3.  [Overview](#org1f2f556)
    1.  [Workflow Manager](#org4f0403b)
    2.  [Health](#org0ec675a)
        1.  [Exercise](#orge6410a2)
        2.  [Nutrition](#org9fea107)
        3.  [Doctor's Visits and Orders](#orgde5c979)
        4.  [Medications](#org422ed33)
    3.  [Time Management](#org83b23f2)
        1.  [Recurrences](#orgdc63f1b)
        2.  [Calendaring](#org108bff1)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#org87f329e)
    4.  [Organization](#orgc5b3366)
        1.  [Inventory Management](#org82df5a7)
    5.  [Self-Discipline](#orgcc9d243)
        1.  [Self-Discipline State Machine](#orgb141189)
    6.  [Transportation/Shopping/Errands](#org5b877b2)
        1.  [Transportation](#org479f992)
        2.  [Shopping](#org622f861)
    7.  [Document Management](#org07f5852)
    8.  [Financial Planner](#orga402a85)
    9.  [Emergency Preparedness](#org70ce4b9)
4.  [Technical Overview](#org4a08f6e)
5.  [More Info](#org064337b)
    1.  [More Use Cases](#org8f2fcf2)
    2.  [User Base](#org04383f1)
    3.  [Links](#orgf215ec3)


<a id="orga41a7e9"></a>

# The Free Life Planner


<a id="orgfe3d556"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="orgd24b145"></a>

# Introduction


<a id="orga05f7df"></a>

## Purpose

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="orgd8f9827"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [5.1](#org8f2fcf2)


<a id="org4be1d68"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="org9580610"></a>

## Summary

-   [Workflow Manager](#org4f0403b) (Guides user through all other systems)
-   [Health](#org0ec675a) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#orgb90e295) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org83b23f2) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#orgc5b3366) (Inventory Management)
-   [Self-Discipline](#orgcc9d243) (State Machine)
-   [Paperwork](#org07f5852) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#orga402a85) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org70ce4b9) ()


<a id="org1f2f556"></a>

# Overview


<a id="org4f0403b"></a>

## Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="org0ec675a"></a>

## Health


<a id="orge6410a2"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="org9fea107"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#orgcc9d243) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="orgde5c979"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] Patient advocate
-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org07f5852)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="org422ed33"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="org83b23f2"></a>

## Time Management


<a id="orgdc63f1b"></a>

### Recurrences


<a id="org108bff1"></a>

### Calendaring


<a id="org87f329e"></a>

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


<a id="orgc5b3366"></a>

## Organization


<a id="org82df5a7"></a>

### Inventory Management

-   Pantry management


<a id="orgcc9d243"></a>

## Self-Discipline


<a id="orgb141189"></a>

### Self-Discipline State Machine


<a id="org5b877b2"></a>

## Transportation/Shopping/Errands


<a id="org479f992"></a>

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


<a id="org622f861"></a>

### Shopping

-   [ ] Receipts
    -   [ ] Parsers and storage for online store receipts
    -   [ ] Parsers for brick and mortar store receipts
        -   [ ] OCR for physical receipts
-   [X] Online order Tracker
    -   [X] Check against OFX export
-   [X] Online Delivery Tracker
-   [ ] Integration with pantry and inventory management


<a id="org07f5852"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="orga402a85"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org70ce4b9"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="org4a08f6e"></a>

# [Technical Overview](https://github.com/aindilis/flp/blob/main/Manual.md)


<a id="org064337b"></a>

# More Info


<a id="org8f2fcf2"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives.
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need.
-   Remembering that when you finish filling out some particular paperwork, to send a copy to your doctor.
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them.
-   Reminding you to work on your taxes, and to change your air filter.
-   Telling you that a particular plan of yours violates various moral and ethical constraints.
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through.


<a id="org04383f1"></a>

## User Base

-   Everyone
-   People with disabilities such as pervasive developmental disorders.
-   People in poverty who are one misstep from disaster.
-   People with unwieldy illnesses.
-   People who are homeless.


<a id="orgf215ec3"></a>

## Links

Here is the main FLP code site:

<https://github.com/aindilis/free-life-planner>

Here is the release of FRDCSA Panoply Git VM (containing older and stripped down versions of FRDCSA and Free Life Planner):

<https://github.com/aindilis/frdcsa-panoply-git-20200329>

Here is a story describing the Free Life Planner:

<https://frdcsa.org/~andrewdo/writings/homeless-story.html>

Here is the most recent talk on FLP.

<https://ontologforum.org/index.php/ConferenceCall_2022_04_20>

Here is the beginning of the release of FRDCSA (marking the Panoply release the official public release and deeming the last five years of work the "private" version of FRDCSA, and backporting from private to public as able):

<https://github.com/aindilis/frdcsa-installer>

Here is a recent talk from EmacsConf2019 about FRDCSA/FLP/Panoply:

<https://frdcsa.org/~andrewdo/frdcsa-emacsconf2019-final.webm>

Here is an independent codebase (no dependencies on FRDCSA) for interactive plan monitoring:

<https://github.com/aindilis/plan-monitor>

Here is some more recent work on the Interactive Execution Monitor:

<https://frdcsa.org/~andrewdo/iem2-2.mp4>

<https://frdcsa.org/~andrewdo/iem2-3.mp4>

Here is a video of an older, much smaller and simpler version of the FLP booting up (be careful, noisy):

<https://www.youtube.com/watch?v=t_dCAlf26LE>

Here is the beginning of a paper on FLP:

<https://frdcsa.org/~andrewdo/pioneer/wk1/flp.pdf>

and one on FRDCSA:

<https://frdcsa.org/~andrewdo/pioneer/wk1/frdcsa.pdf>

Here is a paper on the SPSE2 subsystem, an early planning system for FRDCSA which inspired parts of FLP:

<https://frdcsa.org/visual-aid/pdf/Temporal-Planning-and-Inferencing-for-Personal-Task-Management-with-SPSE2.pdf>

Here is a link to the financial planning submodule:

<https://github.com/aindilis/financial-planning#projected-transactions-for-florence-tucker>

Here is a link to the meal planning submodule:

<https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html>

Here is a video which shows some progress on the planner systems and also later the meal planner:

<https://www.youtube.com/watch?v=XZh_tHNboCI&t=15s>

Here are some earlier documents about the FLP:

<https://frdcsa.org/~andrewdo/writings/News-Challenge-2.html>

<https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanningCoachSoftware.html>

<https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanningCoachSoftwareUpdate.html>

<https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanner.html>

Here is the README for Panoply/FRDCSA:

<https://frdcsa.org/~andrewdo/writings/README.html>

Here is the project blog:

<https://facebook.com/frdcsa>

Here is the LogicMOO system mentioned in the EmacsConf video, which FLP draws heavily upon and intends to integrate with eventually:

<https://github.com/TeamSPoon/prologmud/wiki>

And here the design docs for LogicMOO:

<https://drive.google.com/drive/#folders/0B0QA19UX0ehlV1ZEaXEzc3hjTWM>


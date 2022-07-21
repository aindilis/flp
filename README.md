
# Table of Contents

1.  [The Free Life Planner](#orgc29beb9)
    1.  [THIS README IS UNDER CONSTRUCTION](#orgb262037)
2.  [Introduction](#org2bf4d3a)
    1.  [Purpose](#org20bf226)
    2.  [Sample use cases](#orgd817da3)
    3.  [Status](#orga92adac)
    4.  [Summary](#orgdd71c3f)
3.  [Overview](#org016ad35)
    1.  [Workflow Manager](#orgb9972a2)
    2.  [Health](#orge43a0d4)
        1.  [Exercise](#org18a71d5)
        2.  [Nutrition](#orgef2f24a)
        3.  [Doctor's Visits and Orders](#org616327c)
        4.  [Medications](#org771052e)
    3.  [Time Management](#org44e0ebb)
        1.  [Recurrences](#org3652abd)
        2.  [Calendaring](#orgb1a29c0)
        3.  [Temporal Planning, Scheduling, and Interactive Plan Execution Monitoring](#org42fe6d2)
    4.  [Organization](#org2d48086)
        1.  [Inventory Management](#orgd890991)
    5.  [Self-Discipline](#orgaae0554)
        1.  [Self-Discipline State Machine](#orgd951d61)
    6.  [Transportation/Shopping/Errands](#orgddc0eae)
        1.  [Transportation](#orgf1d2158)
        2.  [Shopping](#orge22bb36)
    7.  [Document Management](#org127ffcf)
    8.  [Financial Planner](#org0dc30df)
    9.  [Emergency Preparedness](#org0c2f246)
4.  [More Info](#org7942672)
    1.  [More Use Cases](#orgac4753a)
    2.  [User Base](#orgfbd67c9)
    3.  [Links](#org0bd4a18)


<a id="orgc29beb9"></a>

# The Free Life Planner


<a id="orgb262037"></a>

## THIS README IS UNDER CONSTRUCTION


<a id="org2bf4d3a"></a>

# Introduction


<a id="org20bf226"></a>

## Purpose

-   A life planner that helps
-   Automates almost every aspect of your life
-   Cognitive prosthetic for executive function


<a id="orgd817da3"></a>

## Sample use cases

-   [Homeless Story](https://frdcsa.org/~andrewdo/writings/homeless-story.html)
-   [Health Story](https://frdcsa.org/~andrewdo/writings/health-story.html)
-   [4.1](#orgac4753a)


<a id="orga92adac"></a>

## Status

-   Currently working to release the latest version onto GitHub
-   Interoperability between all systems


<a id="orgdd71c3f"></a>

## Summary

-   [Workflow Manager](#orgb9972a2) (Guides user through all other systems)
-   [Health](#orge43a0d4) (Exercise, Nutrition, Doctor's Visits & Orders, Medications)
    -   [Meal Planner](#orgbded447) (Nutrition, Taste, Cost, etc)
-   [Time Management](#org44e0ebb) (Recurrences, Calendaring, Planning, Scheduling and Plan Monitoring)
-   [Organization](#org2d48086) (Inventory Management)
-   [Self-Discipline](#orgaae0554) (State Machine)
-   [Paperwork](#org127ffcf) (Mail, Receipts, Doctors Orders etc)
-   [Financial](#org0dc30df) (Bills, Recurrences, Meal)
-   [Emergency Preparedness](#org0c2f246) ()


<a id="org016ad35"></a>

# Overview


<a id="orgb9972a2"></a>

## Workflow Manager

-   [ ] An overarching tool which pages through and helps complete all necessary tasks


<a id="orge43a0d4"></a>

## Health


<a id="org18a71d5"></a>

### Exercise

-   [X] Fitness Manager
-   [X] Alexa interface: "Alexa, tell David - Andrew did his morning exercises"


<a id="orgef2f24a"></a>

### Nutrition

1.  Meal Planner

    -   [ ] [Meal Planning Resources](https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html)
    -   [ ] Improves nutrition and taste
    -   [ ] Reduces cost and prep time 4X
    -   [ ] [Self-Discipline](#orgaae0554) for dieting
    -   [ ] Specialty diets (medical or ethical)
    -   [ ] [Show pictures here]


<a id="org616327c"></a>

### Doctor's Visits and Orders

-   [ ] Symptom and condition tracker
-   [ ] Patient advocate
-   [ ] Tracking visits
-   [ ] [Following through on instructions](#org127ffcf)
-   [ ] For when a physician is unavailable
    -   [ ] First aid course of action system


<a id="org771052e"></a>

### Medications

-   [ ] Refill Tracker
-   [ ] Medication Management


<a id="org44e0ebb"></a>

## Time Management


<a id="org3652abd"></a>

### Recurrences


<a id="orgb1a29c0"></a>

### Calendaring


<a id="org42fe6d2"></a>

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


<a id="org2d48086"></a>

## Organization


<a id="orgd890991"></a>

### Inventory Management

-   Pantry management


<a id="orgaae0554"></a>

## Self-Discipline


<a id="orgd951d61"></a>

### Self-Discipline State Machine


<a id="orgddc0eae"></a>

## Transportation/Shopping/Errands


<a id="orgf1d2158"></a>

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


<a id="orge22bb36"></a>

### Shopping

-   [ ] Receipts
    -   [ ] Parsers and storage for online store receipts
    -   [ ] Parsers for brick and mortar store receipts
        -   [ ] OCR for physical receipts
-   [X] Online order Tracker
    -   [X] Check against OFX export
-   [X] Online Delivery Tracker
-   [ ] Integration with pantry and inventory management


<a id="org127ffcf"></a>

## Document Management

-   [-] [Document Management System](https://frdcsa.org/~andrewdo/projects/paperless-office/)
    -   [X] Scan and OCR all paperwork
    -   [-] Integration of document-related tasks into Workflow Manager
        -   [X] [Extract date and time references](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg) (w/ TIMEX3)
        -   [ ] Integrate with workflow
    -   [X] Backup w/ git
    -   [X] Export selected documents and folders


<a id="org0dc30df"></a>

## Financial Planner

-   [-] [Financial Planning](https://github.com/aindilis/financial-planning#readme)
    -   [X] Quickly forecast finances almost indefinitely into the future
    -   [ ] Metaplanners help develop contingency plans for different financial problems
        -   [ ] Unexpected delays
        -   [ ] Overcharges and unapproved charges
        -   [ ] Cash flow problems and hardships


<a id="org0c2f246"></a>

## Emergency Preparedness

-   [ ] [Personal Emergency Management](https://frdcsa.org/~andrewdo/ontolog-20220410-reduced.mp4)


<a id="org7942672"></a>

# More Info


<a id="orgac4753a"></a>

## More Use Cases

-   Remembering to take the trash out before the trash truck arrives.
-   Getting an automatic notification to stock up on groceries before a predicted storm hits, including the list of the groceries you need.
-   Remembering that when you finish filling out some particular paperwork, to send a copy to your doctor.
-   Remember what the doctors instructions were, in a paperless office with Machine Comprehension software, and helping you to conform to them.
-   Reminding you to work on your taxes, and to change your air filter.
-   Telling you that a particular plan of yours violates various moral and ethical constraints.
-   Generating a complex monthly financial plan with contingencies for unexpected expenses and if certain income doesn't come through.


<a id="orgfbd67c9"></a>

## User Base

-   Everyone
-   People with disabilities such as pervasive developmental disorders.
-   People in poverty who are one misstep from disaster.
-   People with unwieldy illnesses.
-   People who are homeless.


<a id="org0bd4a18"></a>

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


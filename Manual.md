
# Table of Contents

1.  [The Free Life Planner](#orgbbb463c)
2.  [Technical Overview](#org30f722f)
    1.  [Workflow Manager](#org2d47d0b)
    2.  [Health](#org209bc1a)
        1.  [Medications](#org59adbaf)
    3.  [Time Management](#orgc8aca85)
        1.  [Recurrences](#org903f754)
        2.  [Calendaring](#orge4ba15d)
        3.  [Planning, Scheduling and Execution](#orgfe5d775)
    4.  [Organization](#orgdf6aa6b)
        1.  [Inventory Management](#orgf430ffc)
    5.  [Self-Discipline](#orge233eab)
        1.  [Self-Discipline State Machine](#org6233c6f)
    6.  [Transportation/Shopping/Errands](#orgd95ad9b)
    7.  [Document Management](#org8a04e42)
    8.  [Financial Planner](#org50fd068)
    9.  [Emergency Preparedness](#orgbabca63)
3.  [Technologies Most Used](#org4147605)


<a id="orgbbb463c"></a>

# The Free Life Planner


<a id="org30f722f"></a>

# Technical Overview


<a id="org2d47d0b"></a>

## Workflow Manager


<a id="org209bc1a"></a>

## Health


<a id="org59adbaf"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="orgc8aca85"></a>

## Time Management


<a id="org903f754"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orge4ba15d"></a>

### Calendaring

1.  Integrations

    -   [X] Import from
        -   [X] Org-agenda
        -   [X] SPSE2
        -   [X] Google Calendar
        -   [X] ICS
    -   [ ] Export to
        -   [ ] Org-agenda
        -   [ ] SPSE2
        -   [ ] Google Calendar
        -   [ ] ICS


<a id="orgfe5d775"></a>

### Planning, Scheduling and Execution

1.  Planners

    -   [X] [PDDL](https://en.wikipedia.org/wiki/Planning_Domain_Definition_Language) planning
        -   [X] CLG, Colin2<sub>CLP</sub>, HSPS, LPG, LPG<sub>TD</sub><sub>1</sub><sub>4</sub>, MIPS<sub>XXL</sub>, Metric<sub>FF</sub>, OPTIC<sub>CLP</sub>, SGPlan<sub>522</sub>
            -   [X] [More than 200 PDDL life planning domains](https://github.com/aindilis/verber/tree/master/data-git/worldmodel/templates)
        -   [X] [SPSE2](https://frdcsa.org/visual-aid/pdf/Temporal-Planning-and-Inferencing-for-Personal-Task-Management-with-SPSE2.pdf)
    -   [X] Contingent planning
        -   [X] DNFct
            -   [X] More than 10 contingent life planning domains
    -   [ ] Behavior tree reactive planning
        -   [ ] Plan Monitor
            -   [ ] Execution of generated (PDDL/AgentSpeak(L)/BT/etc) plans (similar to [this](https://arxiv.org/pdf/2101.01964.pdf))
    -   [X] BDI Agent
        -   [X] Jason/AgentSpeak(L) w/ SWIPL integration
            -   [X] [More than 10 BDI domains](https://github.com/aindilis/jason/tree/master/examples)

2.  Additional Planning System

    -   [ ] Do system (todo lists)
    -   [ ] Do-Convert system
    -   [ ] Factored planning
    -   [X] Planning systems
        -   [X] Verber
        -   [X] SPSE2
        -   [X] SPSE2-Formalog
    -   [-] Digital twin
        -   [X] World State Monitor
        -   [X] Fitness Manager
        -   [ ] Checklists
    -   [ ] Kanban
    -   [ ] Goalban
    -   [X] User Agenda (for recurrences)
    -   [X] Habit tracker
    -   [ ] Resource Manager (plans over inventory/etc)
        -   [ ] Productivity Requirements
    -   [ ] Subsystem monitoring
        -   [ ] Mission Control
        -   [ ] Normal Form
    -   [-] Gamification
        -   [X] Score
        -   [ ] Rewards/Penalties
        -   [X] Manager

3.  Some domains

    -   [ ] Plan cycles (cycle)
    -   [X] Standard domain library (BASEKB)
        -   [X] agent, biomaintenance, chores, deontic, economic, food, hygiene, misc, security, space, tool, work
    -   [ ] Household emergency preparedness
        -   [ ] Planning ahead for inclement weather
            -   [ ] e.g. Stock up on groceries before a major storm hits


<a id="orgdf6aa6b"></a>

## Organization


<a id="orgf430ffc"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="orge233eab"></a>

## Self-Discipline


<a id="org6233c6f"></a>

### Self-Discipline State Machine


<a id="orgd95ad9b"></a>

## Transportation/Shopping/Errands


<a id="org8a04e42"></a>

## Document Management


<a id="org50fd068"></a>

## Financial Planner


<a id="orgbabca63"></a>

## Emergency Preparedness


<a id="org4147605"></a>

# Technologies Most Used

-   [X] SWI-Prolog
    -   Julian time library
-   [X] Perl    
    -   [X] YASWI Perl<->SWI-Prolog Interface
    -   [X] Catalyst CMS
        -   [X] ShinyCMS
-   [X] Java
    -   [X] JavaPengines (Java<->SWI-Prolog)
    -   [X] Jason/AgentSpeak(L)
        -   [X] JPL Java<->SWI-Prolog
    -   [X] Alexa voice skill interface
-   [X] PDDL 2.2 temporal metric planning
    -   [X] LPG-td-1.0
    -   [X] OPTIC<sub>CLP</sub>


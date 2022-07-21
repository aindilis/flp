
# Table of Contents

1.  [The Free Life Planner](#org8ef0ecd)
2.  [Technical Overview](#orga871ea2)
    1.  [Workflow Manager](#orgb6d1c3e)
    2.  [Health](#orgcc64572)
        1.  [Medications](#org7f753e2)
    3.  [Time Management](#org85e4a54)
        1.  [Recurrences](#org44e34d5)
        2.  [Calendaring](#org06fe09e)
        3.  [Planning, Scheduling and Execution](#org860cbba)
    4.  [Organization](#org9e8944c)
        1.  [Inventory Management](#orgcd45152)
    5.  [Self-Discipline](#orgbaf9533)
        1.  [Self-Discipline State Machine](#orgf12b613)
    6.  [Transportation/Shopping/Errands](#org2333ab7)
    7.  [Document Management](#org43cf43c)
    8.  [Financial Planner](#org10a8d5b)
    9.  [Emergency Preparedness](#org17db430)
3.  [Technologies Most Used](#org07ad87b)


<a id="org8ef0ecd"></a>

# The Free Life Planner


<a id="orga871ea2"></a>

# Technical Overview


<a id="orgb6d1c3e"></a>

## Workflow Manager


<a id="orgcc64572"></a>

## Health


<a id="org7f753e2"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org85e4a54"></a>

## Time Management


<a id="org44e34d5"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org06fe09e"></a>

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


<a id="org860cbba"></a>

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


<a id="org9e8944c"></a>

## Organization


<a id="orgcd45152"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="orgbaf9533"></a>

## Self-Discipline


<a id="orgf12b613"></a>

### Self-Discipline State Machine


<a id="org2333ab7"></a>

## Transportation/Shopping/Errands


<a id="org43cf43c"></a>

## Document Management


<a id="org10a8d5b"></a>

## Financial Planner


<a id="org17db430"></a>

## Emergency Preparedness


<a id="org07ad87b"></a>

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


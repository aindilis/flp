
# Table of Contents

1.  [The Free Life Planner](#org9012e08)
2.  [Technical Overview](#org145db92)
    1.  [Workflow Manager](#org4dc4465)
    2.  [Health](#org3157153)
        1.  [Medications](#org01588f6)
    3.  [Time Management](#org245d040)
        1.  [Recurrences](#orgd356776)
        2.  [Calendaring](#org242fb28)
        3.  [Planning, Scheduling and Execution](#orga6eae61)
    4.  [Organization](#org2d71320)
        1.  [Inventory Management](#org10d9bd7)
    5.  [Self-Discipline](#orgf3c0364)
        1.  [Self-Discipline State Machine](#orgcc1c2a0)
    6.  [Transportation/Shopping/Errands](#orge126ac4)
    7.  [Document Management](#org26dbb48)
    8.  [Financial Planner](#org1e1d8f6)
    9.  [Emergency Preparedness](#org33ae556)


<a id="org9012e08"></a>

# The Free Life Planner


<a id="org145db92"></a>

# Technical Overview


<a id="org4dc4465"></a>

## Workflow Manager


<a id="org3157153"></a>

## Health


<a id="org01588f6"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org245d040"></a>

## Time Management


<a id="orgd356776"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org242fb28"></a>

### Calendaring

1.  Integrations

    -   [ ] Google Calendar
    -   [ ] Org-agenda
    -   [ ] SPSE2
    -   [ ] ICS import


<a id="orga6eae61"></a>

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


<a id="org2d71320"></a>

## Organization


<a id="org10d9bd7"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="orgf3c0364"></a>

## Self-Discipline


<a id="orgcc1c2a0"></a>

### Self-Discipline State Machine


<a id="orge126ac4"></a>

## Transportation/Shopping/Errands


<a id="org26dbb48"></a>

## Document Management


<a id="org1e1d8f6"></a>

## Financial Planner


<a id="org33ae556"></a>

## Emergency Preparedness


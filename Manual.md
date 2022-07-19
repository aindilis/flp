
# Table of Contents

1.  [The Free Life Planner](#org262574a)
2.  [Technical Overview](#org1e840cd)
    1.  [Health](#orgb809c2f)
        1.  [Medications](#org5183f97)
    2.  [Time Management](#org04b09cb)
        1.  [Recurrences](#orgddace79)
        2.  [Calendaring](#org8836c30)
        3.  [Planning, Scheduling and Execution](#orgb8fdf17)
        4.  [Additional Planning System](#org11e8083)
    3.  [Organization](#org8ea42a3)
        1.  [Inventory Management](#org59fea66)
    4.  [Self-Discipline](#org650f58b)
        1.  [Self-Discipline State Machine](#orgbeff58b)
    5.  [Transportation/Shopping/Errands](#org93d51b5)
    6.  [Document Management](#org181d049)
    7.  [Financial Planner](#org9809a14)
    8.  [Emergency Preparedness](#org4c3b5d5)


<a id="org262574a"></a>

# The Free Life Planner


<a id="org1e840cd"></a>

# Technical Overview


<a id="orgb809c2f"></a>

## Health


<a id="org5183f97"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org04b09cb"></a>

## Time Management


<a id="orgddace79"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="org8836c30"></a>

### Calendaring

1.  Integrations

    -   [ ] Google Calendar
    -   [ ] Org-agenda
    -   [ ] SPSE2
    -   [ ] ICS import


<a id="orgb8fdf17"></a>

### Planning, Scheduling and Execution

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


<a id="org11e8083"></a>

### Additional Planning System

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


<a id="org8ea42a3"></a>

## Organization


<a id="org59fea66"></a>

### Inventory Management

-   Pantry management


<a id="org650f58b"></a>

## Self-Discipline


<a id="orgbeff58b"></a>

### Self-Discipline State Machine


<a id="org93d51b5"></a>

## Transportation/Shopping/Errands


<a id="org181d049"></a>

## Document Management


<a id="org9809a14"></a>

## Financial Planner


<a id="org4c3b5d5"></a>

## Emergency Preparedness


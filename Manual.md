
# Table of Contents

1.  [The Free Life Planner](#orgc56f83d)
2.  [Technical Overview](#org35868e7)
    1.  [Workflow Manager](#orgc4302dd)
    2.  [Health](#org6142d38)
        1.  [Medications](#org7e4e4f5)
    3.  [Time Management](#org1d189e3)
        1.  [Recurrences](#orgd82e6a8)
        2.  [Calendaring](#orgfdcd859)
        3.  [Planning, Scheduling and Execution](#org4a38d69)
        4.  [Additional Planning System](#org7f766e6)
    4.  [Organization](#org731b684)
        1.  [Inventory Management](#org5bd0b5d)
    5.  [Self-Discipline](#org3a7ae2f)
        1.  [Self-Discipline State Machine](#orga761440)
    6.  [Transportation/Shopping/Errands](#orgcb05a26)
    7.  [Document Management](#org1c6c200)
    8.  [Financial Planner](#orge299bc9)
    9.  [Emergency Preparedness](#org3ce1038)


<a id="orgc56f83d"></a>

# The Free Life Planner


<a id="org35868e7"></a>

# Technical Overview


<a id="orgc4302dd"></a>

## Workflow Manager


<a id="org6142d38"></a>

## Health


<a id="org7e4e4f5"></a>

### Medications

-   [ ] [PDDL+ Medication Management](https://github.com/fareskalaboud/PDDLPlusBenchmarkDomains)


<a id="org1d189e3"></a>

## Time Management


<a id="orgd82e6a8"></a>

### Recurrences

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).


<a id="orgfdcd859"></a>

### Calendaring

1.  Integrations

    -   [ ] Google Calendar
    -   [ ] Org-agenda
    -   [ ] SPSE2
    -   [ ] ICS import


<a id="org4a38d69"></a>

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


<a id="org7f766e6"></a>

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


<a id="org731b684"></a>

## Organization


<a id="org5bd0b5d"></a>

### Inventory Management

<img src="https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg" width="250px">

-   Pantry management


<a id="org3a7ae2f"></a>

## Self-Discipline


<a id="orga761440"></a>

### Self-Discipline State Machine


<a id="orgcb05a26"></a>

## Transportation/Shopping/Errands


<a id="org1c6c200"></a>

## Document Management


<a id="orge299bc9"></a>

## Financial Planner


<a id="org3ce1038"></a>

## Emergency Preparedness


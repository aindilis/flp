
# Table of Contents

1.  [The Free Life Planner](#org7100580)
    1.  [Summary of Some Areas that the Free Life Planner helps with:](#orgbed4b18)
    2.  [More In-Depth on Some of These Systems](#orgecda0ff)
        1.  [Meal-Planner](#org778abc0)
        2.  [Transportation/Shopping/Errands](#org730ae04)
        3.  [Document Management System)](#orgc8c49b3)
        4.  [Recurrence System](#org510eee9)


<a id="org7100580"></a>

# The Free Life Planner


<a id="orgbed4b18"></a>

## Summary of Some Areas that the Free Life Planner helps with:

-   Health (Doctors Visits & Orders, Paperwork, Medications)

-   Time Management (Recurrences, Calendaring)

-   Organization (????/????)

-   Sequencing (SPSE2/Verber/FLP/etc)

-   Meal Planning (Nutrition, Taste, Cost, etc)

-   Paperwork (Mail, Receipts, Doctors Orders etc)

-   Financial (Bills, Recurrences, Meal)


<a id="orgecda0ff"></a>

## More In-Depth on Some of These Systems


<a id="org778abc0"></a>

### Meal-Planner


<a id="org730ae04"></a>

### Transportation/Shopping/Errands


<a id="orgc8c49b3"></a>

### Document Management System)


<a id="org510eee9"></a>

### Recurrence System

How to schedule something for the last day of every month:

    hasRecurrenceSpec(critical(closeTheBooks),onDate(YMD),[9:0:0,13:0:0,17:0:0]) :-
    	deltaTime([_Year-_Month-1],days(-1),YMD).

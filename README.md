# ucc-et
Dataset for UCC Examination Timetabling 2019 semester 1.

This dataset has been used in the following publication:
Begum Genc and Barry O'Sullivan, A Two-Phase Constraint Programming Model for Examination Timetabling at University College Cork, the 26th International Conference on Principles and Practice of Constraint Programming (CP 2020).

Each line that starts with 'c' denotes a comment line 

<b>Files</b>

<b>exams</b>: duration information of each module

<b>exams-coschedule</b>: group ids of exams that need to be coscheduled

<b>exams-to-students</b>: registration file containing information about which student is registered to which module

<b>periods_2019_sem1</b>: available time-slots for the examination periods including dates, starting times, duration of the time-slot and penalty.

<b>specialRequests_sem1_2019</b>: exact time-slot to sit an exam (EXACT), exams requested to be scheduled outside of the examination period (EXCLUDE), exams to be scheduled before a certain time-slot (BEFORE), exams to be held in a specific venue (VENUE).

<b>studentTag</b>: the special-need tag of students (if any)

<b>specialNeedVenues_sem1_2019</b>: venues used by the special-need students. The list of venues follow the special-need tag. Each venue line contains the name of the venue, capacity, penalty.

<b>venues_all_2019_sem1</b>: the main venues that are available, their capacities, and penalty.

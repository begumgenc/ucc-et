# ucc-et
<h1>Dataset for UCC Examination Timetabling 2019 semester 1</h1>

This dataset has been used in the following publication:
Begum Genc and Barry O'Sullivan, <b>A Two-Phase Constraint Programming Model for Examination Timetabling at University College Cork</b>, <i>the 26th International Conference on Principles and Practice of Constraint Programming (CP 2020)</i>.

Each line that starts with 'c' denotes a comment line 

<h2>Files</h2>

<ul>

<li> <b><i>exams</i></b>: duration information of each module. </li>

<li> <b><i>exams-coschedule</i></b>: group ids of exams that need to be coscheduled. </li>

<li> <b><i>exams-to-students</i></b>: registration file containing information about which student is registered to which module. </li>

<li> <b><i>periods_2019_sem1</i></b>: available time-slots for the examination periods including dates, starting times, duration of the time-slot and penalty. </li>

<li> <b><i>specialRequests_sem1_2019</i></b>: exact time-slot to sit an exam (EXACT), exams requested to be scheduled outside of the examination period (EXCLUDE), exams to be scheduled before a certain time-slot (BEFORE), exams to be held in a specific venue (VENUE). </li>

<li> <b><i>studentTag</i></b>: the special-need tag of students (if any). </li>

<li> <b><i>specialNeedVenues_sem1_2019</i></b>: venues used by the special-need students. The list of venues follow the special-need tag. Each venue line contains the name of the venue, capacity, penalty. </li>

<li> <b><i>venues_all_2019_sem1</i></b>: the main venues that are available, their capacities, and penalty. </li>

<ul>

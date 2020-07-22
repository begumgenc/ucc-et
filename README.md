# ucc-et
UCC Examination Timetabling
Each line that starts with 'c' denotes a comment line 

Files
exams: duration information of each module
exams-coschedule: group ids of exams that need to be coscheduled
exams-to-students: registration file containing information about which student is registered to which module
periods_2019_sem1: available time-slots for the examination periods including dates, starting times, duration of the time-slot and penalty.
specialRequests_sem1_2019: exact time-slot to sit an exam (EXACT), exams requested to be scheduled outside of the examination period (EXCLUDE), exams to be scheduled before a certain time-slot (BEFORE), exams to be held in a specific venue (VENUE).
studentTag: the special-need tag of students (if any)
specialNeedVenues_sem1_2019: venues used by the special-need students. The list of venues follow the special-need tag. Each venue line contains the name of the venue, capacity, penalty.
venues_all_2019_sem1: the main venues that are available, their capacities, and penalty.

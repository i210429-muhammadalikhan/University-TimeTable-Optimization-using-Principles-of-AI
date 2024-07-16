# University-TimeTable-Optimization-using-Principles-of-AI
All the below requirements are fulfilled in the code.

These are the constraints that need to be implemented in your project completely and without
any compromises.
• Classes can only be scheduled in free classrooms.
• A classroom should be big enough to accommodate the section. There should be two
categories of classrooms: classroom (60) and large hall (120).
• A professor should not be assigned two different lectures at the same time.
• The same section cannot be assigned to two different rooms at the same time.
• A room cannot be assigned for two different sections at the same time.
• No professor can teach more than 3 courses.
• No section can have more than 5 courses in a semester.
• Each course would have two lectures per week not on the same or adjacent days.
• Lab lectures should be conducted in two consecutive slots.

• 15 mins breaks allowed between consecutive classes to ensure that there is sufficient
time for transitions between classes.
Soft Constraints:
These are the constraints where some compromise can be expected. Hence, you are expected
to implement them as best as possible.
• All the theory classes should be taught in the morning session and all the lab sessions
should be done in the afternoon session.
• Teachers/students may be facilitated by minimizing the number of floors they have to
traverse. That is, as much as possible, scheduled classes should be on the same floor for
either party.
• A class should be held in the same classroom across the whole week.
• Teachers may prefer longer blocks of continuous teaching time to minimize
interruptions and maximize productivity except when the courses are different.
Other Details:
• The timetable should cover all the 5 days of the week with the morning session from
8:30 – 2:30 and the afternoon session from 2:30 – 5:30.
• The chromosomes should be binary encoded with the following information:
o Course, Theory/Lab, Section, Section-Strength, Professor, First-lecture-day,

First- lecture-timeslot, First-lecture-room, First-lecture-room-size, Second-
lecture-day, Second-lecture-timeslot, Second-lecture-room, Second-lecture-
room-size

• The fitness function should be an inverse or negative of the sum of all the
conflicts/clashes.

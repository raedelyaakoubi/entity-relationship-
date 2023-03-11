# entity-relationship
In this example, we have the following entities and their attributes:

Gymnasium: identified by a gymnasium_id, with attributes for name, address, and telephone number.
Member: identified by a member_id, with attributes for last_name, first_name, address, date_of_birth, and gender.
Session: identified by a session_id, with attributes for type_of_sport and schedule.
Coach: identified by a coach_id, with attributes for last_name, first_name, age, and specialty.
We also have the following relationships:

Registration: connects Member to Gymnasium in a many-to-one relationship, indicating that a member can register at one gymnasium and each gymnasium can have many members registered.
Attendance: connects Member to Session in a many-to-many relationship, indicating that a member can attend many sessions and each session can have many members attending.
Leadership: connects Coach to Session in a many-to-many relationship, indicating that a coach can lead many sessions and each session can have many coaches leading.

tables we have made ***all tables need created_at
1. aircraft - (NONE OF THESE FIELDS WILL CHANGE SO WE *MIGHT* NOT NEED UPDATED AT)
    id
    name
    man_type
    tail_number
    created_at 
    aircraft_sel
    foreign key userID

2. flights
    id
    name
    created_at
    foreign key userID
    pic
    day
    night


missing tables
3. instructors inheret from user
4. billing
5. settings
(6. airports) can pull from API

relationships
instructor can take a flight
1 instuctor: many flights
1flight: only 1 instructor
a user can have many flights
a instructor can fly many planes
a plane doesn't fly itself

billing
1st month free (trial)
monthly billing
premium features - TO-DO

settings - TODO
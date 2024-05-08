ER Diagram for my Service Application

1. **User-Student** --> One-to-One on the UserId field. Each user may have have exactly zero or one student profile associated with it, and each student profile belongs to only one user. 
2. **Student-School** --> Many-to-One on the schoolId field. Each student is associated with one school, but each school can have multiple students.
3. **User-School** --> Many-to-One on the schoolId field. Each user (admin or student) is associated with one school, but each school can have multiple users.
4. **School-ServiceEvent** --> One-to-Many on the schoolId field. Each school can have multiple service events conducted by its students.
5. **Student-ServiceEvent** --> One-to-Many on the studentId field. Each student can create multiple service events, but each service event is associated with only one student.
6. **ServiceEvent-EventComments** --> One-to-Many on the eventId field. Each service event can have multiple comments associated with it.


![Blank diagram](https://github.com/adamnestor/ServiceApplication/assets/79426455/2cdc7069-5eae-4de9-bdbc-41858d442cdf)


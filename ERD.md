Below is the first version of my ER Diagram

1. User-Student --> One-to-One on the <UserId> field
2. Student-School --> Many-to-One on the <schoolId> field
3. User-School --> Many-to-One on the <schoolId> field
4. School-ServiceEvent --> One-to-Many on the <schoolId> field
5. Student-ServiceEvent --> One-to-Many on the <studentId> field
6. ServiceEvent-EventComments --> One-to-Many on the <eventId> field

![ServiceERD](https://github.com/adamnestor/ServiceApplication/assets/79426455/a54d7511-7789-4279-80c3-48d22e95e9ef)


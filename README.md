# CS 255 Portfolio: DriverPass System Analysis and Design

# Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

The client was DriverPass, a company that wants to help people pass their driving tests by offering online practice tests along with scheduled on-the-road driving lessons with instructors. The owner, Liam, explained that many students fail their driving tests because they lack good training, and he wanted a system that could take a student from signing up, to studying, to booking lessons. DriverPass asked for a web-based system that students could use to create accounts, take practice tests, reserve driving lessons with a specific instructor and vehicle, and track their progress, while giving the owner and staff the ability to manage reservations, packages, and user activity, and to receive reports on system use. The system also had to run on the cloud so DriverPass would not have to maintain its own servers, and it had to protect customer data and support offline access to reports.

# What did you do particularly well?

I think I did best at translating the client's interview into clear, organized requirements. I separated the business requirements from the functional and nonfunctional ones, and I identified the different user roles, such as student, secretary, IT officer, and owner, and what each of them needs from the system. I also did well at building the UML diagrams in Lucidchart, including the use case, activity, sequence, and class diagrams, because they let me show the same system from several angles and check that the design held together.

# If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would revise the system design document, specifically the class and sequence diagrams. I would add more detail to the class diagram by including attributes, methods, and relationships such as how a reservation connects a student, an instructor, and a vehicle, and I would add sequence diagrams for more scenarios, like canceling or rescheduling a lesson. I would also go back to the client with questions about parts of the interview that were vague, like how DriverPass wants to handle cancellation policies and package changes, so the design reflects what they actually want and not my assumptions.

# How did you interpret the user's needs and implement them into your system design? Why is it so important to consider the user's needs when designing?

I read through the interview transcript and picked out the pain points and wishes the client and future users described, then turned each one into a specific requirement. For example, because the client wanted students to book lessons and the owner wanted to monitor who made changes to reservations, I included reservation functionality and activity tracking in the design, and the use case diagram showed which role could do what. Considering the user's needs matters because software that does not fit how people actually work goes unused, no matter how well it is built. It also saves money, since misunderstandings found during design are far cheaper to fix than ones found after the system is built.

# How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

I start by understanding the problem and the people involved before thinking about technology. I gather requirements through interviews and documents, organize them, and confirm them with the client, and then I model the system with diagrams so everyone can see the design before any code is written. In the future I would keep using UML diagrams, requirement lists that separate functional from nonfunctional needs, and tools like Gantt charts for planning the schedule. I would also use an iterative approach, checking in with the client regularly and refining the design as I learn more, instead of trying to get everything right in a single pass.

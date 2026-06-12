> **Computer Science Student | SNHU CS-499 Capstone**
> 
> I am completing my Bachelor of Science in Computer Science at Southern New Hampshire University and this is part of my CS-499 Capstone. I came into this program as an auto service technician and transitioned into contact center technology through a professional development bootcamp, where I have been working as a Genesys Cloud platform engineer and DevOps professional ever since. This ePortfolio is the final deliverable of the capstone and brings together three enhanced artifacts that demonstrate my growth across software engineering, algorithms and data structures, and databases throughout the program.
 
---
 
## Professional Self-Assessment
 
I came into the Computer Science program at Southern New Hampshire University as an auto service technician. I transitioned into contact center technology through a professional development bootcamp and am currently working as a Genesys Cloud platform administrator and DevOps engineer while completing my Bachelor of Science degree. I enrolled in this program to formalize the skills I am building on the job, close the gaps in my foundational knowledge, and position myself to grow into technical architect and software engineering roles. Building this ePortfolio in CS-499 has given me the opportunity to see how much ground I have covered and to produce a concrete body of work that represents that growth.
 
The ePortfolio brings together three enhanced artifacts that demonstrate my skills across the core areas of computer science: software design and engineering, algorithms and data structures, and databases. Each artifact started as a completed course project with real limitations, and each enhancement was designed to solve those limitations using skills I have developed throughout the program.
 
**Collaborating in a Team Environment**
 
The most direct experience I have with collaborative software development comes from my day-to-day work on the Genesys Cloud platform team. My team runs one-week Agile sprints with a Kanban board in Jira, and every piece of work follows that cycle from start to finish. I write Jira stories with user voice, acceptance criteria, and subtasks before writing any code, and completed work is documented in shared runbooks and sprint review presentations. CS-250 gave me the academic grounding behind what I was already doing in practice. The course simulated a full Agile and Scrum development cycle and helped me understand the reasoning behind sprint planning, backlog refinement, and retrospectives. The CS-250 artifact I selected for this capstone started as a sprint deliverable in that simulation, and the fact that I have been able to enhance it into a full stack MongoDB application reflects exactly the kind of incremental improvement Agile is designed to support.
 
**Communicating with Stakeholders**
 
Communicating technical work to a non-technical audience is something I do regularly in my professional role. When I build automation scripts or design routing solutions in Genesys Cloud, I write technical design documents and sprint review presentations that explain what was done and why, without assuming the audience knows the technical details. CS-499 reinforced this through the narrative requirement for each artifact. Writing a narrative that explains what you built, why it matters, and what you learned is harder than writing the code itself, and it is a skill that applies directly to every design document and technical proposal I write at work.
 
**Data Structures and Algorithms**
 
CS-260 gave me the theoretical foundation for the data structure knowledge I had been building intuitively on the job. For the Algorithms and Data Structures artifact, I took the CS-320 contact service project and added a PriorityQueue to TaskService and a TreeMap to AppointmentService, documenting the Big-O trade-offs for each decision. I now think about data structure selection as a design decision with real consequences, not just an implementation detail.
 
**Software Engineering and Database**
 
The CS-330 software engineering enhancement was the most technically demanding work in this capstone. I refactored an 800-line hardcoded rendering function using the Factory and Observer design patterns, added an external configuration file, and migrated the project from Windows to Mac using CMake and Homebrew. The CS-250 database enhancement grew into a full stack application: MongoDB stores destination documents, a Python Flask REST API handles CRUD operations and analytical queries, an HTML and JavaScript web UI provides browser-based management with destination photo cards, and the original Java Swing UI reads from a JSON file the Python layer exports automatically.
 
**Security**
 
CS-405 Secure Coding is directly reflected in every artifact. Input validation runs at every boundary in the CS-250 Flask API before any MongoDB operation executes. The SceneConfig class in CS-330 validates configuration entries before use. In my professional work, this mindset applies to API authentication, data handling in contact center automation scripts, and the security topics covered in the Genesys Cloud Architect certification path.
 
**How the Artifacts Fit Together**
 
The three artifacts demonstrate the full range of skills a computer science professional needs. CS-330 shows reasoning about architecture and design patterns. CS-320 shows data structure trade-off analysis. CS-250 shows full stack development from database schema through REST API to web interface. Together they reflect what I have learned across my coursework and through my professional work in contact center technology. I am completing this program with the theoretical foundation and the portfolio to back up the skills I have been building in practice. My goal is to continue building on this in a DevOps architect or software engineering role where the combination of platform knowledge, automation experience, and computer science fundamentals I have developed will matter most.
 
[Download Full Self-Assessment (Word)](narratives/CS499_Professional_Self_Assessment.docx)
 
---

## Code Review

My code review video walks through the three artifacts I selected for enhancement, identifies the weaknesses in the original code, and explains the planned improvements for each category.

▶ [Watch the Code Review on YouTube](https://youtu.be/01WMzNuSs10)


---

## Enhancement 1: Software Design and Engineering

**Artifact:** CS-330 Computational Graphics and Visualization (C++ / OpenGL)

The original project rendered a 3D tabletop scene with a coffee mug, apple, notebook, and pen. The `RenderScene()` function had so many lines of hardcoded object data with no structure. I enhanced it by applying the Factory and Observer design patterns, creating an external `scene.cfg` configuration file so the scene can be changed without recompiling, and migrating the project from Windows Visual Studio to Mac VS Code using CMake and Homebrew.

- [View Enhancement 1 Narrative](narratives/Milestone 2 Software Design and Engineering.docx)
- [View Source Code](https://drive.google.com/file/d/1IZhRedjYR_8ZXIK3TUdUYayhcfrnhizB/view?usp=drive_link)

---

## Enhancement 2: Algorithms and Data Structures

**Artifact:** CS-320 Software Testing and Automation (Java / JUnit / Maven)

The original project contained three service classes each backed by a plain HashMap. I enhanced it by adding a `priority` field to the Task model and implementing a `PriorityQueue` in TaskService to return tasks sorted from most to least urgent. I also added a `TreeMap<Date, Appointment>` to AppointmentService that keeps appointments in chronological order automatically. All three services were unified into a single Maven project with a consistent package structure and a `Main.java` class that demonstrates the sorting behavior at runtime.

- [View Enhancement 2 Narrative](narratives/Milestone 3 Algorithms and Data Structures.docx)
- [View Source Code](artifacts/CS-320-Software-Testing-and-Automation.zip)

---

## Enhancement 3: Databases

**Artifact:** CS-250 Software Development Lifecycle (Java Swing / MongoDB)

The original project displayed five travel destinations in a Java Swing list with all data hardcoded directly in the source file. I enhanced it by building a full stack MongoDB application. Destination records are stored as documents in a MongoDB collection. A Python Flask REST API handles all CRUD operations and two analytical queries. An HTML and JavaScript web UI lets users view, add, edit, and delete destinations through a browser with destination photos displayed on each card. The Java Swing UI reads from a JSON file the Python layer exports automatically after every write, so both interfaces stay in sync. This enhancement satisfies both the MongoDB interface with HTML and JavaScript requirement and the full stack with a different programming language requirement.

- [View Enhancement 3 Narrative](narratives/Milestone 4 Databases.docx)
- [View Source Code](artifacts/CS250-Databases.zip)

---

*Computer Science | DevOps | Cloud Platform Engineering*

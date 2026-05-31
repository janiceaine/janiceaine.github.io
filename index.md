> **Computer Science Student | SNHU CS-499 Capstone**
> Bridging contact center technology and software engineering through hands-on development in C++, Java, and databases.

---

I am a Computer Science student at Southern New Hampshire University completing my Bachelor of Science degree. I came into this program as an auto service technician and transitioned into a career in contact center technology through a professional development bootcamp. This portfolio documents my growth across software engineering, algorithms and data structures, and databases, and reflects the skills I have built through both my coursework and my professional work as a Genesys Cloud platform administrator and DevOps engineer.

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

The original project had all data hardcoded directly into the application. The planned enhancement replaces that hardcoded data with a live MongoDB connection so data is read from and written to a real database at runtime.

- [View Enhancement 3 Narrative](#) *(coming soon)*
- [View Source Code](#) *(coming soon)*

---

## Professional Self-Assessment

*Coming soon: will be added as the first section of the portfolio in Module Seven.*

---

*Computer Science | DevOps | Cloud Platform Engineering*

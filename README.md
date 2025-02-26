# Jira 

## **[Jira Learning Syllabus](./syllabus.md)**


## **[Know the Jargons/Terms First](./jargons.md)**

---

### Project Management

![project workflow](./assets/projectmngmt.png)

---

### Jira Instances

### **Jira Instances Explained (With Examples)**  

A **Jira Instance** refers to a unique installation or cloud-based setup of Jira used by a company, team, or project. It includes all projects, users, and data within that specific Jira environment.  

---

### **Types of Jira Instances**
1. **Jira Cloud Instance** – Hosted by Atlassian on the cloud. No manual server setup is needed.  
   - *Example: A startup uses `company.atlassian.net` to manage their projects on Jira Cloud.*  
2. **Jira Server Instance** – Installed on a company’s own servers. Offers more control and customization.  
   - *Example: A bank installs Jira on its internal servers for security reasons.*  
3. **Jira Data Center Instance** – A scalable, enterprise-level setup for large organizations with high availability.  
   - *Example: A multinational company with 10,000+ users uses Jira Data Center for better performance.*  

---

### **Jira Instance Examples**
- A software company might have a **Jira Cloud Instance** for managing feature development and bug tracking.  
- A government agency might use a **Jira Server Instance** for secure, on-premise project management.  
- A big e-commerce company might use a **Jira Data Center Instance** to handle multiple teams working on different projects simultaneously.  

---

### **How to Identify Your Jira Instance?**
- If your Jira URL looks like `yourcompany.atlassian.net`, it's **Jira Cloud**.  
- If you access Jira via an internal company network, it's **Jira Server** or **Data Center**.  

---

### **Agile and Agile Methodologies**  

#### **What is Agile?**  
Agile is a flexible and iterative approach to project management and software development. It focuses on delivering work in small, manageable parts and adapting to changes quickly based on feedback.  

---

### **Agile Methodologies & Frameworks**  

1. **Scrum Framework** 🏉  
   - Uses time-boxed iterations called **Sprints** (1-4 weeks).  
   - Roles: **Scrum Master**, **Product Owner**, and **Development Team**.  
   - Daily Standups (short meetings) to track progress.  
   - Uses a **Scrum Board** to manage tasks.  
   - *Example:* A software team working in 2-week sprints to build new features.  

2. **Kanban Framework** 📌  
   - Focuses on **visualizing work** and limiting the number of tasks in progress.  
   - Uses a **Kanban Board** with columns (To Do → In Progress → Done).  
   - Tasks move continuously without fixed sprints.  
   - *Example:* A support team managing customer tickets in real-time.  

3. **Extreme Programming (XP)** 💻  
   - Focuses on **high-quality code and fast releases**.  
   - Practices include **Test-Driven Development (TDD)** and **Pair Programming**.  
   - Frequent small releases and continuous customer feedback.  
   - *Example:* A team writes tests before coding to ensure reliability.  

4. **Lean Development** 🔄  
   - Inspired by **Lean Manufacturing (Toyota Production System)**.  
   - Focuses on **eliminating waste** and delivering value faster.  
   - Encourages minimal documentation and fast decision-making.  
   - *Example:* A startup using minimal processes to release software quickly.  

5. **Feature-Driven Development (FDD)** 🚀  
   - Focuses on **developing software based on features**.  
   - Uses short development cycles (2 weeks).  
   - Prioritizes domain modeling and clear design before coding.  
   - *Example:* A mobile app team adds small but valuable features in each release.  

6. **Crystal Methodology** ✨  
   - A **lightweight** Agile approach that adapts to team size and complexity.  
   - Encourages face-to-face communication and team flexibility.  
   - Variants: **Crystal Clear, Crystal Yellow, Crystal Orange** (based on team size).  
   - *Example:* A small startup team using minimal rules for faster development.  

---

### **Which Agile Framework Should You Choose?**  
- **Scrum** → Best for structured teams with well-defined roles.  
- **Kanban** → Best for teams handling continuous work (like support teams).  
- **XP** → Best for teams needing high-quality, bug-free code.  
- **Lean** → Best for startups focusing on quick development with minimal waste.  
- **FDD** → Best for teams working on feature-rich products.  
- **Crystal** → Best for small, highly flexible teams.  

---


### **The Scrum Framework – Explained Simply** 🏉  

Scrum is one of the most popular Agile frameworks used in project management and software development. It helps teams work efficiently by organizing tasks into small, time-boxed periods called **Sprints** (usually 1-4 weeks).  

---

## **🔹 Scrum Key Components**  

### **1️⃣ Scrum Roles**  
There are three main roles in Scrum:  

1. **Product Owner** 🏗️  
   - Defines the product vision.  
   - Prioritizes the backlog (list of tasks).  
   - Ensures the team works on the most valuable features first.  
   - *Example:* A product manager deciding which features are most important for the next release.  

2. **Scrum Master** 🏆  
   - Facilitates the Scrum process.  
   - Removes obstacles for the development team.  
   - Ensures the team follows Agile principles.  
   - *Example:* Helping the team unblock issues like missing resources or dependencies.  

3. **Development Team** 👨‍💻👩‍💻  
   - The people who actually work on the tasks (developers, designers, testers, etc.).  
   - Self-organizing, meaning they decide how to complete the work.  
   - *Example:* A team of developers coding new features for a mobile app.  

---

### **2️⃣ Scrum Events (Meetings & Cycles)**  

1. **Sprint Planning** 📅  
   - Before a sprint starts, the team selects tasks from the backlog.  
   - The team decides how much work they can complete in the sprint.  
   - *Example:* Deciding which features will be built in the next 2-week sprint.  

2. **Daily Scrum (Stand-up Meeting)** ⏳  
   - A short 15-minute meeting every day.  
   - Each team member answers:  
     1. What did I do yesterday?  
     2. What will I do today?  
     3. Any blockers (problems)?  
   - *Example:* A developer mentions they are stuck on a bug, and another teammate helps.  

3. **Sprint Review** 🎉  
   - At the end of a sprint, the team showcases completed work to stakeholders.  
   - Feedback is collected for future improvements.  
   - *Example:* A demo presentation of a new feature to managers and users.  

4. **Sprint Retrospective** 🔄  
   - The team reflects on what went well and what needs improvement.  
   - Action items are discussed to improve the next sprint.  
   - *Example:* If too many bugs appeared, the team decides to improve testing.  

---

### **3️⃣ Scrum Artifacts (Documents & Boards)**  

1. **Product Backlog** 📌  
   - A list of all tasks, features, and bugs for the product.  
   - Managed by the **Product Owner**.  
   - *Example:* A backlog containing tasks like "Add a login feature" and "Fix checkout bug."  

2. **Sprint Backlog** 🏃‍♂️  
   - A list of tasks selected for the current sprint.  
   - Managed by the **Development Team**.  
   - *Example:* Only 5 tasks from the product backlog are picked for a 2-week sprint.  

3. **Increment** ✅  
   - The sum of all completed tasks in a sprint that add value to the product.  
   - *Example:* After a sprint, a new "Dark Mode" feature is fully functional and ready for users.  

---

### **🔄 Scrum Workflow (How Work Moves)**  

1️⃣ **Product Owner** creates the **Product Backlog** (list of tasks).  
2️⃣ During **Sprint Planning**, the **Development Team** selects tasks for the **Sprint Backlog**.  
3️⃣ Every day, the team has a **Daily Scrum** to track progress.  
4️⃣ At the end of the sprint, the team presents the work in the **Sprint Review**.  
5️⃣ The **Sprint Retrospective** helps the team improve the next sprint.  
6️⃣ The process repeats! 🚀  

---

### **📌 Example: How Scrum Works in Real Life**  

📱 **Scenario:** A mobile app company wants to add a **Dark Mode** feature.  

- The **Product Owner** adds “Implement Dark Mode” to the **Product Backlog**.  
- During **Sprint Planning**, the team picks this task for the next sprint.  
- Every day, they discuss progress in the **Daily Scrum**.  
- After 2 weeks, they finish Dark Mode and showcase it in the **Sprint Review**.  
- In the **Sprint Retrospective**, they discuss making UI testing faster for future sprints.  

---

### **✅ Why Use Scrum?**  
✔ Helps teams stay **organized** and **focused**.  
✔ Allows for **quick changes** based on feedback.  
✔ Breaks big projects into **small, manageable** parts.  
✔ Keeps **everyone in sync** with daily updates.  

---


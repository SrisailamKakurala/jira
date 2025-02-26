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

# **Scrum vs. Kanban – A Simple Comparison** 🏉📊  

Scrum and Kanban are both Agile frameworks used for project management, but they have key differences.  

| Feature        | **Scrum** 🏉 | **Kanban** 📊 |
|--------------|------------|------------|
| **Approach** | Iterative & structured | Continuous & flexible |
| **Work Style** | Fixed Sprints (1-4 weeks) | Continuous flow |
| **Team Roles** | Defined (Scrum Master, Product Owner, Developers) | No fixed roles (everyone manages workflow) |
| **Meetings** | Regular (Daily Standup, Sprint Review, Retrospective) | Optional (only if needed) |
| **Board Type** | Scrum Board (organized by sprints) | Kanban Board (tasks move freely) |
| **Work Limit** | Sprint Backlog limits work in a sprint | WIP (Work In Progress) limits for each column |
| **Planning** | Sprint Planning at the start | Continuous planning as needed |
| **Best for** | Teams working in iterations | Teams with continuous workflow (support, maintenance) |
| **Example Use Case** | Developing a new app feature | Managing customer support tickets |

---

## **1️⃣ Scrum Overview 🏉**
✅ Work is done in fixed-length **Sprints** (1-4 weeks).  
✅ Teams follow a **structured workflow** (Sprint Planning → Daily Standups → Sprint Review → Retrospective).  
✅ Best for **software development teams** working on new features.  

📌 **Example:** A mobile app team plans a 2-week sprint to develop a new login feature.  

---

## **2️⃣ Kanban Overview 📊**
✅ Tasks flow continuously without fixed-length sprints.  
✅ Uses **Work In Progress (WIP) Limits** to prevent overload.  
✅ Best for **support teams or teams with ongoing work** (e.g., bug fixes, DevOps).  

📌 **Example:** A customer support team handles tickets as they come in without sprint cycles.  

---

## **📌 When to Use Scrum vs. Kanban?**
- **Use Scrum** if your work has **clear deadlines and structured phases**.  
- **Use Kanban** if your work is **ongoing and requires flexibility**.  
- **Use Scrumban** (a mix of both) for teams that want **structured sprints but continuous workflow**.  

---

Here's a real-world example to help you understand **Scrum vs. Kanban** better.  

---

### **📌 Real-World Example: Developing & Maintaining a Mobile App**  

Imagine your team is working on a **mobile app**. You need to develop **new features** and also **fix bugs** as they arise.  

#### **1️⃣ Scrum for New Feature Development 🏉**  
🔹 Your team plans a **2-week Sprint** to add a **dark mode feature**.  
🔹 The work is broken into **User Stories** (e.g., “Allow users to switch to dark mode”).  
🔹 Every day, the team has a **Daily Standup** to discuss progress.  
🔹 At the end of 2 weeks, the feature is reviewed, tested, and released.  
🔹 The team holds a **Sprint Retrospective** to discuss improvements for the next sprint.  

💡 **Why Scrum?** The work is structured, planned in advance, and delivered in fixed cycles.  

---

#### **2️⃣ Kanban for Bug Fixes & Maintenance 📊**  
🔹 Bugs and issues are reported continuously by users.  
🔹 The team places them on a **Kanban Board** under “To Do.”  
🔹 They fix bugs one by one as per priority, moving tasks from **To Do → In Progress → Done**.  
🔹 No sprint deadlines – work flows as needed.  
🔹 If the team is overwhelmed, they reduce the **Work In Progress (WIP) limit** to stay focused.  

💡 **Why Kanban?** Bugs and maintenance tasks arrive unpredictably, so a **flexible approach** works better.  

---

### **📌 When to Use Scrumban?**  
🔹 Your team needs **structure for new features** (Scrum) but **flexibility for bug fixes** (Kanban).  
🔹 You plan sprints but also handle **urgent tasks** without waiting for the next sprint.  

🔥 **Example:**  
- Use **Scrum** for adding a new "Chat Feature" in a Sprint.  
- Use **Kanban** for handling **urgent security fixes** immediately.  


---

# **Sprint in Scrum – A Simple Guide 🚀**  

A **Sprint** is a short, time-boxed period (usually **1-4 weeks**) where a team completes a set of tasks. It's a **core concept of Scrum** and helps teams deliver work **quickly and consistently**.  

---

## **📌 Sprint Workflow (Step-by-Step)**  

1️⃣ **Sprint Planning** – Decide what tasks to work on in the sprint.  
2️⃣ **Daily Standups** – Short daily meetings to discuss progress.  
3️⃣ **Work Execution** – Team works on tasks from the Sprint Backlog.  
4️⃣ **Sprint Review** – At the end, the team showcases the completed work.  
5️⃣ **Sprint Retrospective** – Discuss what went well and what can be improved.  
6️⃣ **Next Sprint Starts** – The cycle repeats with a new Sprint.  

---

## **📌 Key Sprint Terms**  

- **Sprint Backlog** – List of tasks to complete in a Sprint.  
- **Sprint Goal** – The main objective of the Sprint.  
- **Time-boxed** – Fixed duration (e.g., 2 weeks).  
- **Increment** – The final product or feature delivered.  
- **Burn-down Chart** – A graph showing remaining work vs. time.  

---

## **📌 Example: Mobile App Sprint** 📱  

🔹 **Sprint Goal** – Add a "Dark Mode" feature.  
🔹 **Sprint Backlog** –  
   - Design dark mode UI  
   - Implement toggle button  
   - Test across devices  
   - Fix reported issues  

🔹 **Daily Standups** – Team checks progress every morning.  
🔹 **Sprint Review** – Show the working "Dark Mode" feature.  
🔹 **Sprint Retrospective** – Discuss what went well & improve for next Sprint.  

💡 **Sprints ensure fast, focused, and frequent software releases!**  

---

# **Epic & Roadmap/Timeline – A Simple Guide 🚀**  

## **📌 What is an Epic?**  
An **Epic** is a **big feature or project** that is too large to complete in one sprint. It is broken down into **smaller user stories** and tasks.  

### **Example:**  
📱 **Epic:** "Build a Chat Feature for a Mobile App"  
🔹 **Story 1:** "Design the chat UI"  
🔹 **Story 2:** "Implement real-time messaging"  
🔹 **Story 3:** "Add push notifications"  

👉 **Epics help teams manage large projects by breaking them into smaller, manageable parts.**  

---

## **📌 What is a Roadmap/Timeline?**  
A **Roadmap** (or **Timeline**) is a **visual plan** that shows when different epics, stories, and tasks will be completed.  

### **Example of a Roadmap (3 Months Plan) 🗓️**  

| Month | Epic | Tasks |
|--------|------|-------|
| **March** | "User Authentication" | Login, Signup, Google OAuth |
| **April** | "Chat Feature" | UI, Real-time Messaging, Notifications |
| **May** | "Dark Mode & Performance Improvements" | Dark UI, Speed Optimization |

👉 **A roadmap helps teams track progress and align work with business goals.**  

---

# **Story vs. Task vs. Issue vs. Bug – A Simple Guide 🚀**  

In **Jira** and project management, these terms help categorize different types of work. Let’s break them down with **examples** so you can understand them easily.  

---

## **📌 1. Story (User Story) – A Feature Request**  
A **Story** describes a feature from the user’s perspective. It answers: **"What does the user need?"**  

✅ **Example:**  
- 🛒 "As a user, I want to add items to my cart so I can purchase them later."  
- 🔹 Stories are usually part of a bigger **Epic** (e.g., "Build an E-commerce Website").  
- 🔹 Stories are broken into **Tasks**.  

---

## **📌 2. Task – A Piece of Work to Do**  
A **Task** is an action item that must be completed. It is **smaller than a Story** and is assigned to a team member.  

✅ **Example:**  
- 🎨 "Design the cart UI."  
- 🖥️ "Develop the cart functionality."  
- ✅ "Write test cases for the cart feature."  

🔹 **Tasks can exist independently or be part of a Story.**  

---

## **📌 3. Issue – A General Work Item**  
In Jira, **Issue** is a broad term that can refer to **a Story, Task, or Bug**.  

✅ **Example:**  
- "Implement dark mode" (Story)  
- "Fix checkout page alignment" (Bug)  
- "Upgrade the server" (Task)  

🔹 **In simple terms, every work item in Jira is called an Issue.**  

---

## **📌 4. Bug – A Problem or Error in the System**  
A **Bug** is an issue that needs fixing because something is not working as expected.  

✅ **Example:**  
- ❌ "Checkout button is not working on mobile."  
- 🛑 "App crashes when clicking on the profile page."  
- ⚠️ "Images are loading slowly on the homepage."  

🔹 **Bugs must be prioritized based on severity:**  
  - 🟥 **Critical** – App crashes, security issues.  
  - 🟧 **High** – Major function not working.  
  - 🟨 **Medium** – Minor bugs affecting usability.  
  - 🟩 **Low** – Cosmetic issues (e.g., UI misalignment).  

---

## **📌 Simple Workflow in Jira: How They Connect**  

1️⃣ **Epic**: "Build a Chat Feature"  
2️⃣ **Story**: "Enable users to send messages."  
3️⃣ **Tasks**: "Create UI," "Develop backend," "Add typing indicators."  
4️⃣ **Bugs**: "Messages sometimes fail to send."  

💡 **Understanding these terms helps teams work efficiently in Agile & Scrum!**  

---

# **Hierarchy of Work Items in Jira & Agile 🚀**  

Understanding the hierarchy of **Epics, Stories, Tasks, Issues, and Bugs** is key to managing projects effectively. Here's a simple breakdown:  

---

## **📌 Jira Work Item Hierarchy (Top to Bottom)**
```
1️⃣ Initiative (Optional - Large Business Goal)
    └── 2️⃣ Epic (Big Feature or Project)
         ├── 3️⃣ Story (Feature or User Requirement)
         │    ├── 4️⃣ Task (Work Item to Complete the Story)
         │    └── 4️⃣ Bug (Issue that Needs Fixing)
         └── 3️⃣ Sub-task (Smaller Part of a Task)
```

---

## **📌 Explanation with Example (E-commerce App)**
| Level | Work Item | Example |
|--------|-------------|--------------------------------|
| **1️⃣ Initiative** _(Optional)_ | "Improve Shopping Experience" | A company-wide goal |
| **2️⃣ Epic** | "Build a Checkout System" | A major feature |
| **3️⃣ Story** | "As a user, I want to apply discount codes" | A feature request |
| **4️⃣ Task** | "Develop discount logic in backend" | A specific piece of work |
| **4️⃣ Bug** | "Discount code not applying correctly" | A problem to fix |
| **4️⃣ Sub-task** | "Write unit tests for discount logic" | A small work item within a Task |

---

## **📌 Visualizing the Hierarchy**
```
📌 Initiative: "Improve Shopping Experience"
    └── 📌 Epic: "Build a Checkout System"
        ├── 📌 Story: "As a user, I want to apply discount codes"
        │    ├── ✅ Task: "Develop discount logic in backend"
        │    ├── 🛠️ Sub-task: "Write unit tests for discount logic"
        │    └── 🐞 Bug: "Discount code not applying correctly"
        └── 📌 Story: "As a user, I want to pay with PayPal"
             ├── ✅ Task: "Integrate PayPal API"
             └── 🐞 Bug: "Payment fails for some users"
```

---

## **📌 Simple Rules to Remember**
- **Initiative** → A broad company goal (optional in Jira).  
- **Epic** → A big feature or project that spans multiple sprints.  
- **Story** → A specific feature request from a user.  
- **Task** → A piece of work that contributes to completing a Story.  
- **Bug** → A problem that needs fixing in the system.  
- **Sub-task** → A smaller work item within a Task.  

💡 **Epics contain Stories, Stories contain Tasks, and Bugs/Tasks may have Sub-tasks.**  

![alt text](./assets/epics.png)


---


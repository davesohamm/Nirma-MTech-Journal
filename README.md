# 📘 MTech Data Science Daily Academic Journal  
**University:** Nirma University  
**Program:** M.Tech in Data Science  
**Month:** July

**Click here to read:** [June Journal](https://github.com/davesohamm/Nirma-MTech-Journal/blob/main/June/README.md)

---

**Date:** 1 July 2026, Wednesday  
**Day:** 256

---

# 🌅 Morning

Reached the office around **10:00 AM** and started the day with breakfast consisting of **peanut butter sandwiches** and **Chocos milk**. After breakfast, I set up my workstation and prepared everything for the day's tasks.

Soon after settling in, we had our daily **scrum meeting** with **Rajat Bhai**. The primary discussion revolved around analyzing the difference between **Headroom Compaction** and our newly implemented **Relevance-Based Compaction** in the LLM pipeline.

Initially, the objective was to perform an apple-to-apple comparison between both implementations. However, during the analysis, we discovered that the current Headroom implementation does **not invoke all six of our AI agents**, unlike our architecture. Because of this architectural difference, any comparison would be inherently unfair and inaccurate.

After discussing the findings, we concluded that the Headroom implementation itself would first need to be modified so that it follows the same execution flow as our agentic architecture before meaningful comparisons could be performed.

With that understanding, I immediately started working on updating the Headroom implementation.

---

# 👥 Department Progress Meeting

At **12:00 PM**, we attended our department progress meeting where we demonstrated the current state of our work to **Kumar Kunal**. We shared the ongoing progress, discussed the compaction analysis, and provided updates on the improvements being made to the evaluation pipeline.

---

# 🍽️ Lunch

Lunch today was quite filling:

- Chhole Kulche
- Paneer Chawal
- Dahi Puri
- Ice Cream

After lunch, I spent some time talking to **her** over a call before returning to work.

---

# 💻 Afternoon Work

Following the break, I resumed working on modifying the Headroom implementation so that it could mirror our agent execution flow more closely.

After several iterations and validation, I successfully completed the required implementation around **4:00 PM**.

Once the implementation was complete, I finalized the comparative analysis and shared the results with the **main AI team** for further evaluation.

Later in the afternoon, I also had a detailed discussion with **Rajat Bhai** over Microsoft Teams where I explained:

- The complete **agentic architecture**
- The role and sequence of all **six LLM calls**
- How every agent contributes to the overall workflow
- The purpose and interpretation of each field in the **Grafana dashboard**
- How the dashboards help visualize latency, context windows, and LLM execution metrics

It was a productive knowledge-sharing session that helped document and communicate the overall architecture more clearly.

---

# ☕ Evening

Around **6:00 PM**, we had evening snacks:

- Dhokla
- Kathi Rolls

At approximately **6:30 PM**, I left the office and decided to walk back home. I reached home around **7:30 PM**.

---

# 🏠 Night

After reaching home, I completed my daily chores and relaxed for a while.

I then spent some quality time talking to **her** over a call, followed by another call with my family.

Before ending the day, I solved **one LeetCode problem**, continuing my daily practice and consistency.

With everything completed, I wrapped up the day and got some well-deserved rest.

---

# 📌 Highlights of the Day

- Investigated differences between **Headroom Compaction** and **Relevance-Based Compaction**.
- Identified that Headroom does not invoke all six AI agents, making direct comparison invalid.
- Began modifying the Headroom implementation to enable fair benchmarking.
- Presented progress during the department meeting with **Kumar Kunal**.
- Completed the Headroom implementation changes and shared the analysis with the AI team.
- Explained the complete **6-agent architecture**, LLM call flow, and **Grafana dashboard** metrics to **Rajat Bhai**.
- Solved **1 LeetCode** problem.
- Spent quality time talking with **her** and my family.

---

# 💭 Reflection

Today's work highlighted the importance of ensuring architectural parity before drawing performance conclusions. It was satisfying to identify the root cause behind the misleading comparison and immediately work toward fixing it. Beyond completing the implementation, explaining the overall agentic architecture and dashboard metrics also reinforced my own understanding of the system. Ending the day with meaningful conversations, family time, and a LeetCode problem made it a balanced and productive Wednesday.

---

**Date:** 2 July 2026, Thursday  
**Day:** 257

---

# 🌅 Morning

Reached the office around **10:50 AM** and started the day by setting up my workstation. After getting everything ready, I had breakfast before beginning the day's work.

We had our daily **scrum meeting** with **Rajat Bhai**, where we discussed the ongoing tasks and priorities for the day.

After the scrum, I checked my emails and noticed that we needed to submit our **internship progress report** to our reporting manager, **Manu Shrot**. I spent some time compiling everything I had worked on over the past **one and a half months**. I documented all the major contributions, completed tasks, learnings, and accomplishments in bullet points. Along with the completed work, I also included my planned objectives and the areas I intend to work on during the remaining internship period. It was a good opportunity to reflect on how much I have learned and contributed so far.

---

# 💻 Preparing the Demo

Later in the morning, Rajat Bhai and I worked together on verifying the **HGW-2926 JIRA story**. We performed a complete end-to-end validation of the implementation, ensuring that every workflow behaved as expected.

After thoroughly testing the feature, we were confident that everything was functioning correctly and concluded that the story was now **fully ready for demonstration** to stakeholders or any internal team.

---

# 🍽️ Lunch

Around **1:00 PM**, we headed for lunch.

Today's menu included:

- Curry Chawal
- Aloo-Pav Bhaji
- Roti
- Paneer Sabzi
- Khoya Coconut Balls
- Fresh Salads

After lunch, I returned to my workstation and resumed work.

---

# 🔐 Security Fixes & Future Planning

The first task after lunch was addressing a security issue that had been reported by **Ankit Sir**.

One of my previous Git commits had accidentally exposed my **Cursor CLI API key** as an environment variable. Fortunately, it was identified quickly, and I immediately worked on removing the exposed secret, updating the repository, and ensuring that the sensitive information was no longer accessible. It was a valuable reminder about following secure development practices and carefully reviewing commits before pushing changes.

Later, Rajat Bhai discussed several ideas for future automation initiatives. We brainstormed possible approaches around:

- **JaCoCo-based backend code coverage measurement**
- Additional QA automation improvements
- Future automation strategies that could enhance our testing pipeline

I documented all of these ideas in my notes so that they can be explored in upcoming development cycles.

---

# 🐞 Investigating a New JIRA

During the afternoon, a brand-new **JIRA ticket** was assigned. Interestingly, the ticket contained very little information, making it difficult to understand the actual issue.

We executed our **QA Workflow** on the ticket to analyze the problem.

The first issue we identified was related to how our AI agents were selecting **GitLab repositories** while constructing the Knowledge Base from JIRA comments. We implemented a fix for the repository selection logic.

However, despite this improvement, the generated results were still not satisfactory.

We continued experimenting with additional fixes across the workflow, but the overall quality still failed to meet expectations.

To improve the context available to the agents, we requested the developer to add a proper **README** file to the project repository. Although this provided slightly better context, the improvement in the generated results was still limited.

The investigation remains open, and further enhancements will likely be required to make the workflow more reliable for such minimal-information JIRA tickets.

---

# ☕ Evening

At around **6:00 PM**, we went for evening snacks.

Today's snacks included:

- Pita Pockets
- Masala Sevaiya

After wrapping up work, I headed home and reached around **7:00 PM**.

---

# 🏠 Night

Once home, I completed my daily chores and spent the evening winding down.

I continued my consistency by solving **one LeetCode problem**.

Later, I talked to **her** over a call and also caught up with my family over another call.

An interesting event happened in the evening when our furniture broker arrived to replace our old sofa with a new one. After comparing both, we realized that we actually preferred the comfort and look of our existing sofa. In the end, we decided **not to replace it** and kept the old one.

With everything completed, I wrapped up another productive day.

---

# 📌 Highlights of the Day

- Submitted my internship progress report summarizing the last **1.5 months** of work and future objectives.
- Completed end-to-end validation of **HGW-2926**, making it ready for demonstrations.
- Fixed an accidentally exposed **Cursor CLI API key** after it was reported by Ankit Sir.
- Documented future ideas for **JaCoCo-based backend code coverage** and additional automation strategies.
- Investigated a newly assigned JIRA with limited information and improved GitLab repository selection for the AI agents.
- Requested the addition of a project README to improve Knowledge Base generation.
- Solved **1 LeetCode** problem.
- Spent quality time talking with **her** and my family.
- Decided to keep our old sofa after comparing it with the replacement.

---

# 💭 Reflection

Today combined technical problem-solving with careful planning for future work. Completing the internship progress report gave me a chance to reflect on how much I have learned over the past six weeks, while preparing the HGW-2926 story for demonstration felt like a satisfying milestone. Addressing the exposed API key reinforced the importance of secure development practices, and the investigation into the new JIRA highlighted how critical good documentation is for AI-assisted workflows. Overall, it was a productive day filled with learning, collaboration, and steady progress.

---

# Daily Journal

**Date:** 3 July 2026, Friday
**Day:** 258

---

# 🌅 Morning

Reached the office around **9:50 AM**, slightly earlier than usual. I started the day with breakfast and then set up my workstation for the day ahead.

Once everything was ready, I immediately resumed working on the ongoing bugs and feature additions in our **Agentic QA System**. Since the system is continuously evolving, there were multiple areas that required improvements, fixes, and enhancements.

The first half of the morning was spent going through the existing issues and making progress on the ongoing development tasks before our major team meeting scheduled for noon.

---

# 👥 Agentic QA System Demonstration

At **12:00 PM**, we had an important meeting with:

* Kunal Sir
* Ankit Sir
* Rajat Bhai
* The entire AI Initiators team

The primary purpose of the meeting was to demonstrate our **Agentic QA System** and present its current capabilities to the wider team.

During the demonstration, I actively participated in explaining several important architectural aspects of the system. I walked the team through parts of the agentic workflow and explained how different components interact with one another.

I also handled several data-related questions that came up during the discussion, explaining how the system processes, retrieves, and uses different sources of information throughout the QA workflow.

The meeting became quite detailed and interactive, lasting for approximately **70 minutes**. It was a valuable session because we not only demonstrated the current state of the system but also received several observations, questions, and suggestions from the team.

---

# 🍽️ Lunch

After the long demonstration meeting, I went for lunch.

Today's lunch had a delicious Indo-Chinese spread:

* Noodles
* Manchurian
* Chilli Paneer
* Fried Rice
* Other accompanying dishes

It was a satisfying lunch after an intense and discussion-heavy meeting.

---

# 📝 Documenting the Minutes of Meeting

After returning to my workstation, my first priority was to document everything that had been discussed during the demonstration.

I carefully went through the entire meeting in my mind and noted down all the important feedback, observations, improvements, and action items.

By the end of this exercise, I had documented a total of **14 distinct points** from the meeting.

This was important because the discussion had covered several different aspects of the Agentic QA System, and I wanted to make sure that none of the feedback or suggested improvements were missed.

Once all 14 points were properly documented, I organized them into actionable tasks and started working on them one by one.

---

# 💻 Afternoon Development Sprint

The rest of the afternoon was completely focused on implementing the improvements discussed during the meeting.

I started going through the **14 action items** sequentially, analyzing each issue and making the required code changes.

Some tasks involved fixing existing bugs, while others required adding new functionality or improving the behavior of existing features. I continued working on these items throughout the afternoon without losing momentum.

By approximately **6:40 PM**, I had successfully completed **5 out of the 14 tasks**.

That meant more than one-third of the action items raised during the meeting had already been addressed on the very same day.

The progress felt satisfying, especially considering that the tasks had only been identified a few hours earlier.

---

# ☕ Evening

After finishing the fifth task around **6:40 PM**, I took a break for evening snacks.

Today's snacks included:

* Idli
* Dahi Bhalla

After snacks, I returned to my workstation and made sure that all the completed work was properly pushed to the development branch.

I then shared the updated branch with **Rajat Bhai** so that he could review the changes and continue tracking the progress.

Once everything was pushed and communicated, I packed up my belongings and left the office.

---

# 🚶 Walk Back Home

I decided to walk back home after work.

After the long day of meetings, discussions, documentation, and development, the walk provided a good transition from work mode to the evening.

I reached home around **8:00 PM**.

---

# 🏠 Night

After reaching home, I completed my usual daily chores and settled down for the night.

I talked to my family over a call and spent some time catching up with them.

Later, I watched a **movie with her**, followed by a **funny episode**. It was a relaxing way to unwind after a technically intense and productive day.

Before going to sleep, I maintained my coding consistency by solving **one LeetCode problem**.

With that completed, I finally called it a day.

---

# 📌 Highlights of the Day

* Reached the office around **9:50 AM**.
* Continued working on ongoing bugs and feature additions in the Agentic QA System.
* Participated in a major **70-minute demonstration meeting** with Kunal Sir, Ankit Sir, Rajat Bhai, and the entire AI Initiators team.
* Demonstrated the current capabilities of the **Agentic QA System**.
* Explained several architectural components and workflows of the system.
* Handled multiple data-related questions during the demonstration.
* Carefully documented the complete **Minutes of Meeting**.
* Identified and recorded **14 actionable points** from the meeting.
* Successfully completed **5 out of the 14 tasks** by 6:40 PM.
* Pushed the completed changes and shared the branch with Rajat Bhai.
* Walked back home and reached around **8:00 PM**.
* Talked to my family over a call.
* Watched a movie and a funny episode with **her**.
* Solved **1 LeetCode problem** before sleeping.

---

# 💭 Reflection

Today was one of those days where discussion quickly transformed into execution.

The 70-minute demonstration of our Agentic QA System was an important opportunity to present the work we have been building and improving over the past several weeks. Explaining the architecture and handling data-related questions also helped me look at the system from the perspective of a wider audience.

What made the day especially productive was that the meeting did not end with just feedback and discussion. I carefully converted everything into **14 concrete action items** and immediately started working on them. Completing **5 of those 14 tasks on the same day** gave the project strong momentum and made the feedback session immediately valuable.

The day ended on a balanced note with a walk back home, conversations with family, watching a movie and a funny episode with her, and maintaining my LeetCode consistency.

Overall, it was a long but highly productive Friday filled with **demonstration, technical discussions, documentation, development, collaboration, and steady progress**.

---


**Date:** 6 July 2026, Monday
**Day:** 259

---

# 🌅 Morning

Reached the office around **9:50 AM** and started the day with breakfast:

* Cornflakes with milk
* Peanut butter sandwich

After breakfast, I headed to my workstation, set everything up, and prepared for the day.

We then had our daily **scrum meeting with Rajat Bhaiya**. Since I had completed **5 out of the 14 action items** identified during Friday's Agentic QA System demonstration, I walked him through each of the completed tasks and demonstrated the changes.

We reviewed the improvements one by one and discussed the current state of the remaining tasks.

---

# 🧠 Deep Dive into Prompt Efficiency

After the scrum meeting, Rajat Bhaiya and I had a detailed technical discussion about **prompt efficiency** and improving the way our Agentic QA System uses its Knowledge Base.

One of the major questions we explored was:

> How can we map our actual Knowledge Base to identify API-level impact and eventually generate better and more relevant test cases?

This led to a deep exploration of different strategies and architectural approaches.

The challenge is not simply to retrieve more information. The real goal is to retrieve the **right information** and understand how different pieces of the Knowledge Base are connected to the JIRA story being analyzed.

We explored multiple possible strategies and architectures for:

* Mapping Knowledge Base content to impacted APIs
* Identifying relevant project files
* Tracing dependencies between different components
* Reducing unnecessary information in the LLM context window
* Improving the connection between retrieved knowledge and generated test cases
* Increasing test-case relevance and overall coverage

After discussing the possible approaches, we moved from exploration to implementation.

We used **Cursor** to generate multiple development plans for the proposed architecture. Instead of immediately implementing the first suggestion, we carefully reviewed and compared the different plans.

After evaluating the approaches, we selected one strategy and started working on its implementation.

We continued this work until around **12:00 PM**.

---

# 👥 Daily Team Meeting

At noon, we had our daily team meeting with **Kumar Kunal**, where we shared the latest progress of the Agentic QA System.

We provided updates about:

* The completed action items
* The ongoing prompt-efficiency work
* The improvements being explored for Knowledge Base retrieval
* The current state of the project

During the discussion, Kumar Kunal suggested a few additional improvements.

Most of these suggestions were related to the **frontend and user experience** of the system. Immediately after the meeting, we started working on those improvements and addressing the newly suggested points.

---

# 🌐 Core Broadband Router Discussion

During the day, we also had a technical discussion with **Shobhit Bhaiya** about **Core Broadband Router configuration**.

The discussion went into lower-level networking concepts, particularly around:

* Router configuration
* Hardware-level packet tracing
* Understanding how packets flow through the system

It was interesting to explore a topic closer to the networking and hardware layers, especially alongside our ongoing AI and software development work.

---

# 🍽️ Lunch

Later, we went for lunch.

Today's menu included:

* Malai Kofta
* Chapati
* Dal Makhani
* Pulao
* Kebabs
* Gulab Jamun
* Salad

It was a satisfying lunch before returning to another technically packed afternoon.

---

# 💻 Returning to Prompt Efficiency

After lunch, we returned to our work on **prompt efficiency** and Knowledge Base optimization.

However, while we were working, we received a call from **Ankit Sir**, asking us to join him for a discussion in the **5th-floor conference room**.

We paused our current work and joined the meeting.

---

# 🏢 AI Infrastructure & Agile Stand-up Discussion

We remained in the conference room until approximately **4:00 PM**.

The discussion was centered around their **AI Infrastructure Agentic Framework**.

Apart from the technical discussion, the meeting also gave me an opportunity to observe how actual **Agile stand-up meetings** are conducted in a larger and more practical team environment.

It was useful to see how different team members:

* Shared their progress
* Discussed blockers
* Coordinated dependencies
* Exchanged technical context
* Planned the next steps

The session gave me a better understanding of how real-world Agile collaboration works beyond just theoretical concepts.

---

# 🔗 PageIndex, Context Linking & Advanced Retrieval

From approximately **4:00 PM to 5:30 PM**, Rajat Bhaiya and I had another deep technical discussion.

This time, the primary topic was **PageIndex** and how we could improve the linking and retrieval of information within our Agentic QA System.

The central problem we were trying to solve was:

> How can we keep only the truly relevant files inside the LLM context window while ignoring everything that does not contribute to the current task?

Currently, simply providing more files does not necessarily produce better results. In fact, irrelevant information can increase token usage, reduce prompt efficiency, and distract the LLM from the information that actually matters.

We explored how better data linking could help the system understand relationships between:

* JIRA stories
* APIs
* Source-code files
* Knowledge documents
* README files
* Wiki pages
* Related project components
* Generated test cases

The discussion gradually led us toward more advanced retrieval architectures, particularly:

* **Vector Databases**
* **Graph RAG**
* Better semantic linking between related data
* Dependency-aware retrieval
* Relevance-based context construction

These approaches could potentially help us build a smarter Knowledge Base where the system does not simply search for similar text but also understands how different pieces of information are connected.

---

# 🧪 Improving Test Case Generation

Until around **5:30 PM**, Rajat Bhaiya and I continued experimenting with the test-case generation workflow.

We tried multiple tweaks to improve the quality and coverage of the generated test cases.

One important limitation we identified was that, until now, our agent was **not fetching the contents of Wiki links** referenced in the available project context.

Today, we implemented support for fetching and using information from those Wiki links.

This was an important improvement because Wiki pages can contain valuable information such as:

* Architecture details
* Feature behavior
* API documentation
* Business rules
* Technical constraints
* Implementation-specific knowledge

However, even after adding Wiki retrieval and experimenting with additional tweaks, we still did not see a major improvement in overall **test-case coverage**.

The results were better informed, but the expected jump in coverage was still missing.

This made it clear that the core problem likely requires a deeper architectural solution rather than only adding more sources of information.

---

# ☕ Evening Snacks

Later in the evening, we went for snacks.

Today's snacks included:

* Sprouts cutlets
* Sandwiches
* Bourbon biscuits

After wrapping up the day's work, we booked a cab and headed home.

I reached home around **7:00 PM**.

---

# 🏠 Night

After reaching home, I completed my usual daily chores.

I maintained my coding consistency by solving **one LeetCode problem**.

Later, I talked to my family over a call and spent some time catching up with them.

I also talked to **her** over a call.

After completing everything for the day, I finally wrapped up and called it a day.

---

# 📌 Highlights of the Day

* Demonstrated the **5 completed tasks out of 14** to Rajat Bhaiya.
* Had a deep technical discussion on **prompt efficiency**.
* Explored how to map the Knowledge Base to identify **API-level impact** and improve test-case generation.
* Designed and reviewed multiple architectural plans using Cursor.
* Started implementing the selected architecture.
* Shared project updates with Kumar Kunal during the daily team meeting.
* Worked on additional frontend improvements suggested during the meeting.
* Discussed **Core Broadband Router configuration** and **hardware-level packet tracing** with Shobhit Bhaiya.
* Participated in a discussion about an **AI Infrastructure Agentic Framework**.
* Observed how real-world Agile stand-up meetings are conducted.
* Explored **PageIndex** for better data linking and context management.
* Investigated **Vector Database** and **Graph RAG** approaches.
* Implemented support for fetching information from **Wiki links**.
* Continued experimenting with improvements to test-case generation and coverage.
* Solved **1 LeetCode problem**.
* Talked to my family and **her** over calls.

---

# 💭 Reflection

Today was one of the most technically exploratory days in recent weeks.

A major theme throughout the day was understanding that improving an AI system is not simply about giving the LLM more information. The real challenge is identifying, connecting, and retrieving the **right information at the right time**.

Our discussions around prompt efficiency, API-level impact analysis, PageIndex, Vector Databases, and Graph RAG all pointed toward the same fundamental problem: **context quality matters more than context quantity**.

Implementing Wiki-link retrieval was another useful step forward, although the limited improvement in test-case coverage showed that adding another data source alone is not enough. The system needs a better understanding of relationships between JIRA requirements, APIs, code, documentation, and potential test scenarios.

The discussions around the AI Infrastructure Agentic Framework and observing a real Agile stand-up also added another dimension to the day. Alongside technical development, I gained a better understanding of how larger engineering teams communicate, coordinate, and solve problems collaboratively.

Overall, it was a productive Monday filled with **architecture discussions, prompt optimization, retrieval experiments, networking concepts, implementation work, and continuous learning**.


---


**Date:** 7 July 2026, Tuesday
**Day:** 260

---

# 🌅 Morning

Reached the office around **9:45 AM** and started the day with breakfast:

* Muesli with milk
* Peanut butter sandwich

After breakfast, I headed to my workstation and finished setting everything up by approximately **10:15 AM**.

Once the workstation was ready, I started working.

---

# 👥 Daily Scrum & Feature Branch Review

The first meeting of the day was the daily **scrum meeting with Rajat Bhaiya**.

The main topic of discussion was the new feature branch that I had created. Rajat Bhaiya had already tested the branch, so we went through the implementation, discussed the changes, and reviewed the points that were still pending.

The good news was that the branch had passed his testing and was **approved**.

After that, we discussed the remaining improvements from the **14 action items** that we had documented after our previous Agentic QA System demonstration.

With the feature branch approved, I continued implementing the remaining action items one by one.

---

# 💻 Completing the Demo Action Items

I spent the rest of the morning applying more improvements from the original list of **14 points**.

The work included addressing pending bugs, refining existing functionality, and incorporating the suggestions that had come from the previous demonstration meeting.

By approximately **11:35 AM**, I had completed almost all of them.

Only **3 out of the original 14 points** were still remaining.

The remaining tasks were primarily related to:

* PPT generation
* Prompt improvements
* Further refinement of the prompt-related workflow

Reaching this stage felt satisfying because most of the feedback from the previous demonstration had now been converted into actual working improvements.

---

# 🕸️ Discovering Graphify

Later in the morning, **Ankit Sir** shared an interesting framework with me called **Graphify**.

Graphify is designed to help build a **Graph RAG system directly over a codebase**, allowing the system to understand and query relationships within the code.

Since we had already been exploring:

* Knowledge Base linking
* PageIndex
* Vector Databases
* Graph RAG
* API-level impact analysis
* Better context retrieval

the framework was highly relevant to our current problem.

I spent some time exploring the Graphify repository and reading through its documentation. I also read several blogs to better understand:

* How it creates a graph representation of a codebase
* How relationships between code components are identified
* How the graph can be queried
* How it could potentially improve code-aware retrieval
* Whether it could help our Agentic QA System identify impacted APIs and relevant files

The exploration gave me another possible direction for improving the Knowledge Base and retrieval architecture of our system.

---

# 🍽️ Lunch

Later, we went for lunch.

Today's menu included:

* Palak Paneer
* Chapati
* Dal Chawal
* Mango-Orange Juice
* Papad
* Salad
* Veg Barbecue

After lunch, we returned for another team meeting.

---

# 🏢 DSM Meeting with the AI Infrastructure Team

After lunch, we attended a **DSM meeting with Ankit Sir and the team**.

During the meeting, Ankit Sir formally introduced us interns to the **AI Infrastructure team**.

It was another useful opportunity to observe how sprint and daily team meetings are handled in a real engineering environment.

We observed:

* How team members share their progress
* How sprint tasks are tracked
* How blockers are discussed
* How technical dependencies are coordinated
* How work is divided across the team

Ankit Sir also distributed a few **micro-tasks** among us interns, giving us an opportunity to contribute to smaller tasks alongside our primary project work.

---

# 🧪 Testing the Latest Agentic QA Branch

After the meeting, Rajat Bhaiya and I returned to our Agentic QA System and tested the latest branch together.

We generated test cases using the newest version of the workflow and observed the system's behavior.

One noticeable change is that the complete test-case generation process has now become significantly more time-consuming.

With every improvement iteration, we have added more useful context to the agents. The system now processes information from multiple sources and handles a much larger amount of data than before.

As a result, the agents have more information available for reasoning, but the overall execution time has also increased.

This creates an important engineering trade-off:

> More context can improve understanding, but it also increases processing time and system complexity.

We will eventually need to find the right balance between:

* Context quality
* Context quantity
* Test-case coverage
* Execution time
* Token usage
* Overall system efficiency

After completing the testing, I pushed all my feature branches.

I also created and pushed one final consolidated branch containing all the latest code and ensuring that the complete system was working properly.

---

# 🎱 Playing Pool for the First Time

From approximately **5:30 PM to 6:15 PM**, we went to the **5th floor** to play pool.

This was actually the **first time in my life that I played pool**.

I had never played it before, so learning how to aim, control the cue, and understand the basic flow of the game was a completely new experience.

And it was fun!

After a long day of coding, meetings, testing, and technical discussions, playing pool was a refreshing break.

---

# ☕ Evening Snacks

After playing pool, we went for evening snacks.

Today's snacks included:

* Paneer Kulcha
* Quinoa Fried Rice
* Biscuits

After snacks, we planned to leave for home.

---

# 🌧️ Rain, Research Paper & Waiting for a Cab

However, the weather had other plans.

Due to **heavy rain**, we were unable to book a cab online.

Since there was no immediate way to leave, we sat in the cafeteria and waited for the situation to improve.

Instead of wasting the time, I opened my academic work and continued working on my **research paper for Nirma University**.

While waiting for the cab, I successfully completed the work for **Draft 4 of my research paper**.

What could have been unproductive waiting time turned into useful progress on my academic work.

---

# 🚕 Journey Back Home

While I was still waiting in the cafeteria, **she called me**.

I started talking to her over the call, and shortly afterward, our cab finally arrived.

I continued talking to her during the cab ride as well.

After the long wait caused by the rain, I finally reached home around **7:50 PM**.

---

# 🏠 Night

After reaching home, I maintained my coding consistency by solving **one LeetCode problem**.

I then completed my usual daily chores.

Later, I talked to my family over a call and spent some time catching up with them.

I also spent some time with **her** before finally wrapping up the day.

After another productive and eventful day, I called it a day.

---

# 📌 Highlights of the Day

* Reached the office around **9:45 AM**.
* Got my latest feature branch tested and approved by Rajat Bhaiya.
* Completed almost all of the original **14 demo action items**.
* Reduced the remaining list to only **3 tasks**, mainly related to PPT generation and prompt improvements.
* Explored **Graphify** as a potential framework for building Graph RAG over a codebase.
* Read Graphify's repository, documentation, and related blogs.
* Attended a DSM meeting with the AI Infrastructure team.
* Observed how sprint meetings and task distribution are handled.
* Received micro-tasks along with the other interns.
* Tested the latest Agentic QA System branch with Rajat Bhaiya.
* Observed the increasing execution-time cost of adding more context to the agents.
* Pushed all feature branches.
* Created a consolidated branch containing the latest stable and working code.
* Played **pool for the first time in my life**.
* Completed **Draft 4 of my Nirma University research paper** while waiting for a cab.
* Solved **1 LeetCode problem**.
* Talked to my family and spent time with **her**.

---

# 💭 Reflection

Today felt like a day of both completion and exploration.

On one side, most of the 14 action items from our previous demonstration have now been implemented, leaving only three major areas to address. Getting my feature branch tested and approved was also a positive milestone.

On the other side, exploring Graphify opened another possible direction for solving one of the biggest challenges in our Agentic QA System: understanding relationships inside a large codebase and retrieving only the information that truly matters.

The testing session also highlighted an increasingly important problem. As our system becomes smarter and receives more context, it also becomes slower. The next stage of improvement cannot simply be about adding more data. We need to make the system more selective and efficient so that it can achieve better test-case coverage without unnecessarily increasing execution time and context-window usage.

Beyond work, the day had several memorable moments. I played pool for the first time, completed Draft 4 of my research paper while waiting because of the heavy rain, maintained my LeetCode consistency, and ended the day spending time with the people who matter to me.

Overall, it was a productive Tuesday filled with **development, technical exploration, system testing, new experiences, academic progress, and meaningful conversations**.

 ---


**Date:** 8 July 2026, Wednesday
**Day:** 261

---

# 🌅 Morning

Reached the office around **9:50 AM** and started the day with breakfast.

After breakfast, I headed to my workstation, set everything up, and prepared for the day's work.

Today had a very clear focus. Most of my work revolved around the **three remaining action items out of the original 14 points** that we had documented after our Agentic QA System demonstration.

Over the past few days, I had gradually completed almost all the technical improvements and feedback points. Now, only three tasks remained, and most of them were related to the **presentation and demonstration of the project**.

---

# 👥 Daily Scrum & Presentation Discussion

We had our daily **scrum meeting with Rajat Bhaiya**, where we discussed the remaining tasks and the presentation that needed to be prepared for the project.

Since most of the core development and feature-related action items had already been completed, today's priority was to make sure that the project could also be presented clearly and effectively.

We discussed what the presentation should cover, how the system should be explained, and how the overall flow of the Agentic QA System could be communicated to someone seeing the project for the first time.

The goal was not simply to create slides, but to build a presentation that was actually **demo-ready**.

---

# 📊 Building the Demo-Ready Project Presentation

I spent a major portion of the day working on the presentation for our **Agentic QA System**.

The project has grown considerably over time. It now includes multiple agents, several LLM calls, different retrieval mechanisms, context-management strategies, compaction approaches, monitoring dashboards, and test-case generation workflows.

Because of this, presenting the system in a simple and structured way required careful thought.

I worked on organizing the project into a clear story that could explain:

* The problem we are trying to solve
* Why an Agentic QA System is needed
* The overall architecture of the system
* How the orchestrator coordinates the workflow
* The role of different specialized agents
* How information is retrieved from different sources
* How the Knowledge Base contributes to the workflow
* How context is managed across LLM calls
* How test cases are generated
* The improvements made during recent iterations
* The current capabilities of the system

By the end of the work, I had created a **demo-ready presentation** for the project.

This was an important milestone because the system was now not only technically functional but also better prepared to be explained and demonstrated to a wider audience.

---

# 🍽️ Lunch

Later, we went for lunch and took a break from the morning's work.

After lunch, we returned for another technical and learning-focused session.

---

# 🏢 DSM with the Agentic AI Team

After lunch, I attended the **DSM meeting of Ankit Sir's Agentic AI team**.

These meetings have been useful because they allow us to observe how another team working on agentic systems approaches architecture, infrastructure, retrieval, and task execution.

During today's discussion, we learned about two particularly interesting concepts:

* **Google's OKF**
* **PageIndex**

The discussion gave us a better understanding of how modern AI systems can organize, retrieve, and connect information more intelligently.

This was especially relevant to our own work because we have been actively exploring ways to improve:

* Knowledge Base retrieval
* Context relevance
* Data linking
* Prompt efficiency
* Codebase understanding
* Test-case generation quality

The discussion around PageIndex connected directly with our recent exploration of Graph RAG, Vector Databases, and better methods for keeping only relevant information inside the LLM context window.

---

# 💻 LeetCode Practice

During the office day, I also found some time to solve **one LeetCode problem**.

Maintaining consistency with problem-solving practice alongside internship work and research has become an important part of my routine.

Another problem solved. Another day of consistency maintained.

---

# 📄 Research Paper Progress

I also made progress on my academic work today.

Yesterday, while waiting for a cab because of the heavy rain, I had completed **Draft 4 of my research paper** for Nirma University.

Today, after reviewing the draft, I sent **Draft 4** to **Priti Ma'am**, my internal guide, via email.

Submitting the updated draft marked another important step in the research-paper process. Now, I can wait for her feedback and use it to further improve the paper in the next revision.

Balancing internship work, the Agentic QA project, LeetCode practice, and academic research can sometimes be challenging, but it felt good to make progress across all of them today.

---

# 🚕 Journey Back Home

After completing the day's work, we left the office and headed home.

I reached home around **7:00 PM**.

---

# 🏠 Night

After reaching home, we had dinner.

Later, I talked to my family over a call and spent some time catching up with them.

I also talked to **her** over a call.

Afterward, I completed some of my usual daily chores and gradually wrapped up everything for the night.

With another productive day completed, I finally called it a day.

---

# 📌 Highlights of the Day

* Reached the office around **9:50 AM**.
* Focused on the final **3 remaining action items out of the original 14**.
* Had a scrum meeting with Rajat Bhaiya to discuss the project presentation.
* Created a **demo-ready PPT** for the Agentic QA System.
* Structured the project's architecture, workflow, capabilities, and progress into a clear presentation.
* Attended the DSM meeting of Ankit Sir's Agentic AI team.
* Learned about **Google's OKF** and **PageIndex**.
* Connected these concepts with our ongoing work on retrieval, context management, and Knowledge Base optimization.
* Solved **1 LeetCode problem** in the office.
* Sent **Draft 4 of my research paper** to Priti Ma'am, my internal guide.
* Reached home around **7:00 PM**.
* Talked to my family and **her** over calls.
* Completed my daily chores and wrapped up the day.

---

# 💭 Reflection

Today was largely about turning technical work into something that could be communicated effectively.

Over the past several days, I had been focused on implementing the 14 action items identified during our Agentic QA System demonstration. With most of the development work completed, today's focus shifted toward the final presentation-related tasks.

Creating a demo-ready presentation made me look at the project from a different perspective. Building a system and explaining a system are two very different challenges. A technically complex architecture only becomes truly valuable when its purpose, workflow, and impact can be communicated clearly.

The DSM discussion around Google's OKF and PageIndex also continued the larger theme of this week: improving how AI systems organize, retrieve, and reason over large amounts of information. These concepts are closely aligned with the challenges we are currently facing in our own system.

The day also brought progress outside the internship. Solving another LeetCode problem maintained my consistency, while sending Draft 4 of my research paper to Priti Ma'am marked another step forward in my academic work.

Overall, it was a focused and balanced Wednesday filled with **presentation building, technical learning, problem-solving, academic progress, and meaningful conversations**.


---


**Date:** 9 July 2026, Thursday
**Day:** 262

---

# 🌅 Morning

Reached the office around **10:10 AM** and started the day with a simple breakfast of:

* Milk
* Biscuits

After breakfast, I headed to my workstation and finished setting everything up by around **10:40 AM**.

Unlike the past several days, today was relatively light. I did not have any major development task or urgent action item assigned to me, especially since most of the important points from our previous Agentic QA System demonstration had already been completed.

---

# 👥 Daily Scrum & Automation Speed

We had our daily **scrum meeting with Rajat Bhaiya**, where the main topic of discussion was the **speed of automation generation**.

Over the past few iterations, our Agentic QA System has become increasingly capable. We have continuously added more sources of information, more context, better retrieval mechanisms, and additional processing steps to improve the quality and coverage of the generated test cases.

However, these improvements have also introduced an important trade-off: **the overall execution time has increased**.

During the scrum, we discussed the current speed of the automation-generation workflow and the time required for the complete execution to finish.

After the call, I started a fresh execution of the workflow.

Once the execution was completed, I collected screenshots of the **final deliverables** and sent them to Rajat Bhaiya for review and reference.

---

# 🏢 DSM with the Agentic AI Team

Later, I attended the **DSM meeting of Ankit Sir's Agentic AI team**.

During today's meeting, tasks were assigned to **Nikhil** and **Ayush**.

I was not assigned any additional task from this team because I am already actively working with **Rajat Bhaiya on the QA AI Platform**. Since my primary responsibilities are currently focused on the Agentic QA System, it made sense for me to continue concentrating on that project.

The meeting was still useful to attend because it gave me more exposure to the team's current work, task distribution, and ongoing discussions.

---

# 🍽️ Lunch

After the meeting, we went for lunch.

Today's menu included:

* Fruit Cupcake
* Veg Manchurian
* Chapati
* Matar Paneer
* Chana Rice
* Papad
* Salad

It was another good and filling office lunch.

---

# 🏔️ Planning the Haridwar–Rishikesh Trip

After lunch, I was almost completely free since there were no significant pending tasks for the day.

So, I decided to use the time to plan an upcoming **Haridwar and Rishikesh trip**.

I watched several travel videos about both destinations and started preparing an itinerary.

I explored different places to visit, routes, temples, sightseeing options, and ways to organize the limited time available during the trip.

It was a nice change from the usual technical work and made me even more excited about the upcoming journey.

---

# 🏠 An Early Return Home

We left the office earlier than usual and reached home around **4:00 PM**.

After reaching home, I was feeling tired, so I took a **one-hour power nap**.

The short nap helped me recharge before continuing with the rest of the evening.

---

# 🔧 Fixing the Geyser

Later, we finally got our broken geyser fixed with the help of an electrician.

It was one of those small but necessary household tasks that had been pending, so getting it repaired was a relief.

---

# 🥹 The Best News of the Day!

Later, I talked to my family over a call and got the most exciting news of the day.

**Guess whatttt!! Mummy and Papa are coming to Gurgaon tomorrow morning!! 🎉🥹**

They have already left from **Ahmedabad** and are on their way!

It has been almost **two months** since I last saw them, so I am genuinely very excited to meet them again.

Knowing that they are finally coming tomorrow completely changed the mood of the evening.

**Yayyy! Tomorrow morning cannot come soon enough! ❤️**

---

# 🧹 Preparing for Their Arrival

After hearing the news, I started preparing for my parents' arrival.

I made arrangements in their room and cleaned the house so that everything would be ready and comfortable when they arrived in the morning.

I organized the space, handled the necessary preparations, and made sure the house was in good shape to welcome them.

After finishing the cleaning and arrangements, I took a shower and relaxed for a while.

---

# 📞 Evening & Night

I also talked to **her** over a call for some time.

Before going to bed, I maintained my daily coding consistency by solving **one LeetCode problem**.

With the house cleaned, the room prepared, my parents already on their way from Ahmedabad, and another LeetCode problem completed, I finally called it a day.

Tomorrow is going to be special. ❤️

---

# 📌 Highlights of the Day

* Reached the office around **10:10 AM**.
* Discussed the speed of automation generation with Rajat Bhaiya.
* Executed the latest QA AI workflow and shared screenshots of the final deliverables.
* Attended the DSM meeting of Ankit Sir's Agentic AI team.
* Continued focusing on my primary work with Rajat Bhaiya on the **QA AI Platform**.
* Planned the upcoming **Haridwar–Rishikesh trip** by watching travel videos and preparing an itinerary.
* Reached home early around **4:00 PM**.
* Took a one-hour power nap.
* Got the broken geyser repaired with the help of an electrician.
* Found out that **Mummy and Papa are coming to Gurgaon tomorrow morning!**
* Prepared their room and cleaned the house for their arrival.
* Talked to **her** over a call.
* Solved **1 LeetCode problem** before sleeping.

---

# 💭 Reflection

Today was a much lighter day compared to the technically intense days of the past week.

At work, the main focus was simply monitoring the current automation-generation speed, running the latest workflow, and sharing the final deliverables with Rajat Bhaiya. With no major development tasks pending, I also had some time to plan the upcoming Haridwar–Rishikesh trip.

But the real highlight of the day had nothing to do with work.

Finding out that Mummy and Papa are already on their way to Gurgaon made me incredibly happy. It has been almost two months since I last saw them, and knowing that I will meet them tomorrow morning feels genuinely exciting.

The rest of the evening naturally became about preparing for them—fixing things around the house, arranging their room, cleaning up, and making sure everything was ready.

Overall, it was a calm Thursday filled with **light work, travel planning, household tasks, excitement, and anticipation**.

Tomorrow, after two long months, I finally get to see Mummy and Papa again. ❤️

---


**Date:** 10 July 2026, Friday
**Day:** 263

---

# 🌅 A Morning I Had Been Waiting For

I barely slept throughout the entire night.

The excitement was simply too much because **Mummy and Papa were finally coming to Gurgaon!**

After almost **two months** of staying away from home, I was finally going to meet them again. Every time I looked at the clock, it felt like morning couldn't arrive soon enough.

At around **6:00 AM**, I left for the railway station to receive them.

And finally...

**They were here. ❤️**

The moment I saw them stepping out of the station, I felt an overwhelming wave of happiness and relief. It is difficult to put into words how emotional that moment was. Two months may not sound like a very long time, but when you're away from your family, every week feels much longer.

Seeing them again, talking to them in person, and simply being together after such a long gap made the entire morning incredibly special.

---

# 💻 Work From Home

Since I wanted to spend the day with my parents, I took **Work From Home** today.

After getting home, I logged into my office laptop and completed the necessary work for the day.

The primary task I worked on was creating a **Wiki page** that provided an overview of our **QA AI Agent** project.

The documentation summarized the overall system and acted as a concise reference for the project. It also served as a meaningful work update for the day while keeping me available to spend time with my family.

Once the documentation was completed and my work responsibilities for the day were finished, I logged off and dedicated the rest of the day to my parents.

---

# ❤️ Family Time

The rest of the day was exactly what I had been looking forward to.

There was no rush, no meetings, and no deadlines.

Just quality time with Mummy and Papa.

We spent hours talking about everything that had happened over the past two months. I shared stories from my internship, life in Gurgaon, the projects I had been working on, and all the little experiences that are difficult to explain over phone calls.

We also rested for some time since everyone was tired from the journey.

It felt comforting to simply have them around after such a long time.

Sometimes, the best moments are the simplest ones.

---

# 🎒 Preparing for the Weekend Trip

Since we had already planned a short weekend getaway, we spent part of the evening preparing for our upcoming trip.

We packed our bags, checked our travel essentials, finalized the itinerary, and made sure everything was ready for departure.

The excitement continued because another memorable experience was just a few hours away.

---

# 🍽️ Dinner Together

One of the nicest parts of the day was having dinner together with Mummy and Papa.

After weeks of eating office meals and managing everything independently, sharing a meal with family again felt incredibly comforting.

There is something about eating together at the same table that simply feels like home.

---

# 🚆 Beginning the Journey

As the day came to an end, it was finally time to leave for our long-awaited weekend trip.

Around **11:30 PM** on Friday night, we left Gurgaon and started our journey towards **Haridwar and Rishikesh** for a two-day family trip.

The excitement of the upcoming pilgrimage and sightseeing, combined with finally being with my parents again, made the journey even more special.

---

# 💻 Daily Consistency

Before leaving for the trip, I continued my daily habit by solving **one LeetCode problem**.

No matter how busy or exciting the day gets, maintaining consistency in learning is something I always try to preserve.

---

# 📌 Highlights of the Day

* Stayed awake the entire night because of the excitement of meeting Mummy and Papa.
* Went to the railway station around **6:00 AM** to receive them.
* Met my parents after almost **two months**.
* Worked from home.
* Created a Wiki page documenting the overview of the **QA AI Agent** project.
* Spent the rest of the day talking, relaxing, and enjoying time with Mummy and Papa.
* Prepared for the upcoming **Haridwar–Rishikesh weekend trip**.
* Had dinner together with my parents.
* Left Gurgaon around **11:30 PM** for the two-day family trip.
* Solved **1 LeetCode problem** before starting the journey.

---

# 💭 Reflection

Today reminded me that some of the most meaningful days are not defined by how much work gets done, but by the people we get to spend them with.

Meeting Mummy and Papa after nearly two months was the happiest moment I have had in a long time. The excitement had kept me awake the entire night, and the moment I finally saw them at the railway station made every minute of waiting worthwhile.

Although I completed my office responsibilities by documenting the QA AI Agent project through a Wiki page, the real highlight of the day was simply being with my family again. Talking, resting, sharing meals, and preparing together for our upcoming Haridwar–Rishikesh trip brought a sense of comfort that had been missing for weeks.

As we boarded our journey late at night, I felt grateful—not just for the work I am doing, but for the opportunity to create memories with the people who matter the most.

It was a simple day, but one I know I will remember for a very long time. ❤️


---



**Date:** 13 July 2026, Monday
**Day:** 264

---

# 🌄 Returning from a Refreshing Weekend

After an incredibly memorable and beautiful weekend in **Haridwar and Rishikesh**, we returned feeling refreshed and mentally recharged.

The trip was a wonderful break from the regular work routine. Spending two days with Mummy and Papa, visiting the holy places, enjoying the peaceful atmosphere, and creating new memories together made it one of the most enjoyable weekends in recent months.

There was, however, one small concern during the trip. Due to the continuous travel, restlessness, and changes in food, **Papa's health deteriorated slightly** for a while. Thankfully, after getting some rest and taking proper care, he started feeling much better by the end of the same day, which was a huge relief for all of us.

---

# 💻 Work From Home

Since my parents were still with me, I continued with **Work From Home** today.

Around **10:30 AM**, I attended the daily **scrum meeting with Rajat Bhaiya**.

During the discussion, he asked me to explore and implement **Graphify** within our QA AI Agent project. The objective was to evaluate whether Graphify could provide practical benefits for our use case, particularly around code understanding, graph-based retrieval, and improving the overall quality of our Knowledge Base.

We discussed how Graphify might fit into our existing architecture and whether it could help us build a more effective Graph RAG pipeline for understanding relationships within the codebase.

---

# 🧠 Exploring Graphify

After spending the morning with my family and having lunch together, I started working on the Graphify implementation during the afternoon.

I integrated the framework into a local setup and began experimenting with its capabilities to understand how it represents a codebase as a graph and how effectively it can answer code-related queries.

The goal was not only to make Graphify work technically but also to evaluate whether it could realistically improve our existing QA AI Agent architecture.

It was an interesting exploration, as it aligned well with the retrieval and context-management problems we have been trying to solve over the past few weeks.

---

# 🍽️ Family Time

Apart from work, today was mostly about spending time with Mummy and Papa.

We had lunch together as a family and enjoyed a relaxed afternoon after the hectic weekend trip.

Since they were still visiting, I tried to make the most of every moment with them instead of staying occupied with work for the entire day.

I also managed to get some sleep during the afternoon, which helped me recover from the travel fatigue.

---

# 💻 Daily Consistency

Before the day got busy again, I maintained my routine by solving **one LeetCode problem**.

Keeping this habit alive, even during travel and family time, continues to be something I value.

---

# 🤒 An Unexpected End to the Day

Unfortunately, the evening did not go as smoothly as the rest of the day.

As the night progressed, **my own health started deteriorating**.

It began with general discomfort but gradually became much worse, eventually turning into a severe **upset stomach** and making me feel quite unwell.

To make matters more stressful, another issue arose at home.

Late at night, our **air conditioner suddenly stopped working** and kept switching off automatically.

After investigating the problem, we discovered that it was caused by an electrical switch issue. We contacted an electrician, who helped us resolve the problem.

Although the AC issue was eventually fixed, dealing with both the electrical problem and my worsening health made the end of the day quite exhausting.

---

# 🏙️ Change of Plans

Originally, we had planned to spend the day exploring **Gurgaon** with Mummy and Papa.

However, because of the health issues, we had to cancel all our plans.

Instead, we stayed home, rested, and focused on recovering.

Although it was disappointing to miss the outing, taking care of our health was far more important.

---

# 📌 Highlights of the Day

* Returned from a memorable and refreshing **Haridwar–Rishikesh** weekend trip.
* Felt mentally refreshed after spending quality time with family.
* Papa's health worsened slightly during the trip due to travel fatigue and food changes but recovered by the end of the day.
* Worked from home.
* Attended the daily scrum meeting with Rajat Bhaiya.
* Started exploring and implementing **Graphify** for the QA AI Agent project.
* Evaluated its potential usefulness for Graph RAG and codebase understanding.
* Had a family lunch and spent quality time with Mummy and Papa.
* Solved **1 LeetCode problem**.
* Took an afternoon nap to recover from travel fatigue.
* Planned to visit Gurgaon but cancelled because of health issues.
* Developed an upset stomach late at night.
* Resolved an unexpected AC electrical switch issue with the help of an electrician.

---

# 💭 Reflection

Today was a day of contrasts.

The memories from our Haridwar–Rishikesh trip left me feeling refreshed, peaceful, and grateful for the time I got to spend with my parents. Seeing Papa recover after his brief health issue during the trip was reassuring, and it made the weekend feel even more special.

Work remained meaningful as I began exploring Graphify, another promising direction that could potentially strengthen our QA AI Agent by improving graph-based retrieval and code understanding.

However, the day ended on a challenging note. My own health suddenly worsened, and the unexpected AC issue added to the stress. On top of that, we had to cancel our plans to explore Gurgaon with Mummy and Papa.

Even though things didn't go as planned, I was thankful that we were all together at home. Sometimes, simply resting with family nearby is far more valuable than any outing.

Overall, it was a day filled with **family, learning, recovery, and a reminder that health should always come first**.

---


**Date:** 14 July 2026, Tuesday
**Day:** 265

---

# 🌅 Morning

Today, I continued to work from home as I was still recovering from the stomach infection that had started the previous night. Although I was feeling slightly better than yesterday, my body still needed rest, so working remotely was the best option.

In the morning, **Rajat Bhaiya** called me regarding **HGW-2926**. One of the pending tasks involved deleting the unnecessary comments from the JIRA story. I worked on it immediately and completed the task before **11:00 AM**.

Later, during our daily discussions, I also demonstrated the **Graphify** work that I had been exploring. I explained the implementation, what I had learned from experimenting with it, and how it could potentially be useful for our QA AI Agent project, especially in the context of Graph RAG and codebase understanding.

---

# 💻 A Light Workday

Apart from the Graphify discussion and the JIRA cleanup task, there were no additional assignments for me today.

For once, I was actually grateful for having a lighter workload.

My body was still recovering from the previous day's illness, and the extra time allowed me to rest without worrying about pending office work.

Sometimes, slowing down is exactly what the body needs.

---

# ❤️ Grateful for Family

One thing I kept thinking throughout the day was how thankful I was that **Mummy and Papa were here with me**.

When I wasn't feeling well yesterday, they took care of me just like they always have.

Being away from home for months makes you realize how comforting a parent's presence really is. Whether it's simply asking if you've eaten, making sure you're resting, or just being around, their support brings a sense of peace that is difficult to describe.

I genuinely felt lucky that they happened to be here during the days when I needed them the most.

---

# 🏢 A Visit to My Office

Before leaving Gurgaon, there was one thing I really wanted to do.

I took **Mummy and Papa to my office** and showed them around my workplace.

I showed them where I spend most of my weekdays, the environment I work in, and the place where I have been learning, building projects, and growing professionally over the past few months.

Seeing their smiles while they walked through the office was incredibly special.

They looked genuinely happy and proud.

I also took a picture of them there—a memory that I know I will cherish for a very long time.

It wasn't just a photograph.

It felt like a small milestone.

For the first time, I was able to show my parents the place where I have been working hard every day, and seeing the happiness on their faces made me feel an incredible sense of accomplishment.

---

# 🚉 Saying Goodbye

As evening approached, it was finally time for them to begin their journey back home.

We prepared their luggage and headed towards the railway station.

Sitting in the cab with them, I slowly realized that the past four days had gone by so quickly.

It was difficult saying goodbye.

Watching them leave for Ahmedabad made me emotional once again.

After helping them board their train and making sure everything was settled, I stood there for a moment before heading back home.

The journey back felt much quieter than the journey to receive them a few days ago.

---

# 🏠 Returning to an Empty House

After coming back home, everything suddenly felt different.

Just a few hours earlier, the house was filled with conversations, laughter, family meals, and the comforting feeling of having Mummy and Papa around.

Now, it was quiet again.

Even though they had stayed for only **four days**, those few days had completely changed the feeling of this place.

For those four days...

**This house truly felt like home.**

---

# 💻 Daily Consistency

Before ending the day, I continued my daily routine by solving **one LeetCode problem**.

After that, I decided to sleep a little earlier than usual.

Partly because I was still recovering physically...

And partly because I knew the silence of the house would make me miss them even more.

---

# 📌 Highlights of the Day

* Continued working from home while recovering from poor gut health.
* Completed the **HGW-2926 JIRA comment cleanup** task before 11:00 AM.
* Demonstrated my **Graphify** implementation and findings during the team's discussion.
* Had a lighter workday, which helped me focus on recovering.
* Spent quality time with Mummy and Papa before their departure.
* Took them to my office and showed them my workplace.
* Captured a memorable photograph with them at my office.
* Dropped them at the railway station for their return journey.
* Solved **1 LeetCode problem**.
* Slept early to continue recovering.

---

# 💭 Reflection

Today was emotionally heavier than it was technically challenging.

Work was relatively light, and I was thankful for that because it gave me time to recover both physically and mentally. Completing the Graphify discussion and finishing the JIRA cleanup task were the only office responsibilities I had, allowing me to spend the rest of the day with Mummy and Papa before they left.

Taking them to my office became the most memorable moment of the day. Watching them walk through the place where I spend so much of my time and seeing how proud and happy they were is a memory I will always carry with me. That single photograph means much more than just a picture—it represents a chapter of my life that I was finally able to share with them.

Saying goodbye at the railway station wasn't easy. The house feels quieter now, and I already miss having them around.

For just four days, this place wasn't simply the flat where I live.

**It felt like home.**

**I love you, Mummy and Papa.**

**Miss you already. ❤️**


---



**Date:** 15 July 2026, Wednesday
**Day:** 266

---

# 🌅 Morning

Woke up around **8:00 AM** and got ready for the office.

I reached the office at approximately **10:20 AM** and started the day with breakfast:

* Cornflakes with milk

After breakfast, I set up my workstation around **10:45 AM** and prepared for the day's work.

Soon after, we had our daily **scrum meeting with Rajat Bhaiya**. During the meeting, I learned that we had an important **demo scheduled at 12:00 PM** with **Saravanan B. K.** The meeting was an opportunity to showcase the progress of our **QA AI Agent** platform and demonstrate the latest improvements we had been working on.

---

# 📊 Preparing for the Demo

Following the scrum meeting, Rajat Bhaiya and I focused entirely on preparing for the upcoming demonstration.

Using the guidance and feedback previously provided by **Kumar Kunal**, we refined our presentation and carefully reviewed the entire demo flow.

We made sure that:

* The presentation clearly explained the motivation behind the QA AI Agent.
* The architecture and workflow were easy to follow.
* The sequence of the demonstration was smooth.
* The latest features and improvements were highlighted.
* The overall story of the project was coherent and easy for stakeholders to understand.

By the time we finished preparing, we were confident that both the presentation and the live demonstration were ready.

---

# 👥 Demo Meeting with Saravanan B. K.

Around **12:00 PM**, we booked a training room on the **5th floor** and conducted the demonstration.

We showcased the **QA AI Agent** platform, walking through its architecture, workflow, and the recent enhancements made over the past few weeks.

During the discussion, **Saravanan B. K.** asked several technical questions, particularly around our **context compaction strategies** and the algorithms we had been experimenting with.

I answered questions related to:

* Context compaction approaches
* The reasoning behind our retrieval strategy
* The differences between various compaction techniques
* How these optimizations impact the quality of generated test cases

It was a valuable experience to participate actively in a stakeholder discussion rather than simply observing it. Answering technical questions helped strengthen both my understanding of the project and my confidence in explaining complex concepts to others.

Overall, the meeting went well and provided another great learning experience in both technical communication and product demonstration.

---

# 🎱 A Short Break

After the demo, we took a short break and went to play **pool** for some time.

Having recently learned the game, it has become a fun way to unwind between work sessions and spend some relaxed time with the team.

---

# 🍽️ Lunch

For lunch today, I had:

* Kadhi Pakoda
* Rice
* Salad
* One scoop of Vanilla Ice Cream

It was a simple but satisfying meal after the successful demo.

---

# 🤝 Welcoming a New Intern

The afternoon was comparatively relaxed, and I did not have any major development tasks assigned.

Today, a **new intern** joined the team.

Since I had experienced the first-day nervousness myself a few months ago, I introduced myself to him and spent some time talking with him to help him feel comfortable in the new environment.

We had a friendly conversation about the office, the team, and the work culture. It felt good to welcome someone new and hopefully make their first day a little easier.

---

# 💻 Learning & Personal Development

With a relatively free afternoon, I continued my daily learning routine by solving **one LeetCode problem**.

Maintaining this consistency has become an important habit, regardless of how busy or relaxed the workday is.

---

# ☕ Evening

Around **6:00 PM**, we went for evening snacks.

Today's menu included:

* Podi Idli
* Sandwich

After wrapping up work, I headed home and reached around **7:20 PM**.

---

# 🏠 Night

After reaching home, I completed my usual daily chores.

Later in the evening, I spent a long time talking with **Nikhil** and **Ayush**. It was a nice opportunity to have relaxed conversations outside of regular work discussions.

I also called my family and caught up with them after they had safely returned home from their visit.

After winding down for the day, I went to sleep.

---

# 📌 Highlights of the Day

* Woke up at **8:00 AM** and reached the office around **10:20 AM**.
* Prepared the QA AI Agent presentation with Rajat Bhaiya based on Kumar Kunal's guidance.
* Conducted the project demo with **Saravanan B. K.** in the 5th-floor training room.
* Answered technical questions related to **context compaction algorithms** and retrieval strategies.
* Gained valuable experience presenting technical concepts to stakeholders.
* Played pool after the successful demonstration.
* Had lunch consisting of Kadhi Pakoda, Rice, Salad, and Vanilla Ice Cream.
* Welcomed a new intern and helped him settle into the team.
* Solved **1 LeetCode problem**.
* Enjoyed evening snacks of Podi Idli and Sandwich.
* Spent time talking with Nikhil, Ayush, and my family.

---

# 💭 Reflection

Today was a rewarding blend of technical work, communication, and mentorship.

The highlight of the day was undoubtedly presenting our **QA AI Agent** to **Saravanan B. K.**. Over the past several weeks, I have spent countless hours working on different aspects of the project—from retrieval strategies and context compaction to test-case generation and system improvements. Being able to explain those concepts and answer technical questions during the demo made me realize how much my understanding has grown throughout the internship.

Another meaningful moment was welcoming the new intern. I still remember how unfamiliar everything felt on my own first day, so taking a few minutes to introduce myself and help someone else feel comfortable was a small gesture that felt worthwhile.

The day ended on a relaxed note with conversations with friends, family, and another LeetCode problem completed. Overall, it was a productive Wednesday filled with **preparation, presentation, learning, collaboration, and giving back in a small way to someone just beginning their internship journey**.


---



**Date:** 16 July 2026, Thursday
**Day:** 267

---

# 🌅 Morning

Reached the office around **10:00 AM** and started the day with breakfast:

* Cornflakes
* Chocos
* Milk

After breakfast, I set up my workstation and got ready for the day's work.

As usual, the morning began with the **daily scrum meeting with Rajat Bhaiya**. Since most of our recent tasks had already been completed and there were no major development activities planned for the day, the scrum was relatively short. We discussed the current status of the project, confirmed that there were no urgent action items, and reviewed the work planned for the upcoming days.

---

# 🧠 MARA Knowledge Transfer Session

With a comparatively lighter workload today, I decided to attend a **MARA Knowledge Transfer (KT) session**, which lasted for approximately **two hours**.

The session focused on the **internal MARA Agentic Framework**, an initiative designed to provide a standardized framework that can be adopted across various services within **Deutsche Telekom (DT)**.

During the KT, the team discussed:

* The overall vision behind the MARA framework.
* How agentic applications can be built using a common internal architecture.
* The importance of maintaining consistency across different AI services within DT.
* Standardization of workflows, components, and integrations.
* How different teams can build solutions that comply with the same framework and engineering practices.

Since I have been working extensively on our **QA AI Agent**, it was interesting to compare our current architecture with the ideas presented in MARA. The session provided useful insights into how large organizations approach reusable AI frameworks and establish common development standards across multiple teams.

---

# 🍽️ Lunch

Later in the afternoon, I went for lunch.

Today's menu included:

* Dal Chawal
* Papad
* Doodh Ka Halwa

It was a simple and comforting meal before returning to the rest of the day.

---

# 📞 A Relaxed Afternoon

After lunch, I called **her** and we talked for quite some time.

It turned into a long and relaxing conversation that lasted for a couple of hours. After the busy past few weeks filled with development work, demos, and travel, slowing down for a while and simply talking felt refreshing.

---

# 📚 Reviewing MARA & Learning

Later in the afternoon, I revisited the concepts covered during the MARA Knowledge Transfer session.

I reviewed the framework, went through the notes I had made, and spent some time understanding how its architecture aligns with our ongoing work on the QA AI Agent.

Although I did not have any major coding task today, it was still a productive learning session that expanded my understanding of internal AI infrastructure and enterprise-scale agentic systems.

As part of my daily routine, I also solved **one LeetCode problem**, continuing my consistency with problem-solving practice.

---

# 🚶 Evening

After wrapping up work, I headed back home.

Once home, I took some time to rest after the day, followed by dinner.

The relatively lighter schedule made it a good opportunity to recharge before the upcoming work.

---

# 🌙 Night

In the evening, I talked to my family over a call and caught up with them after their return home.

Later, I also spoke with **her** for a while before winding down for the night.

With another LeetCode problem solved, some new knowledge gained through the MARA framework, and a relaxed day spent balancing work and personal time, I finally called it a day.

---

# 📌 Highlights of the Day

* Reached the office around **10:00 AM**.
* Had breakfast of Cornflakes, Chocos, and Milk.
* Attended the daily scrum meeting with Rajat Bhaiya.
* Participated in a **2-hour MARA Knowledge Transfer** session.
* Learned about the internal **MARA Agentic Framework** and its role in standardizing AI services across Deutsche Telekom.
* Reviewed the MARA framework after the KT session.
* Had lunch consisting of Dal Chawal, Papad, and Doodh Ka Halwa.
* Spent some relaxing time talking with **her**.
* Solved **1 LeetCode problem**.
* Returned home, rested, had dinner, and talked with my family.

---

# 💭 Reflection

Today was a relatively calm and learning-oriented day.

Although there were no major development tasks to complete, attending the MARA Knowledge Transfer session was valuable. It provided a broader perspective on how enterprise-scale AI frameworks are designed to promote consistency and collaboration across different teams. Comparing those ideas with the architecture of our own QA AI Agent gave me new insights into how our project could evolve in the future.

Outside of work, the day offered a welcome opportunity to slow down. Long conversations with my family and **her**, along with some personal study and LeetCode practice, made for a balanced day after several weeks of intense development and project demonstrations.

Overall, it was a peaceful Thursday focused on **learning, reflection, continuous improvement, and maintaining a healthy balance between work and personal life**.


---



**Date:** 17 July 2026, Friday
**Day:** 268

---

# 🌅 Morning

Reached the office around **10:00 AM** and started the day with breakfast:

* Chocos with milk
* Peanut butter sandwich

After breakfast, I set up my workstation and was ready to start working by around **10:45 AM**.

The day started on a relatively light note. Since I did not have any immediate development tasks assigned, I spent some time exploring **YouTube** for inspiration on personal GitHub project ideas. I wanted to look at interesting open-source projects and explore ideas that I could potentially build in my free time to strengthen my portfolio and continue learning outside of work.

---

# 👥 A New Opportunity

Around **11:40 AM**, **Ankit Sir** invited me to join one of the **DSM meetings** for the Agentic AI project.

During the meeting, he introduced me to **Utkarsh Gupta** and assigned me to work under his guidance for a new initiative.

From the coming week onward, I will be contributing to work related to:

* **Guardrails**
* **LLM Evaluations (Evals)**
* **Automation Framework**

This marks the beginning of a new learning opportunity alongside my internship work.

To help me get familiar with the project, Ankit Sir also shared a **one-hour recorded Knowledge Transfer (KT) session**, which would serve as the introductory material for understanding the framework before starting development.

---

# 🍽️ Lunch

Around **1:00 PM**, we went for lunch.

Since I wasn't feeling particularly hungry today, I kept it simple and had:

* Dal Chawal

After lunch, I returned to my workstation and dedicated my time to completing the introductory KT video.

The recording provided a high-level understanding of the project, its objectives, and the architecture that I would be working with in the coming weeks.

---

# 📚 Beginning the MAGNUS Knowledge Transfer

After finishing the introductory recording, I reached out to **Utkarsh Gupta** over Teams for further guidance.

He promptly arranged another Knowledge Transfer session for all the interns from **4:30 PM to 5:40 PM**.

During this session, he explained the **MAGNUS Agentic Framework**, with today's discussion focusing primarily on the **frontend architecture**.

The session covered:

* The overall purpose of the MAGNUS framework.
* The frontend structure and navigation.
* How different modules interact.
* The workflow followed by the application.
* The technologies involved.
* The overall direction of the project.

It was a detailed and informative introduction that provided a much clearer picture of the framework.

By the end of the meeting, it was clear that **this project will become my primary focus starting Monday**, where we will gradually begin contributing to its development.

I am looking forward to working on a new codebase and learning about another large-scale agentic system.

---

# ☕ Evening Snacks

Later in the evening, we went for snacks.

Today's menu included:

* Momos
* French Fries

After wrapping up the day's learning sessions, I headed back home.

I reached home around **7:30 PM**.

---

# 🏠 Night

After reaching home, I completed my usual daily chores.

As part of my daily learning routine, I solved **one LeetCode problem**, continuing the consistency that I have maintained throughout the internship.

Later, I talked to my family over a call and caught up with them after their journey back home.

I also spent some time talking with **her** over a call before winding down for the night.

After another day filled with learning and a brand-new opportunity ahead, I finally went to sleep.

---

# 📌 Highlights of the Day

* Reached the office around **10:00 AM**.
* Started exploring ideas for future personal GitHub projects.
* Joined Ankit Sir's DSM meeting.
* Got assigned to work with **Utkarsh Gupta**.
* Learned that my upcoming work will focus on:

  * Guardrails
  * LLM Evaluations (Evals)
  * Automation Framework
* Received a one-hour introductory Knowledge Transfer recording.
* Completed the introductory KT session.
* Connected with Utkarsh Gupta for further guidance.
* Attended a **4:30 PM – 5:40 PM** Knowledge Transfer session on the **MAGNUS Agentic Framework**.
* Learned about the frontend architecture and workflow of the project.
* Prepared to begin working on the new project starting Monday.
* Had evening snacks of Momos and French Fries.
* Solved **1 LeetCode problem**.
* Talked with my family and **her** before ending the day.

---

# 💭 Reflection

Today marked the beginning of an exciting new chapter in my internship.

After spending the past several weeks working extensively on the **QA AI Agent**, I have now been introduced to another large-scale project—the **MAGNUS Agentic Framework**. Being assigned to work on areas such as **Guardrails**, **LLM Evaluations**, and the **Automation Framework** is a great opportunity to explore another important aspect of AI system development.

The Knowledge Transfer sessions gave me an initial understanding of the project and helped reduce the learning curve before I begin contributing next week. It feels exciting to start fresh on a new codebase while carrying forward everything I have learned from the QA AI Agent project.

Outside of work, it was another balanced day with time for learning, planning personal GitHub projects, maintaining my LeetCode streak, and spending time talking with my family and **her**.

Overall, it was a productive Friday centered around **new beginnings, knowledge transfer, continuous learning, and preparing for the next phase of my internship journey**.


---

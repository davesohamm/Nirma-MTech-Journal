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

# 📘 MTech Data Science Daily Academic Journal  
**University:** Nirma University  
**Program:** M.Tech in Data Science  
**Month:** October  

**Click here to read:** [September Journal](https://github.com/davesohamm/Nirma-MTech-Journal/blob/main/September/README.md)

---

## DAY - 51 : **1 October 2025 (Wednesday)**

### 🏠 Before College
- Solved **3 LeetCode problems** in the morning.

---

### 🧑‍🏫 11:40 AM – 1:30 PM  
**Data Science System Design Lab** — *by Monika Shah Ma’am*  
- Worked on system design tasks related to distributed systems and data/query flow.

---

### 🍽️ 1:30 PM – 2:25 PM  
**Recess**

---

### 🤖 2:25 PM – 3:20 PM  
**Applied Machine Learning** — *by N. K. Patel (NKP) Sir*

Sir discussed **Activation Functions**, mainly focusing on the **Step Activation Function**.

#### **Step Activation Function**
\[
f(x) = 
\begin{cases}
1 & \text{if } x \ge 0 \\
0 & \text{if } x < 0
\end{cases}
\]

- We also discussed **learning step** and compared different activation function behavior graphs:  
  - Step Function  
  - Sigmoid  
  - Tanh  
  - ReLU  

---

### 💻 3:20 PM – 4:15 PM  
**Data Structures & Algorithms** — *by Ankit Thakkar Sir*  

Sir taught **0/1 Knapsack Problem** using Dynamic Programming and **Floyd's All-Pairs Shortest Path Algorithm**.

#### **0/1 Knapsack DP Formula**
Let:
- `wt[i]` = weight of item `i`
- `val[i]` = value of item `i`
- `W` = maximum capacity

\[
dp[i][w] = 
\begin{cases}
dp[i-1][w] & \text{if } wt[i] > w \\
\max(dp[i-1][w],\ dp[i-1][w - wt[i]] + val[i]) & \text{if } wt[i] \le w
\end{cases}
\]

#### **Floyd’s All-Pairs Shortest Path (Floyd–Warshall Algorithm)**
Let `dist[i][j]` = shortest distance between nodes `i` and `j`.

\[
dist[i][j] = \min(dist[i][j],\ dist[i][k] + dist[k][j])
\]

This update is applied for all vertices `k` as an intermediate node.

---

### 🧪 4:15 PM – 6:20 PM  
**Applied Machine Learning Lab** — *by NKP Sir*  
- Continued implementation of activation functions and observed learning behavior across iterations.

---
## DAY - 52 : **3 October 2025 (Friday)**

### 🏠 Before College
- Completed **1 LeetCode problem** in the morning.

---

### 🧑‍💻 11:40 AM – 1:30 PM  
**DSA Lab** — *by Ankit Thakkar Sir*  
- Continued implementation practice for Dynamic Programming and Graph Algorithms.

---

### 🧑‍🏫 2:25 PM – 3:20 PM  
**Data Science System Design** — *by Monika Shah Ma’am*

Topic: **Rate Limiting Algorithms**

We studied different strategies to control request flow in distributed systems:

| Technique | Concept Summary |
|----------|----------------|
| **Token Bucket** | Tokens refill at a fixed rate. A request is allowed if a token is available. |
| **Leaking Bucket** | Requests are processed at a fixed output rate regardless of burst traffic. |
| **Fixed Window Counter** | Requests are counted in fixed time windows; simple but causes burst issues at window boundaries. |
| **Sliding Window Log** | Stores timestamps of requests; more accurate but uses more memory. |
| **Sliding Window Counter** | Uses weighted counts for previous and current windows to smooth burst effects. |

---

### 📊 3:20 PM – 4:15 PM  
**Statistics** — *by Swati Jain Ma’am*

Topics Covered:
- **Critical Region** and hypothesis testing decision rule.
- **Chi-Square Test for Homogeneity / Uniformity**
- Solved numerical examples in class.

#### **Critical Region Concept**
A **critical region** is the range of values of a test statistic that leads to the rejection of the null hypothesis.

If  
\[
\text{Test Statistic} \in \text{Critical Region}
\]
→ Reject \(H_0\)

#### **Chi-Square Test Statistic Formula**
\[
\chi^2 = \sum \frac{(O - E)^2}{E}
\]

Where:  
- \(O\) = Observed frequency  
- \(E\) = Expected frequency  

Decision rule depends on significance level \( \alpha \) and degrees of freedom.

---

## DAY - 53 : **4 October 2025 (Saturday)**

### 🚀 Weekend, but Special!
Participated in the **NASA Space Apps 2025 Global Hackathon**.

### 🌐 Project Developed:
**Project Name:** ISSperience  
A web-based interactive experience that visualizes the **International Space Station’s real-time location, data, and mission environment**.

🔗 **Live Project:** https://issperience.netlify.app/  
💻 **Repository & Certificate:** https://github.com/davesohamm/NASA-SpaceApps-2025  

### 🗒️ Experience
- Collaborated with a team on space visualization & real-time telemetry.
- Worked with APIs, frontend visualization, and interaction design.
- Explored datasets related to **orbit paths, astronaut data, and ISS environment**.
- Learned how global scientific hackathons are structured — **super inspiring**.

---

## DAY - 54 : **5 October 2025 (Sunday)**

### 🚀 Continued NASA Space Apps Hackathon
Second day of the hackathon — refinement, presentation & submission.

### 🎯 What I Focused On:
- Improved the UI & visual storytelling of the web app.
- Optimized API calls for smoother real-time tracking.
- Prepared final explanation, screenshots, and submission details.

### 🏁 Outcome
- Successfully completed & submitted the project.
- Received **participation certificate**.
- Gained strong experience in:
  - Teamwork & rapid prototyping
  - Data visualization
  - Real-world scientific computing challenges

### 💭 Reflection
This hackathon boosted my confidence in:
- Working under time pressure
- Turning ideas into live products
- Communicating scientific data in a meaningful way

It was a **memorable learning journey.**

---

## DAY - 55 : **6 October 2025 (Monday)**

### 🏠 Before College
- Solved **1 LeetCode problem** in the morning.

---

### 🗄️ 11:40 AM – 12:35 PM  
**Big Data Systems** — *by JV Sir*

Topics Discussed:
- Difference between **SQL vs NoSQL**
- **ACID** vs **BASE** properties
- Types of NoSQL Databases:  
  - Key-Value  
  - Document  
  - Column Family  
  - Graph-based Databases
- Use-cases, advantages & trade-offs of NoSQL systems

---

### 🎤 12:35 PM – 1:30 PM  
**Expert Lecture on GenAI & LLMs (Industry Perspective)**

Key Takeaways:
- What happens *internally* when we send a **prompt** to a model
- How GenAI tools are used in **enterprise workflows**
- Improving productivity using AI assistants and automation
- **Core learning:**  
  The combination to become a strong **Software Engineer**:

\[
\textbf{Real World Understanding} + \textbf{SDE Skills} + \textbf{AI Tools} + \textbf{Problem Solving Mindset}
\]

---

### 🍽️ 1:30 PM – 2:25 PM  
**Recess**

---

### 💻 2:25 PM – 4:15 PM  
**Big Data Systems Lab** — *by JV Sir*

Lab Work:
- Configured **Apache Hive** on local systems
- Executed **HQL queries** on sample datasets
- Understood Hive’s metadata storage & execution behavior

---

### 📚 4:20 PM – 7:00 PM  
**Library & Personal Enrichment**

Found and read **Amrita Pritam’s** book *“Kaagaz Aur Canvas.”*  
- Completed it in one sitting.
- The poetry felt **deep, graceful, and ahead of its time**.
- Admired how she expressed emotions with simplicity yet intensity.
- A refreshing experience for the mind.

---




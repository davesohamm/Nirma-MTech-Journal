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

**Real World Understanding** + **SDE Skills** + **AI Tools** + **Problem Solving Mindset**

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

## DAY - 56 : **7 October 2025 (Tuesday)**

### 🏠 Before College
- Solved **1 LeetCode problem** in the morning.

---

### 📊 9:50 AM – 11:40 AM  
**Statistics Lab** — *by Swati Jain Ma’am*

Performed **One-Way Latency Analysis** on two different datasets.

Ma’am explained two hypothesis testing approaches:

| Method | Null Hypothesis (H₀) | Alternative Hypothesis (H₁) |
|-------|----------------------|------------------------------|
| Method 1 | Mean latency of **5G = 4G** | H₀ is wrong (means differ) |
| Method 2 | Both datasets have **same characteristics** | Both are **not same** |

- Computed test values
- Compared with critical region
- Concluded whether to **accept or reject H₀**

---

### 🗄️ 11:40 AM – 12:35 PM  
**Big Data Systems** — *by JV Sir*

- Explained the **Term Paper Template** structure:
  - Abstract  
  - Introduction  
  - Literature Review  
  - Methodology  
  - Results & Findings  
  - Conclusion  
  - References  

---

### 🧑‍💻 12:35 PM – 1:30 PM  
**Data Science System Design** — *by Monika Shah Ma’am*

Topics covered:
- **Rate Limiter Concepts**
- **Token Bucket Mechanism**
- **Requests Per Second (RPS)** Handling
- Logging & Monitoring in distributed loads
- **Singleton Design Pattern** in service instances

---

### 🍽️ 1:30 PM – 2:25 PM  
**Recess**

---

### 🔢 2:25 PM – 3:20 PM  
**Data Structures & Algorithms** — *by Ankit Thakkar Sir*

- Continued **Floyd’s All-Pairs Shortest Path Algorithm**
- Discussed key **Graph Theory** fundamentals:
  - Directed / Undirected Graphs
  - Degrees of vertices
  - Connectivity & path relations

---

### 📚 3:20 PM – 4:15 PM  
**Statistics Lecture** — *by Swati Jain Ma’am*

- Ma'am explained her **INS Valsura** project (Indian Navy).
- Discussed:
  - Operational data validation
  - Statistical inference in defense systems
  - Real-world application of hypothesis testing on naval equipment performance

---

## DAY - 57 : **8 October 2025 (Wednesday)**

### 🏠 Before College
- Solved **3 LeetCode problems** in the morning.

---

### 🧑‍💻 11:40 AM – 1:30 PM  
**Data Science System Design Lab** — *by Monika Shah Ma’am*

Topics Covered:
- **Database Sharding**
  - Concept of splitting large datasets across multiple servers for scalability.
  - Horizontal vs Vertical Sharding.
  - Real-world use cases in large distributed systems.
- Performed practical implementation and understood shard key selection importance.

---

### 🍽️ 1:30 PM – 2:25 PM  
**Recess**

---

### 🤖 2:25 PM – 3:20 PM  
**Applied Machine Learning** — *by NKP Sir*

Topics Discussed:
- **Neural Networks Architecture**
  - Input layer → Hidden layer(s) → Output layer.
  - Weights, biases, and forward propagation.
- **Need for Activation Functions**
  - To introduce non-linearity for learning complex patterns.
- Activation Functions Reviewed:
  - Step Function
  - Sigmoid
  - Tanh
  - ReLU
  - Softmax (for multi-class output)

---

### 🔍 3:20 PM – 4:15 PM  
**Data Structures & Algorithms** — *by Ankit Thakkar Sir*

Topics Covered:
- **Graph Searching Algorithms**
  - **BFS (Breadth-First Search)**
  - **DFS (Depth-First Search)**
- Understood their queue/stack based implementations.
- Discussed where **backtracking** appears in DFS-based solutions.

---

### 🧪 4:20 PM – 6:20 PM  
**Applied Machine Learning Lab** — *by NKP Sir*

Lab Tasks:
- Implemented all **three Decision Tree algorithms** from scratch on the **Iris dataset**:
  - ID3
  - C4.5
  - CART
- Sir asked us to research:
  - **Cost Complexity Pruning (CCP)**  
  - Why adjusting CCP parameter leads to **C4.5-like pruning behavior**.

Key Insight:
**CCP balances model complexity vs accuracy by penalizing deeper trees.**

---

## DAY - 58 : **9 October 2025 (Thursday)**

### 🏠 Before College
- Solved **3 LeetCode problems** in the morning.

---

### 📊 11:40 AM – 12:35 PM  
**Statistics** — *by Swati Jain Ma’am*

- It was a proxy lecture session.
- Utilized the time to **complete Applied Machine Learning Lab work**.

---

### 🎤 12:35 PM – 1:30 PM  
**Alumni Talk** — by **Vimal Sheoran** (M.Tech DS, 2022 | Currently at *Infocusp*)

Key Takeaways:
- **Be honest** to yourself and your work.
- **Go beyond** the classroom — extend learning on your own.
- **Write code yourself** — don’t rely on shortcuts.
- In M.Tech, **there is no CGPA recovery semester** → perform consistently.
- **Technical writing** is a valuable hard skill → helps in research, communication, and industry.

---

### 🍽️ 1:30 PM – 2:25 PM  
**Recess**

---

### 🤖 2:25 PM – 3:20 PM  
**Applied Machine Learning** — *by NKP Sir*

Topics Covered:
- **Learning Step in Perceptron**
- Solved a **detailed perceptron learning example** step-by-step.
- Understood weight updates over iterations.

---

### 🎤 3:20 PM – 4:15 PM  
**Alumni Talk** — by **Jenil Sadrani** (Cyber Security Domain)

Encouragement & Guidance:
- Start career exploration in **Cyber Security & CTFs**.
- Recommended Certifications:
  - **SC-200**
  - **CEH**
  - **eJPT**
  - **PNPT**
  - **AZ-500**
- Start practicing on:
  - **TryHackMe**
  - **HackTheBox**

---

### 🗄️ 4:30 PM – 6:20 PM  
**Big Data Systems** — *by JV Sir*

Topic:
- Continued explanation of **NoSQL Databases**:
  - Flexible schema
  - Horizontal scaling
  - Real-time analytics usage scenarios

---

## DAY - 59 : **10 October 2025 (Friday)**

### 🏠 Before College
- Solved **1 LeetCode problem** in the morning.

---

### 💻 11:40 AM – 1:30 PM  
**DSA Lab** — *by Ankit Thakkar Sir*

Lab Evaluation:
- **Make Change (Greedy Approach)** → Scored **10/10**
- **Kruskal's Minimum Spanning Tree Algorithm** → Scored **9/10**

Feeling very happy and confident with consistency in DSA lab work.

---

### 🍽️ 1:30 PM – 2:25 PM  
**Recess**

---

### 🧑‍💻 2:25 PM – 3:20 PM  
**Data Science System Design** — *by Monika Shah Ma’am*

Topics Covered:
- **Message Queues** (Asynchronous communication between services)
- **Monitoring and Logging** in distributed systems
- **Clock Synchronization** in multi-node environments

---

### 📊 3:20 PM – 4:15 PM  
**Statistics** — *by Swati Jain Ma’am*

Topic: **ANOVA (Analysis of Variance)**

Concepts Learned:
- **Dependent (Response) Variable**
- **Independent (Predictor) Variables**
- **Factors and Levels**
- **Fixed Factor Model** vs **Random Factor Model**
- **F-score tables**
- **One-Way ANOVA**
- Applications in real-world statistical inference

Ma’am also solved a **detailed example** in class for clarity.

---

### 💾 4:30 PM – 6:20 PM  
**ProgCode Lab**

- Continued programming practice and lab exercises.

---


## DAY - 60 : 13 October 2025 (Monday)

**Before College**  
- Solved one LeetCode problem.

---

### 11:30 AM to 12:35 PM — Big Data Systems (JV Sir)
- Sir asked for our **term papers**.
- Conducted **evaluation** of the submissions.

---

### 12:35 PM to 1:30 PM — Alumni Talk (L Engineer + InFocusP)
- She explained:
  - **Bell curves of life**
  - **Agentic AI**
  - Importance of **Kaggle competitions**
  - **Cloud basics are must**:
    - AWS SageMaker
    - Azure ML
    - GCP Vertex AI
- Discussed **I-shaped**, **Dash-shaped**, **Zig-Zag-shaped** people vs **T-shaped** people (combination of depth + breadth).

---

### 1:30 PM to 2:25 PM — Recess

---

### 2:25 PM to 4:30 PM — Big Data Systems Lab (JV Sir)
- Practical lab work continued under guidance of sir.

---

## DAY - 61 : 14 October 2025 (Tuesday) ✨

**Before College**  
- Solved **7 LeetCode problems** 🧠💻

---

### 11:40 AM to 12:35 PM — Big Data Systems (JV Sir) 📊
- Sir announced **sessional exam marks**.
- I scored **45/50** 🎉🔥 (2nd highest in the class!)
- Felt **very happy and motivated** 😄

---

### 12:35 PM to 1:30 PM — Data Science System Design (Monika Shah Ma'am) 🏗️
- Learned about **ATA Model**.
- Ma'am explained how to **implement Message Queue** in the lab 📨⚙️

---

### 1:30 PM to 2:25 PM — Recess 🍽️

---

### 2:25 PM to 3:20 PM — DSA (Ankit Thakkar Sir) 🧮
- Topics covered:
  - **Branch and Bound**
  - **Assignment Problem**
- Understood both logic and approach 👨‍🏫

---

### 3:20 PM to 4:15 PM — Statistics (Swati Jain Ma'am) 📐
- Continued with **ANOVA Testing**.
- Solved more **practice examples** to strengthen understanding ✍️📘

---

### 4:30 PM to 6:20 PM — Statistics Lab (Swati Jain Ma'am) 🧪
- Lab work **checked and evaluated**.
- Performed **ANOVA Testing** using:
  - **Python** 🐍
  - **Excel** 📊

---

## DAY - 62: 15 October 2025 (Wednesday) 🌿

**Before College**  
- Solved **1 LeetCode problem** 🧠

---

### 11:40 AM to 1:30 PM — Data Science System Design Lab (Monika Shah Ma'am) 🏗️
- Performed lab work on **MongoDB**:
  - **Write Concern**
  - **Read Concern**
  - **Auto Failover**  
- Understood how data consistency levels and cluster failover mechanisms work in distributed systems ⚙️🗄️

---

### 1:30 PM to 2:25 PM — Recess 🍛

---

### 2:25 PM to 3:20 PM — Applied Machine Learning (NKP Sir) 🤖
- Sir explained:
  - **Forward Propagation & Backward Propagation** for 2-layer Neural Network (with derivations) 🧮
  - Concept of **Autodifferentiation (AutoDiff)** used in **TensorFlow** and **Keras** 🔄
- It was a deep mathematical lecture — very insightful 🔍

---

### 3:20 PM to 4:15 PM — DSA (Ankit Thakkar Sir) 🧵
- Learned **Binomial Heap**:
  - Structure and properties
  - Operations:
    - Create Binomial Heap
    - Find Minimum
    - **Union of 2 Binomial Heaps** (4 cases explained clearly)  
- Good conceptual clarity 📚

---

### 4:30 PM to 6:20 PM — Applied Machine Learning Lab (NKP Sir) 🧪
- **Viva / Lab Evaluation**  
- Questions asked (and I answered well ✅):

  1. `np.eye()` function 🧱  
  2. `pandas.read_csv(separator=',')` usage  
  3. **SLR vs MLR** — differences in formulas 📈  
  4. **Ridge vs Lasso** — when to use which  
  5. **Elastic Net** and how to convert it to **Lasso**  
  6. **Gaussian, Bernoulli, Multinomial** distributions — usage scenario 📊  
  7. **Entropy vs Gini**, and their ranges  
  8. Differences among **ID3, CART, C4.5** 🌳

- Overall, **my viva went very well**. I answered almost everything confidently 😄💯

---

## DAY 63 — 16 October 2025 (Thursday) 📘

**Before College**  
- Solved **1 LeetCode problem** 🧠

---

### 11:40 AM to 12:35 PM — Statistics (Swati Jain Ma'am) 📊
- I **skipped the lecture** because I had **Teaching Assistant** duty.
- Used this time productively and solved **5 more LeetCode problems** ✅🔥

---

### 12:35 PM to 1:30 PM — Capstone Course 🧩
- Topic: **Operating System — Uniprocessor Scheduling**
- Learned:
  - **PCB (Process Control Block)**
  - **Scheduling Queue**
  - **CPU Burst** & **I/O Burst**
  - **Schedulers** (Long-term, Short-term, Medium-term)
- Understood how OS manages processes and allocates CPU time ⚙️🖥️

---

### 1:30 PM to 2:25 PM — Recess 🍲

---

### 2:25 PM to 3:20 PM — Applied Machine Learning (NKP Sir) 🤖
- Continued **Backpropagation**
- Sir solved a **large numerical example** step-by-step.
- Very important lecture — sir mentioned this exact type can come in exams ✍️

---

### 3:20 PM to 4:15 PM — DSA (Proxy by NKP Sir) 🔄
- Instead of DSA, NKP sir taught:
  - **Semi-Supervised Learning**  
    - *Self Training*
    - *Co-Training*
  - **Reinforcement Learning**
  - Discussed **UNSW-NB15 Intrusion Detection Dataset** (cybersecurity context) 🔐

---

### 4:30 PM to 5:25 PM — Big Data Systems (JV Sir) 🗄️
- Continued **NoSQL Databases** — explained types in depth:

#### Types of NoSQL Databases:
| Type | Explanation |
|------|-------------|
| **Key-Value Store** | Stores data as pairs (key → value). Very fast lookups. Used where simple retrieval is needed. Examples: Redis, DynamoDB. |
| **Document Store** | Data stored in JSON-like documents with flexible schemas. Good when structure varies. Examples: MongoDB, CouchDB. |
| **Column-Family Store** | Data stored in columns rather than rows. Excellent for analytical queries over huge datasets. Examples: Cassandra, HBase. |
| **Graph Databases** | Stores data as nodes and relationships. Ideal for recommendation engines, social networks. Example: Neo4j. |

- After this, sir **started MongoDB chapter** 🟢

---

✅ **A productive day overall** — balanced teaching work, assignments, and solid ML + OS + NoSQL concepts.
---

## DAY 64 — 17 October 2025 (Friday) 🎉

**Before College**  
- Solved **ProgCode Week 3** problems — **10 DSA questions** completed 🧠💻

---

### 11:40 AM to 12:35 PM — Statistics (Swati Jain Ma'am) 📊
- Sir (Ankit Thakkar) was unavailable, so this slot was taken by Swati ma'am.
- Topics Covered:
  - **Correlation Analysis**
  - **Correlation Coefficient** and **Degree of Correlation**
  - **Karl Pearson’s Coefficient of Correlation**
  - Learned both **Direct Method** and **Shortcut Method** formulas ✍️

---

### 12:35 PM to 1:30 PM — Data Science System Design (Monika Shah Ma'am) 🧱
- Ma'am explained **Data Models**.
- Meanwhile... we were **playing Hill Climb Racing** at the back of the class 😆🎮  
  (*Peak Friday vibes*)

---

### After 1:30 PM — Free from College 🎒
- Had lunch 🍱
- Returned home in **2 PM heat** 😓🌞
- Found a **small teddy bear** in college and gave it to a **poor roadside girl** ❤️  
  → She smiled. It felt nice :)

---

### ☀️ Going Home for Diwali Vacation ☀️
- Going to my hometown **Dahegam** 🏡
- Holidays start now!!
- **See you on 27th October** 🎇✨
- *DIWALIIIII HOLIDAYSSSS LET’S GOOOOOO* 🎉🔥🎆

---








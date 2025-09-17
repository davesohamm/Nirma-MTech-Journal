# 📘 MTech Data Science Daily Academic Journal  
**University:** Nirma University  
**Program:** M.Tech in Data Science  
**Month** September 

**Click here to read** [August Journal](https://github.com/davesohamm/Nirma-MTech-Journal/blob/main/August/README.md)

---

## 🗓️ Day 29 - September 1, 2025 (Monday)

---

### 🌅 Pre-College Activity
- **Finetuned Ubuntu setup** on my laptop.  
- **Re-configured Hadoop** for the upcoming Big Data Systems lab.  

---

### 📚 Lectures

#### 🖥️ Big Data Systems (11:40 AM – 12:35 PM) – *JV Sir*
- Topic: **Hadoop Ecosystem**  
- Covered: Pig, Hive, HBase, Sqoop, Mahout, Oozie, Zookeeper, MapReduce, HDFS, etc.  
- Explained **CAP Theorem**.  
- In-depth discussion on:  
  - **HBase**: A distributed, scalable, NoSQL database that runs on top of HDFS. It provides real-time read/write access to large datasets and supports structured as well as semi-structured data.  
  - **Hive**: A data warehouse system built on Hadoop, allowing SQL-like queries (HiveQL) to analyze large datasets. It is more suitable for batch processing and reporting.  
  - **Pig**: A high-level platform for creating MapReduce programs using Pig Latin, a scripting language that simplifies complex data transformations and analysis.  

#### 🤖 Applied Machine Learning (12:35 PM – 1:30 PM) – *NKP Sir*
- Topic: **Naive Bayes Classification**  
- Covered probability basics:  
  - Conditional Probability:  
    \[
    P(A|B) = \frac{P(A \cap B)}{P(B)} = \frac{P(A,B)}{P(B)}
    \]  
  - Independent Probability:  
    \[
    P(A|B) = P(A) \quad \text{or} \quad P(B|A) = P(B)
    \]  
- **Bayes Theorem:**  
  \[
  P(C_k|X) = \frac{P(C_k) P(X|C_k)}{P(X)}
  \]  
  where \(C_k\) are classes and \(X = (x_1, x_2, \dots, x_n)\) are features.  
- Proved the formula mathematically.  
- For comparison (like \(P(C_1|X) / P(C_2|X)\)), \(P(X)\) can be ignored.  
- Derived **Naive Bayes Classifier Equation:**  
  \[
  P(C_k|X) \propto P(C_k) \prod_{i=1}^{n} P(x_i|C_k)
  \]  

---

### ☕ Recess (1:30 PM – 2:25 PM)

---

### 🧪 Big Data Systems Lab (2:25 PM – 4:15 PM) – *JV Sir*
- Performed **Hadoop shell commands**.  
- Received guidance for **Innovative Assignment Project**:  
  *Big Data–Driven Crime Analytics, Hotspot Prediction, and Real-Time Crowd Violence Detection using Machine Learning.*  

---

### 📖 Self-Study (4:15 PM – 6:20 PM)
- Sat in the **library**.  
- Solved **1 LeetCode problem**.  
- Completed **college work revision**.  

---

### 💭 Personal Note
Today is **her birthday**! 🎂❤️❤️  
*Happy Birthday!! Miss youuu* 🥰  

---

## 🗓️ Day 30 - September 2, 2025 (Tuesday)

---

### 🌅 Pre-College Activity
- Solved **1 DSA problem** before leaving for college.  

---

### 📚 Lectures

#### 🖥️ Big Data Systems (11:40 AM – 12:35 PM) – *JV Sir*
- Discussed **Pig** and **Hive**: their advantages, disadvantages, similarities, and differences with **Impala**.  
- Introduced **Apache Derby** and its usefulness in **edge computing**.  
- Explained **Sqoop** – a CLI tool for transferring data between relational databases and Hadoop.  
- Talked about **Flume** and its role in collecting and aggregating log/event data.  
- Discussed **Hue** (Hadoop User Experience) and **Zookeeper**.  
- Guided us on writing the **term paper** for Big Data Systems subject.  

#### 🧮 Data Science System Design (12:35 PM – 1:30 PM) – *Monika Shah Ma’am*
- Topic: **Machine Learning Project Life Cycle**.  
- Explained the process of **framing a data science problem** in two perspectives, with step-by-step methods.  
- Highlighted **similarities and differences** between the approaches.  

---

### ☕ Recess (1:30 PM – 2:25 PM)

---

### 🔢 DSA (2:25 PM – 3:20 PM) – *Ankit Sir*
- Topic: **Quick Sort Algorithm**.  
- Explained Quick Sort with **last element as pivot** and analyzed its **time complexity**.  
- Introduced **Randomized Quick Sort** and **Lomuto’s Partition Method**.  
- Derived formula for the **expected value of total comparisons** in all partition calls:  
  - Used variable \( Z_i \), where \( Z_i \) is the *i-th smallest element*.  

#### 📊 Statistics (3:20 PM – 4:15 PM) – *Swati Jain Ma’am*
- Topics Covered:  
  - **Negative Binomial Distribution** – derived formulas for mean (\(\mu\)) and variance (\(\sigma^2\)).  
  - **Hypergeometric Distribution** –  
    \[
    f(x) = \frac{\binom{K}{x} \binom{N-K}{n-x}}{\binom{N}{n}}
    \]  
    where \(x = \max(0, n+K-N) \dots \min(K, n)\).  
    Derived mean and variance formulas.  
  - **Poisson Distribution** – derived formula.  
  - **Normal Approximation** to the **Binomial** and **Poisson** distributions.  
- Summarization on **when to use which distribution**:  
  - **Binomial**: when trials are fixed and outcomes are success/failure.  
  - **Negative Binomial**: when counting failures until a fixed number of successes.  
  - **Geometric**: when counting trials until the first success.  
  - **Hypergeometric**: when sampling *without replacement*.  
  - **Poisson**: when counting rare events in a fixed time/space.  
  - **Normal**: when data is continuous and approximately bell-shaped.  

---

### 🧪 Statistics Lab (4:30 PM – 6:20 PM) – *Swati Jain Ma’am*
- Installed **Tableau** and created an account.  
- Assignment: Build a **useful and beautiful dashboard** from the **Zomato dataset (Kaggle)**.  
- Focus on identifying useful attributes and applying **clever visualization techniques**.  

---

## 🗓️ Day 31 - September 3, 2025 (Wednesday)

---

### 🌅 Pre-College Activity
- Solved **1 DSA problem**.  
- Studied **Simple & Multiple Linear Regression** with Batch GD, Stochastic GD, and Mini-batch GD.  
  - Reference: [Notes on Regression & Gradient Descent](https://drive.google.com/file/d/1eqr3VNnlTMQwXQbunsTdKL19DWlK8Fgn/view?usp=drive_link)  
- Completed pending **AML Lab work**.  

---

### 📚 Labs & Lectures

#### 🧮 Data Science System Design Lab (11:40 AM – 1:30 PM)
- Implemented **Flask** and **HTTP Request Client/Server** practicals.  
- Files available here: [DSSD REST Practical](https://github.com/davesohamm/Nirma-Practical/tree/main/DSSD/REST%20Practical)  

---

### ☕ Recess (1:30 PM – 2:25 PM)

---

#### 🤖 Applied Machine Learning (2:25 PM – 3:20 PM) – *NKP Sir*
- Solved an **example of Naive Bayes Classification** using the formula.  
- Discussed **Zero Probability Problem** and its solution using **Laplace Smoothing**.  
- Formula:  
  \[
  P_{lap,k} = \frac{c(x,y) + k}{c(y) + k|X|}
  \]  
  - If \(0 < k < 1\): *Sandpaper Smoothing*.  
  - If \(k = 1\): *Laplacian Smoothing*.  

---

#### 🔢 DSA (3:30 PM – 4:15 PM) – *Ankit Sir*
- Started with **Greedy Algorithm**.  
  - **Definition**: A greedy algorithm builds up a solution piece by piece, always choosing the option that offers the most immediate benefit (locally optimal choice) with the hope of reaching a global optimum.  
- Discussed classical greedy problems:  
  - **Coin Change Problem**  
  - **Job Scheduling**  
  - **Huffman Encoding & Huffman Tree**  
  - **Minimum Spanning Tree (MST)**  
  - **Travelling Salesman Problem (TSP)**  

---

#### 🧪 Applied Machine Learning Lab (4:30 PM – 6:20 PM)
- Instructions to perform **Regularization Methods** in gradient descent:  
  - **Lasso Regression**  
  - **Ridge Regression**  
  - **Elastic Net**  
- Introduction to **scikit-learn (sklearn)** library.  
- Implemented regression techniques using **sklearn methods** and compared results with normal regression outputs.  

---

## 🗓️ Day 32 - September 4, 2025 (Thursday)

---

### 🌅 Pre-College Activity
- Solved **4 LeetCode problems** before college.  

---

### 📚 Lectures

#### 📊 Statistics (11:40 AM – 12:35 PM) – *Swati Jain Ma’am*
- Announced **sessional syllabus**: up to *Central Limit Theorem* and *Confidence Intervals*.  
- Taught **approximation formula for z-score** and solved **2–3 examples** using z-table and normal distribution.  
- **Point Estimation**: A reasonable value of a population parameter.  
  - \( \bar{x} \) and \( s^2 \) are *statistics* with their own *sampling distributions*.  
  - \( \hat{\theta} \) and \( \Theta^{\wedge} \) → point estimators.  
- Relationships between parameters and statistics:  
  - \(\mu \leftrightarrow \bar{x}\)  
  - \(\sigma^2 \leftrightarrow s^2\)  
  - \(\sigma \leftrightarrow s\)  
  - \(p \leftrightarrow \hat{p}\)  
  - \(\mu_1 - \mu_2 \leftrightarrow \bar{x}_1 - \bar{x}_2\)  
  - \(p_1 - p_2 \leftrightarrow \hat{p}_1 - \hat{p}_2\)  

#### 💡 Capstone Course (12:35 PM – 1:30 PM)
- Discussed **problem-solving process steps**.  
- Covered algorithms and paradigms:  
  - **Kadane’s Algorithm**  
  - **Dynamic Programming** (memoization & tabularization)  
  - **Greedy**  
  - **Divide & Conquer**  
- Introduction to **C++ Templates**:  
  - Function Templates  
  - Class Templates  
  - Custom Templates  

---

### ☕ Recess (1:30 PM – 2:25 PM)

---

#### 🤖 Applied Machine Learning (2:25 PM – 3:20 PM) – *NKP Sir*
- Taught **Multinomial Naive Bayes Classifier**:  
  \[
  P_{\alpha}(t_i|C)
  \]  
  where \(C\) = class, \(t_i\) = term.  
- Explained **\(P(d_j|C)\)** for documents under class.  
- Covered **Multivariate Bernoulli Naive Bayes Classifier** and derived its formula.  
- Solved a practical example on **spam vs ham email classification**.  

#### 🔢 DSA (3:20 PM – 4:15 PM) – *Ankit Sir*
- **Analysis of Greedy Algorithms**:  
  - Make Change: \(O(n)\)  
  - Huffman: \(O(n \log n) + O(n)\)  
  - MST: \(O(n \log n)\), worst case \(O(n^2)\) (where \(n\) = nodes)  
- Explained **Activity Selection Problem** – \(O(n)\).  
- Covered **Disjoint Sets** & **Connected Components** – \(O(V+E)\).  

#### 🖥️ Big Data Systems (4:30 PM – 5:20 PM) – *JV Sir*
- Topic: **MapReduce Programming Model**.  
- Concepts covered:  
  - Mappers, Reducers, Intermediate Outputs, Shuffling, and Final Results.  
  - Map Function, Reduce Function, Key–Value Pairs.  
  - Tree-style Network Topology.  
  - Hadoop as the open-source implementation of MapReduce.  
- Explained full workflow:  
  **Input → Splitting → Mapping → Shuffling → Reducing → Final Results**.  

---

### 📖 Self-Study (5:20 PM – 6:20 PM)
- Free lecture → Spent time in the **library**.  
- Solved **3 more LeetCode problems**.  

---

## 🗓️ Day 33 - September 5, 2025 (Friday)

---

### 🌅 Pre-College Activity
- Solved **1 LeetCode problem**.  
- Completed **Internal & External Merge Sort Algorithm Practical**.  

---

### 📚 Labs & Lectures

#### 🔢 DSA Lab (11:40 AM – 1:30 PM) – *Ankit Sir*
- Instructions to write **term papers**.  
- Introduction to **IEEE Conference Paper Format**.  
- Explained next practical on **Quick Sort**.  
- Performed practical:  
  - Implemented Quick Sort in **4 ways**:  
    1. First element as pivot  
    2. Last element as pivot  
    3. Random element as pivot  
    4. Median indexed element as pivot  
  - Compared results for input sizes: **10k, 50k, 100k arrays**.  

---

### ☕ Recess (1:30 PM – 2:25 PM)

---

#### 🧮 System Design (2:25 PM – 4:15 PM) – *Monika Shah Ma’am*  
*(Combined class due to Swati Ma’am’s absence)*  
- Topics Covered:  
  - Using **proxy labels** in ML models.  
  - **ETL Pipeline** and its components.  
  - **System Design Overview**: scope, requirements, system parameters.  
  - Key parameters: **Scalability, Performance, Availability, Reliability**.  
  - Also discussed: **Durability, Vertical vs Horizontal Scaling, MTTF/MTTR, Cache Tier, Content Delivery Network (CDN)**.  

---

### 📖 Free Lecture (4:30 PM – 6:20 PM)
- **ProgCode class was skipped**.  
- Sat in the **library**.  
- Read the book **“Tarkash” by Javed Akhtar** in one sitting.  
  - The poem *“Woh Kamra Bohot Yaad Hai”* touched my heart deeply.  
  - Enjoyed many small **shayaris**, such as:  
    > *अपनी वजहे-बरबादी सुनिये तो मज़े की है  
    ज़िंदगी से यूँ खेले जैसे दूसरे की है...*  

---

## 🗓️ Day 34 - September 8, 2025 (Monday)

---

### 🌅 Pre-College Activity
- Solved **1 LeetCode problem**.  
- Revised **term paper work** from yesterday.  
- Downloaded **4 IEEE research papers** using institute Wi-Fi access (for term paper reference).  

---

### 📚 Lectures

#### 🖥️ Big Data Systems (11:40 AM – 12:35 PM) – *JV Sir*
- Continued **MapReduce concepts**:  
  - **Combiner functions**.  
  - Comparison of MapReduce with traditional models (communication, synchronization, hardware support, message passing, etc.).  
- Explained **Hadoop High-Level Architecture**.  
- **MRv1 vs MRv2** comparison.  
- Problems with Hadoop 1.0:  
  - Limited scalability  
  - Availability issues  
  - Resource utilization problems  
  - Limitation in running non-MapReduce applications  
- **Job Tracker vs Resource Manager** → differences & similarities.  
- **Task Tracker vs Node Manager** → differences & similarities.  
- Why **YARN** was needed → in-depth explanation.  
- Started **YARN** topic:  
  - Resource Manager  
  - Node Manager  
  - Containers  
  - Application Master  
  - Explicit explanation of **launch container function**.  

#### 🤖 Applied Machine Learning (12:35 PM – 1:30 PM) – *NKP Sir*
- Topic: **Gaussian Naive Bayes Classifier**.  
- Formula derived:  
  \[
  P(x_k|C_i) = \frac{1}{\sqrt{2 \pi \sigma_{x/C_i}^2}} \, e^{-\frac{(x_k - \mu_{x/C_i})^2}{2\sigma_{x/C_i}^2}}
  \]  
- Solved an example on Gaussian Naive Bayes.  
- Explained:  
  - In **Regression** → error used as performance measure.  
  - In **Classification** → accuracy used, but can fail with **skewed datasets** (dumb classifier problem).  
  - Solution: use **Confusion Matrix** → True Positive, True Negative, False Positive, False Negative.  
- Announced that **Precision & Recall** will be covered in the next lecture.  

---

### ☕ Recess (1:30 PM – 2:25 PM)

---

#### 🧪 Big Data Systems Lab (2:25 PM – 4:15 PM) – *JV Sir*
- Practiced **Hadoop commands**.  
- Prepared one **documentation file**.  
- Helped peers debug **Hadoop installation issues** and command errors.  

---

### 📖 Self-Study (4:30 PM – 6:20 PM)
- No lecture scheduled.  
- Sat in the **library**.  
- Studied **AML theories & formulas** for upcoming **sessional exams (starting 17th Sept)**.  

---

## 🗓️ Day 35 - September 9, 2025 (Tuesday)

---

### 🌅 Pre-College Activity
- Solved **3 LeetCode problems** before college.  

---

### 📚 Lectures

#### 🖥️ Big Data Systems (11:40 AM – 12:35 PM) – *JV Sir*
- Taught **complete MapReduce pipeline** for word count program.  
- Started **Fault Tolerance**: explained consequences of failures in different components:  
  - Container / Task  
  - Application Master  
  - NodeManager  
  - Resource Manager  
- Importance of **MapReduce**:  
  - In traditional parallel programming → programmer handles multithreading, locks, semaphores, and hardware failures.  
  - In MapReduce → these complexities are handled by the framework.  
- Explained **MapReduce framework responsibilities**.  
- Full **execution pipeline**:  
  `Driver → Input Data → Mapper → Shuffle & Sort → Reducer → Combiners → Distributed Cache`.  

---

#### 📊 Data Science System Design (12:35 PM – 1:30 PM) – *Monika Shah Ma’am*
- Covered **Machine Learning Project Lifecycle**.  
- Explained **core concepts of system design**:  
  - Abstraction  
  - Modularity  
  - Decomposition  
  - Interface  
- Discussed **key trade-offs**:  
  - Latency vs Throughput  
  - Consistency vs Availability  
  - Cost vs Performance  
  - Scalability vs Complexity  

---

### ☕ Recess (1:30 PM – 2:25 PM)

---

#### 📘 Data Structures & Algorithms (2:25 PM – 3:30 PM) – *Ankit Thakkar Sir*
- Started **Minimum Spanning Tree (MST)**.  
- Explained **Kruskal’s Algorithm** with full **time complexity derivation**.  
- Solved an **example of MST using Kruskal’s Algorithm**.  
- Covered **make-set, find-set, and union-set functions** in Kruskal’s implementation.  

---

#### 📐 Statistics (3:30 PM – 4:15 PM) – *Swati Jain Ma’am*
- Topic: **Parameter Estimation**.  
- Started **Central Limit Theorem (CLT)**:  
  - Explained required conditions.  
  - Derived formula:  
    \[
    Z = \frac{\bar{X} - \mu}{\sigma / \sqrt{n}}
    \]  
    where \(\bar{X}\) = sample mean, \(\mu\) = population mean, and \(\sigma / \sqrt{n}\) = sample standard deviation.  
- Explained **Moments & k-th Moment**:  
  - At \(k=1\), moment = \(\mu\).  
- Introduced **Moment Estimators**.  
- Gave a **brief idea about Confidence Intervals** using an example.  

---

### 📖 Self-Study (4:30 PM – 6:20 PM)
- **Statistics Lab** was rescheduled (in place of Friday ProgCode Lab).  
- Utilized the time in **library**.  
- Solved **2 LeetCode problems on Binary Search**.  

---

## 🗓️ Day 36 - September 10, 2025 (Wednesday)

---

### 🌅 Pre-College Activity
- Solved **4 LeetCode problems** before college.  

---

### 📚 Labs & Lectures

#### 🖥️ Data Science System Design Lab (11:40 AM – 1:30 PM) – *Monika Shah Ma’am*
- Modified the **previous Flask REST API practical** to work with **local data**.  
- Performed **CRUD operations** on the modified API.  
- Instructed to perform **GraphQL practical**.  

**GraphQL Benefits over REST API:**  
- **Single Endpoint:** Fetches all required data in one request instead of multiple REST endpoints.  
- **Flexible Queries:** Clients can request exactly the data they need, reducing over-fetching and under-fetching.  
- **Strongly Typed Schema:** Provides better validation and auto-documentation compared to REST APIs.  

---

### ☕ Recess (1:30 PM – 2:25 PM)

---

#### 📊 Applied Machine Learning (2:25 PM – 3:20 PM) – *NKP Sir*
- Topics covered:  
  - **Precision** = \( \frac{TP}{TP + FP} \)  
  - **Recall / True Positive Rate / Sensitivity** = \( \frac{TP}{TP + FN} \)  
  - **F1 Score** = \( \frac{2 \times Precision \times Recall}{Precision + Recall} \)  
  - **Beta Score** – extended version of F1 score to emphasize recall or precision.  
- Solved an **example problem** on all these formulas.  
- Introduced **Multiclass Confusion Matrix**.  
- Explained **ROC Curve** and its significance.  

---

#### 📘 Data Structures & Algorithms (3:20 PM – 4:15 PM) – *Ankit Sir*
- Taught **Prim’s Algorithm**:  
  - Root node is defined by the **user**.  
  - Uses **Priority Queue**.  
  - **Extract-Min** function extracts node with **minimum key value**.  
  - MST result depends on the **chosen root node**.  
- Solved **one example step-by-step** for Prim’s Algorithm.  
- Explained **Time Complexity**:  
  - \( O(V \log V) + O(E \log V) \) which simplifies to **\( O(E \log V) \)** for a connected graph.  

---

## 🗓️ Day 37 - September 11, 2025 (Thursday)

---

### 🌅 Pre-College Activity
- Solved **1 LeetCode problem**.  
- Was **sleep deprived and unwell** today, woke up late.  
- **Skipped Statistics Lecture (11:40 – 12:35)** by Swati Jain Ma’am.  

---

### 📚 Labs & Lectures

#### 💻 Capstone Lecture (12:35 PM – 1:30 PM) – *NKP Sir*
- **Data Structures Revision Session**:  
  - Explained **primitive & non-primitive**, **linear & non-linear**, **static & dynamic** data structures.  
  - Covered **Array, Stack, Queue, Tree, Graph, BST, Linked List** and their variants.  
  - Explained **Serialization** of data structures.  

---

### ☕ Recess (1:30 PM – 2:25 PM)

---

#### 📊 Applied Machine Learning (2:25 PM – 3:20 PM) – *NKP Sir*
- **Evaluation Methodologies**:  
  - **Holdout Method:** Splitting dataset into training & testing sets once.  
  - **Random Subsampling:** Repeatedly splitting data randomly into train-test to average results.  
  - **Cross-Validation:**  
    - **k-Fold:** Split data into k parts, train on k-1, test on 1, repeat.  
    - **Leave-One-Out:** Extreme k-fold where k = number of samples.  
    - **Stratified:** Ensures class proportions are maintained across splits.  
- Explained **.632 Bootstrap** and derived its **accuracy formula**.  
- Started **Decision Tree Topic**: briefly explained **ID3**, **C4.5**, and **CART**.  

---

#### 📘 Data Structures & Algorithms (3:20 PM – 4:15 PM) – *Ankit Sir*
- Taught **Approximations for Hard Problems**.  
- Explained **MST Approximation** techniques.  
- Started **Knapsack Problem**:  
  - Two variants: **0-1 Knapsack** and **Fractional Knapsack**.  
  - Solved **examples for both** variants.  
  - Explained **time complexity** of Knapsack algorithms.  

---

#### 🗄️ Big Data Systems (4:30 PM – 5:25 PM) – *JV Sir*
- Explained **HDFS Hello World pipeline**:  
  - **hdfshelloworld.java → hdfshelloworld.jar → MapReduce Execution**.  
- Demonstrated **complete MapReduce pipeline** step-by-step using **Word Count program**.  
- Covered **all commands** for execution in detail.  

---

### 📝 Free Lecture (5:25 PM – 6:30 PM)
- Met college friend **Karan** in the canteen after his **Bangalore business trip**.  
- Discussed **startup culture, relationships, college life, friends**, and more.  
- One thought-provoking takeaway from him today: **“Ready, Fire, Aim” rule** – act first, refine later.  

---

## 🗓️ Day 39 - September 12, 2025 (Friday)

---

### 🌅 Pre-College Activity
- Solved **1 LeetCode problem**.  
- Completed **DSA practicals** for **Merge Sort** and **Quick Sort** and made **reports** for both.  

---

### 📚 Labs & Lectures

#### 💻 DSA Lab (11:40 AM – 1:30 PM) – *Ankit Sir*
- Sir took **evaluation for all 3 DSA practicals**.  
- I didn’t receive very good reviews, which highlighted that I need to **work harder on DSA practicals**, **analyze outputs precisely**, and **document them properly**.  

---

### ☕ Recess (1:30 PM – 2:25 PM)

---

#### 🖥️ Data Science System Design (2:25 PM – 3:30 PM) – *Monika Shah Ma’am*
- **Scalability Approaches**:  
  - **Load Balancing:** Nginx, HAProxy, AWS ELB, Google Cloud.  
  - **Caching:** Cloudflare CDN, Redis, Memcached.  
  - **Database Sharding**.  
  - **Asynchronous Processing:** RabbitMQ, Kafka, Celery.  
- **Reliability Strategies:** Redundancy, Replication, Monitoring & Alerting, Testing.  
- **Availability:**  
  - Formula = **MTVF / (MTBF + MTTR)**.  
  - Factors affecting availability and strategies to improve it.  
- **Message Queues:**  
  - **Definition:** A system that enables asynchronous communication between services by holding and delivering messages between producers and consumers.  
  - **Benefits:** Asynchronous processing, Load Balancing, Decoupling.  
  - **Applications:** RabbitMQ, Apache Kafka, Amazon SQS, Redis Streams.  

---

#### 🗄️ Big Data Systems (3:30 PM – 4:15 PM) – *JV Sir (Proxy for Swati Ma’am)*
- Guided us further on the **term paper innovation assignment**.  
- Asked about our **progress so far** and gave **valuable insights** on our projects.  

---

#### 📊 Statistics Lab (4:30 PM – 6:20 PM) – *Swati Ma’am*
- Created **Zomato Analysis Dashboard** in **Tableau**.  
- Read **DSA PPTs** for upcoming exams.  

---

## 🗓️ Day 40 - September 15, 2025 (Monday)

---

### 🌅 Pre-College Activity
- Solved **1 LeetCode problem**.  
- Read **Data Science System Design course PPTs** for exam preparation.  

---

### 📚 Labs & Lectures

#### 🗄️ Big Data Systems (11:40 AM – 12:35 PM) – *JV Sir*
- Taught **applications of Big Data and Hadoop** in sectors like **retail, telecom, social networking sites**.  
- **Python frameworks for Hadoop:** Hadoop Streaming (best for text processing), MRJob, Dumbo, Hadoopy, Pydoop.  
- **Hadoop Streaming (in-depth):**  
  - A utility included with Hadoop distribution.  
  - Allows creating and running MapReduce jobs with any executable or script as the **mapper** and/or **reducer**.  
  - Example: **mapper.py**, **reducer.py**.  
- Demonstrated **Python Word Count** programs using **mapper.py** and **reducer.py**.  

---

#### 🧠 Applied Machine Learning (12:35 PM – 1:30 PM) – *Avantika Ma’am (Proxy for NKP Sir)*
- Started **Decision Trees**:  
  - A tree structure to represent sequences of **decisions** and **consequences**.  
- **Attribute Selection:**  
  - Uses **entropy-based methods** to choose the most informative attribute.  
  - **Entropy Formula:**  
    - If outcome variable X takes m distinct values:  
      **H(X) = -Σ (Pi * log₂ Pi)** where **Pi = P(X = xi)**.  
- **Information Gain Formula:**  
  - **IG(S,A) = Entropy(S) - Σ (|Sv|/|S| * Entropy(Sv))**.  
- **ID3 Algorithm:**  
  - Selects the attribute with the **highest information gain** at each node.  
  - Stops when:  
    - All instances belong to the same class.  
    - No remaining attributes.  
    - Dataset is empty.  

---

### ☕ Recess (1:30 PM – 2:25 PM)

---

#### 💻 Big Data Systems Lab (2:25 PM – 4:15 PM) – *JV Sir*
- Performed **Word Count** Python **mapper.py** and **reducer.py** programs in **Hadoop MapReduce**.  
- [🔗 View my file here](https://drive.google.com/file/d/1hQvpczn86MV7j7RTguky9f49d7C1YpP7/view).  

---

#### 📖 Free Lecture (4:30 PM – 6:20 PM)
- Sat in the library and **read Chapter 1 of Applied Machine Learning** for exam preparation.  

---

## 🗓️ Day 41 - September 16, 2025 (Tuesday)

---

### 🌅 Pre-College Activity
- Solved **1 LeetCode problem**.  
- Read **Machine Learning exam numerical methods**.  

---

### 📚 Labs & Lectures

#### 🗄️ Big Data Systems (11:40 AM – 12:35 PM) – *JV Sir*
- Due to **tomorrow’s exams** and low attendance, Sir **didn’t teach anything new**.  
- We **revised ML and DSA exam theories** during the lecture time.  

---

#### 🖥️ Data Science System Design (12:35 PM – 1:30 PM) – *Monika Shah Ma’am*
- Explained **exam pattern** and **types of questions** we can expect.  
- Then allowed us to **read exam theories**.  

---

### ☕ Recess (1:30 PM – 2:25 PM)

---

#### 💻 DSA (2:25 PM – 3:30 PM) – *Ankit Sir*
- Taught **Dijkstra’s Algorithm** and **Connecting Wire Algorithm**.  
- Gave **exam preparation tips** and then allowed us to read.  

---

#### 📊 Statistics (3:30 PM – 4:20 PM) – *Swati Jain Ma’am*
- Solved a couple of **numericals** from the syllabus.  
- Then allowed us to **prepare by ourselves** for the exams.  

---

#### 🧮 Statistics Lab (4:30 PM – 6:20 PM) – *Swati Jain Ma’am*
- Free lab session to **prepare for exams**.  
- Completed **ML theories** and **almost completed DSA subject**.  

---

### 📝 End of the Day
- Plan to **brush up knowledge at home** and perform well in **tomorrow’s exams**!  

---

## 🗓️ Day 42 - September 17, 2025 (Wednesday)

---

### 🌅 Pre-College Activity
- Solved **1 LeetCode problem**.  
- Continued **exam preparation** for sessionals.  

---

### 📝 Sessional Examinations – Semester 1 (Day 1)

#### 📚 DSA Paper (11:30 AM – 1:30 PM) – *50 Marks*
- **Paper:** [DSA_SE_Q](https://github.com/davesohamm/Nirma-Papers/DSA_SE_Q)  
- **Answers:** [DSA_SE_Ans](https://github.com/davesohamm/Nirma-Papers/DSA_SE_Ans)  
- **My Experience:**  
  - Paper went **good overall**.  
  - Made **some silly mistakes** in **algorithm time complexity analysis**.  
  - Still **confident about performance**.  

---

#### ☕ Break / Preparation Gap (1:30 PM – 3:30 PM)

---

#### 🤖 Applied Machine Learning Paper (3:30 PM – 5:30 PM) – *50 Marks*
- **Paper:** [AML_SE_Q](https://github.com/davesohamm/Nirma-Papers/AML_SE_Q)  
- **Answers:** [AML_SE_Ans](https://github.com/davesohamm/Nirma-Papers/AML_SE_Ans)  
- **My Experience:**  
  - Exam was **very good overall**.  
  - Made a **logical mistake** in the last question’s **method** due to lack of practice.  
  - Otherwise, the paper was **smooth and clear**.  

---

### 🎯 End of the Day
- **First day of sessionals completed successfully!**  
- Need to brush up weak areas like **algorithm time complexity analysis** and **practice AML methods** before next exams.  

---




















# Unsupervised-Learning
# Unsupervised Learning & Reinforcement Learning Practical

## 📌 About the Project

This repository contains a beginner-friendly **Machine Learning practical** created using **Google Colab and Python**.

The practical introduces two important Machine Learning concepts:

* **Unsupervised Learning** using K-Means Clustering
* **Reinforcement Learning** using a simple reward-based route selection example

The practical uses simple business scenarios to make the concepts easy to understand and interpret.

---

## 🎯 Learning Objectives

By completing this practical, you will learn how to:

* Understand customer segmentation using **K-Means Clustering**
* Group similar customers based on their behaviour
* Interpret customer clusters from a business perspective
* Understand the basic idea of **Reinforcement Learning**
* Identify an **Agent, Action, Environment, and Reward**
* Understand **Exploration vs Exploitation**
* Connect Machine Learning concepts with real-world business applications

---

## 🧩 Part A: Customer Segmentation Using K-Means

### Business Problem

An online retailer wants to understand different types of customers.

The dataset contains two characteristics:

* **Monthly Spending**
* **App Visits**

K-Means Clustering is used to divide the customers into **3 groups (K = 3)**.

### Process

1. Create a small customer dataset
2. Select relevant features
3. Apply K-Means Clustering
4. Assign customers to clusters
5. Visualize the clusters
6. Interpret the groups from a business perspective

### Business Applications

The identified customer groups can help businesses create targeted strategies such as:

* Loyalty rewards for high-value customers
* Personalized recommendations
* Re-engagement campaigns for less active customers

> **Important:** Cluster numbers such as 0, 1, and 2 are only labels. They do not automatically mean good, average, or bad customers.

---

## 🤖 Part B: Introduction to Reinforcement Learning

The second part introduces the basic idea of **Reinforcement Learning**.

### Business Scenario

A delivery company has two possible routes:

* Route A
* Route B

The system receives a **reward** based on delivery performance and can learn which route tends to perform better.

### Key Concepts

| Concept         | Meaning                                  | Example                  |
| --------------- | ---------------------------------------- | ------------------------ |
| **Agent**       | System making the decision               | Delivery decision system |
| **Environment** | Surroundings in which the agent operates | Roads and traffic        |
| **Action**      | Decision taken by the agent              | Choose Route A or B      |
| **Reward**      | Feedback received after an action        | Delivery performance     |

### Exploration vs Exploitation

**Exploration:**
Trying a new or less-used option to learn more about it.

**Exploitation:**
Choosing the option that is already known to perform well.

For example, randomly trying a route represents **exploration**, while selecting the route with the higher average reward represents **exploitation**.

---

## 🛠️ Technologies Used

* **Python**
* **Google Colab**
* **Pandas**
* **Matplotlib**
* **Scikit-learn**
* **Random module**

---

## 📂 Project Structure

```text
Unsupervised-and-Reinforcement-Learning/
│
├── part-a/
│   └── unsupervised-learning/
│       ├── Unsupervised_and_Reinforcement_Learning_Practical_Name.ipynb
│       └── customer-segmentation.png
│
└── README.md
```

---

## 📊 Machine Learning Concepts Covered

| Type                       | Main Idea                      | Business Example          |
| -------------------------- | ------------------------------ | ------------------------- |
| **Supervised Learning**    | Learn from known answers       | Customer churn prediction |
| **Unsupervised Learning**  | Discover hidden patterns       | Customer segmentation     |
| **Reinforcement Learning** | Learn from actions and rewards | Route optimization        |

---

## 📚 Key Takeaways

### K-Means Clustering

* **K** represents the number of clusters.
* Customers are grouped based on similar characteristics.
* Cluster results can be used for business decision-making.

### Reinforcement Learning

* An **Agent** takes an **Action**.
* The Agent receives a **Reward**.
* The Agent learns from the result.
* **Exploration** means trying new options.
* **Exploitation** means using the option already known to perform well.

---

## 🚀 How to Run

1. Download or clone this repository.
2. Open the `.ipynb` notebook in **Google Colab** or Jupyter Notebook.
3. Run the cells from top to bottom.
4. Observe the K-Means clusters and route-reward results.
5. Complete the reflection questions provided in the notebook.

---

## 📝 Practical Questions

The notebook includes reflection questions covering:

* Unsupervised Learning
* Clustering
* K-Means
* Customer segmentation
* Reinforcement Learning
* Agent, Action, Environment and Reward
* Exploration and Exploitation
* Business applications of AI

---

## 👨‍💻 Project Type

**Academic / Educational Machine Learning Practical**

Created for learning the fundamentals of **AI and Machine Learning through simple business applications**.

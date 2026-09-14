# unsupervised-reinforcement-learning-practical
# Unsupervised & Reinforcement Learning Practical

This repository contains a practical implementation of **Unsupervised Learning** and **Reinforcement Learning** using simple business-oriented examples in Python.

The practical is designed to focus not only on the code, but also on understanding how machine learning techniques can support **business decision-making**.

## 📌 Topics Covered

### Part A — Customer Segmentation using K-Means

An online retailer wants to understand different types of customers based on:

* Monthly Spending
* App Visits

Using **K-Means Clustering**, customers are divided into **3 groups**.

The practical covers:

* Creating a customer dataset using Pandas
* Selecting features for clustering
* Applying K-Means clustering
* Visualizing customer groups
* Interpreting clusters from a business perspective
* Understanding possible marketing actions for different customer segments

Possible business segments include:

* Premium Customers
* Medium-Value Customers
* Low-Engagement Customers

Possible business actions include:

* Loyalty rewards
* Personalized recommendations
* Re-engagement campaigns

### Part B — Introduction to Reinforcement Learning

A simple delivery-route example is used to understand the basic concepts of Reinforcement Learning.

The practical demonstrates:

* Agent
* Environment
* Action
* Reward
* Exploration
* Exploitation
* Average reward calculation

Two delivery routes are compared:

* Route A
* Route B

The route with the higher average reward represents the basic idea of choosing an action based on previously observed results.

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab

## 📂 Repository Structure

```text
.
├── part-a/
│   └── unsupervised-learning/
│       ├── Unsupervised_and_Reinforcement_Learning_Practical_Name.ipynb
│       └── customer-segmentation.png
│
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd <your-repository-name>
```

### 2. Install dependencies

```bash
pip install pandas matplotlib scikit-learn jupyter
```

### 3. Run the notebook

Open the notebook using Jupyter:

```bash
jupyter notebook
```

Alternatively, upload the notebook to **Google Colab** and run the cells there.

## 📊 Customer Segmentation

The K-Means model uses two features:

```text
Monthly Spending
App Visits
```

The model is configured with:

```python
KMeans(n_clusters=3, random_state=42, n_init=10)
```

The resulting clusters are visualized to help understand customer behaviour.

> **Note:** Cluster numbers such as 0, 1, and 2 are only labels. They do not represent good, average, or bad customers.

## 🤖 Reinforcement Learning

The reinforcement learning section uses a simplified delivery-route scenario.

The basic learning process can be represented as:

```text
Take an Action
      ↓
Receive a Reward
      ↓
Learn from the Result
      ↓
Make Better Decisions
```

### Key Concepts

| Concept     | Example                                |
| ----------- | -------------------------------------- |
| Agent       | Delivery decision system               |
| Environment | Roads and traffic                      |
| Action      | Choose Route A or Route B              |
| Reward      | Feedback based on delivery performance |

The practical also demonstrates the difference between:

**Exploration** — trying a new or less-used option.

**Exploitation** — choosing the option currently known to perform better.

## 📚 Machine Learning Comparison

| Machine Learning Type  | Main Idea                      | Business Example          |
| ---------------------- | ------------------------------ | ------------------------- |
| Supervised Learning    | Learn from known answers       | Customer churn prediction |
| Unsupervised Learning  | Discover hidden patterns       | Customer segmentation     |
| Reinforcement Learning | Learn from actions and rewards | Route optimization        |

## 🎯 Learning Objectives

After completing this practical, you should be able to:

* Understand customer segmentation using K-Means Clustering.
* Identify groups of similar customers.
* Interpret clusters from a business perspective.
* Understand the basic idea of Reinforcement Learning.
* Identify an Agent, Action, Environment, and Reward.
* Explain Exploration vs. Exploitation.
* Connect machine learning techniques with practical business applications.

## 📸 Practical Output

The repository includes a visualization of the customer groups generated using K-Means clustering.

Add your customer-segmentation graph here:

```text
part-a/unsupervised-learning/customer-segmentation.png
```

## 📝 Reflection

The practical concludes with questions covering:

1. What is Unsupervised Learning?
2. What is clustering?
3. What does K mean in K-Means?
4. How can customer segmentation help a business?
5. What is Reinforcement Learning?
6. What is an Agent?
7. What is an Action?
8. What is a Reward?
9. What is the difference between Exploration and Exploitation?
10. How can AI be applied to business problems?

## 📤 Submission

The notebook should be named:

```text
Unsupervised_and_Reinforcement_Learning_Practical_Name.ipynb
```

and uploaded under:

```text
part-a/unsupervised-learning/
```

A screenshot of the customer-segmentation graph should also be included.

---

**Made for learning and practical exploration of Machine Learning concepts.**

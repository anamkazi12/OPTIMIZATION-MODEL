# OPTIMIZATION-MODEL

**COMPANY**: CODTECH IT SOLUTIONS 

**NAME**: ANAM KAZI  

**INTERN ID**: CTIS0503

**DOMAIN**: DATA SCIENCE  

**DURATION**: 4 WEEKS  

**INTERNSHIP PERIOD**: 18 DECEMBER 2025 - 15 JANUARY 2026  

**MENTOR**: NEELA SANTOSH KUMAR

# Linear Programming for Production Optimization using PuLP

## 📌 Project Overview

This project demonstrates how **Linear Programming (LP)** can be implemented to optimize production planning in a manufacturing environment. Industries often need to decide how many units of different products should be produced to achieve maximum profit while satisfying resource limitations. Making these decisions manually can be complex and prone to error, especially when multiple constraints and profit variations are involved.

To solve this, the project utilizes **Python**, **PuLP**, and **Google Colab** to formulate and solve an optimization problem involving two products: **Product A** and **Product B**. The model incorporates resource constraints such as **labor hours** and **machine hours** and determines the most profitable production combination.



## 🏭 Business Problem Definition

The goal of this project is to determine the ideal production quantities of Product A and Product B such that:

* ✅ Total profit is maximized
* ✅ Labor availability constraints are satisfied
* ✅ Machine capacity limits are not exceeded
* ✅ No negative production values are generated

This type of problem is common in **Operations Research**, **Production Management**, and **Supply Chain Optimization**, where efficient decision-making plays a crucial role in improving productivity and profitability.


## 📐 Mathematical Model

### **Decision Variables**

Let:

* ( X_A ) = Number of units of Product A to produce
* ( X_B ) = Number of units of Product B to produce


### **Objective Function (Maximize Profit)**

[
\text{Maximize } Z = 40X_A + 30X_B
]

Where:

* ₹40 = Profit per unit of Product A
* ₹30 = Profit per unit of Product B



### **Constraints**

**Labor Constraint**

[
2X_A + X_B \leq 100
]

(Product A uses 2 labor hours, Product B uses 1 labor hour, and only 100 hours are available)



**Machine Constraint**

[
X_A + 2X_B \leq 80
]

(Product A requires 1 machine hour, Product B requires 2, with total availability of 80 hours)



**Non-Negativity Constraint**

[
X_A \ge 0,\quad X_B \ge 0
]

Production cannot be negative.



## 💻 Implementation Using Google Colab & PuLP

The model is implemented and executed in **Google Colab**, which provides:

* Cloud-based execution (no installation needed)
* Easy library management
* Fast computation and convenient debugging

Steps followed in implementation:

1️⃣ Import PuLP library
2️⃣ Initialize a maximization LP model
3️⃣ Define decision variables
4️⃣ Add objective function
5️⃣ Add constraints
6️⃣ Use solver to find optimal values
7️⃣ Display optimal production decisions and profit



## 🛠️ Tools & Technologies Used

* **Python 3.x** – Core programming language
* **Google Colab** – Platform for writing and executing the code
* **PuLP Library** – Used to formulate and solve the optimization model
* **CBC Solver** – Default solver used by PuLP to compute optimal results
* **Markdown Documentation** – For structured explanation and reporting



## 📊 Results & Interpretation

After solving the optimization problem, the results obtained are:

* ✔ **Status:** Optimal
* ✔ **Product A Production:** 40 units
* ✔ **Product B Production:** 20 units
* ✔ **Maximum Profit:** ₹2200

This means the factory should produce **40 units of Product A** and **20 units of Product B** to achieve maximum profit while effectively utilizing available labor and machine resources.

## 🚀 Business Impact & Advantages

* 🔹 Ensures efficient resource utilization
* 🔹 Enables data-driven decision making
* 🔹 Scalable to multiple products and complex constraints
* 🔹 Applicable in real-world industrial planning scenarios


## ✅ Conclusion

This project successfully demonstrates the practical application of **Linear Programming** using **Python, PuLP, and Google Colab** to solve production optimization challenges. By converting real-world business constraints into a mathematical model, organizations can make smarter, faster, and more profitable production decisions.

##output
![Image](https://github.com/user-attachments/assets/cb33fb3d-7bcf-41a9-a9a2-ef0e107478db)

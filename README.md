# Dynamic Customer Flow Optimization at Sprouts Grocery Store 🛒
### 📌 Overview
This project focuses on optimizing customer flow in a grocery retail environment, specifically at Sprouts Farmers Market, using Simio simulation modeling. The goal is to address bottlenecks and inefficiencies in customer movement and checkout processes, improving both customer satisfaction and operational efficiency.

## 🎬 Simulation Demo

-- [📽️ Download Demo Video](simulation/demo_video.mp4)


### 🎯 Objective
To design and implement a dynamic simulation model that:

- Analyzes customer arrival patterns and traffic flow.

- Evaluates various checkout counter configurations (normal, special, and self-checkout).

- Identifies optimal cashier and counter arrangements to minimize queue time and maximize resource utilization.

### 🧩 Problem Statement
Sprouts experiences significant variations in customer traffic during peak and off-peak hours. Inefficiencies include:

- Long wait times during peak hours.

- Underutilized staff and infrastructure during non-peak hours.

- These challenges negatively impact customer experience and store profitability.

### 📊 Data Collection
Data was collected in collaboration with the store manager:

- Daily footfall: ~1000 customers

- Peak hours: 10 AM – 2 PM (~40% of traffic)

- Checkout counters: 3–5 during peak, 2–3 during off-peak

- Operational hours: 7 AM – 10 PM

### 🔍 Data Analysis
Interarrival Times:

- Peak: 0.6 minutes

- Off-peak: 1.1 minutes

Weighted Distribution method used to allocate customer inflow across time slots.

Rate Tables: Constructed to represent time-dependent customer entry rates.

### 🛠️ Simulation Model
Developed using Simio, the model includes:

**Departments:** Dairy, Beverages, Fruits, Meat, Bakery, etc.

**Checkout options:**

- Normal Cashiers: Full day

- Special Cashiers: Peak hours only

- Self-checkouts: Available all day

- Service times: Modeled using triangular distributions based on department type.

### 🧪 Scenarios Tested
Five configurations were evaluated for effectiveness:

#### Scenario	Configuration	Outcome
| Scenario   | Configuration                           | Outcome                                                  |
| ---------- | --------------------------------------- | -------------------------------------------------------- |
| **Normal** | 2 Normal Cashiers                       | High wait times, moderate utilization                    |
| **1**      | 2 Normal + 2 Special + 1 Self-checkout  | Lower wait times, lower cashier utilization              |
| **2**      | 3 Normal + 1 Special                    | 🔥 **Best balance of low wait time & high resource use** |
| **3**      | 2 Normal + 1 Self-checkout              | Efficient, but lower capacity                            |
| **4**      | 1 Normal + 1 Special + 2 Self-checkouts | Cost-effective, slightly lower efficiency                |

### 🏆 Key Findings
Scenario 2 was the most optimal, offering:

- High cashier utilization (~99%)

- Low average customer wait time (~0.42 minutes)

Scenario 4 is a strong alternative for minimizing labor costs with slightly higher wait times.

### 🔮 Future Scope
- Integration of real-time data to enable dynamic staffing.

- Impact analysis of mobile payments and app-based checkout.

- Simulation of store layout redesigns for better traffic flow.

### 📚 References
- Mykoniatis, K., Angelopoulou, A., & Nichols, S. S. (2021). Society 5.0: a simulation optimisation study of dynamic scheduling for a grocery store. International Journal of Simulation and Process Modelling.

- Hema, V., & Herman, T. (2023). Optimizing grocery store processes and reducing wait time: A discrete event simulation study. International Journal of Management Communication.

### 👥  Team
- **Mittapally Mahendhar**

- **Srujanth Reddy Gangidi**



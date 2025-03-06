# AZ-900 Certification

## **What is the Microsoft AZ-900 Certification?**

Microsoft AZ-900 is an entry-level certification designed for beginners. This certification provides an understanding of
**Microsoft Azure Fundamentals**. The exam covers foundational knowledge of cloud services and how these services are
provided in Microsoft Azure.

---

## **What is Cloud?**

Cloud refers to the use of **computing resources and services provided by a third party**, eliminating the need for
on-premises physical infrastructure. Instead of maintaining local servers, users can leverage remote compute resources.

---

## **What are the Available Cloud Types Today?**

There are **three types of cloud computing**:

### **1. Public Cloud**

- Computing services **provided by third-party providers** over the **public internet**.
- Accessible to **anyone** who wants to use or purchase them.

### **2. Private Cloud**

- Computing services **offered over the internet or a private internal network**.
- Available **only to select users** instead of the general public.

### **3. Hybrid Cloud**

- A computing environment that **combines a private cloud with a public cloud**, allowing data and applications to be
  shared between them.

---

## **How Can We Calculate the Price for an Azure Service?**

The cost of an **Azure service** can be estimated using the **Azure Pricing Calculator**.

---

## **What is High Availability, and What Are Its Benefits?**

##### **<u>Definition:</u>**

**High Availability (HA)** is a **system design approach** that ensures an application or service remains **operational
with minimal downtime**, even in the event of failures (hardware, software, or network). HA is achieved through
**redundancy, failover mechanisms, and load balancing**.

### **Benefits of High Availability:**

- **Minimized Downtime:** Ensures continuous service availability, reducing the impact of failures.
- **Fault Tolerance:** If one component fails, another takes over without disrupting operations.
- **Load Distribution:** Balances traffic across multiple servers to prevent overload and improve performance.
- **Improved Reliability & Business Continuity:** Essential for **critical applications** to maintain **user trust and
  SLA compliance**.
- **Scalability:** Can handle **increased traffic efficiently** by adding more resources.

---

## **What is Scalability, and What Are the Different Types?**

##### **<u>Definition:</u>**

**Scalability** is the ability of a system to **accommodate increasing demand** by adding or removing resources as
needed.

### **Types of Scalability:**

#### **1. Horizontal Scaling (Scaling Out/In)**

- Involves **adding more servers** to a system.
- No hard limits on scaling.
- Introduces additional complexity for **load balancing**.
- Improves **availability and redundancy**.

#### **2. Vertical Scaling (Scaling Up/Down)**

- Involves **adding more resources (CPU, RAM)** to a single server.
- There is a **physical limit** to how much memory or CPU can be added.
- Suitable for applications that require **higher processing power** on a single machine.

---

## **What is Elasticity?**

##### **<u>Definition:</u>**

The ability of a system to **quickly and easily** scale up or down the amount of resources that a system uses in response to changing demand.

---

## **What is Reliability?**

##### **<u>Definition:</u>**

The ability of a system to **recover from failures**

Azure has several built-in services that you can use,
to **keep an application running after a failure has occurred**.

There are many different failures that can occur even i a well-designed system such as:
- Hardware failure
- Network interruption
- Power failures
- Large-scale regional outage


#### **How is reliability can be achieved in Azure?**
- Auto-scaling
- Avoid single points of failure
- Multi-region deployments
- Data backup and replication
- Health probes and self-healing

---

## **What is Predictability?**

##### **<u>Definition:</u>**

The ability to **forecast and control the performance** and behavior of a systems.
Includes the **ability to predict future costs**

#### **Why is it needed?**
- Predictability gives you the **confidence that the system will continue to perform at the expected level in the future**.

- And also **avoid from unexpectedly bills**


#### **How is reliability can be achieved in Azure?**
- Auto-scaling
- Load balancing
- Different instance types, sizes, pricing tiers
- Cost management tools
- API
- Pricing calculators

---

## **Security Benefits Of Cloud Computing**

Cloud providers are obviously massive targets for hackers,
and so they rightly spend a lot of time, money and effort on platform security.

Cloud providers go through security audits and compliance certifications,
And provides their customers the tools they need to enable and monitor security, with their own applications/data.

---

# Cloud-based-load-balancing-and-auto-scaling
This project demonstrates how to set up load balancing and auto scaling in AWS to achieve high availability, scalability, and fault tolerance for a simple web application.

🎯 Objective

To understand **scalability and fault tolerance** in cloud computing by:
- Creating multiple EC2 instances
- Configuring an **Application Load Balancer (ALB)**
- Implementing **Auto Scaling Groups**
- Testing with load to observe automatic scaling

---

## 🧠 Key Concepts

| Concept | Description |
|----------|-------------|
| Load Balancer | Distributes incoming traffic to multiple servers |
| Auto Scaling | Automatically adds/removes instances based on demand |
| Health Checks | Monitors instance status to ensure reliability |
| Fault Tolerance | Keeps app running even if one server fails |

---

## 🧰 Tools Used

- **AWS EC2** (Virtual Machines)
- **AWS Elastic Load Balancer (ALB)**
- **AWS Auto Scaling Group**
- **Apache Web Server**
- **VS Code** / **AWS CloudShell**

---

## 🪜 Step-by-Step Implementation

### **Step 1: Create Web Application**
- Developed a simple `index.html` file:
  ```html
  <h2>Hello from my Cloud Instance!</h2>
  <p>This page is served from an EC2 instance behind a Load Balancer.</p>

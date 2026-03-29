# AWS Serverless RSVP Web Application 🚀

## 🌐 Live Demo
👉 https://d2nzd2ip30e73z.cloudfront.net

---

## 📌 Project Overview
This is a serverless RSVP web application built using AWS.  
Users can submit RSVP responses in real time, and the response count updates instantly.

The project demonstrates a full-stack cloud architecture using CDN, serverless computing, and both SQL and NoSQL databases.

---

## 🛠️ Technologies Used
- Amazon S3 (Frontend hosting)
- Amazon CloudFront (CDN)
- API Gateway (API management)
- AWS Lambda (Backend logic)
- Amazon RDS (MySQL database)
- Amazon DynamoDB (Real-time RSVP storage)

---

## 🔄 Architecture
User → CloudFront → S3 → API Gateway → Lambda → DynamoDB / RDS

---

## ☁️ Architecture Diagram
<img width="501" height="511" alt="aws-RSVP-architecture drawio" src="https://github.com/user-attachments/assets/0a181331-0b47-4b92-af17-dac3aa4f9da2" />

---



## ⚡ Features
- Real-time RSVP submission
- Instant response count update using DynamoDB
- Serverless backend using AWS Lambda
- Fast global content delivery with CloudFront
- Integration of SQL (RDS) and NoSQL (DynamoDB)

---

## 🧠 Challenges & Solutions
- Fixed event data inconsistency in RDS
- Debugged Lambda execution using CloudWatch logs
- Ensured real-time updates using DynamoDB atomic operations
- Understood data flow between frontend, API, and databases

---

## 📚 What I Learned
- Difference between SQL and NoSQL databases
- Serverless architecture design on AWS
- API Gateway + Lambda integration
- CloudFront caching and content delivery
- Debugging cloud applications using CloudWatch

---

## 📸 Screenshots
<img width="1903" height="953" alt="Screenshot 2026-03-29 162722" src="https://github.com/user-attachments/assets/5ba6f36b-b0fa-4997-a8ed-46b0d611e32d" />
<img width="1000" height="862" alt="Screenshot 2026-03-29 162813" src="https://github.com/user-attachments/assets/18b52462-58d2-4141-a09c-9678704e3bab" />

---


## 🔗 Reference
Original tutorial:
https://github.com/darladvd/event-rsvp-aws-tutorial

📨 **Customer Inquiry Manager (AWS Project #5 — Serverless Upgrade)**
👨‍💻 My 5th AWS Cloud Project — Now React.js frontend + Serverless backend

This project intelligently manages customer inquiries using **Amazon Bedrock, RDS, SES, CloudWatch**, and **AWS Lambda** — all connected through a React.js web application. It demonstrates how cloud automation, AI, and serverless architecture can improve customer support workflows.

---

🧠 **Project Story**
I wanted a project that feels like a real business workflow — not just automation, but true customer understanding.

The upgraded **Customer Inquiry Manager** automatically:
📨 Receives inquiries from a React.js form
🧠 Understands user intent and sentiment using Amazon Bedrock AI
💾 Stores each record in Amazon RDS
✉️ Sends instant replies using Amazon SES
⏰ Generates daily summaries via CloudWatch Events

It’s simple yet powerful — like a smart customer-support assistant that never sleeps, now with serverless scalability.

---

🧩 **Architecture**

| Component           | AWS Service       | Purpose                                                           |
| ------------------- | ----------------- | ----------------------------------------------------------------- |
| Frontend            | React.js          | User interface with inquiry form                                  |
| Backend Logic       | AWS Lambda        | Processes form submissions, calls Bedrock, and stores data in RDS |
| AI Understanding    | Amazon Bedrock    | Detects intent and sentiment                                      |
| Database            | Amazon RDS        | Stores all inquiries                                              |
| Email Notifications | Amazon SES        | Sends confirmation to customer & notification to admin            |
| Automation          | CloudWatch Events | Triggers daily summary emails                                     |
| Monitoring          | CloudWatch Logs   | Tracks errors and performance                                     |

---

⚙️ **How It Works**

1. A user submits an inquiry through the **React.js form**.
2. The submission triggers a **Lambda function**.
3. Lambda calls **Amazon Bedrock** for intent and sentiment analysis.
4. Lambda stores the inquiry and analysis in **RDS**.
5. Lambda uses **SES** to send:

   * Confirmation email to the customer
   * Notification email to the admin team
6. **CloudWatch Events** runs daily, summarizing all inquiries received in 24 hours.

---

🧱 **Tools Used**
🖥️ **React.js** — Frontend UI
🐍 **Python (Lambda)** — Backend logic for handling inquiries
🧠 **Amazon Bedrock** — AI for intent & sentiment detection
🗄️ **Amazon RDS** — Inquiry storage
📧 **Amazon SES** — Automated emails
⏰ **CloudWatch Events** — Daily summaries & scheduling
🪵 **CloudWatch Logs** — Monitoring and error tracking

---

🚀 **Future Improvements**
🔄 Integrate real-time Bedrock API for live AI analysis
📊 Build an admin dashboard for inquiry analytics and trends
📱 Add SNS notifications for urgent or negative inquiries
🧰 Implement IAM roles for secure, resource-level permissions

---

🌟 **Result**
“It’s like giving your customer-support inbox a brain — fully serverless, scalable, and never sleeps.”

---

🧾 **Description**
The **Customer Inquiry Manager** is a serverless cloud-based AI application that intelligently handles customer messages. It shows how React.js, AWS Lambda, Amazon Bedrock, RDS, SES, and CloudWatch can work together in a real-world scenario — automating repetitive support tasks, improving response times, and generating insights into customer sentiment.

**Author:** Haneef Olajobi
**Built with:** React.js + AWS Lambda + Amazon Bedrock + RDS + SES
**Project Type:** Cloud Automation / AI Integration / Serverless Architecture
**Project #5 in my AWS Cloud Journey**


# 📨 Customer Inquiry Manager (AWS Project #5)

### 👨‍💻 My 5th AWS Cloud Project — Built entirely using the AWS Console  

This project manages **customer inquiries intelligently** using **Amazon Bedrock**, **RDS**, **SES**, and **CloudWatch** — all connected through an EC2-hosted web application.  
It demonstrates how cloud automation and AI can improve customer support workflows.

---

## 🧠 Project Story

I wanted to build something that feels close to a *real business workflow* — not just automation, but true customer understanding.

So I created the **Customer Inquiry Manager**, a small AI-powered system that automatically:
- 📨 Receives inquiries from a web form  
- 🧠 Understands what the person wants using **Amazon Bedrock AI**  
- 💾 Stores each record in **Amazon RDS**  
- ✉️ Sends instant replies using **Amazon SES**  
- ⏰ Generates daily summaries via **Amazon CloudWatch Events**

It’s simple yet powerful — like having a smart customer-support assistant that never sleeps.

---

## 🧩 Architecture

| Component | AWS Service | Purpose |
|------------|--------------|----------|
| **Web App** | EC2 | Hosts Flask-based inquiry form |
| **AI Understanding** | Amazon Bedrock | Detects intent and sentiment |
| **Database** | Amazon RDS | Stores all inquiries |
| **Email Notifications** | Amazon SES | Sends customer & admin emails |
| **Automation** | CloudWatch Events | Triggers daily summary emails |
| **Monitoring** | CloudWatch Logs | Tracks errors and performance |

---

## ⚙️ How It Works

1. A user submits an inquiry through the web form hosted on EC2.  
2. **Amazon Bedrock** analyzes the message and returns its category (Request, Complaint, Question) and sentiment (Positive, Neutral, Negative).  
3. The inquiry and AI analysis are saved in **Amazon RDS**.  
4. **Amazon SES** automatically sends:
   - A confirmation email to the customer  
   - A notification email to the admin team  
5. **CloudWatch Events** runs daily, summarizing all inquiries received within 24 hours.

---

## 🧱 Tools Used

- 🖥️ **Amazon EC2** — Host the web application  
- 🧠 **Amazon Bedrock** — Natural-language understanding (intent & sentiment)  
- 🗄️ **Amazon RDS** — Persistent storage for inquiries  
- 📧 **Amazon SES** — Automated emails  
- ⏰ **Amazon CloudWatch Events** — Daily summaries & scheduling  
- 🪵 **Amazon CloudWatch Logs** — Monitoring and error tracking  
- 🐍 **Python (Flask)** — Web framework for the form and backend logic

---

## 🚀 Future Improvements

- 🔄 Integrate real-time Bedrock API for live AI analysis  
- 📊 Build an admin dashboard for inquiry analytics and trends  
- 📱 Add **SNS notifications** for urgent or negative inquiries  
- 🧰 Include IAM roles for secure resource-level permissions  

---

## 🌟 Result

> “It’s like giving your customer-support inbox a brain — one that never sleeps.”

---

### 🧾 Description
The **Customer Inquiry Manager** is a cloud-based AI application that intelligently handles customer messages. It’s designed to show how **Amazon Bedrock**, **RDS**, **SES**, and **CloudWatch** can work together in a real-world scenario — automating repetitive support tasks, improving response times, and generating insight into customer sentiment.

---

**Author:** Haneef Olajobi  
**Built with:** AWS Management Console + Python (Flask)  
**Project Type:** Cloud Automation / AI Integration  
**Project #5 in my AWS Cloud Journey**

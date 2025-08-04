## **"Interactive Web Application with LangChain Integration"**
<h1 align="center">🌐 Interactive Web Application with LangChain Integration</h1>
<p align="center"><i>A powerful cloud-ready, AI-enhanced, DevOps-integrated web application developed using Python, LangChain, and AWS.</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/AI-LangChain%20%26%20ChatGPT-blueviolet" />
  <img src="https://img.shields.io/badge/DevOps-Docker%20%26%20Apache-green" />
  <img src="https://img.shields.io/badge/Cloud-AWS-orange" />
  <img src="https://img.shields.io/badge/Author-Sparsh%20Kumar-lightgrey" />
</p>

---
## 🚀 Project Overview

The **Interactive Web Application with LangChain Integration** is a dynamic, menu-driven platform built to unify multiple technologies into a single intuitive web interface. From Linux command execution and AWS resource management to WhatsApp messaging and Wikipedia querying, this project demonstrates the practical integration of:

- **Cloud Infrastructure**
- **AI via LangChain & OpenAI**
- **DevOps (Docker + Apache)**
- **Python-based backend**
- **Emotion-aware NLP**

It was developed under the mentorship of **Mr. Vimal Daga** at **LinuxWorld Informatics Pvt Ltd**, as part of a certified summer internship from **July 20, 2023 – September 5, 2023**.

---

## 🔧 Technologies Used

| Category           | Technology Stack                                                                 |
|-------------------|-----------------------------------------------------------------------------------|
| Frontend          | HTML, CSS, JavaScript, AJAX                                                       |
| Backend           | Python (CGI scripts), Apache Web Server                                           |
| AI Integration    | LangChain (OpenAI and Hugging Face LLMs)                                          |
| NLP Features      | Emotion detection and sentiment analysis                                          |
| Cloud Platform    | AWS (EC2, S3, IAM, SNS)                                                           |
| DevOps Layer      | Docker Containers                                                                 |
| Real-time Tasks   | Linux command execution, Wikipedia queries, WhatsApp messaging, email sending     |
| Hosting           | Apache HTTP Server hosted on AWS EC2                                              |

---

## 🧠 Key Features

- 📅 **Get Date & Time** from server
- 💻 **Run Real-time Linux Commands**
- 📬 **Send Emails**
- 📤 **Manage AWS Resources** (EC2, S3 Buckets, IAM)
- 🧾 **Send WhatsApp Messages**
- 📚 **Query Wikipedia**
- 🌐 **Deploy via Docker on Apache Server**
- 🤖 **ChatGPT-based NLP for Natural Language Understanding**
- 💬 **Emotion Detection using NLP**

---

## 🖼️ UI Snapshot

> _Include screenshots here if available_

```markdown
![Web UI Preview](./screenshot.png)
````

---

## 📁 Project Structure

```bash
├── cgi-bin/
│   ├── main.py                # Core logic using Python CGI
│   ├── aws_manager.py         # AWS resource scripts
│   ├── nlp_emotion.py         # Emotion detection logic
│   └── ...
├── static/
│   ├── styles.css
│   └── script.js
├── templates/
│   └── index.html
├── Dockerfile
├── app.conf                   # Apache configuration
└── README.md
```

---

## ⚙️ Setup & Deployment

### 🧪 Prerequisites

* Python 3.x
* Apache Server with CGI enabled
* AWS CLI configured with credentials
* Docker installed (optional for container deployment)

### 🛠️ Running Locally

```bash
git clone https://github.com/your-username/interactive-langchain-webapp.git
cd interactive-langchain-webapp
# Start Apache server and visit http://localhost/cgi-bin/main.py
```

### 🐳 Docker Deployment

```dockerfile
FROM python:3.9
WORKDIR /app
COPY . /app
RUN apt-get update && apt-get install -y apache2 && a2enmod cgi
EXPOSE 80
CMD ["apachectl", "-D", "FOREGROUND"]
```

```bash
docker build -t langchain-webapp .
docker run -p 8080:80 langchain-webapp
```

> Access via: `http://localhost:8080`

---

## 🌱 Future Scope

* 🔁 Continuous Integration with updated AI capabilities
* 🧠 Enhanced NLP responses with better language understanding
* ⚖️ Load balancing and performance optimization
* 🔐 Advanced security & authentication features
* 📡 Real-time chatbot and voice input features

---

## 👨‍💻 Developed By

**Sparsh Kumar**
Roorkee Institute of Technology
Email: `sparshvk18dominate@gmail.com`
🔗 GitHub: [github.com/sparsh](https://github.com/SparshVK/Summer_Internship_Project2023)

---

## 📝 Certificate Reference

> This project was certified by **LinuxWorld Informatics Pvt Ltd**, Jaipur
> Ref: `LW/JPR/2023/536`
> Mentored by: **Mr. Vimal Daga**
> Duration: `20 July 2023 – 5 September 2023`

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

> *"Where cutting-edge AI meets DevOps on the cloud — in one unified web platform."* 🌐

```

---

### ✅ To Complete the Setup:

- Add your screenshots (e.g., `screenshot.png`) and demo video (e.g., `demo.gif`) to the repo.
- Replace `your-username` with your actual GitHub username.
- Upload all relevant code files into the GitHub repository before publishing.

Would you like me to also generate a matching `LICENSE`, `.gitignore`, or help you structure the GitHub repo layout?
```

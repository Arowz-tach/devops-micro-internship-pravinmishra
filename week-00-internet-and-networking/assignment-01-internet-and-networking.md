# Week 00 - Internet and Networking

Part of the DevOps Micro Internship (DMI) with Agentic AI

---

# 🧑‍💻 Task 1: Using ChatGPT as Your Learning Assistant

## Scenario
I am a beginner learning DevOps and networking. Please explain what a networking protocol is in very simple, beginner-friendly language. Explain why networking protocols are important and give me one simple real-life example that I can easily understand. Also give one example of a networking protocol used when accessing a website.

## What is a networking protocol?

A networking protocol is simply a set of rules that computers follow when communicating with each other.

Think of it like a **language + rules** that devices use to understand one another.

For example:

> Your computer: “I want this webpage.”
> Website server: “Okay, here is the webpage.”
> Protocol: “Here are the rules for how we make that request and send the response.”

### Why are networking protocols important?

Without protocols, devices would not know **how to send, receive, or understand information**.

They help determine things like:

* 📤 How data is sent
* 📥 How data is received
* 🗣️ How devices communicate
* 🔒 How information can be protected
* ❌ What happens when data is lost or something goes wrong

### Simple real-life example

Imagine you and your friend want to communicate using **walkie-talkies**.

You agree on rules:

1. Press the button before speaking.
2. Say your friend's name first.
3. Only one person speaks at a time.
4. Say “over” when you're finished.

Those agreed rules are similar to a **networking protocol**.

The walkie-talkies are the devices, your voices are the data, and the communication rules are the protocol.

### Example when accessing a website 🌐

When you visit:

`https://example.com`

your browser communicates with the website's server using networking protocols.

One important protocol is **HTTP (Hypertext Transfer Protocol)**.

More specifically, because the website uses `https://`, it uses **HTTPS (HTTP Secure)**, which provides encrypted communication between your browser and the website.

A simplified process looks like:

```text
Your Browser
     │
     │  HTTPS request
     ▼
Website Server
     │
     │  HTTPS response
     ▼
Your Browser
```

### Easy definition to remember

> **A networking protocol is a set of rules that tells devices how to communicate and exchange data over a network.**

As you're learning **DevOps and networking**, you'll encounter protocols such as **HTTP/HTTPS, DNS, TCP, UDP, SSH, FTP, and DHCP** frequently.


You're new to DevOps and will frequently encounter technical questions. ChatGPT can be your learning companion.

## Your Task



Write a clear ChatGPT prompt to help you understand:

> "What is a protocol in networking? Explain with a simple real-life example."

Take a screenshot of your interaction showing:

* Your detailed prompt (with clear expectations)
* ChatGPT's simplified response with an example

## Screenshot

Save your screenshot in the `screenshots` folder and update the file name below.

![Task 1 Screenshot]([alt text](<Screenshot 2026-10-06 102944.png>) ![alt text](<Screenshot 2026-10-06 102843.png>) ![alt text](<Screenshot 2026-10-06 102911.png>) ![alt text](<Screenshot 2026-10-06 102929.png>))


Replace `task-1-chatgpt.png` with your actual screenshot file name.

---

## What I Learned (2–3 lines)

Add your answer here...

---

# 🌐 Task 2: Internet and Networking

## Scenario

Your friend is launching an online bookstore named **EpicReads**.

He asked you to explain how users globally can access his website hosted in Finland.

## Your Task

Write a short explanation (**100–150 words**) that includes:

* Packet Switching
* IP Address
* TCP/IP
* HTTP/HTTPS

💡 **Tip:** You may use ChatGPT (as demonstrated in Task 1) to refine your explanation.

## Answer

Add your answer here...
Mike is in the USA and wants to access EpicReads, an online bookstore hosted in Finland. His device connects to the internet using **TCP/IP**. The device has an **IP address**, which helps identify where the data should go. When Mike requests the EpicReads website, the request is broken into small pieces called packets. **Packet switching** allows these packets to travel across different networks and routes until they reach the EpicReads server in Finland. The browser uses **HTTP/HTTPS** to request the EpicReads webpage from the server. If HTTPS is used, the communication between Mike’s browser and the server is encrypted for better security. The server then sends the requested webpage back to Mike’s device, where his browser displays the EpicReads website.

---

# 🏗️ Task 3: Application Architecture & Stack

## Scenario

EpicReads bookstore has two application versions:

### Two-Tier Application

* Frontend
* Database

### Three-Tier Application

* Frontend
* Backend
* Database

## Your Task

* Draw simple diagrams (hand-drawn or tool-based such as draw.io)
* Label each layer clearly
* List at least two common technologies or tools used for each layer
* Submit a screenshot or photo clearly showing your own drawing

## Diagram Screenshot / Photo

Save your diagram image in the `screenshots` folder and update the file name below.

![Application Architecture Diagram](![alt text](<THREE-TIER ARCHITECTURE.drawio.png>) ![alt text](<TWO-TIER ARCHITECTURE.drawio.png>))


Replace `task-3-diagram.png` with your actual diagram file name.

---

## Technologies Used

### Frontend

* HTML
* CSS
* javaScript

### Backend

* Python
* Node.js

### Database

* MySQL
* PostgreSQL

---

# 🌍 Task 4: Domain Name & DNS (Basic Concepts)

## Scenario

Your friend's bookstore **EpicReads** is currently accessible through:

```text
52.172.142.222:3000
```

He purchased the domain:

```text
epicreads.com
```

## Your Task

In **50–100 words**, explain in your own words:

1. What is DNS (Domain Name System)?
2. Which DNS record type should be used to connect the domain to the given IP, and why?

## Answer

DNS (Domain Name System) translates a domain name into an IP address so that users can access the correct server without having to remember the IP address. For EpicReads, the domain `epicreads.com` should use an **A record** because `52.172.142.222` is an IPv4 address. The A record connects the domain name to this IPv4 address. The port `3000` is handled separately by the application or web server and is not part of the DNS A record.


---

# 💻 Task 5: Visual Studio Code Setup (Hands-on)

## Your Task

Install Visual Studio Code (if not already installed).

Take a screenshot of your VS Code environment showing:

* Terminal open inside VS Code
* Running a basic command:

### Windows

```powershell
dir
```

### Linux / macOS

```bash
pwd
ls
```

* Your selected VS Code theme clearly visible

⚠️ **Important:** The screenshot must show your username or another identifiable detail to confirm it is your environment.

## Screenshot

Save your screenshot in the `screenshots` folder and update the file name below.

![VS Code Setup Screenshot]()


Replace `task-5-vscode.png` with your actual screenshot file name.

---

# 🔗 Task 6: Publish Your Assignment as a LinkedIn Post

## Objective

Publishing on LinkedIn helps you:

* Build your professional online presence
* Reinforce your learning
* Document your DevOps journey publicly

## Your Task

Summarize your answers from Tasks 1–5 into a LinkedIn post.

Clearly structure your post into the following sections:

* ChatGPT
* Internet & Networking
* App Architecture
* DNS
* VS Code Setup

Use the credit note that matches your track:

Add the following credit note at the end of your post **(If you are DMI Cohort 3 student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) with Agentic AI — Cohort 3 — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=cohort3**

**Tag [Pravin Mishra](https://www.linkedin.com/in/pravin-mishra-aws-trainer/) in your LinkedIn post, then tag Lead Co-Mentor — [Anjana Muthunayake](https://www.linkedin.com/in/anjana-muthunayake/).**

Add the following credit note at the end of your post **(If you are DMI Self-paced track student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) — Self-Paced Engineer Track — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=self-paced**

Add the following credit note at the end of your post **(If you are DMI Campus student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) — Campus — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=campus**

**Tag [Pravin Mishra](https://www.linkedin.com/in/pravin-mishra-aws-trainer/) in your LinkedIn post, then tag Lead Co-Mentor — [Anjana Muthunayake](https://www.linkedin.com/in/anjana-muthunayake/).**

Hashtags:

#DMIByPravinMishra #AgenticAI #DevOps

Replace `YOUR-GITHUB-USERNAME` with your GitHub username — that link is your public DMI progress page (your graded badge page).
---

## LinkedIn Post URL

Paste your LinkedIn post URL here:

```text
https://lnkd.in/p/eMkjuK8A
```

---

## LinkedIn Post Backup Copy
https://lnkd.in/p/eMkjuK8A

🚀 **My DevOps Learning Journey — Week 00**

I’m excited to share my progress in the **DevOps Micro Internship (DMI)**.

This week, I learned some important fundamentals about the Internet, networking, and how applications communicate.

Here are some of the things I learned:

🔹 **Networking Protocols**
I learned that a networking protocol is a set of rules that devices follow to communicate with each other.

🔹 **How the Internet Works**
I learned how someone in the USA can access an online bookstore hosted in Finland using **Packet Switching, IP Address, TCP/IP, and HTTP/HTTPS**.

🔹 **Application Architecture**
I learned the difference between **two-tier and three-tier architecture**, including the roles of the Frontend, Backend, and Database.

🔹 **DNS**
I learned how DNS translates a domain name into an IP address and why an **A record** is used for an IPv4 address.

🔹 **VS Code & Terminal**
I also practiced using VS Code, its integrated terminal, and basic commands such as `whoami`, `pwd`, and `ls`.

This foundation is helping me understand what happens behind the scenes when we access websites and applications.

I’m looking forward to learning more about **Linux, Cloud Computing, DevOps, Networking, and Automation** as I continue this journey. 🚀

P.S. This post is part of the DevOps Micro Internship (DMI) — Foundation Track — by [Pravin Mishra](https://www.linkedin.com/in/pravin-mishra-aws-trainer/). My graded progress is public: https://dmi.pravinmishra.com/s/Arowz-tach.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=foundation

#DMIByPravinMishra #DevOps #Networking #CloudComputing #Linux #LearningInPublic


---

# Reflection – Week 0

### What did you find easy?

Add your answer here...
i am a computer science graduate so most of the terms are familiar with me 
---

### What was difficult?

Add your answer here...
 troubleshooting with chat gpt only 
---

### What will you improve next week?

 i will improve the time of studding 

---

## 📌 About DMI & CloudAdvisory

DevOps Micro Internship (DMI) is a project-based DevOps program run by Pravin Mishra (The CloudAdvisory) focused on real-world execution, systems thinking, and career readiness.

It helps learners build strong DevOps foundations with hands-on experience.


## 📌 Resources

- 🌐 **DMI Official Website:** https://dmi.pravinmishra.com?utm_source=github&utm_medium=readme  
- 🎓 **University:** https://university.pravinmishra.com?utm_source=github&utm_medium=readme  
- 💬 **Discord Community:** https://discord.pravinmishra.com?utm_source=github&utm_medium=readme  
- 📝 **Blog:** https://dmi.pravinmishra.com/blog?utm_source=github&utm_medium=readme  
- ▶️ **YouTube Playlist (DMI Cohort 3):** https://www.youtube.com/playlist?list=PLFeSNDtI4Cho  
- 🔗 **Pravin Mishra (LinkedIn):** https://www.linkedin.com/in/pravin-mishra-aws-trainer/  
- 🏢 **CloudAdvisory (LinkedIn):** https://www.linkedin.com/company/thecloudadvisory/

---

*This submission is part of DevOps Micro Internship (DMI) — Agentic AI Track*


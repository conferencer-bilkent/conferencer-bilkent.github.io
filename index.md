---
layout: default
title: "Conferencer"
---

# Welcome to Conferencer 🚀

A modern, intuitive, and scalable platform for academic conference management. Explore the future of conference organization!

---

## About Us

Conferencer is a comprehensive web-based platform designed to streamline and elevate the management of academic conferences. By focusing on flexibility, security, and user experience, it empowers organizers, reviewers, and authors to collaborate efficiently across every stage—from submission to decision-making.

---

## Our Mission

At Conferencer, we believe in empowering academic organizers with a seamless, intuitive conference management experience. Our platform supports diverse conference needs, from managing multi-track events to building shared program committees. With features such as reviewer recommendations, customizable profiles, and advanced filtering options, Conferencer adapts to the evolving needs of the academic community, enabling organizers to focus on meaningful engagement and insights.

---

## Features

- 🔒 **Role-Based Access Control:** Secure permissions for authors, reviewers, chairs, and admins.
- 🔐 **Authentication & Integrations:** Login with email or Google accounts. Integration with ORCID and academic databases.
- 🛠️ **Modular Architecture:** Built with React, Flask, and MongoDB—scalable, secure, and efficient.
- 📄 **Streamlined Submissions:** Easy uploading, tracking, compliance checks, and version control.
- 📌 **Program Committee Management:** Smart invitations, historical performance metrics, and conflict-of-interest detection.
- 📈 **Reviewer Assignment Engine:** Automated matching based on expertise, past performance, and similarity analysis.
- 📊 **Review Analytics & Ratings:** Track reviewer performance, feedback quality, and historical contributions.
- 🧩 **Multi-Track Conference Handling:** Independent track configuration with shared or isolated reviewer pools.
- 🔁 **Real-Time Collaboration:** Integrated chat, notifications, and review discussion features.
- 🎯 **My Tasks Dashboard:** Personalized views of submissions, reviews, and deadlines for each user.
- 🧠 **AI-Powered Review Detection (Future Plan):** NLP tools to detect LLM-generated content and preserve review authenticity.

---

## Scenarios

### Creating a Conference - Demo Video

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; border-radius: 8px; margin: 20px 0;">
  <video id="demoVideo" controls style="width: 100%; border-radius: 8px; margin: 20px 0;">
    <source src="assets/0511_Com.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<div>
  <h3>📽️ Jump to a Scenario</h3>
  <ul>
<ul>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(0);">Create conference</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(27);">Invite people</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(41);">Accept invitation</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(55);">Assign a new superchair</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(107);">Create a new track</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(135);">Add people to track</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(146);">View/edit profile</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(183);">Assign a track chair</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(195);">Conference overview</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(255);">View reviews</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(267);">Change decision</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(277);">Conflict</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(300);">Assign paper</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(320);">Trackchair view</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(337);">My tasks and make review</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(375);">Trackchair read review and make decision</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(405);">Review rating</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(439);">Chat and reply</a></li>
  <li><a href="#" onclick="event.preventDefault(); seekVideo(461);">See my submissions</a></li>
</ul>
  </ul>
</div>

<script>
  function seekVideo(seconds) {
    const video = document.getElementById('demoVideo');
    video.currentTime = seconds;
    video.play();
  }
</script>

---

## Technology Stack

| Component        | Technology                      |
| ---------------- | ------------------------------- |
| Frontend         | React (TypeScript, Context API) |
| Backend          | Flask (Python), Flask-RESTful   |
| Database         | MongoDB                         |
| Authentication   | Session-based + Google OAuth    |
| Containerization | Docker                          |
| Web Server       | Nginx                           |
| Hosting          | Ubuntu VPS                      |
| Tools            | Git, GitHub, Jira, VS Code      |

---

## System Architecture

Conferencer uses a modular and scalable architecture:

- **Frontend (React)**: Provides a dynamic and responsive user interface with real-time interactions.
- **Backend (Flask)**: Handles business logic, API endpoints, security, and communication between modules.
- **Database (MongoDB)**: Stores user data, submissions, reviews, and statistics in a flexible document-based format.
- **Access Control**: Implements secure, role-based access through session management and HTTPS.
- **Containerized Services**: Each component runs in Docker for portability and consistent environments.
- **Reverse Proxy (Nginx)**: Routes client requests securely and efficiently to backend services.

---

## Team

- **Abdurrahman Bilal Kar:** [GitHub](https://github.com/abilalkar) [Logbook](https://docs.google.com/document/d/1tvbA_a8OFBS25H6mmW2rgRJPnKD4thqJQN4Bayte7iM/edit?usp=sharing)
- **Ahmet Memduh Tutuş:** [GitHub](https://github.com/memduhtutus) [Logbook](https://docs.google.com/document/d/1RLuLGbGP9tq8x2x4JN0-rEbsMUVBQWjykxkwLvANRtM/edit?usp=sharing)
- **Atilla Emre Söylemez:** [GitHub](https://github.com/At1llaes22) [Logbook](https://docs.google.com/document/d/1bNkmu5djHaaG9sipRPZrShTFjT25p-enPCtM-9O3fy4/edit?usp=sharing)
- **Berkay Ayçiçek:** [GitHub](https://github.com/brkye) [Logbook](https://docs.google.com/document/d/1PBVK1BPU3sIirE2HYDI7CidOOuJ1UpTuBsUUFxfyN68/edit?usp=sharing)

---

## Deliverables

- 📚 [Project Information Form](assets/Paper-Citadel_Project_Information_Form.docx)
- 📚 [Project Specification Report](assets/T2409-Project_Specification_Document.pdf)
- 📚 [Analysis Requirement Report](assets/T2409-Analysis_Requirement_Report.pdf)
- 📚 [Detailed Design Report](assets/T2409-Detailed_Design_Report.pdf)
- 📚 [Final Report](assets/T2409-Final_Report.pdf)

---

### © 2025 Conferencer

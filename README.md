# Arsalan Khan - Interactive Resume & Portfolio

This repository contains the source code for my interactive online resume, built as a modern, single-page web application. The goal of this project is to provide a more engaging and informative alternative to a traditional paper resume, showcasing not just my experience and skills, but also my ability to build and deploy functional web applications.

The live version can be viewed on GitHub Pages.

---

## Features

* **Clean, Professional UI**: A responsive, two-column layout designed for clarity and easy navigation on any device.
* **Interactive Tabs**: Dynamic content sections for Experience, Projects, and Education to keep the information organized and uncluttered.
* **AI-Powered Assistant**: An integrated chatbot, powered by the Google Gemini API, that acts as an interactive FAQ for recruiters.
* **Project Showcase**: A dedicated section to highlight key development projects with descriptions and links.

---

## Project Structure

The repository is structured with standard web development practices for easy maintenance and deployment on platforms like GitHub Pages.


/
├── index.html      # The main HTML file containing the content structure.
├── style.css       # The CSS file for all styling and layout rules.
└── script.js       # The JavaScript file for interactivity, tabs, and chatbot logic.


---

## Technology Stack

The project leverages a modern, lightweight stack focused on accessibility and performance.

| Category      | Technology / Library                               | Purpose                                      |
| :------------ | :------------------------------------------------- | :------------------------------------------- |
| **Frontend** | HTML5, CSS3, JavaScript (ES6+)                     | Core structure, styling, and logic.          |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/)           | A utility-first CSS framework for rapid UI development. |
| **Fonts** | [Google Fonts](https://fonts.google.com/) (Lora & Inter) | Professional and readable typography.        |
| **AI** | [Google Gemini API](https://ai.google.dev/)        | Powering the conversational AI assistant.    |
| **Hosting** | [GitHub Pages](https://pages.github.com/)          | Deployment of the live interactive resume.   |

---

## AI Assistant Capabilities

The integrated AI assistant is designed to be a helpful tool for recruiters and visitors, offering a quick way to get answers to common questions.

* **Interactive FAQ:** The chatbot starts with pre-defined prompts for key information, such as experience with AI, full-stack projects, and technical skills.
* **Context-Aware Responses:** The assistant's knowledge is based entirely on the content of this resume. It uses a carefully crafted context prompt to ensure its answers are accurate and relevant to my professional profile.
* **Natural Language Queries:** Users can also type their own questions, and the Gemini API will parse the query and provide a response based on the provided context.
* **Error Handling:** If a question falls outside the scope of the resume's content, the assistant is programmed to politely state that the information is not available and recommend contacting me directly.

---

## Resume Content Overview

### Summary

A technical writer with a passion for simplifying complexity. My background in journalism taught me to find the story in any subject, a skill I now apply to technology. I translate the logic of software, cloud infrastructure, and APIs into clear, concise documentation that empowers developers and users. I believe the best documentation isn't just a manual—it's an essential part of a successful product.

### Toolkit

| Category               | Skills                                          |
| :--------------------- | :---------------------------------------------- |
| **Core Disciplines** | Technical Writing, Content Strategy, Information Architecture, Developer Education |
| **Technologies & Tools** | AWS, GCP, Azure, Git & GitHub, Terraform & CI/CD, Markdown & DITA/XML |
| **Languages** | Python, JavaScript, Bash                        |

### Experience

| Role                                   | Company / Context      | Period          | Key Contributions                                                                                              |
| :------------------------------------- | :--------------------- | :-------------- | :------------------------------------------------------------------------------------------------------------- |
| **Cloud Infrastructure & Docs Consultant** | Self-Directed          | 2020 - Present  | Architected developer-centric documentation for cloud SDKs (AWS, GCP, Azure) and automated CI/CD doc pipelines. |
| **Technical Writer & DocOps Architect** | AVIC Heavy Machinery   | 2013 - 2020     | Translated complex engineering schematics and standardized documentation workflows with DITA/XML and Markdown.     |
| **Copywriter & Content Specialist** | QUBEE                  | 2012 - 2014     | My entry into tech, turning dense service details into clear, customer-facing copy and support guides.         |

### Key Projects

| Project                                  | Description                                                                                                                                                             | Links                                                                                                                                                           |
| :--------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Skittly - Full-Stack PM Tool** | A complete MERN-stack application built from the ground up, demonstrating full-stack development capabilities. Features a documented API and a deployed frontend.           | [Live App](https://skittle-frontend.vercel.app/) \| [Frontend Repo](https://github.com/timedilationv2/skittly-frontend)                                         |
| **Sophie AI - Conversational AI Chatbot**| A self-contained, customizable AI chatbot built with Python and Flask. This project showcases the ability to integrate AI/ML models into a functional web application.      | [View on GitHub](https://github.com/timedilationv2/sophie-ai)                                                                                                   |
| **DitaDocs - Doc Workflow Tool** | A command-line tool in Python to convert legacy DITA/XML documentation into modern Markdown, demonstrating domain knowledge and the ability to build workflow improvement tools. | [View on GitHub](https://github.com/timedilationv2/ditadocs)                                                                                                    |



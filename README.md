 ![svgviewer-output](https://github.com/ElloTechnology/backend_takehome/assets/3518127/561bc8d4-bffc-4360-b9ea-61e876bcec93)

 
# Ello Engineering Challenge

👋 Hello,
We are really excited about you potentially joining the team, so we designed this take home exercise to give you a taste of the challenges you may encounter in the role, and better understand what it would be like to work closely together.

Thanks for taking the time!

 ## About Ello

Ello is a forward-thinking educational technology company dedicated to revolutionizing the way children learn to read. Our mission is to empower young readers with the tools they need to become proficient and passionate readers. We believe that fostering a love for reading is essential for a child's academic and personal growth.

**Note:** Please don't fork this repository or create a pull request against it. Other applicants may take inspiration from it. You should create another repository for the challenge. Once the coding challenge is completed, email your solution back to our team at [fullstack2024@ello.com](mailto:fullstack2024@ello.com).

## Challenge: The AI-Powered Learning Companion

This challenge is designed to simulate a real-world problem we might tackle. It's an opportunity for you to showcase your technical skills, architectural thinking, and problem-solving approach in a tangible way. We value creativity and solid engineering principles.

We respect your time. Please do not spend more than 4-8 hours on this challenge. We are more interested in your approach, architectural decisions, and a working proof-of-concept than a perfectly polished, production-ready application.

A key aspect of this challenge is the thoughtful integration of modern tools. We encourage you to use AI assistants to help you build, and we are very interested in learning how you leverage them effectively.

## The project

Your mission is to design and build a prototype for an interactive, AI-powered learning companion for kids. The system will guide a child through a short, voice-driven learning and evaluation session.

The core interaction should be voice-based, facilitated by **LiveKit** for real-time audio streaming between the _client_ and your _backend_ for processing. The interaction should be conversational, driven by prompts you design for a Large Language Model (LLM).

The user journey is as follows:

- A child joins a new session through the UI.
- An AI tutor greets the child, asks for a brief introduction, and requests for childs name and parent's email address to send a progress report.
- The AI tutor conducts a short learning activity on a simple topic.
  - You have the freedom to choose the topic (e.g., "What are the three primary colors?", "What is a planet?").
- Following the lesson, the AI asks a few questions to gently evaluate the child's understanding.
  - e.g. if it was about colors ask something like Can you name one primary color for me?
- Finally, the system generates a summary report of the session and emails it to the address provided.
  - Backend should generate a simple performance report
  - This report must be sent to the email address provided during onboarding.

## Tech Stack

- Python, Flutter and Livekit
- If you believe a different stack is a better fit, you may use it—but explain your decision, why it's better, and how it integrates.
- You may use AI tools to drive teaching and evaluation.

## Submission Deliverables

To complete the challenge, please provide the following:

- A link to a public Git repository (e.g., on GitHub) containing your full source code.
- A short video (e.g., Loom, YouTube) or a series of annotated screenshots that walk us through a complete user session in your application.
- Comprehensive `README.md` containing
  - Setup Instructions: Clear, step-by-step instructions on how to run your project
  - Architectural Overview: A high-level explanation of your system's architecture. Why did you structure your backend and frontend the way you did? What are the main components?
  - Data Flow: A description or diagram explaining how data moves through your system from the moment a user speaks to the moment an email is sent.
  - Trade-offs & Limitations: A brief discussion of the design trade-offs you made and the limitations of your prototype.
  - AI Usage Explained: A dedicated section explaining how you leveraged AI tools.

## Evaluation Creteris

We will be evaluating your submission based on the following criteria:

- System Functionality
  - Meets workflow requirements (session → teaching → evaluation → report).
  - Working over voice interaction
  - Report is generated and emailed.
- Architectural Design & System Thinking:
  - Clarity and soundness of your architecture.
  - Thoughtful justification for your technology and design choices.
  - Demonstrated understanding of asynchronous data flow in a full-stack system.
  - Your ability to articulate trade-offs and identify areas for future improvement.
- Code Quality & Best Practices:
  - Separation of Concerns: Clean separation between frontend, backend, and third-party services.
  - Async/Concurrency: Correct and efficient use of asynchronous patterns in code.
  - Error Handling: How does the system handle potential failures (e.g., LLM API is down, LiveKit disconnects, invalid email)?
- User Experience (UI/UX):
  - Clean and usable UI/UX.
  - The user journey is intuitive and smooth.
  - The UI is clean, responsive, and appropriate for the application's purpose.
- Innovative Use of AI:
  - We want to see how you think about and leverage AI.
  - The quality and creativity of the prompts used to guide the LLM.
  - The seamlessness of the AI integration into the overall application flow.

We are excited to see what you build. Good luck!

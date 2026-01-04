# AthenaHacks - AI Trojan Horse 

An interactive cybersecurity simulation game that educates users on threat detection, malware defense, and ethical hacking techniques—drawing inspiration from the legendary Trojan Horse of Greek mythology.


<img width="806" height="492" alt="image" src="https://github.com/user-attachments/assets/a83fd800-e0ce-4b12-a8e0-964948414cbb" />



## Built With

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![JSX](https://img.shields.io/badge/JSX-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

## Inspiration

Since we attended AthenaHacks, we wanted to work on a project that closely relates to Greek mythology while integrating it with computer science. We decided to create an educational cybersecurity game focused on defense strategies for beginners.

## What It Does

Players take on the role of a cybersecurity defender, protecting their system from AI-generated Trojan Horse cyberattacks. They must:

- Analyze live threat feeds
- Quarantine malware
- Strengthen firewalls
- Counteract evolving digital threats

All within a strategic, mythologically inspired cyber battlefield.

<p align="center">
  <em>Live Threats Feed & Defense Grid</em>
  <br><br>
  <img width="806" alt="Game Dashboard" src="https://github.com/user-attachments/assets/cf8c2ba3-57cd-45f1-9fc5-f3213fc09b13" />
</p>



<p align="center">
  <em>System Health Monitoring</em>
  <br><br>
  <img width="806" alt="System Symptoms" src="https://github.com/user-attachments/assets/93faf233-0557-4f77-907a-cefe8f6b9067" />
</p>



<p align="center">
  <em>Successfully Neutralized Threat</em>
  <br><br>
  <img width="806" alt="Threat Neutralized" src="https://github.com/user-attachments/assets/7545a6e3-3829-49bb-845b-1dde43a0f884" />
</p>


## How We Built It

| Layer | Technology |
|-------|------------|
| **Frontend** | React |
| **Backend** | Flask |
| **Database** | MongoDB |
| **AI** | Google Gemini API |

- **React Frontend** — Dynamic and interactive user interface
- **Flask Backend** — Real-time game state management and API requests
- **MongoDB** — Player progress storage
- **Google Gemini API** — Generates realistic, evolving cybersecurity threats with dynamic descriptions, system symptoms, and interactive challenges

## Challenges We Ran Into

- **Trojan Defense Grid Integration** — Connecting the defense grid with the Live Threats Feed proved difficult. We had the answer sequences but struggled with implementation.
- **Malware Mutation System** — Incorporating mutations required significant changes to our game logic.
- **Button Functionality** — Initially made endpoints reliant on file names, requiring a redesign to work with our logic.
- **Gemini API Rate Limits** — Exceeded allotted limits due to unawareness of restrictions.
- **Prompt Engineering** — Tailoring precise requests to Gemini AI required careful language crafting.

## Accomplishments We're Proud Of

- Created a unique blend of cybersecurity education and gaming
- Significant UI/UX improvement compared to prior projects

## What We Learned

- Creating stars using a randomization algorithm
- Parsing API responses and writing/saving them to files
- Different types of malware and their mutation patterns

## What's Next

- **Dual Role Mode** — Allow players to choose between being a hacker or defender
- **Hacker Campaign** — Craft deceptive cyberattacks and infiltrate secure systems
- **Athena AI Mentor** — An AI guide providing cryptic wisdom and hints about threat detection and hacking strategies

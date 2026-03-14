# Smart-Attend Mobile App – SDLC Assignment

**Author:** Ajay Bisht

---

## Project Overview

Smart-Attend is a mobile-based attendance system designed to automate classroom attendance using **Geo-fencing technology**. When a student enters the classroom boundary, the system detects their location and automatically records attendance.

During development, a new requirement was introduced: **Biometric Face ID verification** to prevent proxy attendance.
This assignment analyzes how different **Software Development Life Cycle (SDLC)** models handle such changes and demonstrates how **Agile Scrum** can adapt to evolving requirements.

---

## Problem Scenario

Initially, the application was designed to mark attendance using **Geo-fencing only**.
However, the Dean later requested an additional feature:

> **Face ID biometric verification to prevent proxy attendance.**

This change occurs **midway through development**, making it a perfect case to compare **Waterfall vs Agile development models**.

---

## Waterfall Model Analysis

The Waterfall model follows a **sequential development process** where each phase must be completed before the next begins.

### Limitations in This Scenario

**1. Rigidity**

* Requirements are fixed at the beginning.
* Adding Face ID later requires revisiting earlier phases.

**2. High Cost of Change**

* System architecture and database structure must be modified.
* Additional modules for biometric authentication are needed.

**3. Delayed Testing**

* Testing occurs only at the end.
* Integration problems with Face ID and Geo-fencing may appear very late.

Because of these limitations, the Waterfall model becomes inefficient when requirements evolve.

---

## Agile Scrum Approach

To handle the new requirement efficiently, the project shifts to **Agile using the Scrum framework**.

Scrum divides development into short iterations called **Sprints**.

### Sprint 1 – Minimum Viable Product (MVP)

Focus on building the core functionality:

* Basic mobile user interface
* Student login using university ID
* Geo-fencing location detection
* Automatic attendance marking
* Teacher dashboard to view attendance

### Sprint 2 – Feature Enhancement

Focus on security and improvements:

* Face ID biometric verification
* Camera integration for facial recognition
* Combined verification (Geo-fencing + Face ID)
* Enhanced reporting dashboard

---

## Sprint Backlog (Sprint 1)

| Task ID | User Story                                          | Priority | Estimated Hours |
| ------- | --------------------------------------------------- | -------- | --------------- |
| US01    | Student login using university ID                   | High     | 4               |
| US02    | Teacher views real-time list of present students    | High     | 6               |
| US03    | System detects student within 10m using Geo-fencing | High     | 8               |
| US04    | Student receives attendance notification            | Medium   | 3               |
| US05    | Admin manually override attendance                  | Low      | 4               |

---

## CI/CD in This Project

**Continuous Integration and Continuous Deployment (CI/CD)** automate building, testing, and deployment of the application.

Benefits include:

* Faster integration of new features
* Automated testing
* Reliable and consistent releases
* Quick deployment of updates to users

Whenever developers push new code to the repository, automated pipelines ensure the application builds successfully and passes all tests.

## Conclusion

The Smart-Attend project demonstrates why **Agile methodologies are better suited for projects with evolving requirements**. By using Scrum, the development team can respond quickly to changes such as integrating **biometric Face ID verification** while continuing to deliver functional software in short iterations.

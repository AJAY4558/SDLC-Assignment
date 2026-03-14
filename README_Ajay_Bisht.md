# SDLC Assignment -- Smart-Attend Mobile App

Author: Ajay Bisht

## Project Description

This project analyzes how different Software Development Life Cycle
(SDLC) models handle changing requirements. The Smart-Attend mobile
application uses Geo-fencing to automatically mark attendance when a
student enters the classroom.

Midway through development, a new requirement was introduced: **Face ID
biometric verification** to prevent proxy attendance.

## Waterfall Model Issues

Using the Waterfall model would cause major problems: - Lack of
flexibility when requirements change - High cost of redesigning system
architecture - Late discovery of integration issues during final testing

## Agile (Scrum) Solution

The Scrum framework allows development in small iterations called
sprints.

Sprint 1: Build the Minimum Viable Product (UI, login system, and
Geo-fencing attendance).\
Sprint 2: Integrate Face ID biometric verification and improve the
reporting dashboard.

## Why CI/CD is Important

CI/CD helps automate testing, integration, and deployment. Each time
developers push code to GitHub, automated pipelines build and test the
application. This ensures faster updates and stable releases for
students and teachers.

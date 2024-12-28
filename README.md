# CourseManagementSystem-WTC
Repo to create first version of WTC's CourseManagementSystem (CMS).

## Project Description

**Description** : 
    The Course Management System (CMS) is a web and mobile application that allows users to access and manage courses. 
    The application will have a dashboard page that displays the user's progress in each course, a marketplace page where users can view and register for courses, and a course page that displays the course content and problems. 
    The application will also have a user authentication system that allows users to log in and access their account.

**Stack** : 

- FE - React + React Native (mobile)

- BE - .Net Core 8.0

- DB - Polyglot persistence - PostgreSQL + MongoDB

- Orchestration & Containerization - Docker + Kubernetes

- VCS - Git

- CI/CD - Git Actions / Jenkins (will finalize post version 1 build ) 

- Micro service architecture ( FE two projects & BE one project) 

## Application Description

1. Welcome Page - 
	- Logo
	- Sign Up / Sign In Button
	- Market Place Button
	- If logged in, Sign Out Button

2. Dashboard Page - 
	- User's progress in each course
	- Current plan
	- Upcoming courses
	- Completed courses

4. Market Place Page - 
	- List of courses (currently, only 3 courses are available)
	- Course details (name, description, price, rating)
	- Register button

5. Course Page - 
	- Course content - List of chapters
	- Flag for each chapter (completed, Important)
	- Problems List Per Chapter
	- Star Question - Save the question for later review
	- Flag for each problem 
		- Not Yet Attempted - Default
		- Attempted - On Visiting the question
		- completed - Only selectable after attempting the question 

## Project Architecture

The architecture for the Course Management System (CMS) will follow a microservices approach, with separate services for the frontend (React and React Native) and backend (.NET Core). The backend will interact with both PostgreSQL and MongoDB databases. Docker and Kubernetes will be used for containerization and orchestration.

## Project Repositories

### Backend Repository:

<div align="center">
  <a href="https://github.com/SaiGopal-Challa/WTC_CMS_BE">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=SaiGopal-Challa&repo=WTC_CMS_BE&theme=radical" alt="CourseManagementSystem-WTC Backend Repo" style="border-radius: 10px; box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);"/>
  </a>
</div>



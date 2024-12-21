# CourseManagementSystem-WTC
Repo to create first version of WTC's CourseManagementSystem (CMS).

## Project Description

**Stack** : 

- FE - React + React Native (mobile)

- BE - .Net Core 9.0

- DB - Polyglot persistence - PostgreSQL + MongoDB

- Orchestration & Containerization - Docker + Kubernetes

- VCS - Git

- CI/CD - Git Actions / Jenkins (will finalize post version 1 build ) 

- Micro service architecture ( FE two projects & BE one project) 

**Application Description**

1. Page 1 - ( Visible to All ) Pre Login

2. Page 2 ( not an actual page, just change in component and state )- Same as Page 1, just logged in

3. Page 3 - Dashboard Page ( might be actual landing page, will decide later )

	- Dashboard Page

	- three boxes for 3 courses

	- each box - 4 metrics ( 1 - % of course content finished ; 2, 3, 4 - count of ( Easy, Medium, Hard) questions solved / total no.of questions).

4. Page 4 - Market Place ( page might be dropped , might have redundancy with dashboard ) - Current plan - Only 3 static Courses , 3 rectangular boxes, ( not present if already registered ) ,

5. Page 5 - Course Page

	- Course name as heading,

	- chapter n ( if clicked , dropdown of content rows, ( like bullet points) . all will be either youtube links or pdfs) ( after each point, can mark completed, or flag it)

	- Problems of chapter n ( if clicked, dropdown of questions ( as bullet points), all redirect to leetcode, after each question can be marked ( attempted, solved, not yet touched ) [ all Qs are in "Not Yet Tried" status, once the link is clicked, it changes to "Attempted", only when the status is Attempted can the user click on status and mark it "solved". If status is in "Not Yet Tried", user can not get the dropdown when clicked, will get pop up saying, attempt the question first.

## Project Setup

## Time/Priority Matrix

#### MVPs
- Render data on page 
- Allow user to choose favorites CRUD functionality on student profiles
- CRUD functionality on teacher profiles
- Match students with teacher(s) based on at least 1 criteria
- Sign-in functionality (on landing page?)
- Deploy early (M/T EOD?)

#### PostMVPs 
- Add additional criteria (idiom, language, secondary instrument, location, etc)
- Save matches/favorites
- Reviews of teachers
- Reviews of students
- Age ranges for students
- Search functionality
- Headshot or thumbnail
- Avatar
- Password functionality
- Track time of submission (newest on top)

#### MVP
| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| CRUD functionality on student profiles | H | 2hr | -hr | -hr|
| CRUD functionality on teacher profiles | H | 2hr | -hr | -hr|
| Match students with teacher(s) based on at least 1 criteria| H | 2hr | -hr | -hr|
| Sign-in functionality (on landing page?) | H | 2hr| -hr | -hr |
| Deploy early (M/T EOD?)| H | 2hr | -hr | -hr|
| Responsive | H | 2hr | -hr | -hr|
| Total | H | 12hrs| -hrs | -hrs |

#### PostMVP
| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Track time of submission (newest on top) | H | 2hr | -hr | -hr|
| Search functionality | H | 2hr | -hr | -hr|
| Add additional criteria (idiom, language, secondary instrument, location, etc) | M | 2hr | -hr | -hr|
| Save matches/favorites | M | 2hr | -hr | -hr|
| Reviews of teachers | M | 2hr | -hr | -hr|
| Reviews of students | M | 2hr | -hr | -hr|
| Headshot or thumbnail| M | 2hr | -hr | -hr|
| Avatar | L | 2hr| -hr | -hr |
| Age ranges for students | L | 2hr | -hr | -hr|
| Password functionality | L | 2hr | -hr | -hr|
| Total | H | 22hrs| -hrs | -hrs |


# Project Overview

## Forte App

## Project Schedule

| Day | Deliverable | Status
|---|---| ---|
|Day 1 - Fri|Project Proposal|In Progress
|Day 1 - Fri|Backend Repo|Done
|Day 1 - Fri|Frontend Repo|Done
|Day 1 - Fri|Create BE Basic File Structure|Incomplete
|Day 1 - Fri|Create FE Basic File Structure|Incomplete
|Day 1 - Fri|BE Placeholder Content|Incomplete
|Day 1 - Fri|FE Placeholder Content|Incomplete
|Stretch Goal|Deploy FE|Incomplete
|Stretch Goal|Deploy BE|Incomplete
|Day 3- Mon|BE Models|Incomplete
|Day 3- Mon|BE Routes|Incomplete
|Day 3- Mon|FE Component Mapping|Incomplete
|Day 3- Mon|FE Component/File Fill|Incomplete
|Day 3- Mon|FE Routes|Incomplete
|Day 3- Mon|Re-Deploy FE/BE|Incomplete
|Day 4 - Tues|FE Components|Incomplete
|Day 4 - Tues|Styling|Incomplete
|Day 4 - Tues|Re-Deploy FE/BE|Incomplete
|Day 5 - Wed|FE Component|Incomplete
|Day 5 - Wed|Styling|Incomplete
|Stretch Goal|Post-MVP Deliverables|Incomplete
|Day 5 - Wed|Re-Deploy FE/BE|Incomplete
|Day 6 - Thurs|Post-MVP Deliverables|Incomplete
|Day 6 - Thurs|Final deployment|Incomplete
|Day 6 - Thurs|Re-Deploy FE/BE|Incomplete
|Day 7 - Fri|Presentation|Incomplete

## Project Description

Forte is an app that allows students to find and connect with music teachers for online lessons.

## User Stories

Forte's user stories correspond with our MVPs and Post MVPs. 

Users want to create accounts, so they can access the app.
Users want to be able to update their account information in case anything changes.
Users want to be able to delete their account to keep their information private if they no longer wish to use Forte.
If the user is a teacher, they want to be matched with students that match certain criteria.
If the user is a student, they want to be matched with teachers hat match certain criteria.
Teacher users want to be able to search for students.
Student users want to be able to search for teachers.
Users want to have passwords to their accounts to feel secure.

Users like to make things personalized, they would like to add headshots or avatars.
Users want to have a timeline refresh to have the newest user match information on top.

## Wireframes

Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe. Do not include the actual image and have it render on the page.

- [Mobile](https://i.imgur.com/P3iBEZf.jpg)
- [Desktop](https://i.imgur.com/xpOWo0E.jpg)
  Wireframing Resources:
- [Mockflow](https://mockflow.com/app/#Wireframe)
- [Figma](https://www.figma.com/)

## Additional Libraries

Use this section to list all supporting libraries and thier role in the project.

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## Issues and Resolutions

Use this section to list of all major issues encountered and their resolution.

#### SAMPLE.....

**ERROR**: app.js:34 Uncaught SyntaxError: Unexpected identifier  
**RESOLUTION**: Missing comma after first object in sources {} object
=======
# P3-GroupLab-ProjectMain

## Models

### Student
- firstName (String) (required)
- lastName (String)
- email (String) (required)
- location (String)
- idiom (String) (required)
- language (String)
- other (String)
- online (Boolean)
- student/teacher (Boolean) (permanent)

### Teacher
- firstName (String) (required)
- lastName (String)
- email (String) (required)
- location (String)
- idiom1 (String) (required)
- idiom2 (String)
- idiom3 (String)
- language (String)
- teachingStyle (String)
- online (Boolean)
- student/teacher (Boolean) (permanent)




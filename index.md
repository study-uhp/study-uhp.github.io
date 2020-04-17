---
  title: "Study UHp"
  layout: default
  tag: 
  - Mockup Ideas
  - Final Project
  image: ![](images/studyuhp_logo_square.jpg)
---

![](images/studyup_logo_final_big.png)



#### Table of contents

* [Overview](#overview)
* [Goals of the Project](#goals-of-the-project)
* [Mockup Ideas](#mockup-ideas)
* [Miletstone 1](#milestone-1)



## Overview

Study UHp is a web application that allows students to organize face-to-face groups for studying course material. It uses various technologies such as: 

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

In order to minimize the possibility of cheating and taking advantage of the monetary incentives, grasshoppers will be required to submit proof of the help that they received (by providing screenshots or assignments). The submission will be sent to moderators to avoid cheating amongst classes. If the moderator decides that the submission was acceptable he/she will approve scoring and give the ‘sensei’ the number of rated points out of 5.



## Team Members

- [Aaron Banks](https://github.com/abanks7)
- [Jack Horton](https://github.com/JohnHortonIV)
- [Michael Gainey](https://github.com/micgainey)
- [Christian Jensen](https://github.com/christianjensenv)



### Goals of the Project

* To encourage the use of ICSpace among ICS students
* To minimize risk of inappropriate encounters by requiring that all meetings occur in ICSpace.
* To encourage face-to-face interaction among ICS students.

### Goals of Team Members

* To put the skills we learn in class to the test.
* To gain experience working in a team to develop a web application.
* To exercise creative abilities
* To practice and improve skills using Meteor, React, Semantic UI, and MongoDB.



## Mockup Ideas

These are our original mockup ideas which have been superseded by the Milestone 1 deployment.

### Landing Page

This is the first page that new or returning users see. Users can sign in or sign up.

![](images/landing-updated.PNG)

After signing in and clicking the top left icon, users will see this landing page.

![](images/landing-updated-signedin.PNG)

### User profile page

The page a user will see when they view (and can edit) their own personal profile.

![](images/user_mockup.jpg)

### Friends

We would like to implement some kind of a "friends list" using the way Discord displays friends as a starting point.

![](images/friends.PNG)



### Other pages that currently do not have mockups:

#### Find study sessions page

Users can search for current and future study sessions by class.

#### Leaderboard

Still a WIP, but our "game mechanic" will have some type of ranking system to displays top users.

#### Messages

Either a private or public message system that will allow users to asks questions and post messages regarding study sessions.



## Additional functionality ideas if time permitting

- UH CAS login
- Text messaging
- Geolocation
- Slack integration
- Rating system



## Use Cases

Need to establish a set of use cases to use as development guidelines



## Milestone 1

- [x] Deployed to Galaxy
- [x] Landing page
- [x] Mockups of at least 4 other pages
- [x] GitHub issues/GitHub project board for management
- [x] IDMP practices
- [ ] Home Page stuff:
  -  A link to the GitHub organization associated with this project and all of its repositories
  -  Up-to-date screen shots with a link to the same page running on Galaxy
  -  A link to the running deployment of your system on Galaxy
  -  A link to the M1 Project page - showing completed - no issues in the Backlog or In Progress for this milestone
  -  A link to the M2 Project page - showing the issues expected to be addressed



### We have deployed Milestone 1 to Galaxy!

#### https://study-uhp.meteorapp.com/



### Current Functionality:

#### Landing

The first page a user will see when coming to site.



#### User Sign Up

If a user does not currently have an account they can create one. We ask for some basic information about the user to get their profile started.



#### User Sign In

If the user already has an account they can proceed to sign in.



#### User Dashboard

The first page a user will see after logging in. They will also be directed here if logged in and return to the site or if they click on the logo in the navigation bar.



#### Study Sessions

The list of all currently scheduled study sessions. This is only available to logged in users. The "Join Session" functionality is not currently active, but will allow a user to join a study session if there is available space.



#### Create A Study Session

A logged in user can create a new study session. Currently only basic options are available, and in the future they will be able to specify more detail and also schedule a session for "Right Now!"



#### Edit A Study Session

A logged in user can edit a study session only if they are the "owner" of the study session. The same fields available upon creation and available to edit.



#### Calendar

Logged in users can view all of the upcoming study sessions in a calendar view. Currently clicking on a session will only provide a modal dialog with placeholder text. In the future a user will be given the option to view details about the session or join it.



#### User Profile

Currently just a placeholder mockup page. In the future logged in users will be able to see their profile which will include their class listing, bio, profile picture, and rating among other things.



#### Admin

If a user is logged in with admin permissions they will be able to navigate to a special "Admin" page that will show a listing of all upcoming sessions. Currently the "Delete" button is not functional. In the future an admin user will have various control abilities over sessions and other aspects of the site.
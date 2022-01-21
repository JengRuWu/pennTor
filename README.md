## Demo
* pennTor: https://penntor-mcit.herokuapp.com/
* Presentation: https://www.youtube.com/watch?v=ixgIjKfXGbk

## Team Members:
* Joyce Wang
* Rita Sabri
* Jeng-Ru Wu
* Rachel Lim

## Project Name 
pennTor

## Description
The process of pairing up the mentors and mentees was troublesome and required the use of google forms, emails, with a lot of human intervention. 
We aim to create a web application that streamlines this process. pennTor is a full-stack web application that allows MCIT students to sign up as mentors/mentees for the MCIT Mentorship Program. Students will fill out a short questionnaire providing information such as background, interests, preferred mentorship, etc.. Then, based on their responses, our app will run a matching algorithm (Gale–Shapley algorithm for stable marriage problem) that determines optimal mentor-mentee matches based on users' responses. Finally, an email notification will be automatically sent out to each mentor-mentee pair to connect them.  

## How we built it
* Frontend: React, CSS, JavaScript
* Backend: Node.js, Express, SendGrid API
* Database: MySQL, AWS RDS
* Deployment: Heroku

## What's next for pennTor
* Refine our criteria for optimal matching
* Improve our matching algorithm to account for unequal numbers of mentors and mentees
* Allow the users to update their information after signing up
* Make the web page responsive/mobile friendly

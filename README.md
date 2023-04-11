# hike-SGREADME




Project/Team Name: HikeSG
Level of Achievement: Project Gemini


Motivation: We have all experienced losing our way on a hiking trail despite the aid of a GPS system. Especially for the older generation, following the GPS system whilst a strenuous exercise is highly inconvenient. Having all the trail routes of Singapore in one space along with information on intensity level, distance and time taken to complete the route, would not just save us time and effort but also promotes a healthy habit of walking among the population!

Aim: We hope to make hiking in Singapore convenient and enjoyable for users through a comprehensive and concise website.


User Stories:
Basic Features:
As a person who loves to go on hiking trails for a good workout, I usually end up going through a very simple short-distance trail which doesn't fulfil my workout goals.

I love nature trails but most of the ones I go on are usually exhausting and make me want to give up midway. I would love to find shorter, easier trails in Singapore where I can take a leisure walk.

As a beginner who enjoys going on walking trails, I want to be able to go on fun and scenic routes to explore the beauty of Singapore without wasting my time on longer and more tiresome trails

Additional Features:
As someone who loves listening to music when working out/walking, I would love for my music, and location to be collated in one space which is easily accessible.

I don't want to have to spend so much time finding an apt route for trekking and then going on the net to find the needed address. I would love to have everything in one space.

Scope of Project:
A website that provides a user-friendly interface for users to access the different functions offered by HikeSG.

Edge features that are completed:
Spotify link - Allows users to open their Spotify accounts to listen to their favourite songs while hiking
Link to GPS - This allows users to follow the GPS while hiking on their chosen track

Features that have been completed (As of milestone 3):
Login Page - The first page that the user sees as the website is opened. The users will be able to enter their email ID’s and password in order to either create a new account or login to an existing one.
Beginner, intermediate and advanced buttons - The three intensity levels of hiking trails can be accessed via these buttons.
Route buttons - The different routes under the respective intensity level can be selected using the route option buttons available.
Spotify link 
Link to GPS

Features that we want to implement in the future:
Review option - In the future we would like to have a review system where users of the web app are able to give their feedbacks in terms of an open ended review or a rating system which will then be open to public for viewing. This would enhance user experience as other users will be able to gauge the different hiking route options before selecting the one of their choice.
More hiking routes - We currently have a limited number of routes on our web app. In the future we would like to expand our data base to include almost all hiking routes that exist in Singapore.
Award system - Receiving awards in terms of points after completing each route would give our users an additional sense of motivation which is also something that we would like to add on in the future.
Information on water coolers on the hiking route - Having information on water coolers and toilet locations would also factor in the decision making process of our users. We would like to take this into consideration as well in the future and update our web page accordingly.

Techstack:
Visual Studio Code
Languages used: 
HTML, CSS, JavaScript

Problems encountered when developing features:
Styling: Even upon importing CSS and JS files into the html file, the styling didn’t seem to appear. This is because the files must all be saved into the same folder
Inconsistent page layout across devices
We initially used firebase in developing the website however since firebase is just a host we found it inconvenient to create the app on it.

Bugs squashed when developing features:
Bugs
Action taken to squash bug
Creating the google maps as a hyperlink was initially difficult as the Google Maps webpage got embedded into the webpage which resulted in styling issues
Deleted the embedded code for Google Maps and replaced it with a hyperlink to the trail webpage on Google Maps 
The buttons were initially overlapping on each other
Changed the distance from ‘top’ to the button to 150 pixels and kept a distance of 150 pixels between each subsequent button too
Upon duplicating some of the pages, headers of the pages and hyperlinks to relevant files were not changed which caused some of the buttons to misdirect users to the wrong page
Changed the hyperlinks to HTML files and changed the  page headers so that users are directed to the correct webpage



Integration of technologies:
HTML provides the basic structure of sites, which is enhanced and modified by other technologies like CSS and JavaScript. CSS is used to control presentation, formatting, and layout. JavaScript is used to control the behaviour of different elements.

Enhancing User Experience:
In order to ensure the best user experience, the styling was given utmost consideration. 
Visually appealing backdrops were used which aided in making the website aesthetic and attractive. 



Acceptance Testing:
A walkthrough of the application can be viewed from this link. Edit: Please note that we have switched to a website which follows the same format.
https://docs.google.com/presentation/d/1MzCT30iFNb285EDX-u5YvY-93xjQYNVyJ5x6vQeu-j0/edit?usp=sharing 

System testing: 
We ensured that there arent any invalid redirects or dead pages on our website.  We verified the workflow of the system and also ran a compatibility test on Chrome, edge, firefox and safari. Web UI testing was done on the different pages of the website ensuring that there were no glitches or styling errors. 

User Testing:
We walked through our website features with our friends and family and noted down their responses to the different features of the website. We also received a few verbal comments regarding the website which were taken into consideration:














Conclusion

Upon evaluating the feedback received through our user testing, we understand that the intent of our application is well appreciated and solves issues that people are facing with regards to hiking in Singapore. We have successfully developed an interactive web application that provides users with hiking trails based on whether they are beginners, intermediate or  advanced athletes regardless of their age or sex. 
However, there are certain areas of improvement that have been identified such as but not limited to, improving the user interface and user experience in general. The options we had were limited and users from whom we received verbal feedback (family members and close friends) suggested that we increase the route options in order to expand the scope of our project. We also find the need to connect our website to a database before splashdown in order to store user information.

All in all, we believe that HikeSG will serve its purpose of catering to the majority of the population, increasing accessibility to hiking trails and making fitness a priority.


Technical Proof of Concept:

Explanation: when the user first opens the web application, the login page is displayed. The user can now either register as a new user or log in to a previous account. The user will then be directed to a page wherein they can choose whether they are a beginner, intermediate or advanced athlete. There will also be an option for them to choose a mystery route. Once the user chooses their level, they will be directed to a page wherein they can choose between three routes. Upon choosing route X, said user will then be able to see the distance of the trail, time of the trail, location of the trail and a link to their Spotify accounts. We will be using spotify and google maps API to execute this. 






Website Prototype:





Homepage


The introductory page of the website
User can log in using their email ID and password to begin their journey on HikeSG







Hiking routes options page

4 options to select from depending on the level of intensity: Beginner, Intermediate, Advanced and Today’s mystery route 

Clicking on each of the buttons will direct them to the different routes available










Route options page


Upon selecting the specific intensity level, the user will be directed to this page with the different routes that fall under the respective level.












Route information page

Upon selecting a particular route, the user will be directed to this page which has information on the time taken to travel the route, the distance of the route, locations option, and a link to their Spotify account option.







Google maps page (location)

Upon clicking the location option, the user will be directed to the Google maps page showing the location for their respective trail.



Project Log 



Task 
Date
Ayushi (hr)
Vidya (hr)
Remarks
1
Liftoff day 1
14/05/22
1
1
Liftoff day 1
2
Liftoff day 2 
15/05/22
1
1
Liftoff day 2 
3
Meeting with adviser 
17/05/22
0.5
0.5
Discussed the main idea of application and got approval from adviser 
4
Team meeting: initial planning  
18/05/22
1
1
Finalising project idea and front end and back end software 
5
Team meeting:
Implementation details and
initial project structure
19/05/22
2
2
Planning how to breakdown different components of the app, confirming the online courses we will take to learn the software 
6
Preparation for Mission Control 
19/05/22
2
2
Going through the material provided to us and preparing ourselves for the workshop. 
7
Mission Control 
20/05/22
2
2
React Native workshop organised by the Orbital team
8
Meeting with advisor


2
2
Meeting with adviser to discuss the front end and back end software and get further advice on what components of the app we must have built by mid-june
9
Team meeting: discussing the technical aspect of the app
21/05/22
2
2
Deciding to use firebase as the back end software and swift as the programming language for the app 
10
Team meeting: setting specific future deadlines for next 3 months
22/05/22
2
2
Creating a common calendar so that we can coordinate our schedules and set further meetings and deadlines accordingly 
11
Team meeting: milestone 1 distribution of work 
23/05/22
1
1
Dividing the 2 main segments of milestone one amongst each other 
12
Team meeting: wrapping up milestone 1 
24/05/22
2
2
Finishing the program flow, UI and explanations of the  aforementioned by compiling them in a document
13
Team meeting: deciding scope of milestone 2 
26/05/22
1
1
Deciding internal deadlines to finish online courses to prepare for app 
14
Team meeting: creating prototype of application 
01/06/22
2
2
Creating prototype of application in order to visualise what the application should look like 
15
Team meeting: researching software required 
09/06/22
2
2
Collating all resources we shall require to build the application 
16
Working on the Login Page
11/06/2 to 12/06/22
5
5
Making login page interactive using JavaScript 
17
Milestone 2 Project video 
16/06/22
4
4
Recording audio and combining it with the video recording for milestone 2
18
Milestone 2 Project Poster
19/06/22
3
3
Adding key points such as the features, goals, etc to our project poster
19
Milestone 2 Readme
25/06/22
7
7
Refining our milestone 1 readme and updating the further requirements from milestone 2
20
Milestone 2 Project log
26/06/22
2
2
Updating our project log 
21
Milestone 2 submission final edits
27/06/22
3
3
Filling in gaps and refining our video, poster and readme submissions
22
Team meeting: beginning JS , HTML and CSS course 
1/07/22
1
1
Joining courses for better understanding and implementation of knowledge 
23
Completing JS, CSS and HTML Course
1/07/22 to 11/07/22
14
14
Using coursera to learn HTML, CSS and JS
24
Team meeting: discuss course progress
4/07/22
2
2
Sharing important information and discussing different areas that were covered which can collectively be implemented into project
25
Meeting with the advisor to clarify queries regarding milestone 3
12/07/22
2
1
Clarifying doubts with regards to integrating 3 languages for web development. Recieving resources for the aforementioned.
26
Team meeting to distribute work for website development 
12/07/22
2
2
Discussing a suitable timeline and dividing coding work between ourselves 
27
Integration of HTML, CSS and JS on VSCode to design several buttons in features 2 and 3
13/07/22 - 18/07/22

(4 hours per day)
24
24
Applying our knowledge from the courses learnt in order to make the individual pages of the website
28
Linking all the web pages with one another 
19/07/22
4
4
Linking the individual pages made previously together
29
Peer evaluation for milestone 2
19/07/22
3
3
Completing our milestone 2 peer evaluations on skylab 
30
Styling all the web pages 
20/07/22
1
1
Using CSS to style the webpages 
31
Compatibility testing
20/07/22
1
1
Ensuring that there are no flaws when the webpage is opened on different browsers
32
Debugging
20/07/22
5
5
Fixing any  errors  that we  come across after conducting testing 
33
Team Meeting: Milestone 3 Distribution of work
21/07/22
2
2
Discussing a suitable timeline and splitting work amongst ourselves
34
Updated survey resent to users 
21/07/22
2
2


35
Milestone 3 Project video
22/07/22 
6
6
Doing a walk-through of the application and explaining software engineering practices employed, testing carried out, etc
36
Milestone 3 Project poster
23/07/22
5
5
Updating our poster from milestone 2 with further details 
37
Milestone 3 Readme 
24/07/22 & 25/07/22
14
14
Adding edge features, test cases etc into our readme
38
Team meeting to discuss project readme gaps
24/07/22
3
3


39
Team meeting to discuss Milestone 2 Project log
25/07/22
3
3


40
Uploading on github
25/07/22
1
1
Uploading HTML, CSS and JS code files onto github 
41
Refining project readme and making final edits
25/07/22
2
2





Note: All the work done was via zoom call 



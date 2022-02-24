A: EXPLANATION OF CHATBOT FUNCTIONALITIES

Purpose: 
The purpose of the chatbot I designed was to lessen the workload of the career advisors by giving computer science students career advice based on their preferences and strengths. It identifies five job types that require an undergraduate degree in computer science. Users can take a career quiz or scroll through a list of links to see if a particular career strikes their interest.
Processes and Features:
Career Quiz: The career quiz offers students personalized career advice based on strengths and preferences the students choose via quiz options. At the end of the quiz, a career suited for the user is displayed as a link provided with more information for the user to explore. 

Career Quiz Screenshot:

![Screenshot (69)](https://user-images.githubusercontent.com/79055002/155602688-428fcb4b-2143-4d5f-989f-8381e05561e7.png)

View All Career Options: This selection provides a link to more information on all five career options for the student to explore. After exploring the presented options, the user is presented with a button to return to the main menu.
Both processes are instituted to reduce the appointment load from students seeking career advice.

Screenshot of "View All" menu:

![all_career_choices](https://user-images.githubusercontent.com/79055002/155602488-8a98b03d-261a-4899-8321-a47569b8fdc4.png)


B: COMPUTING JOB TYPES
The following job types are displayed based on the user’s selection:
•	Software Engineer – Designs and creates programs to solve real-world problems
•	Machine Learning Engineer – Builds self-running artificial intelligence (AI) systems to automate predictive modeling
•	UX Designer – Helps design products that enhance user experience
•	UX Researcher – Studies and communicates with target users to understand their requirements for a product’s use
•	Technical Product Manager – identify customer needs, work with all departments, and measure progress needed to implement the latest technology

C: CHATBOT CODE FILES
All chatbot code files can be found in the zipped file attached with the task submission provided.
Below is a brief description of each file:
•	main.aiml - provides all the code for the initial screen and main screen
•	quiz.aiml  - provides all the code for the career quiz with included HTML links to sites providing more information on career choice options
•	viewall.aiml - provides all the code for links to descriptions of the computing job types described in section B
•	unexpectedresonse.aiml - provides all the code for redirection to the main menu if unrecognized input is provided
•	salutation.set – provides a set of acceptable greetings that will take users to the initial display menu

D: CHATBOT TRAINING CASES
I found AIML an intuitive language that can adapt to many different use cases. I used the following “training cases” to improve my chatbot’s functionality using AIML. I didn’t have large data sets, as one would normally use to train a chatbot, so I tried to think of problems a user would stumble upon with intended use and combat those. I also tried to address career questions I have heard students voice concerns over in conversation.
•	Case 1: The user accidentally types in “helo” or chooses a quirkier greeting like “howdy.”
o	I created it to handle common greetings with a set file so that the user’s command will still be understood and tested with the inputs included in the set.
•	Case 2: The user types in something that isn’t seemingly relevant.
o	I used AIML to reroute them to the main menu.
•	Case 3: A student is further along in the program and decides that coding just isn’t for them, but still wants a career in IT. 
o	This student will be routed to the technical product manager role if their strength lies in their leadership skills.
o	This student will be routed to the UX researcher role if their strength lies in their listening skills.
•	Case 4: A student likes to code but also wants to showcase their designing skills in their new role post-graduation.
o	I used AIML to route this student to the UX designer role.
•	Case 5: A student takes the quiz but isn’t satisfied with the career recommendation they received.
o	The student can return to the main menu and view all five career choices in list form with informative links.
o	I decided to add this functionality after interacting with the chatbot. I added an additional AIML file with a post-back button to link the user to the links contained in the file.

 E: INSTALLATION MANUAL
1.	Through a browser, log into pandorabots.com
2.	Go to https://home.pandorabots.com/dash/bot-directory
3.	In the search bar, type: “C951_Career_Guide”
4.	Click on the chatbot with the above name.
5.	Click on the orange conversation icon in the bottom right-hand corner.
6.	In the chatbot window, type “Hi” or “Hello.”
7.	Follow the chatbot prompts to continue.
F: CHATBOT ENVIRONMENT
I created and deployed my chatbot in the Pandorabots environment using AIML. Below I will discuss both the strengths and weaknesses of the Pandorabots environment used.




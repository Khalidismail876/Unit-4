Contents
-----
  1. [Planning](#planning)
  2. [Design](#design)
  3. [Development](#development)
  4. [Evalution](#evalution)
  
   Planning 
  ----------
  # Definition of the problem
Abokor wants to help most of the Somali teenagers who are struggling with their academics to get support. He wants a platform called AqoonMaal(knowledgeseeker)in which he could upload videos that cover most of the Somali curriculums. But he faced a problem on what kind of platform that he needs and how could he make people access it for free. On top of free access, he wants to have a platform that is organized neatly, and aesthetically appealing to the users.

He wants a platform in which when you access it, one can easily see the available course and if they need any specific lessons, they could use the search mechanic to find it. The platform needs to have some sort of system in which allows the user to not lose track of their progress and all their data to be saved. He wants to show all the available courses after a user gets access to the platform and for each course, the user needs to see the subcategories available in the course. For example, if a user is interested in science, there must be a function in which he could see the sub course such as Biology, chemistry, and physics. There must be a mechanic which allows the manager to upload and edit everything that would be visible to the users.

  
  # Client Request 
  
  ### This figure will display a direct email from the client and his motives and requirements
  ![MartialDec](clientemail.png)

**Fig.1.** Client Email 
  
  
  # Proposed Solution
To help Abokor give Somali teenagers the help they need to get better at their academics, I proposed to design a website called AqoonMaal. To make this website, I decided to use HTML, CSS, Javascript, Hash and Python for Flask to create a functional website in which users can watch videos, study and improve their skills without losing their progress data. Users can also communicate with the manager of the website via email. 

I chose to design a website due to the client’s demand for a website. All the tools that I selected to create this website are all viable for designing phase and starting with both HTML and css, they are the front end of every website page that we use a lot. JavaScript helps web developers to make web pages dynamic and interactive by implementing custom client-side scripts, and 95% of the websites use javascript for their websites (Mindfire Solutions). I decided to use Hash as I’m familiar with the encryption method that Hash uses. And Lastly, I used python due to my decision of using Flask as a framework for this website. Flask is easy to use and learn because it has less base code to implement (GeeksforGeeks).   will be added to help users know who is uploading these videos. 
  
  # Record of Tasks
  The record of task contains the five steps in the design process: Planning, Design, Developement, testing, and implementaion
  
   | __Task no__ | __Planning Action__ | __Expected Outcome__ |__Time Estimated__ |__Target Completion__ |__Criteria__ |
|-------------|---------------------|----------------------|-------------------|----------------------|-------------|
|     1       |Meeting with Client| Get an outline of the type of project that he wants. Also get a written requirements for this project and the design ideals | 1 day | May 3rd, 2020 | A|
|      2      | SKetch of the website | create a sketch that represents the design that the client wants | 2 days | May 5th, 2020| B |
|        3    | Defining the problem | Writing down the problem that the client issues to help build up the website. This could also help the developer to avoid any bad decisions about what is in the website | 4 days | May 14th, 2020 | A |
|         4   | Writing Solutions on Clients's request | I need to come up with a clear solution that will solve all his requirement. These solutions will help me develope the website that he need and also outlines all of his needs | 4 days | May 25th, 2020 | A |
|         5   | Creating Success Criteria | I need to create success criteria as in an outline for everthing that need to be in the website. These success criterias are all based on client's needs and requirements | 2 days| June 9th, 2020| A |
|       6     | Creating grids for each learning page | This will devide each learning course from others, it will also be easy for the user to see which course is which | 5 days | june 23rd, 2020 | C |
|     7       | gethering free to use picture/ coding into the website | This picture will be used to make a visual application which helps the use to identify which courses are which | 1 day | July 13th, 2020 | C |
|     8       | Designing the search button | This will help the user look for any lessons they need from any course | 6 days | July 20th, 2020 | C |
|    9        | Create hover animation for each grid to show the available course/ create a external link in each grid | This is to help the user distinguish between course and also see the general sub courses in each grid | 3 days | Aug 5th, 2020 | C |
|       10    | Create registration/login button | This will help the users create their own account in which they keep track on their progress in each course | 1 week | Aug 7th, 2020 | C |
  
  # success Criteria
  1. accounts could be created by the users
  2. securing the data - This will use Hash to encrypt all the data
  3. Autosaving mechanic - This will allow the user's data to be saved while they are login to their account
  4. clear navigation system - The website is clearly organized and the user won't have any problem navigating through it
  5. Search Button -  This button will help the user find any information in the website without taking the time to look for it
  6. Administration account -  This account will be accessible to those who manage the website and help them upload materials
  7. Feedback Form - This is a mini communication window in which the user can report issues or communicate with the manager of the website

  
More Criteria is coming
  
   Design 
  ----------
  ### The figure below shows an outline of the application

 ![MartialDec](sysdg.png)

**Fig. 2.** SYSTEM DIAGRAM 

### The figure below shows a flowchart for the autosave algorithm 

![MartialDec](autosave.png)

**Fig.3.** AUTOSAVE FLOWCHART  

  The Flowchart displays the steps that the website will take when the user opens the website. It opens a port for the user 
  and in that port, the user would be asked if they have an account or not. If they don't have an account, then they can register
  and create a new account while their data will be saved in the database with hash security. This will take the user back to the first
  page and allow them to login. Then the website will check if the new data entering is valid but checking through the database, if it 
  exists then the user will continue and start his progress. The last part of the flowchart shows how the website will keep track on the 
  progress of the user by constantly saving after every 5 seconds. 

  Development 
  ----------
  
  Evalution 
  ----------

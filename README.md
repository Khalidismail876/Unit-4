Contents
-----
  1. [Planning](#planning)
  2. [Design](#design)
  3. [Development](#development)
  4. [Evalution](#evalution)
  
   Planning 
  ----------
  # Definition of the problem
  Abokor wants to help most of the Somali teenagers who are struggling with their academics to get support. He wants a platform called AqoonMaal(knowledgeseeker)in   which he could upload videos that covers most of the Somali curriculums. But he faced a problem on what kind of platform that he needs and how could he make         people access it for free. On top of free access, he wants to have a platform that is organized neatly, and aesthetically appealing  to the users. 
  
  He wants a platform in which when you access it, one can easily see the available course and if they need any specific lessons, they could use the search mechanic   to find it. The platform need to have some sort of system in which allows the user to not lose track on their progress and all thier data to be saved. He wants to   show all the available course after a user gets access of the platform and for each course, the user need to see the sub catagories available in the course. For     example, if a user is interested in science, there must be a function in which he could see the sub course such as Biology, chemistry, and physics. There must be   a machanic in which allows the manager to upload and edit everything that would be visible to the users. 
  
  # Client Request 
  coming soon (The client need to make sure everything that he need is in his request)
  
  # Proposed Solution
  To help Abokor give Somali teenagers the helps they need to get better at their academics, we proposed to design a website called AqoonMaal. This website will be   free to access and all that the user needs is internet connection. After the user loads the page, a signup/registration page will be presented, this is to help     the user safe all their progress and if they leave or their website is some how closed, they can always come back, login and continue where they left at. When a     user signup or logsin, they will be taken to the main home page which shows the available courses. To know more about the available sub courses, the user can       hover over each course grid to see what is available but if they are using a phone then clicking on it take them to sub course page. A machanic will be created in   which allows abokor to upload and edit everything that the user will see in the website. This machanic will be only available for the manager in this case abokor,   and anyone he wants to share with. The website will be easy to use and it will be aesthetically appealing to the users as good animations are used. The website     will also have a search function, this will allow the user find any specific topic that they need without looking for it and saves them time. Finally, ABOUT page   will be added to help users know who is uploading these videos. 
  
  # Record of Tasks
  The record of task contains the five steps in the design process: Planning, Design, Developement, testing, and implementaion
  
   | __Task no__ | __Planning Action__ | __Expected Outcome__ |__Time Estimated__ |__Target Completion__ |__Criteria__ |
|-------------|---------------------|----------------------|-------------------|----------------------|-------------|
|     1       |Meeting with Client| Get an outline of the type of project that he wants. Also get a written requirements for this project and the design ideals | 30 mins | May 3rd, 2020 | A|
|      2      | SKetch of the website | create a sketch that represents the design that the client wants | 45 mins | May 5th, 2020| B |
|        3    | Defining the problem | Writing down the problem that the client issues to help build up the website. This could also help the developer to avoid any bad decisions about what is in the website | 1 hour | May 14th, 2020 | A |
|         4   | Writing Solutions on Clients's request | I need to come up with a clear solution that will solve all his requirement. These solutions will help me develope the website that he need and also outlines all of his needs | 1 hours | May 25th, 2020 | A |
|         5   | Creating Success Criteria | I need to create success criteria as in an outline for everthing that need to be in the website. These success criterias are all based on client's needs and requirements | 30 mins| June 9th, 2020| A |
|       6     | Creating grids for each learning page | This will devide each learning course from others, it will also be easy for the user to see which course is which | 1 hour and 30 mins | june 23rd, 2020 | C |
|     7       | gethering free to use picture/ coding into the website | This picture will be used to make a visual application which helps the use to identify which courses are which | 40 mins | July 13th, 2020 | C |
|     8       | Designing the search button | This will help the user look for any lessons they need from any course | 30 mins | July 20th, 2020 | C |
|    9        | Create hover animation for each grid to show the available course/ create a external link in each grid | This is to help the user distinguish between course and also see the general sub courses in each grid | 1 hour | Aug 5th, 2020 | C |
|       10    | Create registration/login button | This will help the users create their own account in which they keep track on their progress in each course | 30 mins | Aug 7th, 2020 | C |
  
  # success Criteria
  1. Registration/login function
  2. Search button
  3. six Major courses
  4. Good Aesthetics
  5. Website Management function
  6. Easy to use
  7. Free to access
  
More Criteria is coming
  
   Design 
  ----------
  ### The figure below shows an outline of the application

 ![MartialDec](sysdg.png)

**Fig. 1.** SYSTEM DIAGRAM 

### The figure below shows a flowchart for the autosave algorithm 

![MartialDec](autosave.png)

**Fig.2.** AUTOSAVE FLOWCHART  

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

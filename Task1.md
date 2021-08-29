# Task 1
## 1.1

## The problem:
*user ask for website for showing list of new movies and series*
 
## How we solved the problem and what we add:
 
1. *The client wants the website to have a main page with a slide show for the movies and series trailers that are accessible on the site, as well as three buttons that switch to the movies page or series movies page, or a logo and slide show in the header with a slide show of movie photos.* 

2. *The client wants a slide show at the top of the movies and series pages that presents the top shows on each page, and all shows to be displayed on the page four times in each line.*

3. *As hovering over a show in the movies or on the series page, the customer wants an animation that flips the picture, and when the animation happens, some of the show information, such as a rating, appears.*

4. *When you click on the show, another page should open, with the show photo on the left side of the page and information about the show on the right side of the picture, such as the release date, rating, duration, and kind of show, and so on... The client wants to include the program's trailer under the image and information, as well as a brief description of the show under the trailer video.*

5. *The client wants the social media accounts to have a logo on all pages, and when you click on it, you should be led to the social media sites, and each page should have the website's logo with links to return to the main page, movies, or series page.*

6. *The customer wants to add a cart button to the movies and series pages, and when you click on the cart logo, the list should display. To add a show to your list, click the button that appears next to the movie in the list.*

7. *The customer wishes to add a shopping cart system with the option to remove items from the cart, and after filling out the form with information such as name, email, and phone number, a thanks notice will display.*

## 1.2
## Risk:
1. *The scope of work is not well defined. The danger here is that will overlook critical details or make a mistake while defining the scope of work.*
2. *Adding non-essential features.*
3. *Take extra time to master a new programming language, piece of software, or hardware component, or have a team study it together.*
4. *Improper planning.*
5. *More funds are required.*
6. *updates and corrections at the final minute*
7. *problem in local storige*
8. *problem with server*
9. *have conflict and couldn't solve it*

## 1.3 
+ List of requirements :
*I did mention them at 1.1*

+ Database design and the wireframe:

### wireframe

![main img](/img/home_Page_1.jpeg)
![every show img](/img/every_show_page_1.jpeg)
![show page img](/img/show_info_1.jpeg)
![show img](/img/about_us_page_1.jpeg)
![cartPage](/img/cartPage_1.jpeg)

------------------------------

+ Database design:

*we have used local storage to store our data ,**array of object** in:*

+ movie name
+ movie img
+ movie link
+ add to cart
+ form data

*The data type for all of object will be converted to string so we can store them in our local storage and then we will use them to add to favorite lost.*
---------------------------------------------------------------------

+ Activity Diagram:

![Activity Diagram](/img/ActivityDiagram2.jpeg)

*The user can first start from home page and go to movies/series/about us pages and from movies/series he can go to show page and he can come back from there to the home page or to movies/series ,but in the about us page he can just go from this page to home page .*

+ Coding and implementation technique:

*we will use agile becuse Agile project management is an iterative method to software development project management that emphasizes continuous releases and client input at each iteration.Agile project management techniques help software teams speed up development, enhance communication, and improve their capacity to adapt to market changes.*

## the technique:
**Scrum** *is a methodology for addressing complex adaptive issues while producing and delivering high-value solutions in a productive and creative manner.*

### How does it work?
1. *A Product Owner creates a Product Backlog to organize the work for a complicated challenge.*
2. *During a Sprint, the team converts a portion of the work into a value increment.*
3. *The Team and its stakeholders review the findings and make necessary adjustments for the next Sprint.*
4. *Repeat*

+ 	Testing technique
### we will use balck box testing:

**Black Box Testing** *is a software testing approach that involves testing the functionality of software applications without knowing the internal code structure, implementation details, or internal pathways. Black Box Testing is a type of software testing that focuses on the input and output of software applications and is fully driven by software requirements and specifications. It's also known as Behavioral psychology.*

## How will we do BlackBox testing?
1. First, the system's needs and specifications are evaluated.
2. The tester selects legitimate inputs (a positive test scenario) to determine if the SUT successfully processes them. In addition, certain incorrect inputs are generated (negative test scenario) to ensure that the SUT can detect them.
3. Tester calculates the anticipated outcomes for each of the inputs.
4. With the specified inputs, the software tester creates test cases.
5. The test cases are carried out.
6. The actual outputs are compared to the predicted outputs by the software tester.
7. Any defects are repaired and retested.








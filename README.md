

## Project description

# Udacity | Landing Page Project

**Version 1.0.0**

This Project is about building Navigation Bar for Landing Page Dynamically using JavaScript .


---


## Table of Contents

* [Project description](#Project-description)
* [Instructions](#instructions)
* [Technologies used](#Technologies-used)
* [Dependencies](#Dependencies)
* [Author's name](#Author\'s-name)
* [Credits](#Credits)


---



## Instructions

* [(Back to top)](#table-of-contents)



The starter project had some HTML and CSS styling to display a static version of the Landing Page project. By modification that done by me, it converted this project from a static project to an interactive one. That was done by making Some modifications to HTML and CSS Styling and Creating a whole JS File to make the Project Dynamically.



---



# Technologies used

[(Back to top)](#table-of-contents)
- HTML
- CSS
- JavaScript

After The Installation you can now use the project files by UnZip the file and open it on any Code Text Editor (Atom or VS Code ... etc).


``JS Version: ES2015/ES6.``



``JS Standard: ESlint.``



#### The Project Contains three Files :

#### css /

- styles.css

####  index.html

#### js /

- app.js

####  README.md



##### Each file contains it's modifications and comment above each step of modify.

- In CSS Style there is a lot of edit of classes done and add copule of classes to the section to can make collapse.


- In HTML just add goto TOP Button to scroll at the top of the web page .


- The majority of the work was done on app.js, there is a lot of things done there:


      1. Building NavBar Using createNav() function that executed by for loop .

      2. While i run createNav() Function it's contain createSection() Funtion  because each section and nav take one variable number
      because I create section by Javascript.

      3. Adding active class in addEventListener while scroll to each section on viewport by using offSetTop for each section then get
      pageYOffset.

      3. create 2 Functions scrollToSec() & activeLink() and then run them in forEach of menuList (list of Anchor Tag).

      4. Adding Function to display none the Navbar according to user interaction with a webpage by using the setTimeOut Method.

      5. Building a to-top Button appended to the page while window.scrollY > 400 px and it's fixed of the right bottom og the webpage to
      be easy for the user to click on it to go to the top of the page.

      6. Sections collapsible are made by clicking of each section to toggle collapsed class by using collapse().

---

# Dependencies

[(Back to top)](#table-of-contents)

**(https://developer.mozilla.org/en-US/)**

---

# Author\'s name

[(Back to top)](#table-of-contents)


**© Udacity - Modified By Ayman Hassan Ismail .**

---


# Credits

[(Back to top)](#table-of-contents)


This project exists thanks to EGFWD.

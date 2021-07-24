# Santorini
![Responsive Mockup](docs/Mockups/AmIResponsive.PNG)

[You can visit the live site here](https://j0hn1975.github.io/MS2-Santorini/)

## Table of Contents
>
> 1. [Project Goals](#project-goals)
> 2. [The 5 Planes of UX](#ux)  
    2.1 [Stratergy](#stratergy)  
    2.2 [Scope](#scope)  
          - i [User Stories](#user-stories)   
          - ii  [Site Owner Goals](#site-owner-goals)    
    2.3 [Structure](#structure)  
    2.4 [Skeleton](#skeleton)  
          - i [Wireframes](#wireframes)   
    2.5 [Surface](#surface)  
          - i [Colours](#colours)  
          - ii [Typography](#typography)  
> 3. [Features](#features)
> 4. [Technolgies Used](#technolgies-used)
> 5. [Testing](#testing)  
>   5.1 [Code Validation](#code-validation)
> 6. [Bugs](#bugs)
> 7. [Deployment](#deployment)
> 8. [Credits](#credits)

## Overview
> A website bassed on the real life Greek Island of Santorini. This site is designed to showcase the natural beauty of the isalnd and it's beautiful sunsets.

## Stratergy


## Project Goals
---
The primary business goals of this site are:
> * To promote the island of Santorini
> * Increase the number of vistors to the island
> * Provide inspiration for Santorini as a holiday destination

The primary cusomter goals of this site are:
> * Learn more about the island before visting
> * Contact the site owner with any additional questions or queries
> * Be inspired to choose Santorini as a viable holiday destination

## UX

## Target Audience
> * 

## Scope
## User Stories
As a new or returning visitor I would like to see:
> 1.  A site that is easy and clear to navigate
> 2.  A map of where Santorini is located
> 3.  The current weather conditions in Santorini
> 4.  External social media links to find out more about the island
> 5.  An informative quiz where I can test my knowledge on Santorini
> 6.  Feedback on which answers I have got right
> 7.  A final page that displays how well did on the quiz
> 8.  An option to close out of the final page or play quiz again
> 9.  A contact page to get in touch with the site owner
> 10. A site that responds and provides feedback on my interactions
> 11. A site that I can interact with
> 12. As a user I would like to see a responsive site that can be used on mobile devices
> 13. An error page to show if I have enterted an incorrect URL

## Site owner goals
The main goal of this site is to present useful information about Santorini on a website that is easy to navigate
> 14. Display a contact form so the user can get in touch with the site owner
> 15. Present the end user with a clear and simple navigaion menu
> 16. Display the current weather in Santorini
> 17. Provide a quiz where the user can test their knowledge
> 18. Make a site that is responsive across all devices.
> 19. A site that provides feedback and validation.
> 20. On the 404 page the user shouldn't use the broswer back but instead the nav bar.
> 21. Display a map of Santorini
---

## Structure
The website has been structured with 4 web pages. Each page is cleary designed, easy to navigate, and with well layed out information. With a mobile first approach in mind I have used bootstrap throughout to make the site respoinsive on mobile devices.

> The 4 pages are:
> 1. Home Page: A welcome message, brief description of the island greet the user, as well as a map of where the island is located and the current weather forecast
> 2. Quiz Page: A 10 question quiz on Santorini, with progess indicators for each question, right and wrong answers are higlighted, with a table at the end showing overall progress
> 3. Contact Page: A contact page to allow the user to contact the site owner, warnings if the incorrect information has been entered and alert then the form is submitted.
> 4. 404: This alerts users if they have entered an incorrect URL for the site. The user is presented with warning message, navbar and footer.
---

## Skeleton
To design and develop the wireframes I first used Balsamiq, then used Snipping Tools to create PNG versions. The wireframes images are designed to collaspe.

## Wireframes
> <details><summary>Home Page</summary>
> <img src="https://github.com/J0hn1975/MS2-Santorini/blob/main/docs/Wireframes/Home/Home.PNG">
></details>
>
> <details><summary>Quiz Page</summary>
> <img src="https://github.com/J0hn1975/MS2-Santorini/blob/main/docs/Wireframes/Quiz/Quiz.PNG">
> </details>
> 
> <details><summary>Contact Page</summary>
> <img src="https://github.com/J0hn1975/MS2-Santorini/blob/main/docs/Wireframes/Contact/Contact.PNG">
> </details>
---

## Surface
## Colours
Each page is design with very simple colours and images to showcase the island. The colours I have used are as follows:
> - #FFCC51 - used as a background color for the footer and navbar
> - #050505 - used for the site brand and nav links
> - #009688 - used to style the quiz text.

## Typography
For the most part of I have used the Titilium Web Google font, with a fallback of Sans Serif should Titilium Web not work.

## Design
> The site is made up of three pages, using a simple and clean design. 
> 


# Features
## Existing Features
### Feature 1: The Nav Bar
A boostrap and fully responsive nav bar, that has links to Home, Quiz and Contact pages. As part of it bootstrap functionality the nav bar displays as a burger menu on mobile devices. 
> ![Navbar](docs/Features/navbar.PNG)
> ![MobileNav](docs/Features/navbar_mobile.PNG)  
> User stories feature relates to:
> * 1.1 A site that is easy and clear to navigate
> * 1.12 As a user I would like to see a responsive site that can be used on mobile devices
> * 1.15 Present the end user with a clear and simple navigaion menu

### Feature 2: Weather Widget API
Weather Widget display the current weather for Santorini on the Home Page. When the widget is clicked it takes you to the Forcast7.com website for a more detailed forecast.
> ![Weather Widget](docs/Features/weatherwidget.PNG)
> 24hr Forecast  
> ![Weather Widget 24hr](docs/Features/weather24.PNG)  
> 7 Day Forecast  
> ![Weather Widget 7Day](docs/Features/weather7days.PNG)  
> User stories feature realtes to:  
> * 2.3 The current weather conditions in Santorini
> * 2.13 Display the current weather in Santorini

### Feature 3: Google Maps API
Google maps API to that shows the exact location of Sanitorini.
> ![Google Maps API](docs/Features/map.PNG)  
> User stories feature relates to:
> * 3.2 A map of where Santorini is located
> * 3.18 Display a map of Santorini

### Feature 4: Footer
Footer that displays the site name and two social links; one to youtube and one to Tripadvisor
> ![Footer](docs/Features/footer.PNG)  
> User stories feature relates to:
> * 4.4 External social media links to find out more about the island

### Feature 5: Home Page
Home page that displays a welcome message and short description of the island. A nav bar, footer, google map and weather forecast are displayed to
> ![Home Page](docs/Features/homepage.PNG)  
> USer stories this feature relates to:
> * 5.1 A site that is easy and clear to navigate
> * 5.3 The current weather conditions in Santorini

### Feature 6: Quiz Page
A quiz to that the knowledge of the end user, that responds to and validates user input
> ![Quiz Page](docs/Features/quizpage.PNG)   
> ![Quiz Started](docs/Features/quiz.PNG)  
The quiz displays the right and or wrong answer  
> ![RightWrongAnswer](docs/Features/right_wrong_answer.PNG)  
At the end of the quiz an table displays overall progress with buttons to leave table or start quiz again  
> ![Quiz Results](docs/Features/quiz_result.PNG)  
> User stories the features relates to:  
> * 6.5 An informative quiz where I can test my knowledge on Santorini
> * 6.6 Feedback on which answers I have got right
> * 6.7 A final page that displays how well did on the quiz
> * 6.17 Provide a quiz where the user can test their knowledge
> * 6.19 A site that provides feedback and validation.

### Feature 7: Contact Page
A contact page to allow user to contact site owner.
> ![Contact](docs/Features/contactpage.PNG)
> * 7.9 A contact page to get in touch with the site owner
> * 7.14 Display a contact form so the user can get in touch with the site owner
---



## Technolgies Used
> * HTML5
> * CSS3
> * Javascript
> * Google Maps Api
> * Weather Widget
> * Balsamiq

## Testing

## Code Validation
> ### CSS Validation
> I have used the W3C CSS Validation Service - Jigsaw to check that my CSS is valid
>
> CSS validation passed with 0 error
>
> [CSS Validation Results](/docs/CSS-Validation/CSS_Validation.PNG)
---

### HTML Validation
I have used the W3C Markup Validation Service to check my HTML is valid

|   Page       |  Result              |                      Screenshot                      |
|:------------:|:--------------------:|:----------------------------------------------------:|
|   Home       | 0 errors             | [View Results](docs/HTML-Validation/Home_Page.PNG)   |
|   Quiz       | 0 errors             | [View Results](docs/HTML-Validation/Quiz_Page.PNG)   |
|  Contact     | 0 errors             | [View Results](docs/HTML-Validation/Contact_Page.PNG)|
---

### Javascript Validation
I have used JS Hint to validate my Javascript.

|     Page     |        Result        |                         Screenshot                          |
|:------------:|:--------------------:|:-----------------------------------------------------------:|
|    form.js   | 0 errors, 0 warnings | [View Results](docs/Javascript-Validation/form.js.PNG)      |
|    map.js    | 0 errors, 0 warnings | [View Results](docs/Javascript-Validation/map.js.PNG)       |
|  question.js | 0 errors, 0 warnings | [View Results](docs/Javascript-Validation/question.js.PNG)  |
|    quiz.js   | 0 errors, 0 warnings | [View Results](docs/Javascript-Validation/quiz.js.PNG)      |
| sendemail.js | 0 errors, 0 warnings | [View Results](docs/Javascript-Validation/SendEmail.js.PNG) |
---

### WAVE Accessibilty
I have used the WAVE Web Accessibilty Evaluation Tool to ensure site is accessible

|   Page  |            Result           | Screenshot |
|:-------:|:---------------------------:|:----------:                                                                 
|   Home  | 0 errors, 0 contrast errors | [View results](/docs/WAVE-Accessibilty/index.html_Wave_Validation.PNG)      |
|   Quiz  | 0 errors, 0 contrast errors | [View results](/docs/WAVE-Accessibilty/quiz.html_Wave_Validation.PNG)       |
| Contact | 0 errors, 0 contrast errors | [View results](assets/docs/WAVE-Accessibilty/quiz.html_Wave_Validation.PNG) |
---







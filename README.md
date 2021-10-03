# Overview
The intent of this project is to provide a quasi prioritized to-do list for an emigrant who just arrived in the US.
A new emigrant is likely a bit overwhelmed with everything that they need to do, should do, and could do. 
With a seemingly endless to-do list and so many complex resources available, 
the primary goal of this app is to provide an "aha moment" starting point with links to valuable and appropriate resources.

A users experience starts with a welcome page where they will set a zip code, 
their preferred language, see a welcome message, and an emigration related news feed. From here, 
they can drill down on the prioritized list of to-dos like "get an I-94#" and "Get a Work Permit". 
Each to-so will take them to a page that has brief description, a list of relevant resources, 
and if appropriate a Google Map of relevant locations".

An Admin will be able to login to add more admins, edit the content on each page, and add new a new to-do.

# Features
- User login: a user can track milestones while navigating the emigration process.
- Admin Login: Admins will be able to manage Logins, edit site content/UI, and add a new "Want To", "FAQ", and "links".

- RSS Feed: The landing page will have a news feed with relevant updates pertaining to emigration.
- Add: Admins will have the ability to add and edit a "To-do", FAQ, and Link .
- CMS Edit: Admins will have the ability to edit text on the Home Page, To-Do, FAQ, and About Us pages.
- Google Maps API: If appropriate, a "To-do" page will include a Google Map
- Google Language API: On the landing page, a user will be able to set the language for the site.


# Technologies
- Java
- Javascript
- Spring Boot Web
- Spring Data JPA & Hibernate (data access layer)
- Spring Security (authentication)
- Spring Mail (sending emails to users)
- Thymeleaf (template engine)
- Bootstrap 
- MySQL database

# What the Team Will Have to Learn
- [ ] How to deploy to Heroku
- [ ] Google Maps API (Google Maps based on a search term, and proximity from a zip code
- [ ] Google API (language options)
- [ ] RSS Feed Source unknown API
- [x] Implement email validation (Spring Mail)
- [x] How to manage logins/Roles to determine varying site access. (Spring Security)
- [x] A greater understandingThymeleaf to create a true CMS.

# Project Tracker
https://trello.com/b/ZuQts9x0/launchcode-liftoff-project

# Hosting
https://www.citizenshipplanner.com
registrar enom.com
hosting Heroku
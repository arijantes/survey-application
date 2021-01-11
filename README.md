Requirements
This survey will consist of a single-page form that records a user's answers to survey questions when they hit enter. The questions are up to you, but it must have a required field for user email, and only one response per email address is allowed.

Answers will be stored on the filesystem in data format such as JSON or CSV, so that a site visitor with the admin password can review them and see reports of the results.

It's up to you to design this application however you like in code, but it needs to have the following pages:

Home Page: 
The home page should be a survey form that users see when they navigate to the site. This page should also show any errors from a previously invalid form submission – Note that errors should only be shown to users who submitted them!
Once a user has successfully submitted a survey, the homepage should thereafter always show a thank you message. The app should set a cookie to remember this.
If a survey is submitted with an email that has already been used, the app should not accept it and show a special error message. 

Survey Report - Admin access only:
There will be a special page on the site that is password-protected and that only admins can access. This shows the survey results in a readable form. How to present it is up to you.

Access to the survey report page should be protected using HTTP Basic Authentication. Only users who enter a given password/user combination should be able to view the page.

Tests: 
All of your code for this project should be tested. We'll write two kinds of tests:

Unit Tests - Every file in your program should have a set of unit tests that cover its behavior. 
Integration Test - You should have one set of integration tests that covers end-to-end functionality of your application.
You will run all of these tests and produce a test execution report. 

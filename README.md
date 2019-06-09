![](https://i.imgur.com/KDmXey6.png)

<h1>README</h1>

<h1>Team Acronym</h1>
<p>Owen Shen - Project Manager</br>
Roshan Fernando - Software Development Lead</br>
Cyrus Cowley - Software Development Lead</br>
Zhuoran Liao - Algorithm Specialist</br>
Zebang Liu - Senior System Analyst</br>
Summet Bansal - Software Architect</br>
Cameron Trando - Software Architect</br>
Daniel Wang - Database Specialist</br>
David Hacker - Quality Assurance Lead</br>
Steven Miller - User Interface Specialist</br>
Surya Krishnan - Business Analyst</p>

<p style="page-break-after: always;">&nbsp;</p>

## Introduction

InternHub is a web application that automatically aggregates information about companies and the internships they offer, so that students can have an easier time finding the internships of their dreams. What makes InternHub different, though, is that our internship listings are maintained automatically, rather than by humans. InternHub works by scraping the Internet for companies and the internships on their websites. InternHub also maintains an internal database of companies and positions for internships, which the scraper consistently updates.


## Login Credentials

The details of the InternHub test account are listed here:

| Account Field | Value |
|:----:|:----:|
| Username | finaltester |
| Password | interns2019 |
| Email | internhub.tester@protonmail.com |

Additionally, for testing purposes, we provide the credentials of the above Protonmail email account:

| Email Field | Value |
|:----:|:----:|
| Email | internhub.tester@protonmail.com |
| Password | interns2019 |

## Requirements

* Please use a version of either Google Chrome or Firefox that came out after 2012 to access the website.
* If you wish to contribute, install the `npm` and `yarn` tools.

## How to Run

Visit https://intern-hub.github.io/frontend/ on one of the two supported web browsers.

<p style="page-break-after: always;">&nbsp;</p>

## Contributing

Clone the repo, then go into the cloned directory and run 

```yarn install``` 

```yarn run start```

Have fun developing at ```localhost:3000```!

## Known Bugs

* The scraper can return irrelevant information about location while scraping. This occurs because while most companies follow similar protocols on how they list internships, some companies use slightly different protocols.
* The scraper can return "Internship" as the position title. This is due to the position title formatting differing for certain sites.
* Sometimes, companies can display "No internships found!" temporarily before re-rendering and displaying internships. This is because React needs to wait to fetch data from the backend, and we did not add a loading icon to indicate that it is doing such.
* The dropdown menu for logged-in users in the top navigation bar may need to be clicked two or three times before the click actually registers. This is due to the placement of excessive divs on top of the anchor elements we are using, resulting in the anchors being partially obscurred by the divs.
* Entering more than 65000 characters into the application notes field may cause the server to give a 500 error, since it will be unable to store that amount of characters in the database. If this happens, the notes may silently not be saved.

## Technical Support

Please contact David Hacker, either at dmhacker@ucsd.edu or at (805) 368-5071.



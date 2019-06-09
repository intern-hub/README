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

For testing purposes, we have created a ProtonMail email account and provided the credentials below. The password will change as part of the testing process.

username: finaltester

password: interns2019

email: internhub.tester@protonmail.com

email password: interns2019

## Requirements

* Google Chrome is installed and functional.

## How to Run

Visit https://intern-hub.github.io/frontend/ on Google Chrome.

<p style="page-break-after: always;">&nbsp;</p>

## Known Bugs

* The scraper can return irrelevant information about location while scraping. This occurs because while most companies follow similar protocols on how they list internships, some companies use slightly different protocols.
* The scraper can return "Internship" as the position title. This is due to the position title formatting differing for certain sites.
* Sometimes, companies can display "No internships found!" temporarily before re-rendering and displaying internships. This is a result of how React renders components and how componentDidMount() works.



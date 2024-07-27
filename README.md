# __Career-Application-Form-PHP__

## Table of contents
* [INTRODUCTION](#introduction)
* [PROBLEM](#problem)
* [GETTING STARTED](#getting-started)
* [STATUS](#status)
* [OUTPUT](#output)
## __INTRODUCTION__

This project targets career application forms, with database and and report generation.

This project coinsides with Admin Pages, built to mannage the data and generate report.
\
\
Right now mostly the focus is on design and security.
\
\
Have used vanila PHP as much as possible so that it is easy to implement and deploy for anyone new to PHP.
\
\
This project will also focus on report generation on the side of Admin, also having some basic controls to manage users, their issues and getting final report of applied candidate.
<br>

### __Extra Features__
1. Getting an excel sheet having all related information of candidate.
1. Producing CV style pdf that Admin can then check and print for record keeping.
1. Status of people completed and uncompleted forms.
1.  Sendig email to people who have not completed the form but have started filling.
<br>

## __PROBLEM__

__From experience of filling forms, have encountered the many issues like data getting lost if connection is lost and while uploading images the size is specified which is very hard to manage for normal people, and even if you manege to upload proper image the image comes streshed or squezed.__

To sum up most of the applilcation form have unstisfactory experience and data is not handled properly.

<br>

## __GETTING STARTED__

Can use any server of PHP

    ALL SETTINGS REQUIRED TO CHANGE IS IN "include/config.php"

Thigs required to change:
```PHP
    $dbhost="localhost"; //hostname
    $dbuser="<your-database-username>";  //mysql acc/ username
    $dbpass="<your-databse-password>";  //mysql scc/ password
    $dbname="<your-database-name>"; //mysql database name
    $adminemail="<your-admin-mail>";
```
<br>

## __STATUS__
Have just started this project will continue to develop on it.

## __OUTPUT__

<img src="./screenshots/Web 1920 – 1.png">
<img src="./screenshots/Web 1920 – 2.png">
<img src="./screenshots/Web 1920 – 3.png">
<img src="./screenshots/Web 1920 – 4.png">
<img src="./screenshots/Web 1920 – 5.png">
<img src="./screenshots/Web 1920 – 6.png">
<img src="./screenshots/Web 1920 – 7.png">
<img src="./screenshots/Web 1920 – 8.png">
<img src="./screenshots/Web 1920 – 9.png">
<img src="./screenshots/Web 1920 – 10.png">
<img src="./screenshots/Web 1920 – 11.png">
<img src="./screenshots/Web 1920 – 12.png">
<img src="./screenshots/Web 1920 – 13.png">
<img src="./screenshots/Web 1920 – 14.png">
<img src="./screenshots/Web 1920 – 15.png">
<img src="./screenshots/Web 1920 – 16.png">
<img src="./screenshots/Web 1920 – 17.png">
<img src="./screenshots/Web 1920 – 18.png">
<img src="./screenshots/Web 1920 – 19.png">
<img src="./screenshots/Web 1920 – 20.png">
<img src="./screenshots/Web 1920 – 21.png">
<img src="./screenshots/Web 1920 – 22.png">
<img src="./screenshots/Web 1920 – 23.png">
<img src="./screenshots/Web 1920 – 24.png">
<img src="./screenshots/Web 1920 – 25.png">
<img src="./screenshots/Web 1920 – 26.png">
<img src="./screenshots/Web 1920 – 27.png"
STU625cf1a18318f1650258337



## __CONTRIBUTE__

Checkout [Contribution Guide](CONTRIBUTING.md) for local setup and contribution guide.

Check the design planning of the project at [Design Planning](/design/planning/DESIGN_PLANNING.md).

For Data Plalning check at [Data Planning](/design/planning/DATA_PLANNING.md).

## __LIBRABRY USED__

- [html2Canvas](https://github.com/niklasvh/html2canvas) - Turns DOM into Canvas.
- [jsPDF](https://github.com/MrRio/jsPDF) - To generate PDF from images.
- [cypress](https://github.com/cypress-io/cypress) - Testing Library
---



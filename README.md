# __Career-Application-Form-PHP__

## Table of contents
* [INTRODUCTION](#introduction)
* [PROBLEM](#problem)
* [GETTING STARTED](#getting-started)
* [STATUS](*status)
* [OUTPUT](*output)
## __INTRODUCTION__
---
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
---
__From experience of filling forms, have encountered the many issues like data getting lost if connection is lost and while uploading images the size is specified which is very hard to manage for normal people, and even if you manege to upload proper image the image comes streshed or squezed.__

To sum up most of the applilcation form have unstisfactory experience and data is not handled properly.

<br>

## __GETTING STARTED__
---

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
---
Have just started this project will continue to develop on it.

## __OUTPUT__

---
## __CONTRIBUTE__
---

Checkout [Contribution Guide](CONTRIBUTING.md) for local setup and contribution guide.
## __LIBRABRY USED__
---
- [html2Canvas](https://github.com/niklasvh/html2canvas) - Turns DOM into Canvas.
- [jsPDF](https://github.com/MrRio/jsPDF) - To generate PDF from images.
- [cypress](https://github.com/cypress-io/cypress) - Testing Library
---

[<img alt="Buy me a Coffee Button" width=200 src="https://c5.patreon.com/external/logo/become_a_patron_button.png">](https://www.patreon.com/) &nbsp; [<img alt="Buy me a Coffee Button" width=200 src="https://cdn.buymeacoffee.com/buttons/default-yellow.png">](https://www.buymeacoffee.com/)

Bye!
Have fun

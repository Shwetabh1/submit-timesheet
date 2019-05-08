<h1 align="center"> Automate Timesheet Submission </h1>

<div align="center">
    <img src="https://github.com/Shwetabh1/submit-timesheet/blob/master/time-isnt-the-main-thing-1000x486.png" alt="Essential JavaScript" width="400" height="200"/>
  <br>
</div>


## What is this?
This project aims to automate time sheet submission in SAP FIORI.

## Table of Contents
1. Features
1. Technologies Used
1. Future Enhancements

## Introduction
1. Users simply need to run a shell script `fill-timesheet.sh`
1. The script can be used for 1 time filling or for scheduling (with the help of `--schedule`)to fill your timesheet before weekend & monthend.
1. users can cancel the scheduling using `stop` or `hardstop` options.
1. Users will also be notified through SMS.

## Technologies Used
1. Node.js
1. puppeteer
1. Amazon SNS
1. Shellscripts

## Future Enhancements
Given the short time frame this has a lot of scope for improvement. Listing down a few
1. Access to Employee DB to Find employee Assigned Projects access.
1. Integration with Outlook Calendar to find Planned Leaves or Meeting Invites.
1. Integration with JIRA for Logged hours.
1. Integration with Confluence for Leave Calender.

## Crew Members
1. Shwetabh Shekhar
1. Veda Prakash
1. Poornesh Ramalingam
1. Lakkappa Kalli


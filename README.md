# TBD, LLC

## Table of Contents
- [Concept](https://github.com/tbd-llc/planning#concept)
- [Communication](https://github.com/tbd-llc/planning#communication)
- [Resources](https://github.com/tbd-llc/planning#resources)

## Concept
**Working Title:** "Patsi" (Personal Application Tracking System Interface)

**Concept:** Job searching for any role is a royal pain in the a$$. There's a lot of balls to juggle between reading posts online, reading emails about posts online, applying, tailoring your application (resume / cover letter) to the role, follow up about the position, etc. and frankly it's bullsh!t that companies have all of these different ATS systems to manage a job search when job seekers only have their two hands and an email client.

Enter Patsi! Patsi aggregates your job search into a single tool that is managed either from your inbox or a web app. Her features include:

- Aggregating all of the jobs you receive in your job search emails (LinkedIn, DICE, Indeed, VentureFizz, etc.) into a single, easily filterable database (one job description, one record row)
- Read the parsed job description without ever having to leave your email and with a click of a button
- Generate a templated resume based off prior bullets you've used for other applications
- Generate a templated cover letter based off prior sentences / paragraphs you've used for other applications
- Navigate directly to the appropriate site to apply with your templated (and slightly tweaked) materials
- Track every application and be prompted to automatically follow up weekly, whether that's via LinkedIn or through direct email to the job poster
- Track each interaction with the employer (up to and including offer stage)
- Compare your job search metrics against others within your industry to see how well your job search strategy is performing against the average

...and so much more!

## User Stories
- [ ] As a User I want to click a button in my Gmail so that I can see a dashboard of the present status of my job search.
- [ ] As a User I want to see a "spreadsheet" and / or "Kanban board" of my job search in my dashboard so I can better visualize the present status of my job search.
- [ ] As a User I want to be able to compare my search metrics against other Users who share my [NAICS code](https://www.census.gov/naics/) so I can benchmark my job search strategy against other Users.
- [ ] As a User I want to be able to isolate my job hunt emails - by tag - so that only those emails can be read by the program.
- [ ] As a User I want to be able to read all of the parsed Job Descriptions within the program's Gmail interface so I don't have to click several links to get to the information that I want to read.
- [ ] As a User I want to be able to skim all of the parsed Job Description's basic data (i.e. software, year's of experience, requirements, necessary skills, etc.) in my Dashboard view so I can get a bird's eye view of whether the job is worth investigating.
- [ ] As a User I want to be able to filter out job descriptions that do not match my skills by a certain percentage so I only see those job descriptions that I deem relevant in my dashboard.
- [ ] As a User I want to be able to add companies to my dashboard so that I am alerted when a new job is posted for that organization that I might be a fit for.
- [ ] As a User I want to be able to receive alerts when a job description at a company I've prioritized / starred has posted a job I'm qualified for so I can apply quickly to the position.
- [ ] As a User I want to be able to receive alerts when a job description has been parsed that is above a percentage relevancy that I set so I can apply quickly to the position.
- [ ] As a User I want to be able to enter my present qualifications, skills, and next role / title for the program to use in excerpting / parsing job descriptions links from various job hunt emails I receive. 
- [ ] As a User I want to be able to enter various iterations of my resume bullet points to the program so that I can generate a more accurate resume template requiring less tweaking before I actually apply to the job.
- [ ] As a User I want to be able to enter various iterations of my cover letter paragraphs to the program so that I can generate a more accurate cover letter template requiring less tweaking before I actually apply to the job.
- [ ] As a User I want to be able to create associations between the resume bullet points I enter into the program and the jobs I held where I performed that bullet so I can be sure when the template is created the bullet is appropriately assigned to the right position.
- [ ] As a User I want to be able to enter a company that I worked for, the dates that I worked there, and the position I held so that the program can prepopulate that information in the resume template.
- [ ] As a User I want to be able to upload a letterhead format that will be used when creating a template resume so I do not have to copy and paste the generated text into the letterhead.
- [ ] As a User I want to be able to upload a letterhead format that will be used when creating a template cover letter so I do not have to copy and paste the generated text into the letterhead.
- [ ] As a User I want the program to automatically ignore [common unhelpful](https://en.wikipedia.org/wiki/Most_common_words_in_English) words so that the returned results are more accurate.

## Communication
Communication with the larger team will primarily occur either via email or [Slack](https://join.slack.com/t/slack-zpl9544/shared_invite/zt-1xjuujyvk-Kas4hWXpiPX89BYQr5pAsA).

### Time Zone Considerations
Given everyone's respective time zones, the following two-hour block works best for scheduling purposes:

PST (08:00a - 10:00a): Ryan
EST (11:00a - 01:00p): Greg, Scott
BST (04:00p - 06:00p): Jacob, Chris

## Resources
### Similar Software (My Original Inspiration)
- [Streak](https://www.streak.com/)

### Google Workspace / Gmail
- [Google Workspace Add-ons](https://developers.google.com/workspace/add-ons)
- [Extend Google Workspace with add-ons](https://developers.google.com/apps-script/add-ons/overview)
- [Build A Google Workspace Add-On in any coding language](https://developers.google.com/workspace/add-ons/guides/alternate-runtimes)
- [Gmail API Reference](https://developers.google.com/gmail/api/reference/rest)
- [Google Docs API Reference](https://developers.google.com/docs/api/reference/rest)
- [Google Calendar API Reference](https://developers.google.com/calendar/api/v3/reference)

### Standardizing Data
- [NAICS Code Reference](https://www.census.gov/naics/)
- [Most common words in English](https://en.wikipedia.org/wiki/Most_common_words_in_English)
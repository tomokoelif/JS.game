# JavaScript Group Hackathon Project <a id="top"/>

## Introduction

Live site: [Enter Link Here]

## Table of Contents
- [User Experience Design](#user-experience-design)
- [Project Brief](#project-brief)
- [Users](#users)
    - [User Stories](#user-stories)
    - [Wireframes](#wireframes)
- [Design](#design)
    - [Colour Scheme](#colour-scheme)
    - [Typography](#typography)
    - [Imagery](#imagery)
- [Website Features](#website-features)
    - [Footer](#footer)
- [Responsive Design](#responsive-design)
- [Future Features](#future-features)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [Testing](#testing)
- [Credits](#credits)

[Back to top](#top)

## User Experience Design

### Project Brief
The project goal is to provide a tool for users that wish to be UK citizens, which involves taking a quiz about Life in the UK as part of their assessment to get citizenship.

The site user's goals are to provide a short quiz about Life in the UK, with different categories available for the user to test their knowledge and practice for the formal test.
Allowing the user to have feedback throughout the quiz about their answers and also in the end to let them know their score.
Also providing a quick and efficient way for the user to test their knowledge on the go or during a short break.

### Users

- Persona 1: "Sophie – The Student"<br>
Sophie Li, 24 years old, international university student that recently finished her degree in the UK. Needs to pass the Life in the UK test to be able to stay and work in the UK.<br>
Looking to find an engaging and interactive way to study for the citizenship test whilst balancing study with her academic workload, in an effective way, which can be hard to do and also trying to avoid burnout.<br>
Likes to a modern, interactive tool that make learning fun. Very comfortable using new technologies, using mostly her mobile and the laptop to study.<br>
Would like a mobile-friendly design that can be used on the go, that feels less like a shore and more like a fun moment.<br>
Wishes to do the quiz and practice for the test between classes and her study breaks.

- Persona 2: "Ali – The Busy Professional"<br>
Ali Ahmed, 40 years, IT Manager, has been living in the UK for 5 years and needs to pass the Life in the UK test to apply for British citizenship.<br>
Aims to efficiently prepare for the test alongside a busy work     schedule.<br>
Wants to find resources that look straightforward and time-efficient, so that he can practice for the test.<br>
Has no problems using different technologies to study and prefers to do this on his tablet during his commute or at home on the desktop.<br>
Finds it difficult to find a high-quality, time-efficient study tool that can be adapted to his work schedule and family time, whilst keeping him motivated.<br>
Wants to use a clean, professional interface with minimal distractions, that can be time-efficient and completed quickly, also providing a summarized feedback and analysis of the performance during the quiz.

- Persona 3: "Emma – The New Immigrant"<br>
Emma Johnson, 32 years old, Healthcare Assistant, recently moved to the UK from Australia. Is settling in and needs to pass the Life in the UK test to get her indefinite leave to remain.<br>
Comfortable using new technologies to study and prefers to use the smartphone or laptop to search and study, mostly during her breaks at work and in the evenings.<br>
Hopes to find reliable resources to study for the Life in the UK test, like quizzes that she can use to practice for the actual exam. Wants a user-friendly layout with clear and concise information for each answer.<br>
And, if possible, track her progress and identify areas where she needs to study more.<br>
She's looking for an app that can show diverse, engaging and reliable information.<br>
Also needs to get feedback about her choices for each question, if right/wrong, allowing her to do further research when the answer is wrong.<br>
Wishes to be able to test her knowledge in different areas/subjects of the Life in the UK.

### User Stories
User Stories and the associated Acceptance Criteria and Tasks were generated using Microsoft Copilot. 

The aim is to produce a minimum viable product (MVP) in the 2.5 days given. The AI-generated user stories were reviewed and edited to be SMART and focused for the delivery of an MVP. A Project Board was set up in GitHub Projects to track project progress. The user stories were prioritised using MoSoCoW based of benefits to users and viability.

Here are the user stories that have been prioritised as "must have":

### Wireframes

- Mobile view:
  <img src="">
  
- Tablet view:
  <img src="">
  
- Desktop/Laptop view:
  <img src="">

[Back to top](#top)

## Design

### Colour Scheme
The aim of the project is to provide a calm environment that would be suited to both teenage users and their parents. I took inspiration from the colours from my garden and used ColorSpace to derive a calm and subtle palette.

<div style="display: flex; gap: 10px;">
  <div style="width: 50px; height: 50px; background-color: #00247D;"></div>
  <div style="width: 50px; height: 50px; background-color: #710005;"></div>
  <div style="width: 50px; height: 50px; background-color: #206537;"></div>
  <div style="width: 50px; height: 50px; background-color: #0005FF;"></div>
  <div style="width: 50px; height: 50px; background-color: #FFD700;"></div>
</div>


After the initial Lighthouse audit, I checked some of the colour combinations on [WCAG Contrast Checker](https://webaim.org/resources/contrastchecker/), and they were adjusted for better contrast and readability:

![Contrast](https://github.com/user-attachments/assets/3cdb157d-19e3-470d-9462-34c21215ec3a)


### Typography
[Google Fonts](https://fonts.google.com/) have been used as these are convenient to embed into the CSS file as an @import. 

Because both teenagers and their parents are in the userbase, a more distinct and handwritten font ([Gloria Hallelujah](https://fonts.google.com/specimen/Gloria+Hallelujah)) was chosen as the primary font, which helps to keep the reader at ease and imply that this is a site about young adults without it looking too childlike. In addition, a calmer and more open typeface ([Open Sans](https://fonts.google.com/specimen/Open+Sans)) was chosen to complement it to convey credibility and warmth while being a sans-serif font makes it quicker and easier to read.

![Font](https://github.com/user-attachments/assets/5702b1b8-7a3f-425a-a2aa-6d7fd6a3fd6a)


### Imagery
Initially I experimented with using MS Copilot to generate most of the images. The results were not very reliable and the process of refining prompts was taking too long, so I went to Pexels and found all of the photos from their photo library. The search function did not work well to bring back too many results, but there are additional tags in the search results page which open up the search and direct you to more photos. I found a range of photos showing a diverse range of ages, race and background with teenagers. Most of these were reduced in filesize and optimised on Squoosh and save as WEBP format to reduce page loading time.

The use of higher quality and slightly more stylised photos in muted tones would compliment the site design and appeal to teenagers who are more accustomed to visual apps like Instagram and Snapchat.

![anxiousboy](https://github.com/user-attachments/assets/be3792c8-cb01-474a-9ff2-e65760a3f604)

![meditate](https://github.com/user-attachments/assets/3dd33d2a-7ad0-4c57-b968-717634a93b37)

![family](https://github.com/user-attachments/assets/2e5cd7e7-e49e-410b-9a4f-b9d0df3c07d7)

![breathe](https://github.com/user-attachments/assets/2ad21648-a56a-4007-acd3-50d9fff85b7e)

## Website Features

Levels
Results included words per minute
[Back to top](#top)

## Responsive Design
Most of the content is responsive to different screen sizes as it was built using components from the Bootstrap Library.

[Back to top](#top)

## Future Features

[Back to top](#top)

## Technologies Used
### Languages and Technologies
![Static Badge](https://img.shields.io/badge/HTML5-Language-blue)
![Static Badge](https://img.shields.io/badge/CSS3-Language-blue)
![Static Badge](https://img.shields.io/badge/GitHub-RepoHosting-black)
![Static Badge](https://img.shields.io/badge/Gitpod-IDE-yellow)

### Libraries
![Static Badge](https://img.shields.io/badge/Bootstrap-5.3-purple)
![Static Badge](https://img.shields.io/badge/FontAwesome-icons-navy)
![Static Badge](https://img.shields.io/badge/GoogleFonts-Typography-blue)
### Tools and Programs
![Static Badge](https://img.shields.io/badge/LogoAI-LogoGenerator-red)
![Static Badge](https://img.shields.io/badge/Favicon.io-icons-navy)
![Static Badge](https://img.shields.io/badge/Balsamiq-Wireframes-green)
![Static Badge](https://img.shields.io/badge/Balsamiq-Wireframes-green)
![Static Badge](https://img.shields.io/badge/MSCopilot-AI-orange)
![Static Badge](https://img.shields.io/badge/GitHubCopilot-AI-orange)

[Back to top](#top)

## Deployment
The [Code Institute Template](https://github.com/Code-Institute-Org/ci-full-template) was used to create the GitHub repository, so that the website could be developed in the correct setup of Gitpod IDE.

The GitHub Copilot extension was also installed in my local client version of MS VS Code, which was also connected with the same GitHub repository and linked to Gitpod via SSH. This allows for AI pair programming in the initial stages of development to create certain sections faster.

The process is as follows:
1. Login to your GitHub profile.
2. Go to the [Code Institute Template] (https://github.com/Code-Institute-Org/ci-full-template).
3. Click **Use this template** and then **Create a new repository**.
4. Enter the repo name and choose to create from template
5. Click **Open** with the Gitpod logo to open the Code Institute IDE workspace.
6. Open VS Code locally and click on Gitpod logo on the left. Click on right arrow next to the workspace you want to work on.
 
Once the MVP has been created in Gitpod, go to GitHub Pages to make an early deployment of the project, so that testing can be done in Dev Tools to highlight key issues that need to be resolve early on in the project.

[Back to top](#top)

## Testing
Validation of HTML/CSS, Lighthouse Audits, Bugs
#### HTML Validation

#### CSS Validation

#### Lighthouse Audit

### Bugs yet to be Fixed

[Back to top](#top)

## Credits
### Content References
MS Copilot was used to generate much of the content on coping strategies and online resources, which was then reviewed and edited before including into the site.

### Media References

#### Acknowledgements
Everyone in our WECA group who have been so helpful and supportive leading up to this group project, and
Code Institute tutors (Dillon, Mark and Roo) for answering our questions

[Back to top](#top)


# Hackday#6 - 29 Iunie 2019

## Proiecte:

### Monitorizare Vot

A digital tool for election monitoring. It has three main parts: 

- a [public platform](https://monitorizarevot.ro/) where anyone can read the voting rules and report if they notice anything that goes against the voting rules 
- native apps for both Android and iOS allowing observers to send real-time reports from the field
- admin platform for NGOs that register election observers

After the latest elections, we realized we need to enhance the platform with new functionalities, so right now we are focusing on:

- enhancements on [NGO platform](https://github.com/code4romania/monitorizare-vot-ong/issues) for the next set of elections coming in November - the features we are looking at implementing are importing polling station information, observer management, forms management and reporting
- a new [admin dashboard](https://github.com/code4romania/monitorizare-vot-votanti-client/issues?q=is%3Aopen+is%3Aissue+label%3Amay-release) for the public platform that will allow admins to easily update the website info (voting rules, report form) and approve or reject reports sent by users
- setting up some [manual](https://github.com/code4romania/monitorizare-vot-android/labels/testing) and automated tests for the apps and APIs
- integrate the realtime vote counting project in the public platform of Monitorizare Vot (https://github.com/code4romania/rezultate-vot/issues)
- improve both the codebase and the UX of the mobile apps, for this we have some [research tasks](https://github.com/code4romania/monitorizare-vot-android/issues?q=is%3Aissue+is%3Aopen+label%3Aresearch)

**Tech stack**:

- public platform: [PHP](https://github.com/code4romania/monitorizare-vot-votanti-api/issues?q=is%3Aissue+is%3Aopen+label%3Aphp) (Laravel 5) for the API, [React](https://github.com/code4romania/monitorizare-vot-votanti-admin/issues?q=is%3Aissue+is%3Aopen+label%3Areact) on frontend
- NGO admin platform: [.NET Core API](https://github.com/code4romania/monitorizare-vot-ong) and [Angular 2](https://github.com/code4romania/monitorizare-vot-ong) frontend

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/7)**

[![QA issues](https://img.shields.io/badge/open%20issues-QA-red.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-android/labels/testing)
[![PHP issues](https://img.shields.io/badge/open%20issues-php-yellow.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-votanti-api/issues?q=is%3Aissue+is%3Aopen+label%3Aphp) [![React issues](https://img.shields.io/badge/open%20issues-react-orange.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-votanti-admin/issues?q=is%3Aissue+is%3Aopen+label%3Areact) [![.NET Core issues](https://img.shields.io/badge/open%20issues-dotnet-blue.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-ong/labels/may-release) [![Angular issues](https://img.shields.io/badge/open%20issues-angular-cyan.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-ong/labels/may-release)


**[Slack channel](https://codeforromania.slack.com/messages/CGE0NEG5S)**

:question: **Contact person**: @radu.stefanescu, @bogdanvizureanu on slack

### Catalog politic - Declaratii de avere

Catalog Politic - Asset declarations is a crowd sourcing and volunteer aid app for digitizing asset declarations of Romania's public figures. This tool aims to provide an easy and simple way to transform asset declarations from a pdf format to a consistent data model that can be analyzed and interpreted, while opening this information to a larger audience.

We are currently working on:

- Docker-izing Catalog Politic - Digitalizare Declarații (which includes the web application used for digitalization and PyBossa)
- autoamtic deployment using Travis CI and AWS
- creating automated tests
- testing the workflow, manually, to ensure it works end to end and to get feedback on ways to improve on it


**Tech stack**: [Python 3](https://github.com/code4romania/catpol-declaratii/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Apython)
[Docker](https://github.com/code4romania/catpol-declaratii/issues?q=is%3Aissue+is%3Aopen+label%3ADocker)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/10)**

[![Python 3 issues](https://img.shields.io/badge/open%20issues-python-green.svg?style=for-the-badge)](https://github.com/code4romania/catpol-declaratii/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Apython)
[![Docker issues](https://img.shields.io/badge/open%20issues-docker-orange.svg?style=for-the-badge)](https://github.com/code4romania/catpol-declaratii/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Apython)

**[Slack channel](https://codeforromania.slack.com/messages/CGF3WESK1)**

:question: **Contact person**: @catileptic @radu.stefanescu on Slack

### ANABI - Portalul Bunurilor Confiscate
ANABI - Portalul bunurilor confiscate Dezvoltăm pentru Agenția Națională pentru Administrarea Bunurilor Indisponibilizate (ANABI) o platformă despre ce, cât și de unde se confiscă în România, din infracțiuni. Punem totul pe hartă, pentru ca tu să știi ce se petrece. ANABI va folosi platforma pentru a gestiona aceste bunuri la nivel național, inclusiv re-directionarea acestor resurse. Astfel, platforma va transparentiza procesul de utilizare a bunurilor confiscate.

**Tech stack**: [Angular](https://github.com/code4romania/anabi-gestiune-client/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Aangular),
[.NET Core](https://github.com/code4romania/anabi-gestiune-api/labels/dotnet)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/13)**

[![Angular issues](https://img.shields.io/badge/open%20issues-angular-orange.svg?style=for-the-badge)](https://github.com/code4romania/anabi-gestiune-client/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Aangular)
[![.NET Core issues](https://img.shields.io/badge/open%20issues-.NET%20Core-brightgreen.svg?style=for-the-badge)](https://github.com/code4romania/anabi-gestiune-api/labels/dotnet)

**[Slack channel](https://codeforromania.slack.com/messages/CGEBAPH29)**

:question: **Contact person**: @vlad.dinulescu @Bogdan Constantinescu @alex_albu on Slack

### Centru Civic

The project aims to turn into the public library of Romanian civic tech.

- There are some [API defects](https://github.com/code4romania/civichq-api/issues?q=is%3Aissue+is%3Aopen+label%3Abug) that hinder the current deployment and need urgent atention.
- We also have some new designs for the site. We have some [Front end](https://github.com/code4romania/civichq-client/issues?q=is%3Aissue+is%3Aopen+label%3Afront-end) issues and [Research](https://github.com/code4romania/civichq-client/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3AResearch) tasks and also some small API development issues. 
- We would also like to set up some automated tests for the API so we have some open [testing](https://github.com/code4romania/civichq-api/labels/testing) tasks as well.
- Another step for improving the solution is to provide a [Dockerfile](https://github.com/code4romania/civichq-api/issues/68) for running this solution as a standalone container.

**Tech stack**: [Express.js](https://github.com/code4romania/civichq-api/issues?q=is%3Aissue+is%3Aopen+label%3Aespress-js+project%3Acode4romania%2F8), [Angular 7](https://github.com/code4romania/civichq-client/issues?q=is%3Aopen+label%3Aangular+project%3Acode4romania%2F8)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/8)**

[![QA issues](https://img.shields.io/badge/open%20issues-QA-red.svg?style=for-the-badge)](https://github.com/code4romania/civichq-api/labels/testing) [![Research issues](https://img.shields.io/badge/open%20issues-Research-9cf.svg?style=for-the-badge)](https://github.com/code4romania/civichq-client/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3AResearch)  [![Express.js issues](https://img.shields.io/badge/open%20issues-expressjs-yellow.svg?style=for-the-badge)](https://github.com/code4romania/civichq-api/issues?q=is%3Aissue+is%3Aopen+label%3Aespress-js+project%3Acode4romania%2F8)  [![Angular issues](https://img.shields.io/badge/open%20issues-angular-orange.svg?style=for-the-badge)](https://github.com/code4romania/civichq-client/issues?q=is%3Aopen+label%3Aangular+project%3Acode4romania%2F8) 

**[Slack channel](https://codeforromania.slack.com/messages/CGD9BHS56)**

:question: **Contact person**: @radu.stefanescu @oliviavereha @aniri on slack  

### RVM - Resource & Volunteer Management App

RVM is a technical solution that will serve the Department for Emergency Situations in case of any natural or accidental crisis situation, allowing them to keep track of CSO resource stock and volunteering capacity at any given moment in time. The solution will cut down bureaucracy, human error and both human and time resource waste on logistical aspects of maintaining such a database up to date and make use of it in times of distress.

The project has 3 modules:
- An API that will serve both the web client and the mobile application
- A web application client, that will be used by administrators and NGOs
- A mobile application, used by DSU agents

Wireframes for the solution can be found here: 

- [Web Wireframes](https://www.figma.com/file/K7Qqywpx1QFVzG1ml2Fa3qsv/Resource-%26-Volunteer-Management-App)

- [Mobil App Wireframes](https://www.figma.com/file/RIKRNKzDKb1VH3sOmEiER9/VoluntarDRM-(Copy))


**Tech stack**: [Angular](https://github.com/code4romania/rvm-client/issues?q=is%3Aissue+is%3Aopen+label%3Aangular),
[PHP/Laravel](https://github.com/code4romania/rvm-api/issues?q=is%3Aissue+is%3Aopen+label%3APHP%2FLaravel)
[React Native](https://github.com/code4romania/rvm-mobile/issues?q=is%3Aissue+is%3Aopen+label%3Areact-native)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/14)**

[![Angular issues](https://img.shields.io/badge/open%20issues-angular-orange.svg?style=for-the-badge)](https://github.com/code4romania/rvm-client/issues?q=is%3Aissue+is%3Aopen+label%3Aangular) 
[![PHP/Laravel issues](https://img.shields.io/badge/open%20issues-php/laravel-red.svg?style=for-the-badge)](https://github.com/code4romania/rvm-api/issues?q=is%3Aissue+is%3Aopen+label%3APHP%2FLaravel)
[![React Native issues](https://img.shields.io/badge/open%20issues-react%20native-blue.svg?style=for-the-badge)](https://github.com/code4romania/rvm-mobile/issues?q=is%3Aissue+is%3Aopen+label%3Areact-native)


**[Slack channel](https://codeforromania.slack.com/messages/CKRQ1TF09)**

:question: **Contact person**: @radu.stefanescu on Slack


### Legal Consultation App

Legal Consultation App is a digital tool to allow groups of experts to work directly on the text of law proposals, to contribute feedback, suggestions, comments, vote and amend certain proposals, articles or comments of other participants etc. and then automatically reinforce the final document. This tool will make it easier to consult experts with enough time to give everyone an opinion, eliminating unnecessary bureaucracy and allowing real-time access to the same information for thousands of people who otherwise would only interact with a single contact point.

Wireframes for the project can be found here:

- [Legal Consultation Wireframes](https://www.figma.com/file/7VLlmWKJOjS3YXkOFjMRi0/Legal-Consultation)

**Tech stack**: 
[Angular](https://github.com/code4romania/legal-consultation-client/issues),
[Java](https://github.com/code4romania/legal-consultation-api/issues)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/15)**


[![Angular issues](https://img.shields.io/badge/open%20issues-angular-orange.svg?style=for-the-badge)](https://github.com/code4romania/legal-consultation-client/issues) 
[![Java/Spring Boot issues](https://img.shields.io/badge/open%20issues-java-green.svg?style=for-the-badge)](https://github.com/code4romania/legal-consultation-api/issues)

**[Slack channel](https://codeforromania.slack.com/messages/CKRS59XTK)**

:question: **Contact person**: @radu.stefanescu on Slack


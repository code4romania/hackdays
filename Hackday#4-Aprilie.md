
# Hackday#4 - 4 Aprilie 2019

## Proiecte:

### Monitorizare Vot

A digital tool for election monitoring. It has three main parts: 

- a [public platform](https://monitorizarevot.ro/) where anyone can read the voting rules and report if they notice anything that goes against the voting rules 
- native apps for both Android and iOS allowing observers to send real-time reports from the field
- admin platform for NGOs that register election observers

We are currently working on:

- small [fixes](https://github.com/code4romania/monitorizare-vot-android/issues/113) and [improvements](https://github.com/code4romania/monitorizare-vot-android/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement+project%3Acode4romania%2F7) for the Android app
- enhancements on [Android platform](https://github.com/code4romania/monitorizare-vot-android/labels/may-release) and [iOS platform](https://github.com/code4romania/monitorizare-vot-ios/labels/may-release) for May 2019 European Parlamentery elections release
- enhancements on [API](https://github.com/code4romania/monitorizare-vot/issues/111), merge the datamodel on NGO API and Mobile API 
- enhancements on [NGO platform](https://github.com/code4romania/monitorizare-vot-ong/labels/may-release) for May 2019 European Parlamentery elections release
- a new admin dashboard for the public platform that will allow admins to easily update the website info (voting rules, report form) and approve or reject reports sent by users
- setting up some [manual](https://github.com/code4romania/monitorizare-vot-android/labels/testing) and automated tests for the apps and APIs

**Tech stack**:

- public platform: [PHP](https://github.com/code4romania/monitorizare-vot-votanti-api/issues?q=is%3Aissue+is%3Aopen+label%3Aphp) (Laravel 5) for the API, [React](https://github.com/code4romania/monitorizare-vot-votanti-admin/issues?q=is%3Aissue+is%3Aopen+label%3Areact) on frontend
- mobile apps: [Java (Android)](https://github.com/code4romania/monitorizare-vot-android/labels/may-release), [Swift](https://github.com/code4romania/monitorizare-vot-ios/labels/may-release); backed by a [.NET Core API](https://github.com/code4romania/monitorizare-vot)
- NGO admin platform: [.NET Core API](https://github.com/code4romania/monitorizare-vot-ong) and [Angular 2](https://github.com/code4romania/monitorizare-vot-ong) frontend

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/7)**

[![QA issues](https://img.shields.io/badge/open%20issues-QA-red.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-android/labels/testing)
[![Android issues](https://img.shields.io/badge/open%20issues-android-green.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-android/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+project%3Acode4romania%2F7+) [![iOS issues](https://img.shields.io/badge/open%20issues-iOS-red.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-ios/labels/may-release)  [![PHP issues](https://img.shields.io/badge/open%20issues-php-yellow.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-votanti-api/issues?q=is%3Aissue+is%3Aopen+label%3Aphp) [![React issues](https://img.shields.io/badge/open%20issues-react-orange.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-votanti-admin/issues?q=is%3Aissue+is%3Aopen+label%3Areact) [![.NET Core issues](https://img.shields.io/badge/open%20issues-dotnet-blue.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-ong/labels/may-release) [![Angular issues](https://img.shields.io/badge/open%20issues-angular-cyan.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-ong/labels/may-release)


**[Slack channel](https://codeforromania.slack.com/messages/CGE0NEG5S)**

:question: **Contact person**: @radu.stefanescu , @aniri on slack

### Catalog politic - Declaratii de avere

Catalog Politic - Asset declarations is a crowd sourcing and volunteer aid app for digitizing asset declarations of Romania's public figures. This tool aims to provide an easy and simple way to transform asset declarations from a pdf format to a consistent data model that can be analyzed and interpreted, while opening this information to a larger audience.

**Tech stack**: [Python 3](https://github.com/code4romania/catpol-declaratii/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Apython)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/10)**

[![Python 3 issues](https://img.shields.io/badge/open%20issues-python-green.svg?style=for-the-badge)](https://github.com/code4romania/catpol-declaratii/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Apython)

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

:question: **Contact person**: @vlad.dinulescu @Bogdan Constantinescu on Slack

### Data Portal

Data Portal will be a CKAN-based user-friendly web application meant to showcase curated data sets in simple and intuitive visual designs. It will also put forward standards and guidelines for cleaning and organizing data. The portal will be open to any NGO and institution that works with public data and our team will be there to help them validate and bring the information up to standards.

Last but not least. The app will serve as a base for developing Romania’s open data community: we will make our infrastructure and know-how available to volunteers interested in opening up and cleaning Romanian public data.

We are currently working on:

- implementing platform [UI](https://github.com/code4romania/ckanext-dataportaltheme/issues)
- a  [github extension](https://github.com/code4romania/ckanext-githubfeed/issues) to bring the latest issues into DataPortal
- a  [Medium extension](https://github.com/code4romania/ckanext-mediumfeed/issues) to bring all Medium posts into DataPortal


**Tech stack**:

- (backend) CKAN 2.8 Platform: Python 2.7
- (frontend) CKAN 2.8 Templating engine: HTML, Javascript and CSS


:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/12)**

[![Python 3 issues](https://img.shields.io/badge/open%20issues-python-green.svg?style=for-the-badge)](https://github.com/code4romania/ckanext-dataportaltheme/issues)

**[Slack channel](https://codeforromania.slack.com/messages/CGF3V9X63)**

:question: **Contact person**: @costi (Costin Bleotu) on Slack

### Redirectioneaza 2%

Helping NGOs collect the 230 tax form

**Tech stack**: [Python](https://github.com/code4romania/redirectioneaza/issues)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/9)**

[![Python issues](https://img.shields.io/badge/open%20issues-python-green.svg?style=for-the-badge)](https://github.com/code4romania/redirectioneaza/issues)

**[Slack channel](https://codeforromania.slack.com/messages/CGE0LAEMA)**

:question: **Contact person**: @onel on Slack

### Centru Civic

The project aims to turn into the public library of Romanian civic tech.

We are currently working on some fixes and small improvements for the first version of the app. And also looking for ideas to start developing version 2. We have some [UX](https://github.com/code4romania/civichq-client/issues?q=is%3Aissue+is%3Aopen+label%3AUX), [UI](https://github.com/code4romania/civichq-client/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3AUI) and [Research](https://github.com/code4romania/civichq-client/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3AResearch) tasks and also some small front end & API development issues. We would also like to set up some automated tests for the API so we have some open [testing](https://github.com/code4romania/civichq-api/labels/testing) tasks as well.

**Tech stack**: [Express.js](https://github.com/code4romania/civichq-api/issues?q=is%3Aissue+is%3Aopen+label%3Aespress-js+project%3Acode4romania%2F8), [Angular 7](https://github.com/code4romania/civichq-client/issues?q=is%3Aopen+label%3Aangular+project%3Acode4romania%2F8)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/8)**

[![QA issues](https://img.shields.io/badge/open%20issues-QA-red.svg?style=for-the-badge)](https://github.com/code4romania/civichq-api/labels/testing) [![UX issues](https://img.shields.io/badge/open%20issues-UX-blue.svg?style=for-the-badge)](https://github.com/code4romania/civichq-client/issues?q=is%3Aissue+is%3Aopen+label%3AUX)  [![UI issues](https://img.shields.io/badge/open%20issues-UI-79A0D1.svg?style=for-the-badge)](https://github.com/code4romania/civichq-client/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3AUI)  [![Research issues](https://img.shields.io/badge/open%20issues-Research-9cf.svg?style=for-the-badge)](https://github.com/code4romania/civichq-client/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3AResearch)  [![Express.js issues](https://img.shields.io/badge/open%20issues-expressjs-yellow.svg?style=for-the-badge)](https://github.com/code4romania/civichq-api/issues?q=is%3Aissue+is%3Aopen+label%3Aespress-js+project%3Acode4romania%2F8)  [![Angular issues](https://img.shields.io/badge/open%20issues-angular-orange.svg?style=for-the-badge)](https://github.com/code4romania/civichq-client/issues?q=is%3Aopen+label%3Aangular+project%3Acode4romania%2F8) 

**[Slack channel](https://codeforromania.slack.com/messages/CGD9BHS56)**

:question: **Contact person**: @radu.stefanescu , @aniri on slack  

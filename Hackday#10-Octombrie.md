# Hackday#10 - 26 Octombrie 2019

## Proiecte:

### Monitorizare Vot

A digital tool for election monitoring. It has two main parts: 

- native apps for both Android and iOS allowing observers to send real-time reports from the polling stations
- admin platform for NGOs that register election observers, create election monitoring forms and send real-time notifications to observers

After the latest elections, we realized we need to enhance the platform with new functionalities, so right now we are focusing on:

- enhancements on [NGO platform](https://github.com/code4romania/monitorizare-vot-ong/issues) for the next set of elections coming in November - the features we are looking at implementing are importing polling station information, observer management, forms management, push notifications
- update the iOS application with a new UX/UI and re-write the [Android application from scratch in Kotlin](https://github.com/code4romania/mon-vot-android-kotlin/issues)
- setting up some [manual](https://github.com/code4romania/monitorizare-vot-android/labels/testing) and automated tests for the apps and APIs
- improve both the codebase and the UX of the mobile apps, for this we have some [research tasks](https://github.com/code4romania/monitorizare-vot-android/issues?q=is%3Aissue+is%3Aopen+label%3Aresearch)

**Tech stack**:

- NGO admin platform: [.NET Core API](https://github.com/code4romania/monitorizare-vot/issues) and [Angular 5](https://github.com/code4romania/monitorizare-vot-ong/issues?q=is%3Aissue+is%3Aopen+label%3Aangular) frontend
- mobile applications: [Kotlin](https://github.com/code4romania/mon-vot-android-kotlin/issues) and [Swift 5](https://github.com/code4romania/monitorizare-vot-ios/issues)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/7)**

[![QA issues](https://img.shields.io/badge/open%20issues-QA-red.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-android/labels/testing)
[![.NET Core issues](https://img.shields.io/badge/open%20issues-dotnet-blue.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot/issues) [![Angular issues](https://img.shields.io/badge/open%20issues-angular-cyan.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-ong/labels/may-release) [![Kotlin issues](https://img.shields.io/badge/open%20issues-kotlin-brown.svg?style=for-the-badge)](https://github.com/code4romania/mon-vot-android-kotlin/issues) [![iOS issues](https://img.shields.io/badge/open%20issues-ios-green.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-ios/issues)

**[Slack channel](https://codeforromania.slack.com/messages/CGE0NEG5S)**

:question: **Contact person**: @bogdanvizureanu, @aniri on slack

### Catalog politic - Declaratii de avere

Catalog Politic - Asset declarations is a crowd sourcing and volunteer aid app for digitizing asset declarations of Romania's public figures. This tool aims to provide an easy and simple way to transform asset declarations from a pdf format to a consistent data model that can be analyzed and interpreted, while opening this information to a larger audience.

We are currently working on:

- Docker-izing Catalog Politic - Digitalizare Declarații (which includes the web application used for digitalization and PyBossa)
- autoamtic deployment using Travis CI and AWS
- creating automated tests
- testing the workflow, manually, to ensure it works end to end and to get feedback on ways to improve on it


**Tech stack**: [Python3](https://github.com/code4romania/catpol-declaratii/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Apython)
[Docker](https://github.com/code4romania/catpol-declaratii/issues?q=is%3Aissue+is%3Aopen+label%3ADocker)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/10)**

[![Python 3 issues](https://img.shields.io/badge/open%20issues-python-green.svg?style=for-the-badge)](https://github.com/code4romania/catpol-declaratii/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Apython)
[![Docker issues](https://img.shields.io/badge/open%20issues-docker-orange.svg?style=for-the-badge)](https://github.com/code4romania/catpol-declaratii/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Apython)

**[Slack channel](https://codeforromania.slack.com/messages/CGF3WESK1)**

:question: **Contact person**: @catileptic on Slack

### Rezultate Vot

The project aims to be an aggregator for election information in Romania. The project will contain historic information for elections in Romania, will contain real time results for each election, as it will parse results published by BEC (Biroul Electoral Central) and it will also contain information about the budgets spent during the electoral campaign.

Currently our focus is on:
- [importing historic results](https://github.com/code4romania/rezultate-vot/issues?q=is%3Aissue+is%3Aopen+label%3Ahistoric-results) of elections 
- being prepared for providing [live results](https://github.com/code4romania/rezultate-vot/issues?q=is%3Aissue+is%3Aopen+label%3Avote-results) during the counting of the next round of elections.

**Tech stack**: [.NET Core](https://github.com/code4romania/rezultate-vot/issues?q=is%3Aissue+is%3Aopen+label%3Adotnet)
[React](https://github.com/code4romania/rezultate-vot/issues?q=is%3Aissue+is%3Aopen+label%3Areact)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/18)**

[![dotnet issues](https://img.shields.io/badge/open%20issues-.NET%20Core-blue.svg?style=for-the-badge)](https://github.com/code4romania/rezultate-vot/issues?q=is%3Aissue+is%3Aopen+label%3Adotnet) [![React issues](https://img.shields.io/badge/open%20issues-react-green.svg?style=for-the-badge)](https://github.com/code4romania/rezultate-vot/issues?q=is%3Aissue+is%3Aopen+label%3Areact)

**[Slack channel](https://codeforromania.slack.com/messages/CNNQ78J2Z)**

:question: **Contact person**: @Bogdan Bujdea on slack

### Seismic Alert

Let's save lives together!

Seisimic Alert aims to become an aggregator of seismic data and building analysis, currently focusing on data in Bucharest, but looking towards expading for the whole country.

Currently we are focusing on:
- building a [map](https://github.com/code4romania/seismic-risc/issues?q=is%3Aissue+is%3Aopen+label%3Amap) that displays information about buildings and their classification
- a simple [CMS](https://github.com/code4romania/seismic-risc/issues?q=is%3Aissue+is%3Aopen+label%3Acms) to be able, as an admin of the platform, to insert data, validate user inputs

**Tech stack**: [Python/Django](https://github.com/code4romania/seismic-risc/issues?q=is%3Aissue+is%3Aopen+label%3Adjango)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/16)**

[![Django issues](https://img.shields.io/badge/open%20issues-django-orange.svg?style=for-the-badge)](https://github.com/code4romania/seismic-risc/issues)

**[Slack channel](https://codeforromania.slack.com/messages/CLM4014BB)**

:question: **Contact person**: @tamariei on slack

### Expert Consultation App

Expert Consultation App is a digital tool to allow groups of experts to work directly on the text of law proposals, to contribute feedback, suggestions, comments, vote and amend certain proposals, articles or comments of other participants etc. and then automatically reinforce the final document. This tool will make it easier to consult experts with enough time to give everyone an opinion, eliminating unnecessary bureaucracy and allowing real-time access to the same information for thousands of people who otherwise would only interact with a single contact point.

Wireframes for the project can be found here:

- [Legal Consultation Wireframes](https://www.figma.com/file/7VLlmWKJOjS3YXkOFjMRi0/Legal-Consultation)

**Tech stack**: 
[Angular](https://github.com/code4romania/legal-consultation-client/issues),
[Java](https://github.com/code4romania/legal-consultation-api/issues)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/15)**

[![Angular issues](https://img.shields.io/badge/open%20issues-angular-orange.svg?style=for-the-badge)](https://github.com/code4romania/legal-consultation-client/issues) 
[![Java/Spring Boot issues](https://img.shields.io/badge/open%20issues-java-green.svg?style=for-the-badge)](https://github.com/code4romania/legal-consultation-api/issues)

**[Slack channel](https://codeforromania.slack.com/messages/CKRS59XTK)**

:question: **Contact**: Slack channel hackday_legal_cons

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

:question: **Contact person**: @Gheorghe on Slack

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

[![Python 3 issues](https://img.shields.io/badge/open%20issues-python-green.svg?style=for-the-badge)](https://github.com/code4romania/data-portal/issues)

**[Slack channel](https://codeforromania.slack.com/messages/CGF3V9X63)**

:question: **Contact person**: @costi on Slack

### Theatre Hub

The main goal of Theater Hub is to form a community of professionals working in the theater industry. 

We are currently looking for devops helpers :smile: as we need an automatic deployment pipeline that would deploy the solution to AWS.

**Tech stack**:

- (backend) NodeJS
- (frontend) Nuxt.js

[![DevOps issues client](https://img.shields.io/badge/open%20issues-frontend-green.svg?style=for-the-badge)](https://github.com/code4romania/theater-hub-client/issues)
[![DevOps issues API](https://img.shields.io/badge/open%20issues-backend-blue.svg?style=for-the-badge)](https://github.com/code4romania/theater-hub-api/issues)


**[Slack channel](https://codeforromania.slack.com/messages/CGE57L5T2)**

:question: **Contact person**: @andreimitrea on Slack

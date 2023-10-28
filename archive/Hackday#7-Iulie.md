
# Hackday#7 - 27 Iulie 2019

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
- integrate the realtime vote results project in the public platform of Monitorizare Vot [Rezultate Vot](https://github.com/code4romania/rezultate-vot/issues)
- improve both the codebase and the UX of the mobile apps, for this we have some [research tasks](https://github.com/code4romania/monitorizare-vot-android/issues?q=is%3Aissue+is%3Aopen+label%3Aresearch)

**Tech stack**:

- public platform: [PHP](https://github.com/code4romania/monitorizare-vot-votanti-api/issues?q=is%3Aissue+is%3Aopen+label%3Aphp) (Laravel 5) for the API, [React](https://github.com/code4romania/monitorizare-vot-votanti-admin/issues?q=is%3Aissue+is%3Aopen+label%3Areact) on frontend
- NGO admin platform: [.NET Core API](https://github.com/code4romania/monitorizare-vot-ong) and [Angular 2](https://github.com/code4romania/monitorizare-vot-ong) frontend

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/7)**

[![QA issues](https://img.shields.io/badge/open%20issues-QA-red.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-android/labels/testing)
[![PHP issues](https://img.shields.io/badge/open%20issues-php-yellow.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-votanti-api/issues?q=is%3Aissue+is%3Aopen+label%3Aphp) [![React issues](https://img.shields.io/badge/open%20issues-react-orange.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-votanti-admin/issues?q=is%3Aissue+is%3Aopen+label%3Areact) [![.NET Core issues](https://img.shields.io/badge/open%20issues-dotnet-blue.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-ong/labels/may-release) [![Angular issues](https://img.shields.io/badge/open%20issues-angular-cyan.svg?style=for-the-badge)](https://github.com/code4romania/monitorizare-vot-ong/labels/may-release)


**[Slack channel](https://codeforromania.slack.com/messages/CGE0NEG5S)**

:question: **Contact person**: @radu.stefanescu, @bogdanvizureanu on slack

### ANABI - Portalul Bunurilor Confiscate
ANABI - Portalul bunurilor confiscate Dezvoltăm pentru Agenția Națională pentru Administrarea Bunurilor Indisponibilizate (ANABI) o platformă despre ce, cât și de unde se confiscă în România, din infracțiuni. Punem totul pe hartă, pentru ca tu să știi ce se petrece. ANABI va folosi platforma pentru a gestiona aceste bunuri la nivel național, inclusiv re-directionarea acestor resurse. Astfel, platforma va transparentiza procesul de utilizare a bunurilor confiscate.

**Tech stack**: [Angular](https://github.com/code4romania/anabi-gestiune-client/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Aangular),
[.NET Core](https://github.com/code4romania/anabi-gestiune-api/labels/dotnet)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/13)**

[![Angular issues](https://img.shields.io/badge/open%20issues-angular-orange.svg?style=for-the-badge)](https://github.com/code4romania/anabi-gestiune-client/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3Aangular)
[![.NET Core issues](https://img.shields.io/badge/open%20issues-.NET%20Core-brightgreen.svg?style=for-the-badge)](https://github.com/code4romania/anabi-gestiune-api/labels/dotnet)

**[Slack channel](https://codeforromania.slack.com/messages/CGEBAPH29)**

:question: **Contact person**: @Radu.stefanescu @Bogdan Constantinescu @alex_albu on Slack

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


### Seismic Risc

Seismic Risc - Un cutremur în București nu este o situație ipotetică. Este o certitudine că acest lucru se va întâmpla. În acest context, la mai bine de 40 de ani de la cutremurul din 1977, memoria colectivă a ascuns în profunzime amintirile acelui dezastru în încercarea de a-și înnăbuși teama. Dar realitatea este că, patru decenii mai târziu, Bucureștiul, la fel ca restul orașelor cu risc seismic ridicat, nu ar face față unui asemenea eveniment, iar pierderile de vieți omenești ar fi uriașe. Exercițiul Seism 2018, derulat de DSU arată că cel puţin 4.587 persoane şi-ar pierde viaţa, iar 8.585 ar fost rănite, 6 spitale vor fi distruse, 23 de unităţi spitaliceşti distruse parţial, iar 9 avariate, dar funcţionale O estimare, am spune noi, destul de optimistă.

Ce putem face pentru a deveni mai puțin vulnerabili? Să știm totul despre oraș, despre clădirile în care locuim și sa putem sa cerem consolidarea lor. Seismic risk nu este doar un nou site de informare, ci o platforma care colectează și validează apoi cu experti date despre clădirile din București și care va fi extins la nivel national, ajuta asociațiile de proprietari sa își consolideze clădirile, te tine la curent cu legislația și ți-o explica și are grija sa ai la îndemână informații utile la orice moment.

Let's save lives together.

Wireframes for the project can be found here:

- [Seismic Risc Wireframes](https://www.figma.com/file/qOyFrU8T6LXnJw7YcoVW85/Seismic-Risk?node-id=0%3A1)

**Tech stack**: 
[Django/Pyhton/HTML](https://github.com/code4romania/seismic-risc/issues)

:clipboard: **[Github Board](https://github.com/orgs/code4romania/projects/16)**

[![Django/Python issues](https://img.shields.io/badge/open%20issues-angular-orange.svg?style=for-the-badge)](https://github.com/code4romania/legal-consultation-client/issues) 

**[Slack channel](https://codeforromania.slack.com/messages/CLM4014BB)**

:question: **Contact person**: @radu.stefanescu on Slack

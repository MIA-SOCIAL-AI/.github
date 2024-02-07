<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/MIA-Marketing-AI/condoor-backend" id= "readme-top">
    <img src="media/svg/logoMIA.svg" alt="Logo" width="250" height="auto">
  </a>

  <!-- PROJECT SHIELDS -->
<a href="https://discord.gg/MJQAdZMYQW" target="_blank"><img src="https://img.shields.io/badge/discord-online-5865F2?style=for-the-badge&logo=discord" alt="Discord"/></a>
<a href="https://github.com/Neodaten/adac_back/tree/main" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master?style=for-the-badge" alt="CircleCI" /></a>
<a href="https://github.com/Neodaten/adac_back/tree/main" target="_blank"><img src="https://img.shields.io/badge/Coverage-96.67%25-brightgreen?style=for-the-badge" alt="Coverage" /></a>



  # Welcome! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">
 <img src="https://media.giphy.com/media/htinLom37opJDyuajR/giphy.gif" width="auto">


  <p align="center">
    In this readme file you will get all the information you need to get to work on this repository, we hope you enjoy working with us 😃!
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
# Table of Contents
- [Welcome! ](#welcome-)
- [Table of Contents](#table-of-contents)
- [About the Project](#about-the-project)
  - [Built With](#built-with)
    - [Package installer:](#package-installer)
    - [Framework:](#framework)
    - [Programming language:](#programming-language)
    - [Reverse proxy:](#reverse-proxy)
    - [Database:](#database)
    - [Linter \& Formatter:](#linter--formatter)
    - [Environment:](#environment)
    - [Containerization:](#containerization)
  - [APIs](#apis)
    - [Digital marketing tool:](#digital-marketing-tool)
    - [Cloud computing:](#cloud-computing)
    - [Identity platform:](#identity-platform)
    - [Database:](#database-1)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
- [Running the app](#running-the-app)
- [Test](#test)
- [Documentation](#documentation)
  - [Recommended software \& tools](#recommended-software--tools)
  - [VS code extensions we recommend](#vs-code-extensions-we-recommend)
- [Agile methodology (Workflow)](#agile-methodology-workflow)
- [The team](#the-team)
    - [Project Owner](#project-owner)
    - [Project Managers](#project-managers)
    - [Back end developers](#back-end-developers)
    - [Cloud computing team](#cloud-computing-team)
    - [Data scientist](#data-scientist)
    - [Front end developers](#front-end-developers)
    - [UX/UI Designer](#uxui-designer)
- [Contributing](#contributing)
- [Contact](#contact)
- [Security Concerns](#security-concerns)
  - [License](#license)


<!-- ABOUT THE PROJECT -->
# About the Project
<div align="center">
<img src="https://media.giphy.com/media/xUA7biJu1P8G6BTYYM/giphy.gif" width="px">
</div>


This backend serves as the nerve center for our platform, which is engineered to amplify the voices of individuals and businesses across various social media channels through intelligent, data-driven recommendations. At its core, the backend is designed to handle intricate logic that synergizes with our powerful AI and machine learning algorithms. These algorithms are adept at analyzing social media data to tailor content recommendations that resonate with the user's intended audience, significantly enhancing engagement.

The system’s recommendation engine processes user data gleaned from social media interactions to generate personalized content strategies. This not only simplifies content creation but also ensures that the posts are targeted and effective. The automation feature of the backend is responsible for the seamless scheduling and distribution of these posts across different social media platforms, enabling users to maintain a consistent and impactful online presence.

An integral part of our backend is the WhatsApp CRM integration. This feature allows our users to directly manage leads and interactions that result from the enhanced engagement driven by our custom algorithms. With this, users can maintain a productive dialogue with their audience, fostering relationships and converting interactions into opportunities.

The backend is built using robust technologies: NestJS orchestrates the backend services providing a scalable framework for server-side applications, while Node.js and TypeScript offer a high-performance, type-safe environment for our server logic. Our data pipelines are managed by Apache Airflow, ensuring that data processing is timely and reliable. Docker containers encapsulate our services, ensuring consistency across development, testing, and production environments. With npm for package management, our dependencies are kept in check, while Eslint and Prettier maintain code quality and consistency.

Our backend is also fortified with industry-standard security and authentication protocols using Auth0, and it leverages the expansive capabilities of AWS for hosting and data storage with PostgreSQL, ensuring scalability and high availability. This combination of cutting-edge technology and best practices allows us to deliver a backend solution that is not only powerful in its analytical and automation capabilities but is also secure, scalable, and ready to meet the demands of a growing user base.

Through this platform, we aim to democratize the reach on social media, providing every user the ability to be heard, to grow their audience, and to manage their digital interactions effectively and efficiently.



Feel free to explore the different features and sections of MIA to make the most out of your experience.



<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Built With

The MIA project is built using a combination of various technologies and frameworks to ensure a robust and seamless user experience. The key technologies utilized in the development of MIA include:

<table>
<tr>
<td>

### Package installer:

- [![NPM Version](https://img.shields.io/npm/v/npm?color=%23CB3837&label=npm&logo=npm&style=for-the-badge)](https://www.npmjs.com/package/npm)

</td>
<td>

### Framework:

- [![NestJs Version](https://img.shields.io/badge/nest.js-v9.0.0-%23E0234E?style=for-the-badge&logo=nestjs)](https://www.npmjs.com/package/@nestjs/core)

</td>
<td>

### Programming language:

- [![TypeScript](https://img.shields.io/badge/TypeScript-4.3.5-%233178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

</td>
<td>

### Reverse proxy:

- [![Nginx](https://img.shields.io/badge/Nginx-Latest-%23009639?style=for-the-badge&logo=nginx)](https://www.nginx.com/)


</td>
</tr>
<tr>
<td>

### Database:

- [![MongoDB](https://img.shields.io/badge/MongoDB-5.0.2-%2347A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/cloud/atlas/lp/try4?utm_source=google&utm_campaign=search_gs_pl_evergreen_atlas_core_prosp-brand_gic-null_amers-mx_ps-all_desktop_eng_lead&utm_term=mongodb&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=12212624326&adgroup=115749706303&cq_cmp=12212624326&gad=1&gclid=CjwKCAjw4ZWkBhA4EiwAVJXwqaMNQG81DSAq-1j8h9DQdNlpIG6LTEOPbIM8ItWAOqVIElfXB0WYfRoCel8QAvD_BwE)
- [![Prisma](https://img.shields.io/badge/Prisma-%5E4.4.0-%232D3748?style=for-the-badge&logo=prisma&logoColor=white)](https://www.prisma.io/)

</td>
<td>

### Linter & Formatter:

- [![ESLint](https://img.shields.io/badge/ESLint-%5E8.0.1-%234B32C3?style=for-the-badge&logo=eslint)](https://eslint.org/)
- [![Prettier](https://img.shields.io/badge/Prettier-%5E2.3.2-%23F7B93E?style=for-the-badge&logo=prettier)](https://prettier.io/)


</td>
<td>

### Environment:

- [![Node.js](https://img.shields.io/badge/Node.js-%5E18.12.1-%23339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/es)
- [![NVM Version](https://img.shields.io/badge/%F0%9F%85%BD%F0%9F%86%85%F0%9F%85%BC%20nvm-LATEST-%23339933?style=for-the-badge)](https://github.com/nvm-sh/nvm)

</td>
<td>

### Containerization:

- [![Docker](https://img.shields.io/badge/Docker-3.8-%230db7ed.svg?logo=docker&style=for-the-badge)](https://www.docker.com/)

</td>
</tr>
</table>

## APIs

<table>
<tr>
<td>

### Digital marketing tool:

- [![MailerLite](https://img.shields.io/badge/MailerLite-30B980?logo=minutemailer&logoColor=fff&style=for-the-badge)](https://www.mailerlite.com/)


</td>
<td>

### Cloud computing:

- [![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)

</td>
<td>

### Identity platform:

- [![Auth0](https://img.shields.io/badge/Auth0-EB5424?style=for-the-badge&logo=auth0&logoColor=white)](https://auth0.com/)

</td>
<td>

### Database:

- [![MongoDB Atlas](https://img.shields.io/badge/MongoDB%20Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/cloud/atlas)

</td>
</tr>
</table>


By leveraging these technologies, MIA is able to provide a user-friendly and efficient platform that incorporates real-time data tracking, interactive interfaces, and seamless integration with external APIs. This powerful combination ensures that users can access up-to-date information and enjoy a personalized experience while using MIA.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
# Getting Started

<div align = "center">
 <img src="https://media2.giphy.com/media/NhWZxXB1zoMapS1jtN/giphy.gif?cid=ecf05e470upzpsfayua6zkhx444ph63hbpc5hpyi44h1xja4&ep=v1_gifs_search&rid=giphy.gif&ct=g" width="px">
</div>



This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

<div align = "center">

| ![Node](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/200px-Node.js_logo.svg.png) | ![NVM](https://raw.githubusercontent.com/nvm-sh/logos/bf1f9618e83e5098024b18c73ada1b0f542db5f8/nvm-logo-black.svg) | ![Docker](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Docker_%28container_engine%29_logo.svg/200px-Docker_%28container_engine%29_logo.svg.png) |
| --- | --- | --- |
| [Node.js Installation](https://kinsta.com/blog/how-to-install-node-js/) | [NVM Installation](https://heynode.com/tutorial/install-nodejs-locally-nvm/) | [Docker Compose Installation](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-22-04) |
</div>

### Installation

1. Clone the repo
   ```sh
   git clone git@github.com:Neodaten/adac_back.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```


Make sure you have installed the tools shown below the company logo with the required versions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Running the app

1. Initialize docker container
```bash
$ npm run db:local:start
```
2. Development (watch mode)
```bash
$ npm run start:dev
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Test 

1. Unit tests
```bash
$ npm run test
```
2. e2e tests
```bach
$ npm run test:e2e
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Documentation

- [Documentation of endpoints](http://localhost:4444/api-docs) (Run server to visualize)
- [User interface](https://www.figma.com/file/LPDWABcPKrECWVxLQrBkeI/Blog?node-id=23%3A28)
- [Site map](https://www.figma.com/file/2F7PQ9pXTLULPN8g20jYhp/SiteMap-Blog)
- [Database diagrams](https://app.diagrams.net/#G1qmfD7Y4q4u-st3dUeYlMycrHx9jOvArW) (EER)
- [Brainstorm UX/UI references](https://miro.com/app/board/uXjVPMvtd3k=/)

To know further information about ADAC project you can visit the following website

<a href="https://neodaten.atlassian.net/wiki/spaces/UID/overview"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://adac-comming-soon-front.vercel.app/">View Demo</a>
    ·
    <a href="https://docs.google.com/document/d/1VFWSyrHbE5w5tnC7-TDe3vnd2i-fG_PFCqCmlEIhajw/edit?usp=sharing">Report Bug</a>
    ·
    <a href="https://neodaten.atlassian.net/wiki/spaces/UID/pages/27623426/Proposals+for+software+development">Request Feature</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

    

## Recommended software & tools

- [Oh my zsh!](https://ohmyz.sh/)
- [Terminator](https://terminator-gtk3.readthedocs.io/en/latest/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Ubuntu 22.04](https://ubuntu.com/download/desktop)

## VS code extensions we recommend

Please checkout the recommended extensions on file `.vscode/extensions.json`.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Agile methodology (Workflow)

<div style="text-align: center;" align= "center"> 
  <img src="https://media4.giphy.com/media/xT1XGOGdyDrL2BTfxK/giphy.gif?cid=ecf05e47mcecf95l4tye7lwj8ylbuuu0nk92uwqn4k7b5ldh&ep=v1_gifs_search&rid=giphy.gif&ct=g" width="550px">
</div>


We're currently using [Jira Software](https://www.atlassian.com/software/jira) for both scrum and sprint planning, please go to the board to see the current tasks of the sprint.

[ADAC board](https://justcripto.atlassian.net/jira/software/projects/ADAC/boards/16)

If you want to understand the workflow with more detail go to  

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# The team 
<img src="https://www.godfrey.com/application/files/2516/5594/4141/sg-blog-trdshw-pr-p1.gif" width="px">

### Project Owner

- Rafael Musi Ortega

### Project Managers

- Yonathan Berith Jaramillo Ramírez.
- Santiago Villavicencio Cruz.
  
### Back end developers

- Yonathan Berith Jaramillo Ramírez.
- Santiago Villavicencio Cruz.

### Cloud computing team

- Yonathan Berith Jaramillo Ramírez.
- Santiago Villavicencio Cruz.

### Data scientist

- Diego Arturo Velazquez Trejo.
- Samuel Schimdt Rovero

### Front end developers

- Nicole Cruz
- Leon Chavez

### UX/UI Designer

- Daniela Urbina Flores.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
# Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- CONTACT -->
# Contact

- [![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-%23181717?style=for-the-badge&logo=github)](https://github.com/Neodaten/adac_back)
- [![Twitter Follow](https://img.shields.io/badge/Twitter-Follow-blue?style=for-the-badge&logo=twitter)](https://twitter.com/adacblog)
- [![Facebook Like](https://img.shields.io/badge/Facebook-Like-%23157EFB?style=for-the-badge&logo=facebook)](https://www.facebook.com/people/ADAC/100090649664671)
- [![TikTok Follow](https://img.shields.io/badge/TikTok-Follow-%23FF0000?style=for-the-badge&logo=tiktok)](https://www.tiktok.com/@adac.mx)
- [![Instagram Follow](https://img.shields.io/badge/Instagram-Follow-%23E4405F?style=for-the-badge&logo=instagram)](https://www.instagram.com/adac.mx)
- [![LinkedIn Connect](https://img.shields.io/badge/LinkedIn-Connect-%230077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/company/adacmx/)
- [![Reddit Join](https://img.shields.io/badge/Reddit-Join-%23FF4500?style=for-the-badge&logo=reddit)](https://www.reddit.com/r/ADAC_Blog/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

# Security Concerns

Here are some useful links addressing the security concerns:

1. **Node.js Vulnerabilities Blog**: [Visit here](https://nodejs.org/en/blog/vulnerability)
2. **CVE Details for Node.js**: [Visit here](https://www.cvedetails.com/vulnerability-list/vendor_id-12113/Nodejs.html)
3. **OWASP Top Ten Project**: [Visit here](https://owasp.org/www-project-top-ten/)


## License
We most obey the "laws" of the cybersecurity community and pay attention to them to make sure we're covering all security aspects while we work on this repo.

Distributed under the Proprietary software. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

https://www.figma.com/file/sXWSQKJT8uB7UAnc9PfCck/Aurora?type=whiteboard&node-id=0%3A1&t=cvp3HMyq3pzEdnBh-1

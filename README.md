<a name="readme-top"></a>
<div align="center">

  ![Project Banner](readme_assets/readme_banner.png#gh-dark-mode-only)
  ![Project Banner](readme_assets/readme_banner-light.png#gh-light-mode-only)

  <h1>AI-Prompt Sharing Web</h1>
  
  <p>
  well-designed full-stack web application for share & disocver AI-Prompts - using Next.js 13 powered by MongoDB.
  </p>

<!-- Badges -->
<p>
  <a href="https://github.com/ladunjexa/AI-Prompt-Sharing-Web/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/ladunjexa/AI-Prompt-Sharing-Web" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/ladunjexa/AI-Prompt-Sharing-Web" alt="last update" />
  </a>
  <a href="https://github.com/ladunjexa/AI-Prompt-Sharing-Web/network/members">
    <img src="https://img.shields.io/github/forks/ladunjexa/AI-Prompt-Sharing-Web" alt="forks" />
  </a>
  <a href="https://github.com/ladunjexa/AI-Prompt-Sharing-Web/stargazers">
    <img src="https://img.shields.io/github/stars/ladunjexa/AI-Prompt-Sharing-Web" alt="stars" />
  </a>
  <a href="https://github.com/ladunjexa/AI-Prompt-Sharing-Web/issues/">
    <img src="https://img.shields.io/github/issues/ladunjexa/AI-Prompt-Sharing-Web" alt="open issues" />
  </a>
  <a href="https://github.com/ladunjexa/AI-Prompt-Sharing-Web/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/ladunjexa/AI-Prompt-Sharing-Web.svg" alt="license" />
  </a>
</p>
   
 <h4>
    <a href="https://creativ-ai-prompt-sharing-web.vercel.app/">View Demo</a>
  <span> · </span>
    <a href="https://github.com/ladunjexa/AI-Prompt-Sharing-Web">Documentation</a>
  <span> · </span>
    <a href="https://github.com/ladunjexa/AI-Prompt-Sharing-Web/issues/">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/ladunjexa/AI-Prompt-Sharing-Web/issues/">Request Feature</a>
  </h4>
</div>

<br />

<!-- Table of Contents -->
<details>

<summary>

# :notebook_with_decorative_cover: Table of Contents

</summary>

- [About the Project](#star2-about-the-project)
  * [Folder Structure](#bangbang-folder-structure)
  * [Tech Stack](#space_invader-tech-stack)
- [Getting Started](#toolbox-getting-started)
  * [Environment Variables](#key-environment_variables)
  * [Installation](#gear-installation)
  * [Run Locally](#running-run-locally)
- [Contributing](#wave-contributing)
- [License](#warning-license)
- [Contact](#handshake-contact)
- [Acknowledgements](#gem-acknowledgements)

</details>  

<!-- About the Project -->
## :star2: About the Project

<div align="center">
  <img src="readme_assets/mockup.png" height="auto" width="90%"/>
</div>
<br />

This repository houses an incredible AI-Prompts Sharing Web Application - modern full-stack Next.js 13 application powered by MongoDB 🤖

<!-- Folder Structure -->
### :bangbang: Folder Structure

Here is the folder structure of CreativAI.
```bash
AI-Prompt-Sharing-Web/
|- app/
  |-- api/
    |-- auth/[...nextauth]
    |-- prompt/
        |-- [id]/
        |-- new/
    |-- users/[id]/posts/
  |-- create-prompt/
  |-- profile/
  |-- update-prompt/
|- components/
|- models/
|- public/assets/
|- styles/
|- utils/
|- jsconfig.json
|- next.config.js
|- package.json
|- postcss.config.js
|- tailwind.config.js
```
<br />

<!-- TechStack -->
### :space_invader: Tech Stack

[![My Skills](https://skillicons.dev/icons?i=react,nextjs,tailwind,mongodb)](https://skillicons.dev)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Getting Started -->
## :toolbox: Getting Started

<!-- ENV VARIABLES -->
### :key: Environment Variables

In order to use this AI-Prompt Sharing Webapp you have to add some environment variables to .env file,

create `.env` file in root folder & add the following environment variable:
```env
GOOGLE_CLIENT_ID=<GOOGLE_CLIENT_ID>
GOOGLE_SECRET_ID=<GOOGLE_SECRET_ID>
MONGODB_URI=<MONGODB_URI>
MONGODB_DB=<DATABASE_NAME>
NEXTAUTH_URL=<BASE_URL> 
NEXTAUTH_URL_INTERNAL=<BASE_URL>
NEXTAUTH_SECRET=<SECRET> // generate one using openssl (`openssl rand -base64 32`)
```

<!-- Installation -->
### :gear: Installation

#### Step 1:
Download or clone this repo by using the command below:

```bash
 https://github.com/ladunjexa/AI-Prompt-Sharing-Web.git
```

#### Step 2:

This webapp using NPM (Node Package Manager), therefore, make sure that Node.js is installed by execute the following command in console:

```bash
  node -v
```

#### Step 3:

In root folder execute the following command to get the required packages:

```bash
  npm install
```

<!-- Run Locally -->
### :running: Run Locally

#### Step 1:

Go to root folder and execute the following command in order to run the webapp:

```bash
  npm run dev
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Contributing -->
## :wave: Contributing

<a href="https://github.com/ladunjexa/AI-Prompt-Sharing-Web/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ladunjexa/AI-Prompt-Sharing-Web" />
</a>


Contributions are always welcome!

See [`contributing.md`](https://contributing.md/) for ways to get started.

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- License -->
## :warning: License

Distributed under the MIT License. See [LICENSE.txt](https://github.com/ladunjexa/AI-Prompt-Sharing-Web/blob/main/LICENSE) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Contact -->
## :handshake: Contact

Liron Abutbul - [@lironabutbul6](https://twitter.com/lironabutbul6) - [@ladunjexa](https://t.me/ladunjexa)

Project Link: [https://github.com/ladunjexa/AI-Prompt-Sharing-Web](https://github.com/ladunjexa/AI-Prompt-Sharing-Web)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Acknowledgments -->
## :gem: Acknowledgements

This section used to mention useful resources and libraries that used in CreativAI Webapp:

 - [React Framework](https://react.dev/)
 - [Next.js 13](https://nextjs.org/)
 - [NextAuth.js](https://next-auth.js.org/)
 - [TailwindCSS](https://tailwindcss.com/)
 - [MongoDB](https://www.mongodb.com/)
 - [Mongoose](https://mongoosejs.com/)
 - #JSMastery

<p align="right">(<a href="#readme-top">back to top</a>)</p>

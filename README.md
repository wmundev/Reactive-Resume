![Reactive Resume](https://res.cloudinary.com/amruth-pillai/image/upload/v1699180255/reactive-resume/readme/banner_zvieca.png)

![App Version](https://img.shields.io/github/package-json/version/AmruthPillai/Reactive-Resume/v4?label=version)
[![Docker Pulls](https://img.shields.io/docker/pulls/amruthpillai/reactive-resume)](https://hub.docker.com/repository/docker/amruthpillai/reactive-resume)
[![GitHub Sponsors](https://img.shields.io/github/sponsors/AmruthPillai)](https://github.com/sponsors/AmruthPillai)
[![Crowdin](https://badges.crowdin.net/reactive-resume/localized.svg)](https://crowdin.com/project/reactive-resume)
![Discord](https://img.shields.io/discord/1173518977851473940?label=discord&link=https%3A%2F%2Fdiscord.gg%2FhzwkZbyvUW)

# Reactive Resume

A free and open-source resume builder that simplifies the process of creating, updating, and sharing your resume.

### [Go to App](https://rxresu.me/) | [Docs](https://docs.rxresu.me/)

## Description

Reactive Resume is a free and open-source resume builder that simplifies the process of creating, updating, and sharing your resume. With zero user tracking or advertising, your privacy is a top priority. The platform is extremely user-friendly and can be self-hosted in less than 30 seconds if you wish to own your data completely.

It's available in multiple languages and comes packed with features such as real-time editing, dozens of templates, drag-and-drop customisation, and integration with OpenAI for enhancing your writing.

You can share a personalised link of your resume to potential employers, track its views or downloads, and customise your page layout by dragging-and-dropping sections. The platform also supports various font options and provides dozens of templates to choose from. And yes, there's even a dark mode for a more comfortable viewing experience.

Start creating your standout resume with Reactive Resume today!

## Screenshots

TODO: Add screenshots of major sections of the app

## Features

- **Free, forever** and open-source
- No telemetry, user tracking or advertising
- You can self-host the application in less then 30 seconds
- **Available in 20+ languages**, and counting ([help add/improve your language here](https://translate.rxresu.me/))
- Use your email address (or a throw-away address) to create an account
- You can also sign in with your GitHub or Google account, and even set up two-factor authentication for extra security
- Create as many resumes as you like under a single account, optimising each resume for every job application based on it's description for a higher ATS score
- **Bring your own OpenAI API key** and unlock features such as improving your writing, fixing spelling and grammar or changing the tone of your text in one-click
- Translate your resume into any language using ChatGPT and import it back for easier editing
- Create single page resumes or a resume that spans multiple pages easily
- Customize the colors and layouts to add a personal touch to your resume
- Customise your page layout as you like just by dragging-and-dropping sections
- Jot down personal notes specific to your resume that's only visible to you
- **Dozens of templates** to choose from, ranging from professional to modern to swanky
- Supports printing resumes in A4 or Letter page formats
- Design your resume with any font family and variant that's available on [Google Fonts](https://fonts.google.com/)
- **Share a personalised link of your resume** to companies or recruiters for them to get the latest updates and as a bonus, you can track how many times your resume has been viewed or downloaded since it's creation
- You can track the number of views or downloads your public resume has received
- Built with state-of-the-art (at the moment) and dependable technologies with the simplest and most human-readable code on all of GitHub
- **MIT License**, so do what you like with the code as long as you credit the original author
- And finally yes, there's a dark mode too 🌓

## Built With

- Postgres (primary database)
- DigitalOcean (infrastructure)
- Prisma ORM, which frees you to switch to any other relational database with a few minor changes in the code
- Redis (for caching, session storage and resume statistics)
- Minio (for object storage: to store avatars, resume PDFs and previews)
- Browserless (for headless chrome, to print PDFs and generate previews)
- SMTP Server (to send password recovery emails)
- Sentry (for error tracing and performance monitoring)
- GitHub/Google OAuth (for quickly authenticating users)
- LinguiJS and Crowdin (for translation management and localization)

## Star History

<a href="https://star-history.com/#AmruthPillai/Reactive-Resume&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=AmruthPillai/Reactive-Resume&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=AmruthPillai/Reactive-Resume&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=AmruthPillai/Reactive-Resume&type=Date" />
  </picture>
</a>

## License

Reactive Resume is packaged and distributed using the [MIT License](/LICENSE.md) which allows for commercial use, distribution, modification and private use provided that all copies of the software contain the same license and copyright.

_By the community, for the community._  
A passion project by [Amruth Pillai](https://www.amruthpillai.com/)

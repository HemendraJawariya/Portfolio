<a name="readme-top"></a>

# A Modern UI/UX Portfolio using Next.JS

![A Modern UI/UX Portfolio using Next.JS](/.github/images/img_main.png "A Modern UI/UX Portfolio using Next.JS")

[![Ask Me Anything!](https://flat.badgen.net/static/Ask%20me/anything?icon=github&color=black&scale=1.01)](https://github.com/HemendraJawariya/Portfolio "Ask Me Anything!")
[![GitHub license](https://github.com/HemendraJawariya/Portfolio?icon=github&color=black&scale=1.01)](https://github.com/HemendraJawariya/Portfolio/blob/main/LICENSE "GitHub license")
[![Maintenance](https://github.com/HemendraJawariya/Portfolio&color=black&scale=1.01)](https://github.com/HemendraJawariya/Portfolio/commits/main "Maintenance")
[![GitHub branches](https://github.com/HemendraJawariya/Portfolio?icon=github&color=black&scale=1.01)](https://github.com/HemendraJawariya/Portfolio/branches "GitHub branches")
[![Github commits](https://github.com/HemendraJawariya/Portfolio?icon=github&color=black&scale=1.01)](https://github.com/HemendraJawariya/Portfolio/commits "Github commits")
[![GitHub issues](https://github.com/HemendraJawariya/Portfolio?icon=github&color=black&scale=1.01)](https://github.com/HemendraJawariya/Portfolio/issues "GitHub issues")
[![GitHub pull requests](https://github.com/HemendraJawariya/Portfolio?icon=github&color=black&scale=1.01)](https://github.com/HemendraJawariya/Portfolio/pulls "GitHub pull requests")
[![Vercel status](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/HemendraJawariya/Portfolio/ "Vercel status")

<!-- Table of Contents -->
<details>

<summary>

# :notebook_with_decorative_cover: Table of Contents

</summary>

- [Folder Structure](#bangbang-folder-structure)
- [Getting Started](#toolbox-getting-started)
- [Screenshots](#camera-screenshots)
- [Tech Stack](#gear-tech-stack)
- [Stats](#wrench-stats)
- [Contribute](#raised_hands-contribute)
- [Acknowledgements](#gem-acknowledgements)
- [Buy Me a Coffee](#coffee-buy-me-a-coffee)
- [Follow Me](#rocket-follow-me)
- [Learn More](#books-learn-more)
- [Deploy on Vercel](#page_with_curl-deploy-on-vercel)
- [Give A Star](#star-give-a-star)
- [Star History](#star2-star-history)
- [Give A Star](#star-give-a-star)

</details>

## :bangbang: Folder Structure

Here is the folder structure of My Portfolio.

```bash
portfolio/
  |- public/
  |- app/
    |-- apple-icon.png
    |-- favicon.ico
    |-- globals.css
    |-- layout.tsx
    |-- page.tsx
  |- components/
    |-- about.tsx
    |-- contact.tsx
    |-- experience.tsx
    |-- footer.tsx
    |-- header.tsx
    |-- index.ts
    |-- intro.ts
    |-- projects.ts
    |-- section-divider.ts
    |-- section-heading.ts
    |-- skills.ts
    |-- theme-switch.ts
  |- constants/
    |-- index.ts
  |- context/
    |-- active-section-context.tsx
    |-- theme-context.tsx
  |- lib/
    |-- hooks.ts
    |-- types.ts
  |- public/
    |-- icons/
  |- .env.example
  |- .env.local
  |- .eslintrc.json
  |- .gitignore
  |- environment.d.ts
  |- next.config.js
  |- package-lock.json
  |- package.json
  |- postcss.config.cjs
  |- tailwind.config.cjs
  |- tsconfig.json
```

<br />

## :toolbox: Getting Started

1. Make sure **Git** and **NodeJS** is installed.
2. Clone this repository to your local computer.
3. Create `.env.local` file in root folder.
4. Contents of `.env.local`:

```env
# .env.local

# disabled next.js telemetry
NEXT_TELEMETRY_DISABLED=1

# email.js id and key
NEXT_PUBLIC_EMAILJS_SERVICE_ID=service_xxxxxxxxxx
NEXT_PUBLIC_EMAILJS_TEMPLATE_ID=template_xxxxxxxxxxxx
NEXT_PUBLIC_EMAILJS_PUBLIC_KEY=XXXXXXXXXXXXXXX

# google verification key (optional) - used for domain verification on https://search.google.com/search-console
NEXT_PUBLIC_GOOGLE_VERIFICATION_KEY=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

```

5. Create new account in [EmailJS](https://www.emailjs.com/ "EmailJS").

6. From dashboard, choose Email Services > Add New Service and connect your mail to emailjs.

7. Once new service is configured, copy your **Service ID** to `NEXT_PUBLIC_EMAILJS_SERVICE_ID`.

8. Now, go to Email Templates > Create New Template to create your mail template. Once it is done, you can copy **Template ID** to `NEXT_PUBLIC_EMAILJS_TEMPLATE_ID`.

9. To get your **Public Key**, click on your username on navbar and go to account settings > Copy Public Key to `NEXT_PUBLIC_EMAILJS_PUBLIC_KEY`.

10. Open terminal in root directory. Run `npm install --legacy-peer-deps` or `yarn install --legacy-peer-deps`.

![Copy Public Key](/.github/images/step_emailjs.png "Copy Public Key")

11. Now app is fully configured :+1: and you can start using this app using `npm run dev` or `yarn dev`.

**NOTE:** Ensure you don't share these keys publicly.

## :camera: Screenshots:

![Modern UI/UX using Tailwind CSS](/.github/images/img1.png "Modern UI/UX using Tailwind CSS")

![Showcase Projects](/.github/images/img2.png "Showcase Projects")

![Tell about your Experiences](/.github/images/img3.png "Tell about your Experiences")

![Working Contact Form](/.github/images/img4.png "Working Contact Form")

## :gear: Tech Stack

[![React JS](https://skillicons.dev/icons?i=react "React JS")](https://react.dev/ "React JS") [![Next JS](https://skillicons.dev/icons?i=next "Next JS")](https://nextjs.org/ "Next JS") [![Typescript](https://skillicons.dev/icons?i=ts "Typescript")](https://www.typescriptlang.org/ "Typescript") [![Tailwind CSS](https://skillicons.dev/icons?i=tailwind "Tailwind CSS")](https://tailwindcss.com/ "Tailwind CSS") [![Vercel](https://skillicons.dev/icons?i=vercel "Vercel")](https://vercel.app/ "Vercel")

## :wrench: Stats

[![Stats for My portfolio](/.github/images/stats.svg "Stats for My portfolio")](https://github.com/HemendraJawariya/Portfolio/ "Stats for My portfolio")

## :raised_hands: Contribute

You might encounter some bugs while using this app. You are more than welcome to contribute. Just submit changes via pull request and I will review them before merging. Make sure you follow community guidelines.

## :gem: Acknowledgements

Useful resources and libraries that are used in My Portfolio

- [Email JS](https://www.emailjs.com/ "Email JS")
- [Framer Motion](https://www.framer.com/motion/ "Framer Motion")
- [CLSX](https://www.npmjs.com/package/clsx "CLSX")
- [React Icons](https://react-icons.github.io/react-icons/ "React Icons")
- [React Vertical Timeline Component](https://www.npmjs.com/package/react-vertical-timeline-component "React Vertical Timeline Component")
- [React Hot Toast](https://www.npmjs.com/package/react-hot-toast "React Hot Toast")
- [React Intersection Observer](https://www.npmjs.com/package/react-intersection-observer "React Intersection Observer")
- [Next PWA](https://www.npmjs.com/package/next-pwa "Next PWA")

## :coffee: Buy Me a Coffee

[<img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" width="200" />](https://www.buymeacoffee.com/hemendrajawariya "Buy me a Coffee")

## :rocket: Follow Me

[![Follow Me](https://github.com/HemendraJawariya/Portfolio?style=social&label=Follow&maxAge=2592000)](https://github.com/HemendraJawariya/Portfolio "Follow Me")
[![Tweet about this project](https://github.com/HemendraJawariya/Portfolio)](https://twitter.com/intent/tweet?text=Check+out+this+amazing+app:&url=https%3A%2F%2Fgithub.com%2Fsanidhyy%portfolio "Tweet about this project")
[![Subscribe to my YouTube Channel](https://github.com/HemendraJawariya/Portfolio)](https://github.com/HemendraJawariya/Portfolio "Subscribe to my YouTube Channel")

## :books: Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## :page_with_curl: Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## :star: Give A Star

You can also give this repository a star to show more people and they can use this repository.

## :star2: Star History

<a href="https://github.com/HemendraJawariya/Portfolio&Timeline">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/HemendraJawariya/Portfolio&type=Timeline&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/HemendraJawariya/Portfolio&type=Timeline" />
    <img alt="Star History Chart" src="https://github.com/HemendraJawariya/Portfolio&type=Timeline" />
  </picture>
</a>

<br />
<p align="right">(<a href="#readme-top">back to top</a>)</p>

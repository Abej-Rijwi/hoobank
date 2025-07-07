<div align="center">
  <br />
    <a href="https://youtu.be/Ou77zEajm1U" target="_blank">
      <img src="https://i.ibb.co/BK1Hn0x/Screenshot-2022-08-08-at-4-05-48-PM.png" alt="Project Banner">
    </a>
  <br />

  <div>
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-0EA5E9?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
      <img src="https://img.shields.io/badge/React_Router_DOM-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white" alt="React Router DOM" />
  </div>

  <h3 align="center">HooBank Application</h3>

   <div align="center">
     Build this project step by step with our detailed tutorial on <a href="https://www.youtube.com/@MasterJavaScript" target="_blank"><b>JavaScript Tutorial</b></a> YouTube. Join the JSM family!
    </div>
   </div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets](#snippets)
6. 🔗 [Links](#links)

## 🚨 Tutorial

This repository contains the code corresponding to an in-depth tutorial available on our YouTube
channel, <a href="https://www.youtube.com/@MasterJavaScript" target="_blank"><b>JavaScript Tutorial</b></a>.

If you prefer visual learning, this is the perfect resource for you. Follow our tutorial to learn how to build projects
like these step-by-step in a beginner-friendly manner!

<a href="https://youtu.be/Ou77zEajm1U target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/1736fca5-a031-4854-8c09-bc110e3bc16d" /></a>

## <a name="introduction">🤖 Introduction</a>

Welcome to the HooBank Application – a fully responsive and interactive web application built using React JS TailwindCSS and React Router DOM.

<a href="https://discord.com/invite/ZwbTTDWGF8" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/618f4872-1e10-42da-8213-1d69e486d02e" /></a>

## <a name="tech-stack">⚙️ Tech Stack</a>

- React
- TailwindCSS
- React Router DOM

## <a name="features">🔋 Features</a>

👉 **Routing with React Router**: Enjoy smooth page navigation using client-side routing for a seamless user experience.

👉 **React Functional Components & Reusabilitye**: Build modular, reusable components to make your codebase cleaner and more efficient.

👉 **Optimized File & Folder Structure**: Learn to organize your React projects using best practices for easy scalability and maintenance.

👉 **Master Tailwind CSS**: Achieve mastery in Tailwind CSS and speed up your UI development with utility-first styling.

👉 **CSS Flexbox Essentialsr**: Deeply understand fundamental CSS properties and master Flexbox layouts for responsive designs.

👉 **Responsive Design**: Optimized for desktops, tablets, and mobile devices.

👉 **Advanced UI Design**: Create everything from soft, subtle animations to complex gradients for eye-catching interfaces.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/Abej-Rijwi/hoobank.git
cd hoobank
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## <a name="snippets">🕸️ Snippets</a>

<details>
<summary><code>constants.ts</code></summary>

```typescript
import { people01, people02, people03, facebook, instagram, linkedin, twitter, airbnb, binance, coinbase, dropbox, send, shield, star  } from "../assets";

export const navLinks = [
  {
    id: "home",
    title: "Home",
  },
  {
    id: "features",
    title: "Features",
  },
  {
    id: "product",
    title: "Product",
  },
  {
    id: "clients",
    title: "Clients",
  },
];

export const features = [
  {
    id: "feature-1",
    icon: star,
    title: "Rewards",
    content:
      "The best credit cards offer some tantalizing combinations of promotions and prizes",
  },
  {
    id: "feature-2",
    icon: shield,
    title: "100% Secured",
    content:
      "We take proactive steps make sure your information and transactions are secure.",
  },
  {
    id: "feature-3",
    icon: send,
    title: "Balance Transfer",
    content:
      "A balance transfer credit card can save you a lot of money in interest charges.",
  },
];

export const feedback = [
  {
    id: "feedback-1",
    content:
      "Money is only a tool. It will take you wherever you wish, but it will not replace you as the driver.",
    name: "Herman Jensen",
    title: "Founder & Leader",
    img: people01,
  },
  {
    id: "feedback-2",
    content:
      "Money makes your life easier. If you're lucky to have it, you're lucky.",
    name: "Steve Mark",
    title: "Founder & Leader",
    img: people02,
  },
  {
    id: "feedback-3",
    content:
      "It is usually people in the money business, finance, and international trade that are really rich.",
    name: "Kenn Gallagher",
    title: "Founder & Leader",
    img: people03,
  },
];

export const stats = [
  {
    id: "stats-1",
    title: "User Active",
    value: "3800+",
  },
  {
    id: "stats-2",
    title: "Trusted by Company",
    value: "230+",
  },
  {
    id: "stats-3",
    title: "Transaction",
    value: "$230M+",
  },
];

export const footerLinks = [
  {
    title: "Useful Links",
    links: [
      {
        name: "Content",
        link: "https://www.hoobank.com/content/",
      },
      {
        name: "How it Works",
        link: "https://www.hoobank.com/how-it-works/",
      },
      {
        name: "Create",
        link: "https://www.hoobank.com/create/",
      },
      {
        name: "Explore",
        link: "https://www.hoobank.com/explore/",
      },
      {
        name: "Terms & Services",
        link: "https://www.hoobank.com/terms-and-services/",
      },
    ],
  },
  {
    title: "Community",
    links: [
      {
        name: "Help Center",
        link: "https://www.hoobank.com/help-center/",
      },
      {
        name: "Partners",
        link: "https://www.hoobank.com/partners/",
      },
      {
        name: "Suggestions",
        link: "https://www.hoobank.com/suggestions/",
      },
      {
        name: "Blog",
        link: "https://www.hoobank.com/blog/",
      },
      {
        name: "Newsletters",
        link: "https://www.hoobank.com/newsletters/",
      },
    ],
  },
  {
    title: "Partner",
    links: [
      {
        name: "Our Partner",
        link: "https://www.hoobank.com/our-partner/",
      },
      {
        name: "Become a Partner",
        link: "https://www.hoobank.com/become-a-partner/",
      },
    ],
  },
];

export const socialMedia = [
  {
    id: "social-media-1",
    icon: instagram,
    link: "https://www.instagram.com/",
  },
  {
    id: "social-media-2",
    icon: facebook,
    link: "https://www.facebook.com/",
  },
  {
    id: "social-media-3",
    icon: twitter,
    link: "https://www.twitter.com/",
  },
  {
    id: "social-media-4",
    icon: linkedin,
    link: "https://www.linkedin.com/",
  },
];

export const clients = [
  {
    id: "client-1",
    logo: airbnb,
  },
  {
    id: "client-2",
    logo: binance,
  },
  {
    id: "client-3",
    logo: coinbase,
  },
  {
    id: "client-4",
    logo: dropbox,
  },
];
```

</details>

<details>
<summary><code>index.css</code></summary>

```css
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800;900&display=swap");

@tailwind base;
@tailwind components;
@tailwind utilities;

:root {
  --black-gradient: linear-gradient(
    144.39deg,
    #ffffff -278.56%,
    #6d6d6d -78.47%,
    #11101d 91.61%
  );
  --card-shadow: 0px 20px 100px -10px rgba(66, 71, 91, 0.1);
}

* {
  scroll-behavior: smooth;
}

.text-gradient {
  background: radial-gradient(
    64.18% 64.18% at 71.16% 35.69%,
    #def9fa 0.89%,
    #bef3f5 17.23%,
    #9dedf0 42.04%,
    #7de7eb 55.12%,
    #5ce1e6 71.54%,
    #33bbcf 100%
  );
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  text-fill-color: transparent;
}

.bg-blue-gradient {
  background: linear-gradient(
    157.81deg,
    #def9fa -43.27%,
    #bef3f5 -21.24%,
    #9dedf0 12.19%,
    #7de7eb 29.82%,
    #5ce1e6 51.94%,
    #33bbcf 90.29%
  );
}

.bg-black-gradient {
  background: linear-gradient(
    144.39deg,
    #ffffff -278.56%,
    #6d6d6d -78.47%,
    #11101d 91.61%
  );
}

.bg-black-gradient-2 {
  background: linear-gradient(
    -168.39deg,
    #ffffff -278.56%,
    #6d6d6d -78.47%,
    #11101d 91.61%
  );
}

.bg-gray-gradient {
  background: linear-gradient(
    153.47deg,
    rgba(255, 255, 255, 0) -341.94%,
    #14101d 95.11%
  );
}

.bg-discount-gradient {
  background: linear-gradient(125.17deg, #272727 0%, #11101d 100%);
}

.box-shadow {
  box-shadow: 0px 20px 100px -10px rgba(66, 71, 91, 0.1);
}

.sidebar {
  -webkit-animation: slide-top 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
  animation: slide-top 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
}

@-webkit-keyframes slide-top {
  0% {
    -webkit-transform: translateY(100px);
    transform: translateY(100px);
  }
  100% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
}

@keyframes slide-top {
  0% {
    -webkit-transform: translateY(100px);
    transform: translateY(100px);
  }
  100% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
}

.feature-card:hover {
  background: var(--black-gradient);
  box-shadow: var(--card-shadow);
}

.feedback-container .feedback-card:last-child {
  margin-right: 0px;
}

.feedback-card {
  background: transparent;
}

.feedback-card:hover {
  background: var(--black-gradient);
}

.blue__gradient {
  background: linear-gradient(180deg, rgba(188, 165, 255, 0) 0%, #214d76 100%);
  filter: blur(123px);
}

.pink__gradient {
  background: linear-gradient(90deg, #f4c4f3 0%, #fc67fa 100%);
  filter: blur(900px);
}

.white__gradient {
  background: rgba(255, 255, 255, 0.6);
  filter: blur(750px);
}
```

</details>

<details>
<summary><code>style.js</code></summary>

```javascript
const styles = {
  boxWidth: "xl:max-w-[1280px] w-full",

  heading2: "font-poppins font-semibold xs:text-[48px] text-[40px] text-white xs:leading-[76.8px] leading-[66.8px] w-full",
  paragraph: "font-poppins font-normal text-dimWhite text-[18px] leading-[30.8px]",

  flexCenter: "flex justify-center items-center",
  flexStart: "flex justify-center items-start",

  paddingX: "sm:px-16 px-6",
  paddingY: "sm:py-16 py-6",
  padding: "sm:px-16 px-6 sm:py-12 py-4",

  marginX: "sm:mx-16 mx-6",
  marginY: "sm:my-16 my-6",
};

export const layout = {
  section: `flex md:flex-row flex-col ${styles.paddingY}`,
  sectionReverse: `flex md:flex-row flex-col-reverse ${styles.paddingY}`,

  sectionImgReverse: `flex-1 flex ${styles.flexCenter} md:mr-10 mr-0 md:mt-0 mt-10 relative`,
  sectionImg: `flex-1 flex ${styles.flexCenter} md:ml-10 ml-0 md:mt-0 mt-10 relative`,

  sectionInfo: `flex-1 ${styles.flexStart} flex-col`,
};

export default styles;
```

</details>

<details>
<summary><code>tailwind.config.cjs</code></summary>

```javascript
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./index.html", "./src/**/*.{js,jsx}"],
  mode: "jit",
  theme: {
    extend: {
      colors: {
        primary: "#00040f",
        secondary: "#00f6ff",
        dimWhite: "rgba(255, 255, 255, 0.7)",
        dimBlue: "rgba(9, 151, 124, 0.1)",
      },
      fontFamily: {
        poppins: ["Poppins", "sans-serif"],
      },
    },
    screens: {
      xs: "480px",
      ss: "620px",
      sm: "768px",
      md: "1060px",
      lg: "1200px",
      xl: "1700px",
    },
  },
  plugins: [],
};
```

</details>

## <a name="links">🔗 Links</a>

Assets used in the project are [here](https://drive.google.com/drive/u/1/folders/1Z4Zjg3umOZYIBYafS_S2kO-NMZzKjjd2)

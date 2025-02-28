## Description

- Send me the instructions how can I change the code. Simple stuff like background color, logo image, which file I need to change on GitHub.
- Send me the instructions how can I build and push the code to Vercel so I can learn 😉(you can just push code on github after you change any code. Please check readme.md)
- Send me the instructions how can I set up the crossmint production (API key, etc..)
  (Sure, Please check readme.md)

## Customized CrossMint App

This is a Next.js application designed for a seamless cross-platform user experience. The project includes various components, pages, and configurations tailored for efficient user interaction.

<!-- TABLE OF CONTENTS -->

### Built With

- Next.js, TypeScript, Tailwidn CSS, Crossmint SDK

<!-- GETTING STARTED -->

## Getting Started

Follow these steps to set up your project locally and get it running. This guide provides clear instructions to help you get started quickly.

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v20.12 or later)
- npm (comes with Node.js)

### Installation

1. Obtain a free API Key from the Crossmint Console. Refer to [Get an API Key](https://docs.crossmint.com/wallets/smart-wallets/quickstart#2-get-an-api-key) from the Quickstart guide for detailed instructions.

2. Clone the repo
   ```sh
   git clone git repo
   ```
3. Install PNPM packages
   ```sh
   npm i
   ```
4. In the directory containing this README.md file, rename the `.env.example` file to `.env` and add your API key to the file.
   ```bash
   NEXT_PUBLIC_CROSSMINT_AUTH_SMART_WALLET_API_KEY="ENTER YOUR CROSSMINT API KEY";
   ```
5. Start the development server
   ```sh
   npm run dev
   ```
6. Once you start the Next.js development server, the application can be found at `http://localhost:3000`.

7. Deploy project on vercel(if you change code in our project, you can follow below step to deploy on vercel)
   ```sh
   git status
   git add .
   git commit -m "COMMIT_NAME"
   git push
   ```

## File Structure

```plaintext
customized-crossmint-app/
├── .next/                     # Automatically generated files for Next.js
├── node_modules/              # Project dependencies
├── public/                    # Static files served directly (Images used in the application)
│   └── fireworks.gif          # Fireworks animation image
│   └── emoji-nft.gif          # nft image
├── src/
│   ├── app/                   # Main application files
│   │   ├── providers.tsx      # Context providers for state management
│   ├── components/            # Reusable UI components
│   │   ├── avatar.tsx         # Avatar component for user profiles
│   │   ├── button.tsx         # General button component
│   │   ├── dropdown-menu.tsx   # Dropdown menu component
│   │   ├── firework.tsx       # Fireworks animation component
│   │   ├── page.tsx           # Main page component
│   │   ├── sign-in-auth-button.tsx # Sign-in button for authentication
│   │   ├── skeleton.tsx       # Skeleton loader component
│   │   ├── tabs.tsx           # Tabbed navigation component
│   │   ├── toast.tsx          # Toast notifications component
│   │   ├── typography.tsx     # Typography styles and components
│   │   ├── use-toast.ts       # Custom hook for toast notifications
│   │   ├── spinner.tsx        # Spinner/loading component
│   │   └── icon/              # Icons used in the application
│   │       └── crossmint-leaf.tsx # Custom icon for the project
│   ├── icons/                   # Main application files
│   │   ├── providers.tsx      # Context providers for state management
│   ├── lib/                   # Main application files
│   │   ├── providers.tsx      # Context providers for state management
│   ├── utils/                   # Main application files
│   │   ├── providers.tsx      # Context providers for state management
│   │   └── icon/              # Icons used in the application
│   ├── .env.example           # Example environment variables file
│   ├── .gitignore             # Files and directories to ignore
│   ├── CHANGELOG.md           # Changelog for tracking changes
│   ├── next-env.d.ts              # TypeScript definitions for Next.js
│   ├── next.config.mjs            # Configuration file for Next.js
│   ├── package-lock.json          # Lock file for npm dependencies
│   ├── package.json               # Project dependencies and scripts
│   ├── postcss.config.mjs         # Configuration for PostCSS
│   ├── README.md                  # Project documentation
│   ├── tailwind.config.ts         # Configuration for Tailwind CSS
│   └── tsconfig.json              # TypeScript configuration file

## Explain about your point

- Send me the instructions how can I change the code. Simple stuff like background color, logo image, which file I need to change on GitHub.

  - background color

  - logo image

- Send me the instructions how can I build and push the code to Vercel so I can learn 😉
```

you can just push code on github after you change any code. Please check readme.md

```
- Send me the instructions how can I set up the crossmint production (API key, etc..)
```

Sure, Please check readme.md

```

```

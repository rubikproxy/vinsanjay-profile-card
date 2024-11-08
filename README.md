# Personal Professional Card - Astro Template

**Hello! I'm vinsanjay.**  
This template is designed to help you showcase your projects and achievements. I hope it helps you gain visibility and progress in your work. Thank you for using it! Wishing you success in all your endeavors—you are bound to achieve amazing things.

If you find it useful, I’d appreciate a follow, a Star on this template, and sharing it with others so more people can benefit.

Have a fantastic day ahead!

---

## User Guide

This guide will walk you through customizing the Personal Professional Card template for your own use. All customization is done within the `src/pages/index.astro` file.

### External Card Customization

- **`title`**: Modify this field to update the browser tab title.
- **`description`**: This metadata tag will appear in search engine results, providing a brief description of your page.

### Internal Card Customization

- **`name`**: Enter your full name here.
- **`position`**: Specify your job title.
- **`about me`**: Provide a brief description of who you are and what you do. We recommend keeping it under 540 characters.
- **`linkedin` and `github`**: Enter the URLs to your LinkedIn and GitHub profiles.
- **`cvLink`**: Add the URL to your resume in PDF format for easy download.
- **`profileImage`**: Upload your professional profile picture here.

### File Management

- **Resume**: Place your PDF resume in the `public/files` folder.
- **Profile Image**: Place your profile image in the `public/images` folder. We suggest using the `.webp` format for optimal web performance.
- **Favicon**: Replace the `public/favicon.ico` file with your own favicon, keeping the same file name.

### Layout Customization

In the `src/layouts` folder, you’ll find the `BaseLayout.astro` file. Here, you can edit the entire HTML structure, including the favicon, Google fonts, and Bootstrap icons.

### Style Customization

The `src/styles` folder contains the styles for your card. You can modify colors, fonts, sizes, and other visual elements here to make it your own.

**Easy, right?**

---

## Getting Started

To get your template up and running, follow these steps to initialize and deploy it using Astro and Netlify.

### Prerequisites

Before starting, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14.x or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Astro](https://astro.build/) (installed globally)

### Installation

#### Option 1: Clone the Template Repository

1. **Clone the Template Repository:**

    ```bash
    git clone https://github.com/rubikproxy/vinsanjay-profile-card
    cd vinsanjay-profile-card
    ```

2. **Install Dependencies:**

    ```bash
    npm install
    ```

---

### Running the Project Locally

To start the development server, run the following command:

```bash
npm run dev
```

The Astro development server will start, and you can view your site at [http://localhost:4321](http://localhost:4321). Any changes you make to the project files will be instantly reflected in your browser. To stop the server, press **Ctrl+C** in your terminal.

---

### Building the Project for Production

To prepare your project for deployment, run:

```bash
npm run build
```

---

### Deploying to Netlify

#### Using Netlify Drop

1. **Build the Project** to make sure it's ready for deployment:

   ```bash
   npm run build
   ```

---

## Available Commands

All commands should be run from the root of the project, in your terminal:

| Command               | Action                                               |
| --------------------- | ---------------------------------------------------- |
| `npm install`         | Installs all dependencies                           |
| `npm run dev`         | Starts the local development server at `localhost:4321` |
| `npm run build`       | Builds your site for production in the `./dist/` folder |

---

## Want to Learn More?

Check out the official [Astro documentation](https://docs.astro.build) for more information, or join the [Astro Discord server](https://astro.build/chat) to connect with the community.

---

## Contact

[![](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rubikproxy)

--- 

This version has a more streamlined format and clearer section titles, while keeping all the necessary information intact!
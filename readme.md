# Ebook Website

Bootstrap website for downloading a free E-book. This website has a light, business-oriented design.

<img src="./images/screen.PNG"  />

## Features

- Modern layout with custom colors/styles/backgrounds
- Responsive design
- Sticky navbar with style changes on scroll
- Bootstrap modals
- Form & input styles
- Testimonials
- Contact page with Google Map

## Usage

This website is built with [Bootstrap](https://getbootstrap.com/) and [Sass](https://sass-lang.com/). It uses [Font Awesome](https://fontawesome.com/) for icons.

In order to customize this website, you need to install [Node.js](https://nodejs.org/en/). Then, clone this repository and run:

```bash
npm install
```

This will install Bootstrap, Sass and Font Awesome. To build your CSS files from Sass, run:

```bash
npm run sass:build
```

To watch your Sass files for changes, run:

```bash
npm run sass:watch
```

You can add Bootstrap variables to the `bootstrap.scss` file. You can look at the file `node_modules/bootstrap/dist/scss/_variables.scss` for a list of all the variables. Do NOT edit the `variables.scss` file directly, as it will be overwritten when you update Bootstrap.

To add your own custom styles, use the `styles.scss` file.

## View the Site

The live version of the site, hosted on Vercel, can be viewed at the following link:

[Live Demo](https://vercel.com/sandor-toths-projects/ebook-website/deployments)

Click on the link to view the website and explore the latest version of the project.

## Functional Contact Form

The website features a fully functional contact form, powered by Formspree. This allows for easy and efficient communication. Feel free to test it out and get in touch!

---

For more information and details about the project, please browse through the files in this repository.

Thank you for your interest in the project!


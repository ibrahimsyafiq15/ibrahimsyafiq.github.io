# Syafiq Portfolio

## Introduction

I created this portfolio to display my work in the form of a personal website that refers to other websites where I upload my work such as Behance, Dribbble and others. I built this website starting from the Atlas template by Red Pixel Themes. You can also get the template at the following [link](https://redpixelthemes.com/templates/atlas/).

Currently I have developed and redesigned the appearance of the template based on [Bootstrap v5.3](https://getbootstrap.com)

## Site Map

- `Intro` - This is basically the home page, a simplification of all the pages in my portfolio.

- `Projects` - I will publish all the projects that I have worked on and uploaded to various platforms here too. From practice work to projects with various clients during my UI/UX career.

- `Gallery` - At the moment I haven't started developing it, but in the future this will become a page where I publish my work other than UI/UX such as logos, posters, etc.

## Project Structure

The project uses a mostly flat structure with a key folders and files:

- `assets` folder: This is where all of the projects styles, javascript, fonts (if any) and images live, each on their own folder for better organization. - One thing to keep in mind if that if you want to use the project as is and decide to rename the `styles` folder, be sure to update the `css` NPM script with the new name.
- `browser-sync-config.js`: Pretty self-explanatory, this is the config that BrowserSync uses when we launch our live reload server. Here are the [options docs](https://www.browsersync.io/docs/options) in case you want to customize it.
- `package.json`: Where our dependencies, [browserlist](https://github.com/browserslist/browserslist) config and NPM scripts live. - _Note_: Since we mainly use `yarn` for our local development, you’ll also see a `yarn.lock` file on the project.
- `postcss.config.js`: This is where the styling magic happens, here you can add any postCSS plugin that you fancy, we’re currently only using these at the moment: - TailwindCSS: obviously - [postcss-nested](https://github.com/postcss/postcss-nested): To mimic SCSS nesting - [autoprefixer](https://github.com/postcss/autoprefixer): To support old browsers - [postcss-clean](https://github.com/leodido/postcss-clean): To minify our CSS on production
- `tailwind.config.js`: The project’s tailwind config, here you will find our custom classes and tailwind plugin’s config.

Everything else are the HTML templates.

## Want To Get To Know Me?

You can check out my social media
- [Instagram](https://instagram.com/ibrahimsyafiq15/)
- [Linkedin](https://www.linkedin.com/in/ibrahimsyafiq15/)
- [Behance](https://behance.com/ibrahimsyafiq15)
- [Dribbble](https://dribbble.com/ibrahimsyafiq15)
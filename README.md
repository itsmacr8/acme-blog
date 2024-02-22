# Blog Acme

This is a simple and elegant blog website. It features a responsive design, a homepage, a blog page, and an article page. It also showcases some reusable components such as a header, a footer, and a card. You can see a live demo of the app [here](https://blog-acme.netlify.app/)

## Technologies

This project is built with [vite](https://vitejs.dev/) and uses the following technologies:

- HTML for the structure and content of the website
- SCSS for the styling and layout of the website
- TypeScript for the logic and functionality of the website
- Vite for module bundler
- Netlify for deployment

## Project structure

The project folder contains the following files and folders:

- `public:` This folder contains the static assets such as images and favicon.
- `src:` This folder contains the source code of the website such as the SCSS files and the TypeScript files.
- `index.html:` This file contains the HTML content for the homepage.
- `blog.html:` This file contains the HTML content for the blog page.
- `article.html:` This file contains the HTML content for the article page.
- `README.md:` This file contains the documentation for this project.
- `LICENSE:` This file contains the MIT license for this project.
- `package.json:` This file contains the information about the project and the scripts.
- `package-lock.json:` This file contains the information about the installed packages and their versions.
- `tsconfig.json:` This file contains the configuration for TypeScript.
- `vite.config.js:` This file contains the configuration for vite.
- `.gitignore:` This file specifies the files and folders that are ignored by git.

## Installation

To run the project locally, you need to have [Node.js](https://nodejs.org/) installed on your machine.

- Clone the project repository:

```sh
git clone https://github.com/itsmacr8/acme-blog.git
```

- Navigate to the project directory

```sh
cd acme-blog
```

- Install the dependencies:

```sh
npm install
```

## Usage

To start the development server, run the following command. This will open the web application in your default browser at http://localhost:5173/

```sh
npm run dev
```

To build the production bundle, run the following command. This will create a dist folder with the minified and optimized files for deployment.

```sh
npm run build
```

To preview the project for production, run the following command and to preview the website open http://localhost:4173/

```sh
npm run preview
```

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

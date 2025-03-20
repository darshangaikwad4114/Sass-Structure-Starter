# Sass Structure Starter

![Landing Page](/public/landing-page.png)

## Tech Stack
- Vite
- Sass

## Description
Sass Structure Starter is a project template designed to help developers quickly set up a well-structured Sass project. It provides a clear folder structure and essential configurations to streamline the development process. This project aims to solve the problem of disorganized stylesheets by promoting a modular and maintainable approach to writing Sass.

## Key Features
- Organized folder structure for Sass files
- Pre-configured with Vite for fast development
- Includes common Sass utilities and mixins
- Easy to extend and customize

## Folder structure

```bash
sass/
├── abstracts/
│   ├── _variables.scss
│   ├── _mixins.scss
│   ├── _functions.scss
│   ├── _placeholders.scss
│   ├── _index.scss
├── base/
│   ├── _root.scss
│   ├── _reset.scss
│   ├── _global.scss
│   ├── _index.scss
├── pages/
│   ├── _home.scss
│   ├── _about.scss
│   ├── _index.scss
├── layouts/
│   ├── _header.scss
│   ├── _footer.scss
│   ├── _grid.scss
│   ├── _index.scss
├── components/
│   ├── _buttons.scss
│   ├── _card.scss
│   ├── _index.scss
├── utilities/
│   ├── _accessibility.scss
│   ├── _helpers.scss
│   ├── _shame.scss
│   ├── _index.scss
├── style.scss
```

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd sass-Structure-Starter
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Run the development server:
   ```bash
   npm run dev
   ```

## Usage

Once the project is set up and the development server is running, you can start developing your Sass styles. The project is pre-configured with a modular folder structure to help you organize your stylesheets efficiently. Simply add your styles to the appropriate files and folders within the `sass/` directory.

# tailwind-post-scss-template
A basic tailwindcss + PostCSS + node-sass template.

<p align="center">
    <a href="https://github.com/TitusKirch/tailwind-post-scss-template/actions"><img src="https://github.com/TitusKirch/tailwind-post-scss-template/workflows/Build/badge.svg" alt="Build action status"></a>
    <a href="https://github.com/TitusKirch/tailwind-post-scss-template/blob/master/LICENSE"><img src="https://img.shields.io/github/license/TitusKirch/tailwind-post-scss-template?label=License&labelColor=30363D&color=2FBF50" alt="License"></a>
    <a href="https://packagist.org/packages/tituskirch/tailwind-post-scss-template"><img src="https://img.shields.io/packagist/dm/tituskirch/tailwind-post-scss-template?label=Downloads&labelColor=30363D&color=2FBF50" alt="Packagist Downloads"></a>
    <a href="https://github.com/TitusKirch/tailwind-post-scss-template/graphs/contributors"><img src="https://img.shields.io/github/contributors/TitusKirch/tailwind-post-scss-template?label=Contributors&labelColor=30363D&color=2FBF50" alt="Contributors"></a>
    <a href="https://discord.tkirch.dev"><img src="https://img.shields.io/discord/576562577769889805?label=Discord&labelColor=30363D&color=2FBF50&logoColor=959DA5&logo=Discord" alt="Discord"></a>
</p>

## Table of contents

* [About the project](#about-the-project)
* [Getting Started](#getting-started)
* [Howto](#howto)
* [Contributing](#contributing)
* [Versioning](#versioning)
* [Built With](#built-with)
* [Authors](#authors)
* [License](#license)

## About the project

This project is a very simple template to start with a tailwindcss project (including SCSS compiler).

## Getting started
First you have to install npm. [Installation instructions](https://www.npmjs.com/get-npm)
Than you have to install composer. [Installation instructions](https://getcomposer.org/download/)

Require the project.
```BASH
composer require tituskirch/tailwind-post-scss-template
```

Now install all required resources.
```BASH
composer install
npm install
```

Ready! Now you can start with your project.

## Howto
To convert your SCSS code under /scss/app.scss to CSS code use the following command.
```BASH
npm run build
```

Afterwards your CSS code is created under /public/css/app.css.

Alternatively you can also use the following command.
```BASH
npm run watch
```

This will execute `npm run build` after each change.

## Contributing
There are many ways to help this open source project. Write tutorials, improve documentation, share bugs with others, make feature requests, or just write code. We look forward to every contribution.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For available versions, see the [tags on this repository](https://github.com/TitusKirch/tailwind-post-scss-template/tags).

## Built with

* [node-sass](https://github.com/sass/node-sass) - Node.js bindings to libsass
* [nodemon](https://github.com/remy/nodemon/) - Monitor for any changes in your node.js application and automatically restart the server - perfect for development
* [PostCSS CLI](https://github.com/postcss/postcss-cli) - CLI for postcss
* [postcss-import](https://github.com/postcss/postcss-import) - PostCSS plugin to inline @import rules content
* [tailwindcss](https://github.com/tailwindcss/tailwindcss/) - A utility-first CSS framework for rapid UI development.

## Authors

* **Titus Kirch** - *Main development* - [TitusKirch](https://github.com/TitusKirch)

See also the list of [contributors](https://github.com/TitusKirch/tailwind-post-scss-template/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


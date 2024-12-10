<span style="font-size: 10px;">Developed by:</span>
# <a href="https://www.fuerzastudio.com"><img src="https://www.fuerzastudio.com.br/wp-content/themes/fuerza/resources/img/logo.png" height="79" alt="Fuerza Studio Logo"/></a>

# Fuerza Starter Elementor

## Summary

- [Documentation](#documentation)
- [Requirements](#requirements)
- [Local environment](#setup-local-environment)
- [Development patterns](#development-patterns)

## Documentation
Our theme core is based on Elementor Pro, a powerful page builder for WordPress. To learn more about Elementor Pro and its features, take a look at the official documentation:

- [Elementor Help Center](https://elementor.com/help/)
- [Getting Started with Elementor](https://elementor.com/getting-started/)

## Requirements

- [PHP](http://php.net/) >= 8.1
- [WordPress](https://wordpress.org/) >= 5.0
- [Composer](https://getcomposer.org/) >= 2.0

## Setup local environment
Let's run the project locally! 🚀 <br/>
Follow the steps below to take up and running a local environment.

1. (Of course) - Clone this repository;
2. Inside root folder: `composer install`;
4. Create a new WordPress installation (for internal reasons we recommend that you create with: .local, .test or .loc; ended URL);
5. Activate the ACF, Elementor and Elementor PRO plugins;
6. Done!

## Development patterns
Before publish the website our default branch is setted to `develop`.
While developing make sure that you're following the [Branch naming and Commits conventions](https://outline.fuerzastudio.com/doc/instrucoes-do-git-GNUD47SZUM).
When working with PHP also make sure that you're applying the [WordPress Coding Standards](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/) (whenever possible) and always using [SOLID and CALISTHENICS](https://pt.slideshare.net/guilhermeblanco/php-para-adultos-clean-code-e-object-calisthenics) code.

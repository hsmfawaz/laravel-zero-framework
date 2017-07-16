Laravel Zero Framework
================

Laravel Zero was created by, and is maintained by [Nuno Maduro](https://github.com/nunomaduro), and is a micro-framework that provides an elegant starting point for your next console application.

> **Note:** This repository contains the core code of the Laravel Zero framework. If you want to build an application using Laravel Zero, visit the main [Laravel Zero repository](https://github.com/nunomaduro/laravel-zero).

<p align="center">
  <a href="https://styleci.io/repos/96572957"><img src="https://styleci.io/repos/96572957/shield" alt="StyleCI Status"></img></a>
  <a href="https://travis-ci.org/nunomaduro/zero-framework"><img src="https://img.shields.io/travis/nunomaduro/zero-framework/stable.svg?style=flat-square" alt="Build Status"></img></a>
  <a href="https://scrutinizer-ci.com/g/nunomaduro/zero-framework"><img src="https://img.shields.io/scrutinizer/g/nunomaduro/zero-framework.svg?style=flat-square" alt="Quality Score"></img></a>
  <a href="https://packagist.org/packages/nunomaduro/zero-framework"><img src="https://poser.pugx.org/nunomaduro/zero-framework/v/stable.svg" alt="Latest Stable Version"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square" alt="Software License"></img></a>
</p>

- Build on top of the [Laravel 5](http://laravel.com) components.
- Built with [PHP 7](http://php.net) using modern coding standards.
- Ships with a [standalone compiler](#build-an-standalone).
- Automatic Dependency Injection on commands and support of [Laravel 5](http://laravel.com) Service Providers.
- Supports [desktop notifications](https://github.com/nunomaduro/laravel-zero) on Linux, Windows or MacOS.

<p align="center">
    <img title="Terminal icon" src="https://raw.githubusercontent.com/nunomaduro/laravel-zero-docs/master/images/logo.png" />
</p>

Feel free to check out the [change log](CHANGELOG.md), [releases](nunomaduro/laravel-zero/releases), [license](LICENSE), and [contribution guidelines](CONTRIBUTING.md).

## Installation

[PHP](https://php.net) 7.1+

To get the latest version of Laravel Zero, simply create a new project using [Composer](https://getcomposer.org):

```bash
$ composer create-project --prefer-dist nunomaduro/laravel-zero <application-name>
```

<p align="center">
    <img title="Installation" src="https://raw.githubusercontent.com/nunomaduro/laravel-zero-docs/master/images/install.gif" />
</p>

<a name="usage"></a>
## Usage

Laravel Zero provides a default command placed in app/DefaultCommand.php.

You may review the documentation of the Artisan Console component [on Laravel Official Website](https://laravel.com/docs/5.4/artisan).

<p align="center">
    <img title="Installation" src="https://raw.githubusercontent.com/nunomaduro/laravel-zero-docs/master/images/commands.gif" />
</p>

<a name="build-an-standalone"></a>
## Build an standalone

Your Laravel Zero project, by default, allows you to build an standalone application.

```sh
$ php application build <name>
```

The build will provide you can a single executable, ready to use, of your application.

## Git branching model

The git branching model used for development is the one described and assisted by `twgit` tool: [https://github.com/Twenga/twgit](https://github.com/Twenga/twgit).

## Stay In Touch

For latest releases and announcements, follow on Twitter: [@enunomaduro](https://twitter.com/enunomaduro)

## Credits

This project uses code from several open source packages.

- [Laravel](https://laravel.com)
- [Symfony](http://symfony.com)
- [JoliNotif - Send notifications to your desktop](https://github.com/jolicode/JoliNotif)

## License

Laravel Zero is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

Copyright (c) 2017-2017 Nuno Maduro

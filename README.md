Laravel PackMe
=================

#### Tests are on the go but this tool works ;)

[![Build Status](https://travis-ci.org/ptondereau/laravel-packme.svg?branch=master)](https://travis-ci.org/ptondereau/laravel-packme)
[![StyleCI](https://styleci.io/repos/61112074/shield)](https://styleci.io/repos/61112074)

Laravel PackMe is a project starter pack which combine all basic stuff (src, tests) in order to develop a package for Laravel 5.*. It takes care about tests and best pratices I gathered over some cool repository. With one command line, you are ready to develop a package in good condition. It works like Laravel installer.

Most of this repository's common practices comes from [Graham Campbell](https://github.com/GrahamCampbell). You should follow him!


Laravel PackMe was created by, and is maintained by [Pierre Tondereau](https://github.com/ptondereau). It utilises my [Laravel TestBench](https://github.com/GrahamCampbell/Laravel-TestBench) package. Feel free to check out the [change log](CHANGELOG.md), [releases](https://github.com/ptondereau/laravel-packme/releases), [license](LICENSE), and [contribution guidelines](CONTRIBUTING.md).

## Installation

Either [PHP](https://php.net) 5.5+ or [HHVM](http://hhvm.com) 3.6+ are required.

To get the latest version of Laravel PackMe, simply require the project using [Composer](https://getcomposer.org):

```bash
$ composer global require ptondereau/laravel-packme
```

## Usage

```bash
$ packme create my-package
```

This will prompt to you so question and it will create a folder `my-package/` with all prepared files. Such as laravel installer. You should review `composer.json`, `README.md` and `LICENSE`.

##### Further Information

There are other classes in this package that are not documented here. This is because they are not intended for public use and are used internally by this package.

## License

Laravel PackMe is licensed under [The MIT License (MIT)](LICENSE).

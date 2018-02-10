# TYPO3 Development Collection
A collection of TYPO3 extensions and PHP tools to support TYPO3 development.

More specific it is meant to help you build sites powered by TYPO3.

## How?
This is a [composer meta package](https://getcomposer.org/doc/04-schema.md#type) and depends on other composer packages[^1](#packages). Thereby you only need to include this package and the other tools are automatically included in your project:
```
composer require --dev jdoubleu/typo3-development-collection
```

## Packages
The following TYPO3 extensions and PHP tools are included:
* [`georgringer/backend_debug`](https://github.com/georgringer/backend_debug) shows TCA field names next to the field title, so far.
* [`namelesscoder/typo3-cms-fluid-precompiler-module`](https://github.com/NamelessCoder/typo3-cms-fluid-precompiler-module) provides a backend module to precompiles Fluid templates.
* [`portrino/typo3-whoops`](portrino/typo3-whoops) integrates the [Whoops Exception Handler](https://github.com/filp/whoops) into TYPO3 to nicely display exceptions and errors.
* [`friendsofphp/php-cs-fixer`](https://github.com/FriendsOfPHP/PHP-CS-Fixer) changes your php code to fulfill a given code standard, it can also be used for PHP code linting.
* [`nimut/testing-framework`](https://github.com/nimut/testing-framework), a framework for testing in TYPO3.

### Configuration
Some packages need to be configured in your project to work properly or at all.
Please checkout their documentations.
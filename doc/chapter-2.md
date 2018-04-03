# Generator

`EasyAdminPlus` is packaged with a generator which create the default [EasyAdmin](https://symfony.com/doc/current/bundles/EasyAdminBundle/book/configuration-reference.html) configuration file based on your `Entities` reflection.

### Intro

:exclamation: The purpose of this generator is not to write all the configuration for you but to get rid of the tedious writing time of the settings if you've many entities.

**Up to you to enrich these settings by yourself after the complete generation.**

 Generator tries to guess to correct type based on several reflection processes:
 * PHP typehinting
 * Doctrine types
 * Annotations
 * Asserts

### Todo

:exclamation: Write the doc [@kasou](https://github.com/kasou)

### Type Guessing
* Doctrine match
  * 
* EA match
  * 


### Supported 3rd party vendors

* VichUploaderBundle
* StofDoctrineExtensionsBundle

----------

Next chapter: [Chapter 3 - Translation Action](chapter-3.md)
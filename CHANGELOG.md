# Changelog

All notable changes to `laravel-database-mail-templates` will be documented in this file

## 3.2.0 - 2019-09-04

- add support for Laravel 6.0

## 3.1.1 - 2019-05-09

- allow html to be rendered in blade templates

## 3.1.0 - 2019-02-27

- Drop support for Laravel 5.7 and lower
- Drop support for PHP 7.1 and lower

## 3.0.1 - 2019-02-27

- Add support for Laravel 5.8

## 3.0.0 - 2019-02-04

- Add support for text mails (#10)
- Fix issues when using the package with Laravel Nova (#9)

The interface and table structure have been changed in this version. Please read the notes in `UPGRADING.md`

## 2.0.0 - 2018-11-19

- Use an interface for the `MailTemplate` model

## 1.0.1 - 2018-10-25

- fix `MailTemplate::getVariables()` for models with missing/incorrect mailable classes

## 1.0.0 - 2018-10-18

- initial release

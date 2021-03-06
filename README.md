# PHP Desktop


Table of contents:
* [Introduction](#introduction)
* [Sponsors](#sponsors)
* [Fundings for new features](#fundings-for-new-features)
* [Downloads](#downloads)
* [Support](#support)
* [Support development](#support-development)


## Introduction

PHP Desktop is an open source project founded by [Czarek Tomczak](https://drive.google.com/file/d/17xmoT5Z_zTHkVclqPzrs2aAV64Uiu7fh/view)
(hire me!) in 2012 to provide a way for developing native 
desktop GUI applications using web technologies such as PHP, HTML5, JavaScript and SQLite. The development workflow 
you are used to while creating web applications remains the same. There is no new API/framework to learn. The process 
of turning an existing website into a desktop application is basically a matter of copying it to the "phpdesktop/www/" 
directory.

In a certain sense phpdesktop acts as a PHP to EXE compiler. It embeds a web browser, a multithreaded web server 
and a PHP interpreter. All embedded into a single application. The web server embedded is 
[Mongoose](https://en.wikipedia.org/wiki/Mongoose_(web_server)) (the MIT-licensed version). Supported browsers are
Internet Explorer and Google Chrome. The package with Chrome embedded has no external dependencies, everything 
is included in the phpdesktop binaries and works out of the box on a user's computer. PHP Desktop actually embeds Chromium browser (using [Chromium Embedded Framework](https://bitbucket.org/chromiumembedded/cef) to be specific) which is open source software on which Google Chrome is based, but for the sake of simplicity we just call it Chrome or Google Chrome.

All popular PHP frameworks are supported, see the [PHP frameworks support](../../wiki/PHP-frameworks-support) wiki page 
for example configurations for CakePHP, CodeIgniter, Laravel, Symfony, Yii and Zend Framework.  You can create 
a standalone executable for distribution with the help of the 
[Inno Setup installer](../../wiki/Knowledge-Base#application-installer). PHP sources can be protected with the many
of the available [PHP encoders](../../wiki/Knowledge-Base#how-do-i-protect-php-sources-in-the-www-directory).
PHP Desktop is released under non-restrictive license, thus it is 
[free for commercial use](../../wiki/Knowledge-Base#can-i-use-php-desktop-in-a-commercial-closed-sourced-project).

It is one of the top goals for PHP Desktop to be stable, to work reliably. PHP Desktop does not suffer from memory leaks. 
PHP by design was never intended for running long hours/days, as desktop applications usually do. This is not a concern 
when using PHP Desktop, as it is running an internal web server and serving pages through CGI. So when PHP script ends 
execution PHP-CGI process is killed and all memory is always freed.

Lots of other useful information can be found on the [Knowledge Base](../../wiki/Knowledge-Base) wiki page and on the 
[PHP Desktop Forum](https://groups.google.com/d/forum/phpdesktop).


## Sponsors

The PHP Desktop project is seeking companies to help make the project great again. If your company would like to sponsor PHP Desktop development efforts then please contact [Czarek](https://drive.google.com/file/d/17xmoT5Z_zTHkVclqPzrs2aAV64Uiu7fh/view). Your company logo would appear here on the project's main page. Long term sponsorships are welcome. Czarek would love to spend more time on developing this project, but he can't afford doing so in his free time.


## Fundings for new features

Here is a list of ongoing fundings for new features in PHP Desktop Chrome:

Feature | Funds gathered | Issue
--- | --- | ---
Chrome v70 release for Windows | $0 of $2,000 | [Issue #227](https://github.com/cztomczak/phpdesktop/issues/227)
Initial Mac release | $150 of $2,000 | [Issue #208](https://github.com/cztomczak/phpdesktop/issues/208)
Initial Linux release | $1,500 of $1,500 | [Issue #221](https://github.com/cztomczak/phpdesktop/issues/221)

Fundings for other features presented on the
[PHP Desktop Pro](https://github.com/cztomczak/phpdesktop/wiki/PHP-Desktop-Pro)
wiki page are also possible.


## Downloads

  * PHP Desktop Chrome for Windows - go to the [Download Chrome](../../wiki/Download-Chrome) wiki page.
  * PHP Desktop for Linux - see the [linux-v70.0](https://github.com/cztomczak/phpdesktop/releases/tag/linux-v70.0) release
  * PHP Desktop MSIE (Internet Explorer) - go to the [Download MSIE](../../wiki/Download-MSIE) wiki page.

__New releases RSS/Atom feed__  
To be notified of new releases subscribe to this [Atom feed](https://github.com/cztomczak/phpdesktop/releases.atom).


## Support

* Documentation is on the [Wiki Pages](../../wiki). Start with the [Knowledge Base](../../wiki/Knowledge-Base), 
    [Settings](../../wiki/Settings) and [Chrome settings](../../wiki/Chrome-settings) wiki pages.
* Ask questions and report problems on the [PHP Desktop Forum](https://groups.google.com/d/forum/phpdesktop)
* Please do not create issues in the Issue Tracker
* See also this tutorial (externally maintained): [Create your first Desktop Application with PHP and PHP Desktop](http://phpocean.com/tutorials/design-and-illustration/create-your-first-desktop-application-with-php-and-php-desktop/4)


## Support development

If you would like to support PHP Desktop general development efforts by making a donation please click the Donate button below:

[![Donate](https://raw.githubusercontent.com/cztomczak/phpdesktop/master/var/donate.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=JQSTPDRRM8AQ8)

If you would like to see some feature implemented you can make a comment about that when making a donation. It will give it a higher priority.

For sponsorship opportunities please contact [Czarek](https://drive.google.com/file/d/17xmoT5Z_zTHkVclqPzrs2aAV64Uiu7fh/view).

Complete github statistics are available in this topic on the Forum: [[ANN] Call for sponsors](https://groups.google.com/d/topic/phpdesktop/1T7jictpJ5M/discussion).

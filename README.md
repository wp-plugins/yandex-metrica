# Yandex Metrica #

Contributors: [m_uysl](https://github.com/mustafauysal/)			
Tags: yandex,metrica,stats,statistics,tools,analytics,analytics tool,metrika	
Requires at least: 3.0		
Tested up to: 4.1.1	
Stable tag: 1.1.1	
License: GPLv2 (or later)	

Easy way to use Yandex Metrica in your WordPress site.

## Description ##

Best Metrica plugin for the using Yandex Metrica in your WordPress site.

### What is Metrica ###

Metrica is an analytics tool like as google analytics.If you didn't hear metrica yet, you can [check official metrica](http://metrica.yandex.com/) page.


### Features ###

- Easy to manage counter's  tracking options.
- Role based user tracking
- Dashboard widget that displaying metrica graphic, summary of site usage, top pages etc..
- Role based user access for the displaying dashboard widget
- Basic mode ready! If you don't want to give API access, you can try basic mode.
- i18n support: Completely translation ready!


### Translations ###

* English (en\_US), built-in
* Turkish (tr\_TR), native support

## Installation ##

Extract the zip file and just drop the contents in the `wp-content/plugins/` directory of your WordPress installation and then activate the Plugin from admin's Plugins page.

## Frequently Asked Questions ##

* What is metrica?
 - Metrica is a powerful analytics tool that provided by Yandex.
* Is it free?
 - Definitely, metrica service and this plugin totally  free.
* Can I see statistics on the WordPress dashboard?
	- Yes, version 1.0 or higher versions support dashboard widget. But you need to use advanced mode. (Because this feature needs API access)
* I can see dashboard widget but no graph?
	- If your counter hasn't any visitors or visits value it could be empty, but probably your counter not working correctly, Check counter status from official metrica site.
* Localization issue?
	- Yandex Metrica plugin is using native WordPress localization of the some piece of code. For example date, user roles etc...
*	Everything done, but metrica service doesn't work for me?
	- Yandex Metrica plugin uses wp_footer hook for the adds necessary trancking code. Please, check your theme has wp_footer hook?
	
## Screenshots ##

1. Select mode, basic mode for who don't want to use metrica api. But advanced mode recommended!
2. Displaying graph with metrica results.
3. Settings page.

## Changelog ##

#### 1.1.1 ####
 - Dashboard widget daily order fixed
 
### 1.1 ###
 - Dashboard widget UI improvements
 - Bug fixes

#### 1.0.2 ####
 - Capability checking before display temporary dashboard widget
 
#### 1.0.1 ####
 - Closure function removed
 - Typo fix
 
### 1.0 ###
 - Metrica API integration
 - Backward compatibility mode
 - Tracking by user role
 - Dashboard widget
 - New widget, informer widget still exist
 - Better localization
 - Performance improvements
 - Special thanks to Yandex Team for all support.

#### 0.1.3 ####

 - Minor bug fixes
 
#### 0.1.2 ####

 - Bug fix - about options

#### 0.1.1 ####

 - bug fix - header output

#### 0.1 ####

 - Initial release.

## Upgrade Notice ##

### 1.0 ###

Including major changes, recommended update!

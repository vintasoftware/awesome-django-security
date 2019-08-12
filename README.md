
<br/>
<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

_List inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing._

Supported by: [Vinta Software](https://www.vinta.com.br)
</div>
<br/>

# Awesome Django Security

A collection of Django security-related tools and topics. If you are concerned about security and use django for productivity, this can be of help.

If you'd like to __contribute__ to this list, simply open a PR with your additions.

Maintained by [@tcostam](https://twitter.com/tcostam). If you have contributions but don't have the time, give me a shout at twitter

Table of Contents
=================

   * [Libs](#libs)
      * [MFA](#mfa)
      * [Session Management](#session-management)
      * [Permissions Management](#permissions-management)
      * [Honeypots](#honeypots)
      * [Cryptography](#cryptography)
      * [Storage](#storage)
      * [Other](#other)
   * [Tools](#tools)
   * [Vulnerabilities](#vulnerabilities)
   * [Guidelines](#guidelines)
   * [Documentation](#documentation)
   * [Courses](#courses)
   * [Talks](#talks)
   * [Articles](#articles)

## Libs

### MFA

* [Django Secure Auth](https://github.com/gotlium/django-secure-auth): Secure authentication by TOTP, SMS, Codes & Question. Login protected by IP ranges and with captcha
* [Django MFA2](https://github.com/mkalioby/django-mfa2): A Django app that handles MFA, it supports TOTP, U2F, FIDO2 U2F (Webauthn), Email Token and Trusted Devices
* [Django Two Factor Auth](https://github.com/Bouke/django-two-factor-auth): Django Two Factor Auth: Complete Two-Factor Authentication for Django providing the easiest integration into most Django projects


### Session management

* [Django Defender](https://github.com/kencochrane/django-defender): A simple super fast django reusable app that blocks people from brute forcing login attempts
* [Django Axes](https://github.com/jazzband/django-axes): Keep track of failed login attempts in Django-powered sites
* [Django Registration](https://github.com/ubernostrum/django-registration): django-registration is an extensible application providing user registration functionality for Django-powered Web sites
* [Django Session Activity](https://github.com/nigma/django-session-activity): List recent account activity and sign-out from all sessions opened on other computers
* [Django Restricted Sessions](https://github.com/mxsasha/django-restricted-sessions): Restrict Django sessions to IP and/or user agent
* [Django Ratelimit Backend](https://github.com/brutasse/django-ratelimit-backend): Rate-limit your login attempts at the authentication backend level
* [Django Session Security](https://github.com/yourlabs/django-session-security): Django Session Security: user's page activity monitoring for logging him out
* [Django Simple Captcha](https://github.com/mbi/django-simple-captcha)

### Permissions management

* [DjangoRestFramework Api Key](https://github.com/florimondmanca/djangorestframework-api-key): API key permissions for the Django REST Framework
* [Django Rules](https://github.com/maraujop/django-rules): flexible and scalable Django authorization backend for unified per object permission management
* [Django Rules](https://github.com/dfunckt/django-rules): provides object-level permissions to Django, without requiring a database
* [Django Role Permissions](https://github.com/vintasoftware/django-role-permissions): A django app for role based permissions
* [Dry Rest Permissions](https://github.com/dbkaplan/dry-rest-permissions): Dry Rest Permissions: Rules based permissions for the Django Rest Framework
* [Django Guardian](https://github.com/django-guardian/django-guardian): implementation of per-object permissions on top of Django's authorization backend.
* [Django Authority](https://github.com/jazzband/django-authority): A Django app that provides generic per-object-permissions for Django's auth app and helpers to create custom permission checks
* [Django Permission](https://github.com/lambdalisue/django-permission): An enhanced permission system which support object permission in Django
* [Django Rulez](https://github.com/chrisglass/django-rulez): A lean and mean object-level rules system for the Django framework

### Honeypots

* [Django Admin Honeypot](https://github.com/dmpayton/django-admin-honeypot): django-admin-honeypot is a fake Django admin login screen to log and notify admins of attempted unauthorized access
* [Django Honeypot](https://github.com/jamesturk/django-honeypot): Django Honeypot: Generic honeypot utilities for use in django projects

### Cryptography

* [Django Cryptography](https://github.com/georgemarshall/django-cryptography): Easily encrypt data in Django

### Storage

* [Django Safe Filefield](https://github.com/mixkorshun/django-safe-filefield): Secure file field, which allows you to restrict uploaded file extensions
* [Django Random Filestorage](https://github.com/mxsasha/django-random-filestorage): Django storage class that assigns random filenames to all stored files

### Other

* [Django Security](https://github.com/sdelements/django-security): A collection of models, views, middlewares, and forms to help secure a Django project.
* [Django Sudo](https://github.com/mattrobenolt/django-sudo): Extra security for your sensitive pages
* [Django Impersonate](https://bitbucket.org/petersanchez/django-impersonate/): Simple app to allow superusers to login as other (non-superuser) accounts via a quick user switch process
* [Wemake Django Template](https://github.com/wemake-services/wemake-django-template): Bleeding edge django template focused on code quality and security
* [Django SSLify](https://github.com/rdegges/django-sslify/): Force SSL on your Django site
* [Django Stronghold](https://github.com/mgrouchy/django-stronghold/): Make all your Django views default login_required
* [Django Lockdown](https://github.com/Dunedan/django-lockdown): Django Lockdown: Lock down a Django site or individual views, with configurable preview authorization
* [Impostor](https://github.com/samastur/Impostor): Django app that enables staff to log in as other users using their own credentials
* [Django Primate](https://github.com/sorl/django-primate): A Modular Django User
* [Django HTML Sanitizer](https://github.com/ui/django-html_sanitizer): A set of HTML input sanitization or cleaning utilities for django models, forms and templates
* [Django Rules Light](https://github.com/yourlabs/django-rules-light): This is a simple alternative to django-rules. The core difference is that it uses as registry that can be modified on runtime, instead of database models.
* [Django Inspectional Registration](https://github.com/lambdalisue/django-inspectional-registration): Django registration app with Inspection before activation
* [Django Mongo Auth](https://github.com/mitar/django-mongo-auth): Django authentication based on an extensible MongoEngine user class
* [HTML Sanitizer](https://github.com/matthiask/html-sanitizer): Allowlist-based HTML cleaner
* [Bleach](https://github.com/mozilla/bleach): Bleach is an allowed-list-based HTML sanitizing library that escapes or strips markup and attributes

## Tools

* [Django Trawler](https://bitbucket.org/onelson/django-trawler/src/default/): This app is used to send out phishing emails and collect data on which recipients acted on them
* [Pony Checkup](https://www.ponycheckup.com/): basic automated security checkup for Django websites
* [SSL Checker](https://www.sslshopper.com/ssl-checker.html): diagnose problems with your SSL certificate installation
* [Safety](https://pyup.io/safety/): check your dependencies for known security vulnerabilities
* [Mozilla Observatory](https://observatory.mozilla.org): The Mozilla Observatory is a set of tools to analyze your website and inform you if you are utilizing the many available methods to secure it.
* [Snyk](https://snyk.io): CLI and build-time tool to find & fix known vulnerabilities in open-source dependencies 

## Vulnerabilities

* [Django Debreach](https://github.com/lpomfrey/django-debreach/): Basic/extra mitigation against the BREACH attack for Django projects
* [Django CVEs](https://www.cvedetails.com/vulnerability-list/vendor_id-10199/product_id-18211/Djangoproject-Django.html)
* [Django: CVE-2019-12308 AdminURLFieldWidget XSS (plus patched bundled jQuery for CVE-2019-11358)](https://seclists.org/oss-sec/2019/q2/138)

## Guidelines

* [Django Security Tips](https://github.com/sellonen/django-security-tips): Learn and promote secure system administration tips and practices in the Django community
* [OWASP Python Security Project](http://www.pythonsecurity.org/)

## Documentation

* [Django Docs: Security in Django](https://docs.djangoproject.com/en/2.2/topics/security/)
* [Django Packages: Security](https://djangopackages.org/grids/g/security/)
* [Deployment checklist](https://docs.djangoproject.com/en/2.2/howto/deployment/checklist/)
* [Mozilla's tutorial on Django web application security](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/web_application_security)

## Courses

* [Learn the secrets to defensive programming in Python and Django](https://www.synopsys.com/blogs/software-security/defensive-programming-python-django/)

## Talks

* [Terri Oda - Python Security Tools - PyCon 2019](https://www.youtube.com/watch?v=e7zzdl8OXCU)

## Articles

* [What You Need to Know to Manage Users in Django Admin](https://realpython.com/manage-users-in-django-admin/)
* [MDN - Django web application security](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/web_application_security)
* [Protect Your Django Web Application From Security Threats](https://dzone.com/articles/protect-your-django-web-application-from-security-1)
* [10 tips for making the Django Admin more secure](https://opensource.com/article/18/1/10-tips-making-django-admin-more-secure)
* [Tips and Tools for Securing Django](https://www.laurencegellert.com/2019/01/tips-and-tools-for-securing-django/)
* [Django in the wild: tips for deployment survival](https://medium.freecodecamp.org/django-in-the-wild-tips-for-deployment-survival-9b491081c2e4)
* [Django Web Application Security](https://pt.slideshare.net/levigross/django-web-application-security)
* [Django in the real world](https://pt.slideshare.net/jacobian/django-in-the-real-world/)
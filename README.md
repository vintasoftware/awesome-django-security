# awesome-django-security

A collection of Django security-related tools and topics. If you are concerned about security and use django for productivity, this can be of help.

If you'd like to contribute to this list, simply open a PR with your additions.

If you have contributions but don't have the time, give me a shout at twitter ([@tcostam](https://twitter.com/tcostam))

Table of Contents
=================

   * [Libs](#libs)
      * [MFA](#mfa)
      * [Session Management](#session-management)
      * [Permissions Management](#permissions-management)
      * [Other](#other)
   * [Tools](#tools)
   * [Vulnerabilities](#vulnerabilities)
   * [Documentation](#documentation)
   * [Courses](#courses)
   * [Articles](#articles)

## Libs

### MFA

* https://github.com/gotlium/django-secure-auth Secure authentication by TOTP, SMS, Codes & Question. Login protected by IP ranges and with captcha
* https://github.com/mkalioby/django-mfa2 A Django app that handles MFA, it supports TOTP, U2F, FIDO2 U2F (Webauthn), Email Token and Trusted Devices
* https://github.com/Bouke/django-two-factor-auth Django Two Factor Auth: Complete Two-Factor Authentication for Django providing the easiest integration into most Django projects


### Session management

* https://github.com/kencochrane/django-defender A simple super fast django reusable app that blocks people from brute forcing login attempts
* https://github.com/jazzband/django-axes Django Axes: Keep track of failed login attempts in Django-powered sites
* https://github.com/ubernostrum/django-registration django-registration is an extensible application providing user registration functionality for Django-powered Web sites
* https://github.com/nigma/django-session-activity List recent account activity and sign-out from all sessions opened on other computers
* https://github.com/mxsasha/django-restricted-sessions Restrict Django sessions to IP and/or user agent
* https://github.com/brutasse/django-ratelimit-backend Rate-limit your login attempts at the authentication backend level
* https://github.com/yourlabs/django-session-security Django Session Security: user's page activity monitoring for logging him out
* https://github.com/mbi/django-simple-captcha Django Simple Captcha

### Permissions management

* https://github.com/florimondmanca/djangorestframework-api-key API key permissions for the Django REST Framework
* https://github.com/maraujop/django-rules Django Rules: flexible and scalable Django authorization backend for unified per object permission management
* https://github.com/dfunckt/django-rules Django Rules: provides object-level permissions to Django, without requiring a database
* https://github.com/dbkaplan/dry-rest-permissions Dry Rest Permissions: Rules based permissions for the Django Rest Framework
* https://github.com/django-guardian/django-guardian Django Guardian: implementation of per-object permissions on top of Django's authorization backend.
* https://github.com/jazzband/django-authority Django Authority: A Django app that provides generic per-object-permissions for Django's auth app and helpers to create custom permission checks
* https://github.com/lambdalisue/django-permission Django Permission: An enhanced permission system which support object permission in Django
* https://github.com/chrisglass/django-rulez Django Rulez: A lean and mean object-level rules system for the Django framework

### Other

* https://github.com/sdelements/django-security Django Security: A collection of models, views, middlewares, and forms to help secure a Django project.
* https://github.com/dmpayton/django-admin-honeypot django-admin-honeypot is a fake Django admin login screen to log and notify admins of attempted unauthorized access
* https://github.com/jamesturk/django-honeypot Django Honeypot: Generic honeypot utilities for use in django projects
* https://github.com/mattrobenolt/django-sudo Django Sudo: Extra security for your sensitive pages
* https://bitbucket.org/petersanchez/django-impersonate/ Simple app to allow superusers to login as other (non-superuser) accounts via a quick user switch process
* https://github.com/wemake-services/wemake-django-template Bleeding edge django template focused on code quality and security
* https://github.com/rdegges/django-sslify/ Force SSL on your Django site
* https://github.com/mgrouchy/django-stronghold/ Make all your Django views default login_required
* https://github.com/Dunedan/django-lockdown Django Lockdown: Lock down a Django site or individual views, with configurable preview authorization
* https://github.com/samastur/Impostor Impostor: Django app that enables staff to log in as other users using their own credentials
* https://github.com/georgemarshall/django-cryptography Django Cryptography: Easily encrypt data in Django
* https://github.com/sorl/django-primate Django Primate: A Modular Django User
* https://github.com/ui/django-html_sanitizer A set of HTML input sanitization or cleaning utilities for django models, forms and templates
* https://github.com/yourlabs/django-rules-light This is a simple alternative to django-rules. The core difference is that it uses as registry that can be modified on runtime, instead of database models.
* https://github.com/lambdalisue/django-inspectional-registration Django registration app with Inspection before activation
* https://github.com/mixkorshun/django-safe-filefield Secure file field, which allows you to restrict uploaded file extensions
* https://github.com/mxsasha/django-random-filestorage Django storage class that assigns random filenames to all stored files
* https://github.com/mitar/django-mongo-auth Django authentication based on an extensible MongoEngine user class

## Tools

* https://bitbucket.org/onelson/django-trawler/src/default/ django-trawler: This app is used to send out phishing emails and collect data on which recipients acted on them
* https://www.ponycheckup.com/ basic automated security checkup for Django websites
* https://www.sslshopper.com/ssl-checker.html diagnose problems with your SSL certificate installation
* https://pyup.io/safety/ Safety: check your dependencies for known security vulnerabilities

## Vulnerabilities

* https://github.com/lpomfrey/django-debreach/ Basic/extra mitigation against the BREACH attack for Django projects
* https://www.cvedetails.com/vulnerability-list/vendor_id-10199/product_id-18211/Djangoproject-Django.html


## Documentation

* https://docs.djangoproject.com/en/2.2/topics/security/ Django Docs: Security in Django
* https://djangopackages.org/grids/g/security/ Django Packages: Security
* https://docs.djangoproject.com/en/2.2/howto/deployment/checklist/ Deployment checklist

## Courses

* https://www.synopsys.com/blogs/software-security/defensive-programming-python-django/ Learn the secrets to defensive programming in Python and Django

## Articles

* https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/web_application_security MDN - Django web application security
* https://dzone.com/articles/protect-your-django-web-application-from-security-1 Protect Your Django Web Application From Security Threats
* https://opensource.com/article/18/1/10-tips-making-django-admin-more-secure 10 tips for making the Django Admin more secure
* https://www.laurencegellert.com/2019/01/tips-and-tools-for-securing-django/ Tips and Tools for Securing Django
* https://medium.freecodecamp.org/django-in-the-wild-tips-for-deployment-survival-9b491081c2e4 Django in the wild: tips for deployment survival
* https://pt.slideshare.net/levigross/django-web-application-security Django Web Application Security
* https://pt.slideshare.net/jacobian/django-in-the-real-world/ Django in the real world
# Drupal Security
Resources, tips, howtos, and everything in between to secure your Drupal app.

Resources
---------
1. [Steps to a Drupal security review](http://crackingdrupal.com/node/71)
2. [Automated Security Review](http://crackingdrupal.com/node/70)
3. [Cracking Drupal](http://crackingdrupal.com/)
4. [Drupal Security Report](http://drupalsecurityreport.org/)
5. [Drupal Security Group](https://groups.drupal.org/security)
6. [Securing your site](https://www.drupal.org/security/secure-configuration)
7. [Enhancing security using contributed modules](https://www.drupal.org/node/382752)
8. [The 10 most critical Drupal security risks](http://www.cameronandwilding.com/blog/pablo/10-most-critical-drupal-security-risks)
9. [Doing Drupal Security Right](https://www.youtube.com/watch?v=FNCfavtz9vQ)
10. [How to Check Your Drupal Site Security](https://www.ostraining.com/blog/drupal/check-drupal-site-security/)
11. [How to Restore Your Hacked Site](https://modulesunraveled.com/blog/how-restore-your-hacked-site)
12. [Web Application Security Testing Cheat Sheet](https://www.owasp.org/index.php/Web_Application_Security_Testing_Cheat_Sheet)
13. [Handle text in a secure fashion](https://www.drupal.org/node/28984)

Modules
-------
1. [Paranoia](https://www.drupal.org/project/paranoia) - The Paranoia module attempts to identify all the places that a user can evaluate PHP via Drupal's web interface and then block those. It reduces the potential impact of an attacker gaining elevated permission on a Drupal site.
2. [Security Review](https://www.drupal.org/project/security_review) - The Security Review module automates testing for many of the easy-to-make mistakes that render your site insecure.
3. [Drupalgeddon](https://www.drupal.org/project/drupalgeddon) - Drupalgeddon (with an "L") checks for backdoors and other traces of known Drupal exploits of "Drupageddon" (no "L"), aka [SA-CORE-2014-005 SQL injection](https://www.drupal.org/SA-CORE-2014-005). Drupalgeddon is not a module; it's a Drush command.
4. [Hacked!](https://www.drupal.org/project/hacked) - This module scans the currently installed Drupal, contributed modules and themes, re-downloads them and determines if they have been changed.
5. [MD5 Check](https://www.drupal.org/project/md5check) - The MD5 Check generates a md5 checksum of all module files. If module is changed a critical security error is generated in watchdog log.
6. [File Integrity Check](https://www.drupal.org/project/file_integrity) - This module lets the site maintainer “fingerprint” an entire site (except the files below the public:// upload directory) when it is in an untainted state.
7. [Site Audit](https://www.drupal.org/project/site_audit) - Site Audit is a Drupal static site analysis platform that generates reports with actionable best practice recommendations.
8. [Security Kit](https://www.drupal.org/project/seckit) - SecKit provides Drupal with various security-hardening options. This lets your mitigate the risks of exploitation of different web application vulnerabilities.
9. [Unused Modules](https://www.drupal.org/project/unused_modules) - Not really for security but still good to have it here. This is a helper / development module that lists unused modules / projects that can be safely deleted. This makes your repository cleaner and your website faster.
10. [Login Security](https://www.drupal.org/project/login_security) - Login Security module improves the security options in the login operation of a Drupal site. With Login Security module, a site administrator may protect and restrict access by adding access control features to the login forms (default login form in /user and the block called "login form block").
11. [Flood Control](https://www.drupal.org/project/flood_control) - This project is intended to add an administration interface for hidden flood control variables in Drupal 7, like the login attempt limiters and any future hidden variables.
12. [Captcha](https://www.drupal.org/project/captcha) - A CAPTCHA is a challenge-response test most often placed within web forms to determine whether the user is human.
13. [Spamspan Filter](https://www.drupal.org/project/spamspan) - The SpamSpan module obfuscates email addresses to help prevent spambots from collecting them.
14. [ACL](https://www.drupal.org/project/acl) - The ACL module, short for Access Control Lists, is an API for other modules to create lists of users and give them access to nodes.
15. [Content Access](https://www.drupal.org/project/content_access) - This module allows you to manage permissions for content types by role and author. It allows you to specifiy custom view, edit and delete permissions for each content type. Optionally you can enable per content access settings, so you can customize the access for each content node.
16. [Lightweight Directory Access Protocol (LDAP)](https://www.drupal.org/project/ldap) - The Lightweight Directory Access Protocol (LDAP) project provides integration with LDAP for authentication, user provisioning, authorization, feeds, and views.
17. [Password Policy](https://www.drupal.org/project/password_policy) - This module provides a way to enforce restrictions on user passwords by defining password policies.
18. [Oauth](https://www.drupal.org/project/oauth) - This module implements the OAuth 1.0 standard for use with Drupal and acts as a support module for other modules that wish to use OAuth.
19. [Security Testing](https://www.drupal.org/project/securitytesting) - Security Testing is a tool for locating XSS, CSRF and SQL Injection vulnerabilities in Drupal contributed modules. This tool will scan the source code of contributed module(s) for vulnerabilities and display warnings.
20. [ClamAV](https://www.drupal.org/project/clamav) - Drupal integration with the ClamAV virus scanner. This module will verify that files uploaded to a site are not infected with a virus, and prevent infected files from being saved.
21. [Spambot](https://www.drupal.org/project/spambot) - Spambot protects the user registration form from spammers and spambots by verifying registration attempts against the [Stop Forum Spam](http://www.stopforumspam.com/) online database. It also adds some useful features to help deal with spam accounts.
22. [Honeypot](https://www.drupal.org/project/honeypot) - Honeypot uses both the honeypot and timestamp methods of deterring spam bots from completing forms on your Drupal site [read more here](http://www.midwesternmac.com/blogs/jeff-geerling/introducing-honeypot-form-spam). These methods are effective against many spam bots, and are not as intrusive as CAPTCHAs or other methods which punish the user [YouTube](http://www.youtube.com/watch?v=FPOezLL398U).
23. [Taxonomy Access Control](https://www.drupal.org/project/taxonomy_access) - Access control for user roles based on taxonomy categories (vocabulary, terms).
24. [reCaptcha](https://www.drupal.org/project/recaptcha) - Uses the Google [reCAPTCHA](https://www.google.com/recaptcha) web service to improve the [CAPTCHA](https://www.drupal.org/project/captcha) system and protect email addresses.
25. [Spamicide](https://www.drupal.org/project/spamicide) - The purpose of Spamicide is to prevent spam submission to any form on your Drupal web site. Spamicide adds an input field to each form then hides it with css, when spam bots fill in the field the form is discarded.

Standalone Applications
-----------------------
1. [Droopescan](https://github.com/droope/droopescan) - A plugin-based scanner that aids security researchers in identifying issues with several CMSs, mainly Drupal & Silverstripe.
2. [CMSmap](https://github.com/dionach/CMSmap) - CMSmap is a python open source CMS scanner that automates the process of detecting security flaws of the most popular CMSs.
3. [DPScan](https://github.com/maxousc59/Blue-Sky-Information-Security) - Note: No updates from the author. Drupal modules enumerator.

HowTo and Best Practices
------------------------
### Javascript
1. Avoiding unreachable code - The `eval()` function is evil and **SHOULD NOT** be used. The browser has to create an entirely new scripting environment (just like creating a new web page), import all variables from the current scope, execute the script, collect the result, and export the variables back into the original environment. Additionally, the code cannot be cached for optimization purposes. It is both the most powerful and most misused method in JavaScript. Note that JavaScript implicitly uses `eval()` for some other language constructs.
2. Preventing XSS - All output to the browser that has been provided by a user **SHOULD** be escaped through `Drupal.checkPlain()` first. This is similar to Drupal's PHP `check_plain()` and encodes special characters in a plain-text string for display as HTML.
3. String Translation - All strings in JavaScript files **SHOULD** be wrapped in `Drupal.t()`, which is an equivalent of the well-known `t()` function. Likewise, there is an equivalent to `format_plural()`, named `Drupal.formatPlural()`. Their parameter order is exactly like their server-side counterparts.

Source: *[JavaScript best practices](https://www.drupal.org/node/2297057)*

### Server-side
1. **Securing Your Site: Clickjacking and X-Frame-Options** - By default Drupal doesn't have support
   for `X-Frame-Options`. The `X-Frame-Options` HTTP response header can be used to indicate whether or not a browser should be allowed to render a page in a `<frame>`, `<iframe>` or `<object>` .
   Sites can use this to avoid clickjacking attacks, by ensuring that their content is not embedded into other sites.

  Possible values:

  **DENY**: When the `X-Frame-Options` http header is set to this value a page can never be
            embedded in a frame/iframe.<br>
  **SAMEORIGIN**: In this case only the originating domain can embed pages in a frame/iframe.
            This is specific to a domain including the subdomain. Pages on `foo.example.com` cannot
            embed pages from `bar.example.com` if this value is used.

  **Example**:<br>
  In Drupal: `drupal_add_http_header('X-Frame-Options', 'SAMEORIGIN');`<br>
  In Apache: `Header always append X-Frame-Options SAMEORIGIN`<br>
  In Nginx: `add_header X-Frame-Options SAMEORIGIN;`<br>
  In PHP: `header('X-Frame-Options: SAMEORIGIN');`

Credits
-------
1. [Greggles](https://www.drupal.org/u/greggles)
2. [Droope](https://github.com/droope)
3. Drupal community and contributors
4. [Dionach](https://www.dionach.com)
5. [Matt Farina](http://mattfarina.com/)


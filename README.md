Symfony certification guide
===========================

This is not an official guide, it's only a compilation of links extracted from the documentation based on the [Symfony Certification](http://sensiolabs.com/en/symfony/certification.html) page topics.

Even if you have no plans to take the Symfony certification exam, this list of resources may help you better understand the Symfony framework.

Feel free to fork and send a PR.

### **Topics**
---
#### **PHP**
- [ ] Object Oriented Programming  
  * http://www.php.net/manual/en/oop5.intro.php
- [ ] Namespaces  
  * http://www.php.net/manual/en/language.namespaces.php  
  * https://knpuniversity.com/screencast/php-namespaces-in-120-seconds/namespaces  
- [ ] Interfaces  
  * http://www.php.net/manual/en/language.oop5.interfaces.php
- [ ] Anonymous functions and closures  
  * http://www.php.net/manual/en/functions.anonymous.php
- [ ] Abstract classes  
  * http://www.php.net/manual/en/language.oop5.abstract.php

---

#### **HTTP**
- [ ] Client / Server interaction  
  * https://symfony.com/doc/3.0/introduction/http_fundamentals.html
- [ ] HTTP request  
  * https://symfony.com/doc/3.0/components/http_foundation.html#request
- [ ] HTTP response  
  * https://symfony.com/doc/3.0/components/http_foundation.html#response
- [ ] Status codes  
  * http://en.wikipedia.org/wiki/List_of_HTTP_status_codes
- [ ] RFC 2616
  * http://www.ietf.org/rfc/rfc2616.txt

---

#### **Symfony2 Architecture**
- [ ] Standard edition of Symfony2  
  * http://symfony.com/distributions
- [ ] Components  
  * http://symfony.com/doc/3.0/components/index.html
- [ ] Bundles  
  * http://symfony.com/doc/3.0/bundles/best_practices.html#configuration
  * http://symfony.com/doc/3.0/quick_tour/the_architecture.html#understanding-the-bundle-system
- [ ] Bridges  
  * http://stackoverflow.com/questions/11888522/what-are-symfony-bridges-bundles-and-vendor?answertab=votes#tab-top
- [ ]  Configuration  
  * http://symfony.com/doc/3.0/quick_tour/the_architecture.html#configuring-a-bundle  
  * http://symfony.com/doc/3.0/configuration.html
  * http://symfony.com/doc/3.0/components/index.html
  * http://symfony.com/doc/3.0/bundles/best_practices.html#configuration  
  * http://symfony.com/doc/3.0/bundles/extension.html  
- [ ]  Code organization  
  * http://symfony.com/doc/3.0/quick_tour/the_architecture.html#understanding-the-directory-structure
- [ ] Request handling  
  * https://symfony.com/doc/3.0/introduction/http_fundamentals.html#the-journey-from-the-request-to-the-response

---

#### **Standardisation**
- [ ] Naming conventions  
  * http://symfony.com/doc/3.0/contributing/code/standards.html#naming-conventions
- [ ] Coding standards  
  * http://symfony.com/doc/3.0/contributing/code/standards.html
- [ ] Integration of third-party libraries  
  * http://symfony.com/doc/3.0/bundles/installation.html
- [ ] Composer packages handling  
  * http://symfony.com/doc/3.0/setup.html
  * https://knpuniversity.com/screencast/composer
- [ ] Development best practices
  * http://symfony.com/doc/3.0/best_practices/index.html
- [ ] Override the framework  
  * http://symfony.com/doc/3.0/bundles/override.html

---

#### **The Bundles**
- [ ] Naming conventions  
  * http://symfony.com/doc/3.0/bundles/best_practices.html#bundle-name
- [ ] Code organization  
  * http://symfony.com/doc/3.0/bundles/best_practices.html#directory-structure
- [ ] The controllers  
  * http://symfony.com/doc/3.0/bundles/best_practices.html#controllers
  * http://symfony.com/doc/3.0/controller.html
  * http://symfony.com/doc/3.0/controller.html#learn-more-about-controllers
- [ ] The views  
  * http://symfony.com/doc/3.0/quick_tour/the_view.html
- [ ] The resources

---

#### **The controllers**
- [ ] Naming conventions  
  * http://symfony.com/doc/3.0/routing.html#controller-string-syntax
- [ ] Get the request  
  * http://symfony.com/doc/3.0/controller.html
  * * http://symfony.com/doc/3.0/components/http_foundation.html#request
- [ ] Generate the response  
  * http://symfony.com/doc/3.0/controller.html
  * * http://symfony.com/doc/3.0/components/http_foundation.html#response
- [ ] The cookies  
  * * http://symfony.com/doc/3.0/components/http_foundation.html#setting-cookies
- [ ] The session  
  * http://symfony.com/doc/3.0/controller.html#managing-the-session
  * http://symfony.com/doc/3.0/components/http_foundation/sessions.html
- [ ] Session flashbag  
  * http://symfony.com/doc/3.0/controller.html#flash-messages
  * http://symfony.com/doc/3.0/components/http_foundation/sessions.html#flash-messages
- [ ] Redirects  
  * http://symfony.com/doc/3.0/controller.html#redirecting
- [ ] Internal redirects  
  * http://symfony.com/doc/3.0/controller/forwarding.html
- [ ] Generate 404 pages  
  * http://symfony.com/doc/3.0/controller.html#managing-errors-and-404-pages
  * http://symfony.com/doc/3.0/controller/error_pages.html

---

#### **The Routing**
- [ ] Configuration (YAML / XML / PHP & annotations)  
  * http://symfony.com/doc/3.0/routing.html#routing-examples
- [ ] Restrict URL parameters  
  * http://symfony.com/doc/3.0/routing.html#adding-wildcard-requirements
- [ ] Set default values to URL parameters  
  * http://symfony.com/doc/3.0/routing.html#giving-placeholders-a-default-value
- [ ] Generate URL parameters  
  * http://symfony.com/doc/3.0/routing.html#generating-urls
  * http://symfony.com/doc/3.0/routing.html#generating-urls-with-query-strings
- [ ] Trigger redirections  
  * http://symfony.com/doc/master/cmf/components/routing/dynamic.html#redirections
  * http://symfony.com/doc/3.0/routing/redirect_in_config.html

---

#### **Templating with Twig**
- [ ] Auto escape  
  * http://twig.sensiolabs.org/doc/tags/autoescape.html
  * http://symfony.com/doc/3.0/templating.html#output-escaping-in-twig
- [ ] Template inheritance  
  * http://twig.sensiolabs.org/doc/tags/extends.html
  * http://twig.sensiolabs.org/doc/templates.html#template-inheritance
  * http://symfony.com/doc/3.0/templating.html#template-inheritance-and-layouts
- [ ] Global functions  
  * http://twig.sensiolabs.org/doc/functions/index.html
- [ ] Filters  
  * http://twig.sensiolabs.org/doc/filters/index.html
- [ ] Template includes  
  * http://twig.sensiolabs.org/doc/tags/include.html
- [ ] Control statements (loops and conditions)  
  * http://twig.sensiolabs.org/doc/tags/for.html
  * http://twig.sensiolabs.org/doc/templates.html#control-structure
- [ ] Urls generation  
  * http://symfony.com/doc/3.0/routing.html#generating-urls-from-a-template
  * http://symfony.com/doc/3.0/templating.html#linking-to-pages
- [ ] Call a controller from a view  
  * http://symfony.com/doc/3.0/templating/embedding_controllers.html
- [ ] Translations  
  * http://symfony.com/doc/3.0/translation.html#translations-in-templates

---

#### **Forms**
- [ ] Create forms  
  * http://symfony.com/doc/3.0/forms.html#creating-a-simple-form
- [ ] Handling forms  
  * http://symfony.com/doc/3.0/forms.html#handling-form-submissions
- [ ] Form types  
  * http://symfony.com/doc/3.0/forms.html#creating-form-classes
  * http://symfony.com/doc/3.0/forms.html#built-in-field-types
- [ ] Render forms with Twig  
  * http://symfony.com/doc/3.0/forms.html#rendering-the-form
  * http://symfony.com/doc/3.0/form/form_customization.html
- [ ] Forms security (CSRF)  
  * http://symfony.com/doc/3.0/form/csrf_protection.html

---

#### **Validation**
- [ ] Validate a PHP object  
  * http://symfony.com/doc/3.0/validation.html#the-basics-of-validation
- [ ] Native validation rules  
  * http://symfony.com/doc/3.0/validation.html#constraints
- [ ] Validation scopes  
- [ ] Validation groups  
  * http://symfony.com/doc/3.0/validation/group_service_resolver.html
  * http://symfony.com/doc/3.0/validation/sequence_provider.html

---

#### **Dependency Injection**
- [ ] The Service container  
  * http://symfony.com/doc/3.0/service_container.html
- [ ] Global configuration parameters
  * http://symfony.com/doc/3.0/service_container/parameters.html
  * http://symfony.com/doc/current/components/dependency_injection.html#setting-up-the-container-with-configuration-files
- [ ] Symfony2 services  
  * http://symfony.com/doc/3.0/service_container.html#what-is-a-service
- [ ] Register new services  
  * http://symfony.com/doc/3.0/service_container.html#creating-configuring-services-in-the-container
- [ ] Tags  
  * http://symfony.com/doc/3.0/service_container/tags.html
  * http://symfony.com/doc/3.0/reference/dic_tags.html
- [ ] Semantic configuration  
  * http://symfony.com/doc/3.0/bundles/extension.html

---

#### **Security**
- [ ] Authentication  
  * http://symfony.com/doc/3.0/security.html#initial-security-yml-setup-authentication
  * http://symfony.com/doc/3.0/components/security/authentication.html
  * http://symfony.com/doc/3.0/security.html
- [ ] Authorization  
  * http://symfony.com/doc/3.0/components/security/authorization.html
  * http://symfony.com/doc/3.0/security.html#security-authorization
- [ ] Configuration  
  * http://symfony.com/doc/3.0/reference/configuration/security.html
- [ ] Providers  
  * http://symfony.com/doc/3.0/security.html#where-do-users-come-from-user-providers
- [ ] Firewalls  
  * http://symfony.com/doc/3.0/security/firewall_restriction.html
  * http://symfony.com/doc/3.0/components/security/firewall.html
- [ ] Users  
  * http://symfony.com/doc/3.0/security.html#b-configuring-how-users-are-loaded
  * http://symfony.com/doc/3.0/security/multiple_user_providers.html
- [ ] Encoders  
  * http://symfony.com/doc/3.0/security.html#c-encoding-the-user-s-password
- [ ] Roles  
  * http://symfony.com/doc/3.0/components/security/authorization.html#roles
  * http://symfony.com/doc/3.0/security.html#roles
- [ ] Access Control Rules  
  * http://symfony.com/doc/3.0/security.html#access-control-in-templates
  * http://symfony.com/doc/3.0/security.html#securing-controllers-and-other-code
  * http://symfony.com/doc/3.0/security/securing_services.html

---

#### **HTTP Cache**
- [ ] Cache types (browser, proxies and reverse proxies)  
  * http://symfony.com/doc/3.0/http_cache.html
- [ ] Expiration (Expires, Cache-control)  
  * http://symfony.com/doc/3.0/http_cache.html#expiration-caching
- [ ] Validation (ETag, Last-Modified)  
  * http://symfony.com/doc/3.0/http_cache/validation.html
  * http://symfony.com/doc/3.0/http_cache/cache_invalidation.html#http-cache-invalidation
- [ ] Client cache  
- [ ] Server cache  
- [ ] Edge Side Includes  
  * http://symfony.com/doc/3.0/http_cache.html#using-edge-side-includes
  * http://symfony.com/doc/3.0/http_cache/esi.html

---

#### **The command line**
- [ ] Symfony2 commands  
  * http://symfony.com/doc/3.0/components/console/usage.html#built-in-commands
- [ ] Custom commands  
  * http://symfony.com/doc/3.0/console.html#creating-a-command
- [ ] Configuration  
- [ ] Options and arguments  
  * http://symfony.com/doc/3.0/console/input.html#using-command-options
  * http://symfony.com/doc/3.0/console/input.html#using-command-arguments
  * http://symfony.com/doc/3.0/components/console/console_arguments.html
- [ ] Read the entry and write the output  

---

#### **Automated tests**
- [ ] Unit tests with PHPUnit  
  * http://symfony.com/doc/3.0/testing.html#the-phpunit-testing-framework
- [ ] Functional tests  
  * http://symfony.com/doc/3.0/testing.html#functional-tests
- [ ] The Client object  
  * http://symfony.com/doc/3.0/testing.html#working-with-the-test-client
- [ ] The Crawler object  
  * http://symfony.com/doc/3.0/testing.html#the-crawler
- [ ] The Profile object  
  * http://symfony.com/doc/3.0/testing.html#accessing-the-profiler-data
  * http://symfony.com/doc/3.0/testing/profiling.html
- [ ] Access framework objects  
  * http://symfony.com/doc/3.0/testing.html#accessing-internal-objects
  * http://symfony.com/doc/3.0/testing.html#accessing-the-container
- [ ] Configure the client  
  * http://symfony.com/doc/3.0/testing/http_authentication.html
- [ ] Introspect the request and response  
  * http://symfony.com/doc/3.0/testing.html#accessing-internal-objects

---

#### **Miscellaneous**
- [ ] Error handling  
  * http://symfony.com/doc/3.0/controller/error_pages.html
- [ ] Debug the code  
  * http://symfony.com/doc/3.0/debug/debugging.html

### **Resources**
---
#### **Documentation**
* Symfony Documentation
http://symfony.com/doc/3.0/index.html
* The Symfony Book  
http://symfony.com/doc/2.3/book/index.html
* The Symfony Cookbook  
http://symfony.com/doc/2.3/cookbook/index.html
The Symfony Glossary  
http://symfony.com/doc/2.3/glossary.html

---

#### **Books**
* Desarrollo web ágil con Symfony2 Spanish  
http://symfony.es/libro/  
* A year with Symfony  
https://leanpub.com/a-year-with-symfony  
* Un año con Symfony Spanish  
https://leanpub.com/un-ano-con-symfony  
* Extending Symfony2 Web Application Framework  
http://www.packtpub.com/extending-symfony-2-web-application-framework/book  
* Testing para Aplicaciones Symfony2 Spanish  
https://leanpub.com/testingsymfony2  
* Symfony Enterprise Applications
https://leanpub.com/symfony-enterprise-applications
* Extending Symfony2 Web Application Framework
https://www.packtpub.com/web-development/extending-symfony2-web-application-framework
* Symfony Certification. Unofficial self-study guide  
https://leanpub.com/symfony-selfstudy

---

#### **Other**
* KNP University - PHP and Symfony Tutorial Screencasts  
http://knpuniversity.com/
* SymfonyBricks  
https://symfonybricks.com/
* Symfony2 cheat sheet  
http://www.symfony2cheatsheet.com/
* Symfony2 Tutorials  
http://www.screenfony.com/
* Symfony2 deployment checklist  
http://www.symfony2-checklist.com/
* A Symfony Console CLI tool to train on Symfony certification  
https://github.com/certificationy/certificationy-cli  
* A Symfony Web Platform tool to train on Symfony certification  
http://www.certificationy.com/

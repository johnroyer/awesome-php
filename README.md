# Awesome PHP

A curated list of amazingly awesome PHP libraries, resources, and shiny things.

## Table of Contents
- [Awesome PHP](#awesome-php)
  - [Library](#library)
    - [Authentication](#authentication)
    - [Cache](#cache)
    - [Code Quality](#code-quality)
    - [Configuration](#configuration)
    - [Console Tool](#console-tool)
    - [Continuous Integration (CI)](#continuous-integration-ci)
    - [Convertor](#convertor)
    - [Crawler](#crawler)
    - [Data Structure](#data-structure)
    - [Database](#database)
    - [Date and Time](#date-and-time)
    - [Dependency Injection](#dependency-injection)
    - [Documentation](#documentation)
    - [Email](#email)
    - [Encode Decode](#encode-decode)
    - [Event](#event)
    - [File](#File)
    - [Geolocation](#geolocation)
    - [Globalization](#globalization)
    - [HTTP](#http)
    - [Image](#image)
    - [Intergration](#intergration)
    - [JSON](#json)
    - [Logging](#logging)
    - [Math](#math)
    - [Middleware](#middleware)
    - [Multi-Proccesses](#multi-proccesses)
    - [Multi-Thread](#multi-threads)
    - [Navigation](#navigation)
    - [Notifications](#notifications)
    - [Office](#office)
    - [PDF](#pdf)
    - [Queue](#queue)
    - [Profiling](#profiling)
    - [Router](#router)
    - [Security](#security)
    - [Static Analysis](#static-analysis)
    - [Stream](#stream)
    - [Task Runner and Scheduler](#task-runner-and-scheduler)
    - [Template](#template)
    - [Testing](#testing)
    - [URL](#url)
    - [Validator](#validator)
    - [Video](#video)
    - [Misc](#misc)
  - [Frameworks](#framework)
  - [Extensions](#extensions)
  - [Platforms](#platforms)
    - [Analytics](#analytics)
    - [Content Management Systems (CMS)](#content-management-systems-cms)
    - [E-commerce](#e-commerce)
    - [ERP / CRM](#erp--crm)
    - [File Server](#file-server)
    - [Forum](#forum)
    - [Photo and Video](#photo-and-video)
    - [Static Site Generators](#static-site-generators)
  - [Ecosystem](#ecosystem)
    - [Build Tool](#build-tool)
    - [Development Environment](#development-environment)
    - [Dependency Management](#dependency-management)
    - [PHP Installation](#php-installation)
    - [Server](#server)
    - [Editor and IDE](#editor-and-ide)
    - [Virtual Machines](#virtual-machines)
    - [Web Application](#web-application)
    - [Utility](#utility)
  - [Resources](#resources)
    - [Web Service](#web-service)
    - [Tutorial / Learning](#tutorial--learning)
    - [Books](#books)
    - [Videos](#videos)
    - [Conferences](#conferences)
    - [Podcasts](#podcasts)
    - [Newsletters](#newsletters)
    - [Reading](#reading)
    - [Internals Reading](#internals-reading)
  - [Package Repository](#package-repository)

### Library

#### Authentication

- [Aura.Auth](https://github.com/auraphp/Aura.Auth) - Provides a unified interface to local and remote authentication systems (BSDv2)
- [SocialConnect Auth](https://github.com/socialConnect/auth) - Connect your application(s) with social network(s) (MIT)
- [Json Web Token](https://github.com/lcobucci/jwt) - A simple library to work with JSON Web Token and JSON Web Signature (BSDv3)
- [OAuth 1.0 Client](https://github.com/thephpleague/oauth1-client) - OAuth 1 Client (MIT)
- [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client) - Easy integration with OAuth 2.0 service providers (MIT)
- [bshaffer/oauth2-server-php](https://github.com/bshaffer/oauth2-server-php) - A library for implementing an OAuth2 Server in php (MIT)
- [league/oauth2-server](https://github.com/thephpleague/oauth2-server) - A spec compliant, secure by default PHP OAuth 2.0 Server (MIT)
- [Opauth](https://github.com/opauth/opauth) - Multi-provider authentication framework for PHP (MIT)
- [Paseto](https://github.com/paragonie/paseto) - Platform-Agnostic Security Tokens (ISC License)
- [PHP oAuthLib](https://github.com/daviddesberg/PHPoAuthLib) - PHP 5.3+ oAuth 1/2 Client Library (MIT)
- [Sentinel Social](https://github.com/cartalyst/sentinel-social) - About A Sentinel addon that makes authenticating your users through social networks & third-party OAuth providers in Sentinel an absolute breeze (PSL)
- [Sentinel](https://github.com/cartalyst/sentinel) - A framework agnostic authentication & authorization system (BSDv3)
- [TwitterOAuth](https://github.com/abraham/twitteroauth) - PHP library for use with the Twitter OAuth REST API (MIT)

#### Cache

- [APIx Cache](https://github.com/apix/cache) - A thin PSR-6 cache wrapper to various caching backends emphasizing cache tagging and indexing (BSDv3)
- [CacheTool](https://github.com/gordalina/cachetool) - CLI App and library to manage apc & opcache (MIT)
- [CakePHP Cache](https://github.com/cakephp/cache) - Caching library with support for multiple caching backends (MIT)
- [Doctrine Cache](https://github.com/doctrine/cache) - Doctrine Cache component (MIT)
- [Metaphore](https://github.com/sobstel/metaphore) - Cache slam defense using a semaphore to prevent dogpile effect (MIT)
- [Stash](https://github.com/tedious/Stash) - place to keep your cache (BSDv3)
- [Laminas Cache](https://github.com/laminas/laminas-cache) - Caching implementation with a variety of storage options, as well as codified caching strategies for callbacks, classes, and output (BSDv3)

#### Code Quality

- [PHP CodeSniffer](https://github.com/PHPCSStandards/PHP_CodeSniffer) - tokenizes PHP files and detects violations of a defined set of coding standards (BSDv3)
- [PHP CS Fixer](https://github.com/PHP-CS-Fixer/PHP-CS-Fixer) - automatically fix PHP Coding Standards issues (MIT)
- [PHP CS Fixer Configurator](https://github.com/mlocati/php-cs-fixer-configurator) - Inspect PHP-CS-Fixer fixers and easily configure them (MIT)
- [PHPMD](https://github.com/phpmd/phpmd) - a spin-off project of PHP Depend and aims (BSDv3)
- [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) - tool that helps PHP programmers adhere to certain coding conventions (LGLPv3)
- [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - Copy/Paste Detector (CPD) for PHP code (BSDv3)
- [Laravel Pint](https://github.com/laravel/pint) - an opinionated PHP code style fixer for minimalists (MIT)
- [editorconfig-checker](https://github.com/editorconfig-checker/editorconfig-checker.php) - tool to verify that your files are in harmony with your .editorconfig (MIT)
- [GrumPHP](https://github.com/phpro/grumphp) - A PHP code-quality tool (MIT)
- [PHP AST Viewer](https://github.com/RightCapitalHQ/php-ast-viewer) - tool for viewing the Abstract Syntax Tree of PHP code (MIT)
- [PHP Magic Number Detector](https://github.com/povils/phpmnd) - help you to detect magic numbers in your PHP code (MIT)
- [PHP Parser](https://github.com/nikic/PHP-Parser) - A PHP parser written in PHP (BSDv3)
- [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - Compares two source sets and determines the appropriate semantic versioning to apply (MIT)
- [Phpactor](https://github.com/phpactor/phpactor) - PHP Language Server with more features than you can shake a stick at (MIT)
- [PHPLOC](https://github.com/sebastianbergmann/phploc) - tool for quickly measuring the size of a PHP project (BSDv3)
- [PHPQA](https://github.com/EdgedesignCZ/phpqa) - Analyze PHP code with one command (MIT)
- [Rector](https://github.com/rectorphp/rector) - Instant Upgrades and Automated Refactoring of any PHP 5.3+ code (MIT)
- [Scrutinizer](https://scrutinizer-ci.com/) - A web tool to [scrutinise PHP code](https://github.com/scrutinizer-ci/php-analyzer).
- [UBench](https://github.com/devster/ubench) - A simple micro-benchmark library.

#### Configuration

- [PHP Dotenv](https://github.com/vlucas/phpdotenv) - Loads environment variables from `.env` to `getenv()`, `$_ENV` and `$_SERVER` automagically (BSDv3)
- [Symfony Dotenv](https://github.com/symfony/dotenv)- Registers environment variables from a .env file (MIT)
- [Yo! Symfony TOML](https://github.com/yosymfony/toml) - A PHP parser for TOML (MIT)

#### Console Tool

- [Aura.Cli](https://github.com/auraphp/Aura.Cli) - Command-Line Interface tools (BSDv2)
- [Cilex](https://github.com/Cilex/Cilex) - Cilex a lightweight framework for creating PHP CLI scripts inspired by Silex (MIT)
- [CLI Menu](https://github.com/php-school/cli-menu) - Build beautiful PHP CLI menus. Simple yet Powerful (MIT)
- [CLIFramework](https://github.com/c9s/CLIFramework) - A powerful command line application framework for PHP (BSD)
- [CLImate](https://github.com/thephpleague/climate) - PHP's best friend for the terminal (MIT)
- [Commando](https://github.com/nategood/commando) - An Elegant CLI Library for PHP (MIT)
- [Cron Expression](https://github.com/mtdowling/cron-expression) - Calculate the next or previous run date and determine if a CRON expression is due (MIT)
- [GetOpt](https://github.com/getopt-php/getopt-php) - library for command-line argument processing (MIT)
- [GetOptionKit](https://github.com/c9s/GetOptionKit) - object-oriented option parser library for PHP, which supports type constraints, flag, multiple flag, multiple values, required value checking (MITT)
- [PsySH](https://github.com/bobthecow/psysh) - runtime developer console, interactive debugger and REPL for PHP (MIT)
- [ShellWrap](https://github.com/MrRio/shellwrap) - Lovely PHP wrapper for using the command-line (MIT)

#### Continuous Integration (CI)

- [JoliCi](https://github.com/jolicode/JoliCi) - Run your TravisCi builds locally (MIT)
- [PHPCI](https://github.com/dancryer/phpci) - free and open source continuous integration tool specifically designed for PHP (BSDv2)
- [Setup PHP](https://github.com/shivammathur/setup-php) - GitHub action to set up PHP with extensions, php.ini configuration, coverage drivers, and various tools (MIT)

#### Crawler

- [Chrome PHP](https://github.com/chrome-php/chrome) - Instrument headless chrome/chromium instances from PHP (MIT)
- [CrawlerDetect](https://github.com/JayBizzle/Crawler-Detect) - PHP class for detecting bots/crawlers/spiders via the user agent (MIT)
- [DiDOM](https://github.com/Imangazaliev/DiDOM) - Simple and fast HTML and XML parser (MIT)
- [Embed](https://github.com/php-embed/Embed) - Get info from any web service or page (MIT)
- [PHP Spider](https://github.com/mvdbos/php-spider) - configurable and extensible PHP web spider (MIT)
- [Symfony Panther](https://github.com/symfony/panther) - A browser testing and web crawling library for PHP and Symfony (MIT)

#### Convertor

- [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) - An ANSI to HTML5 converter library (MIT)
- [Hyphenation](https://github.com/heiglandreas/Org_Heigl_Hyphenator) - Provide TeX-Hyphenation to PHP (MIT)
- [Slugify](https://github.com/cocur/slugify) - Converts a string to a slug. Includes integrations for Symfony, Silex, Laravel, Zend Framework 2, Twig, Nette and Latte (MIT)
- [SQL Formatter](https://github.com/jdorn/sql-formatter/) - lightweight php class for formatting sql statements. Handles automatic indentation and syntax highlighting (MIT)
- [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) - library for manipulating and converting colors (unknown)
- [PHP Conversion](https://github.com/Crisu83/php-conversion) - Library for converting units and sizes (Apachev2)
- [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) - handling physical quantities and the units of measure in which they're represented (MIT)
- [ByteUnits](https://github.com/gabrielelana/byte-units) - parse, format and convert byte units (MIT)
- [Hateoas](https://github.com/willdurand/Hateoas) - implementing representations for HATEOAS REST web services (MIT)
- [Jane](https://github.com/janephp/janephp/) - a set of libraries to generate Models & API Clients based on JSON Schema / OpenAPI specs (MIT)

#### Data Science

datamining, machine learning

- [PHP-ML](https://github.com/jorgecasas/php-ml) - PHP Machine Learning library (MIT)
- [PHP-MLX](https://github.com/php-ai/php-mlx) - PHP-MLX (php-ml next generation) - Machine Learning library for PHP (MIT liked)
- [Rubix ML](https://github.com/RubixML/ML) - A high-level machine learning and deep learning library for the PHP language (MIT)

#### Data Structure

- [CakePHP Collection](https://github.com/cakephp/collection) - Collection library in CakePHP (MIT)
- [convert_mbox_to_eml_files](https://github.com/uzulla/convert_mbox_to_eml_files) - Split huge mbox file to many .eml(.emlx) file (unknow)
- [Fractal](https://github.com/thephpleague/fractal) - Output complex, flexible, AJAX/RESTful data structures (MIT)
- [Ginq](https://github.com/akanehara/ginq) - `LINQ to Object` inspired DSL for PHP (MIT)
- [JsonMapper](https://github.com/cweiske/jsonmapper) - Map nested JSON structures onto PHP classes (OSLv3)
- [JSON Machine](https://github.com/halaxa/json-machine) - Efficient, easy-to-use, and fast PHP JSON stream parser (Apachev2)
- [Knapsack](https://github.com/DusanKasan/Knapsack) - Collection pipeline library for PHP (MIT)
- [mbox-splitter](https://github.com/devgiants/mbox-splitter) - Allow to split mbox filesn smaller files to allow POST import (GPLv2)
- [msgpack.php](https://github.com/rybakit/msgpack.php) - pure PHP implementation of the [MessagePack](https://msgpack.org/) serialization format (MIT)
- [PINQ](https://github.com/TimeToogo/Pinq) - real LINQ library for PHP (MIT)
- [Serializer](https://github.com/schmittjoh/serializer) - Library for (de-)serializing data of any complexity (supports JSON, and XML) (MIT)
- [SphinxQL Query Builder](https://github.com/FoolCode/SphinxQL-Query-Builder) - generates SphinxQL, a SQL dialect, which is used to query the Sphinx search engine (Apachev2)
- [YaLinqo](https://github.com/Athari/YaLinqo) - Yet Another LINQ to Objects for PHP (BSDv2)
- [Laminas Serializer](https://github.com/laminas/laminas-serializer) - Serialize and deserialize PHP structures to a variety of representations (BSDv3)
- [Laravel Serializable Closure](https://github.com/laravel/serializable-closure) - Laravel Serializable Closure provides an easy and secure way to serialize closures in PHP (MIT)

#### Database

- [Atlas.Orm](https://github.com/atlasphp/Atlas.Orm) - data mapper implementation for your persistence model in PHP (MIT)
- [Aura.Sql](https://github.com/auraphp/Aura.Sql) - SQL database access through PDO (MIT)
- [Aura.SqlQuery](https://github.com/auraphp/Aura.SqlQuery) - Independent query builders for MySQL, PostgreSQL, SQLite, and Microsoft SQL Server (MIT)
- [Baum](https://github.com/etrepat/baum) - implementation of the Nested Set pattern for Laravel's Eloquent ORM (MIT)
- [CakePHP ORM](https://github.com/cakephp/orm) - flexible, lightweight and powerful Object-Relational Mapper for PHP, implemented using the DataMapper pattern (MIT)
- [Cycle ORM](https://github.com/cycle/orm) - PHP DataMapper, ORM (MIT)
- [Doctrine Extensions](https://github.com/doctrine-extensions/DoctrineExtensions ) - Doctrine2 behavioral extensions, Translatable, Sluggable, Tree-NestedSet, Timestampable, Loggable, Sortable (MIT)
- [doctrine/orm](https://github.com/doctrine/orm) - A comprehensive DBAL and ORM (MIT)
- [Laravel Eloquent](https://github.com/illuminate/database) - Subtree split of the Illuminate Database component (MIT)
- [Pomm](https://github.com/chanmix51/Pomm) - Object Model Manager for Postgresql (MIT, mixed)
- [RedBean](https://github.com/gabordemooij/redbean) - ORM layer that creates models, config and database on the fly (BSD & GPLv2 ([ref](https://www.redbeanphp.com/index.php?p=/license)))
- [Slimdump](https://github.com/webfactory/slimdump) - tool for creating configurable dumps of large MySQL-databases (MIT)
- [Spot2](https://github.com/spotorm/spot2) - Spot v2.x DataMapper built on top of Doctrine's Database Abstraction Layer (BSDv3)
- [Doctrine Migrations](https://github.com/doctrine/migrations/) - Doctrine Database Migrations Library (MIT)
- [Migrations](https://github.com/icomefromthenet/Migrations) - php 5.3 Migration Manager (MIT)
- [Phinx](https://github.com/cakephp/phinx) - PHP Database Migrations for Everyone (MIT)
- [PHPMig](https://github.com/davedevelopment/phpmig) - Simple migrations system for php (MIT)
- [Ruckusing](https://github.com/ruckus/ruckusing-migrations) - Database migrations for PHP ala ActiveRecord Migrations with support for MySQL, Postgres, SQLite (LGPL)
- [MongoDB](https://github.com/mongodb/mongo-php-driver) - The Official MongoDB PHP driver (Apachev2)
- [PHPMongo](https://github.com/sokil/php-mongo) - MongoDB ODM, Part of [PHPMongoKit](https://github.com/PHPMongoKit) (MIT)
- [Predis](https://github.com/predis/predis) - flexible and feature-complete Redis/Valkey client for PHP (MIT)

#### Date and Time

- [CalendR](https://github.com/yohang/CalendR) - A modern, object-oriented calendar management library (MIT)
- [Carbon](https://github.com/briannesbitt/Carbon) - simple PHP API extension for DateTime (MIT)
- [Chronos](https://github.com/cakephp/chronos) - standalone DateTime library originally based off of Carbon (MIT)
- [Moment.php](https://github.com/fightbulc/moment.php) - Parse, validate, manipulate, and display dates in PHP w/ i18n support (MIT)
- [Yasumi](https://github.com/azuyalabs/yasumi) - The easy PHP Library for calculating holidays (MIT)

#### Dependency Injection

- [Aura.Di](https://github.com/auraphp/Aura.Di) - Dependency Injection System (MIT)
- [Acclimate](https://github.com/AcclimateContainer/acclimate-container) - Adapters for PHP framework containers to an interoperable interface (MIT)
- [Auryn](https://github.com/rdlowrey/Auryn) - IoC Dependency Injector (MIT)
- [Container](https://github.com/thephpleague/container) - Small but powerful dependency injection container (MIT)
- [Disco](https://github.com/bitExpert/disco) - PSR-11 compatible Dependency Injection Container for PHP (Apachev2)
- [PHP-DI](https://github.com/PHP-DI/PHP-DI) - dependency injection container for humans (MIT)
- [Pimple](https://github.com/silexphp/Pimple) - small PHP dependency injection container (MIT)
- [Symfony DI](https://github.com/symfony/dependency-injection) - Allows you to standardize and centralize the way objects are constructed in your application (MIT)

#### Documentation

- [APIGen](https://github.com/apigen/apigen) - PHP 7.1 ready Smart and Simple Documentation for your PHP project (MIT)
- [daux.io](https://github.com/dauxio/daux.io) - documentation generator that uses a simple folder structure and Markdown files to create custom documentation on the fly (MIT)
- [phpDocumentor](https://github.com/phpdocumentor/phpdocumentor) - Documentation Generator for PHP (MIT)
- [phpDox](https://github.com/theseer/phpdox) - Documentation generator for PHP Code using standard technology (BSDv3)
- [zircote/swagger-php](https://github.com/zircote/swagger-php) - swagger annotation and parsing library (Apachev2)
- [Drest](https://github.com/leedavis81/drest) - Quickly and easily expose Doctrine entities as REST resource endpoints with the use of simple configuration with annotations, yaml, json or a PHP array (MIT)
- [Annotations](https://github.com/doctrine/annotations) - Annotations Docblock Parser (MIT)

#### Email

- [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) - enables you to convert HTML-pages/files into HTML-pages/files with inline styles (BSDv3)
- [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - parsing plain text email content (MIT)
- [Email Validator](https://github.com/nojacko/email-validator) - valid email addresses using a number of methods (MIT)
- [Fetch](https://github.com/tedious/Fetch) - IMAP library for PHP (BSDv3)
- [Mautic](https://github.com/mautic/mautic) - Open Source Marketing Automation Software (GPLv3)
- [PHPMailer](https://github.com/PHPMailer/PHPMailer) - classic email sending library for PHP (LGPLv2)
- [PHP IMAP](https://github.com/barbushin/php-imap) - Manage mailboxes, filter/get/delete emails in PHP (MIT)
- [Stampie](https://github.com/Stampie/Stampie) - Library for using online Email providers (MIT)
- [SwiftMailer](https://github.com/swiftmailer/swiftmailer) - Comprehensive mailing tools (MIT)
- [Symfony Mailer](https://github.com/symfony/mailer) - Helps sending emails (MIT)

#### Encode Decode

- [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - Extensive, portable and performant handling of UTF-8 and grapheme clusters (ApacheV2, GPLv2)
- [Portable ASCII](https://github.com/voku/portable-ascii) - Portable ASCII library - performance optimized (ascii) string functions (MIT)
- [Portable UTF-8](https://github.com/voku/portable-utf8) - Portable UTF-8 library - performance optimized (unicode) string functions (Apachev2, GPLv2)

#### Event

- [Broadway](https://github.com/broadway/broadway) - Infrastructure and testing helpers for creating CQRS and event sourced applications (MIT)
- [CakePHP Event](https://github.com/cakephp/event) - The event dispatcher library for CakePHP (MIT)
- [Elephant.io](https://github.com/ElephantIO/elephant.io) - Send events to a socket.io server through PHP (MIT)
- [Evenement](https://github.com/igorw/evenement) - simple event dispatching library for PHP (MIT)
- [Event](https://github.com/thephpleague/event) - Event package for your app and domain (MIT)
- [Fast CGI Client](https://github.com/hollodotme/fast-cgi-client) - fast CGI client for sending requests (a)synchronously to PHP-FPM (MIT)
- [Pawl](https://github.com/ratchetphp/Pawl) - Asynchronous WebSocket client (MIT)
- [Prooph Event Store](https://github.com/prooph/event-store) - PHP 7.4 EventStore Implementation (BSDv3)
- [PHP Defer](https://github.com/php-defer/php-defer) - Golang's defer statement for PHP (MIT)
- [RxPHP](https://github.com/ReactiveX/RxPHP) - Reactive extensions for PHP (MIT)

#### File

- [CSV](https://github.com/thephpleague/csv) - CSV data manipulation made easy (MIT)
- [Flysystem](https://github.com/thephpleague/Flysystem) - Abstraction for local and remote filesystems (MIT)
- [Gaufrette](https://github.com/KnpLabs/Gaufrette) - provides a filesystem abstraction layer (MIT)
- [UnifiedArchive](https://github.com/wapmorgan/UnifiedArchive) - archive manager with unified interface for different formats (MIT)
- [Parquet](https://github.com/flow-php/parquet) - PHP ETL - parquet library (MIT)

### Geolocation

- [Country List](https://github.com/umpirsky/country-list) - List of all countries with names and ISO 3166-1 codes in all languages and data formats (MIT)
- [GeoCoder](https://github.com/geocoder-php/Geocoder) - The most featured Geocoder library written in PHP (MIT)
- [GeoJSON](https://github.com/jmikola/geojson) - GeoJSON implementation for PHP (MIT)
- [GeoTools](https://github.com/thephpleague/geotools) - Geo-related tools PHP 7.3+ library built atop Geocoder and React libraries (MIT)
- [PHPGeo](https://github.com/mjaschen/phpgeo) - Simple Yet Powerful Geo Library for PHP (MIT)

### Globalization

Include internationalization (I18n), localization (L10n) and translation

- [Aura.Intl](https://github.com/auraphp/Aura.Intl) - Internationalization tools, particularly message translation (MIT)
- [CakePHP I18n](https://github.com/cakephp/i18n) - Provides support for message translation and localization for dates and numbers (MIT)

#### HTTP

- [Buzz](https://github.com/kriswallsmith/Buzz) - PHP's lightweight HTTP client (MIT)
- [Guzzle]( https://github.com/guzzle/guzzle) - extensible PHP HTTP client (MIT)
- [HTTPlug](https://github.com/php-http/httplug) - HTTPlug, the HTTP client abstraction for PHP (MIT)
- [Nyholm PSR-7](https://github.com/Nyholm/psr7) - A super lightweight PSR-7 implementation (MIT)
- [PHP VCR](https://github.com/php-vcr/php-vcr) - Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests (MIT)
- [Requests](https://github.com/WordPress/Requests) - Requests for PHP is a humble HTTP request library. It simplifies how you interact with other sites and takes away all your worries (BSD liked)
- [Retrofit](https://github.com/tebru/retrofit-php) - Retrofit implementation in PHP. A REST client for PHP (MIT)
- [Symfony HTTP Client](https://github.com/symfony/http-client) - Provides powerful methods to fetch HTTP resources synchronously or asynchronously (MIT)
- [Laminas Diactoros](https://github.com/laminas/laminas-diactoros) - PSR HTTP Message implementations (BSDv3)

#### Intergration

SDK, client API

- [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php) - Official repository of the AWS SDK (Apachev2)
- [AsyncAWS](https://github.com/async-aws/aws) - AWS SDK with readable code and async responses (MIT)
- [Bref](https://bref.sh/) - helps you go serverless on AWS with PHP (MIT)
- [createsend-php](https://github.com/campaignmonitor/createsend-php) - library for the Campaign Monitor API (MIT,BSDv2)
- [Elastica](https://github.com/ruflin/Elastica) - PHP client for elasticsearch (MIT)
- [ElasticSearch PHP](https://github.com/elastic/elasticsearch-php) - Official PHP client for Elasticsearch (MIT)
- [Ganesha](https://github.com/ackintosh/ganesha) - Circuit Breaker pattern implementation for PHP applications (MIT)
- [Gotenberg](https://github.com/gotenberg/gotenberg-php) - PHP client for interacting with Gotenberg
- [Github](https://github.com/KnpLabs/php-github-api) - simple PHP GitHub API client, Object Oriented, tested and documented (MIT)
- [Instructor for PHP](https://github.com/cognesy/instructor-php) - Unified LLM API, structured data outputs with LLMs, and agent SDK (MIT)
- [Mailgun](https://github.com/mailgun/mailgun-php) Mailgun's Official SDK (MIT)
- [meilisearch-php](https://github.com/meilisearch/meilisearch-php) - PHP client for Meilisearch (MIT)
- [OpenAI Client](https://github.com/openai-php/client) - supercharged community-maintained PHP API client that allows you to interact with OpenAI API (MIT)
- [OpenAI Client for Laravel](https://github.com/openai-php/laravel) - OpenAI PHP for Laravel is a supercharged PHP API client that allows you to interact with OpenAI API (MIT)
- [Pheanstalk](https://github.com/pheanstalk/pheanstalk) - client for beanstalkd queue (MIT)
- [PHP AMQP](https://github.com/php-amqplib/php-amqplib) - most widely used PHP client for RabbitMQ (LGPL)
- [PHP Mistral AI SDK](https://github.com/SoftCreatR/php-mistral-ai-sdk) - A powerful and easy-to-use PHP SDK for the Mistral AI API, allowing seamless integration of advanced AI-powered features into your PHP projects (ISC)
- [Square](https://github.com/square/connect-php-sdk) - client library for the Square Connect APIs (Apachev2)
- [Stripe](https://github.com/stripe/stripe-php) - library for the Stripe API (MIT)
- [Solarium](https://github.com/solariumphp/solarium) - Solr client library (BSDv2)
- [Tarantool Queue](https://github.com/tarantool-php/queue) - bindings for Tarantool Queue (MIT)
- [Twilio](https://github.com/twilio/twilio-php) - library for communicating with the Twilio REST API and generating TwiML (MIT)


#### Image

- [Color Extractor](https://github.com/thephpleague/color-extractor) - Extract colors from an image like a human would do (MIT)
- [Glide](https://github.com/thephpleague/glide) - Wonderfully easy on-demand image manipulation library with an HTTP based API (MIT)
- [Image Hash](https://github.com/jenssegers/imagehash) - Perceptual image hashing (MIT)
- [Image Optimizer](https://github.com/psliwa/image-optimizer) - Image optimization / compression library (MIT)
- [Imagine](https://github.com/php-imagine/Imagine) - PHP Object Oriented image manipulation library (MIT,Adobe ICC)
- [Intervention Image](https://github.com/Intervention/image) - Image Processing (MIT)
- [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) - PHP5.3+ library that helps you to manage images based on GD library (MIT)
- [PHP QR Code](https://github.com/chillerlan/php-qrcode/) - QR Code generator and reader with a user-friendly API (MIT,Apachev2)

#### JSON

- [JSON Lint](https://github.com/Seldaek/jsonlint) - JSON Lint for PHP (MIT)
- [JSONMapper](https://github.com/JsonMapper/JsonMapper) - Map nested JSON structures to PHP classes (MIT)
- [HAL](https://github.com/blongden/hal) - application/hal builder / formatter for PHP 5.4+ (MIT)

#### Logging

- [Monolog](https://github.com/Seldaek/monolog) - Sends your logs to files, sockets, inboxes, databases and various web services (MIT)

#### Machine Learning / LLM

- [Jieba-PHP](https://github.com/fukuball/jieba-php) - Chinese text segmentation: built to be the best PHP Chinese word segmentation module (MIT)
- [LLPhant](https://github.com/LLPhant/LLPhant) - comprehensive PHP Generative AI Framework using OpenAI GPT 4. Inspired by Langchain (MIT)

#### Math

- [Brick Math](https://github.com/brick/math) - Arbitrary-precision arithmetic library for PHP (MIT)
- [MathPHP](https://github.com/markrogoyski/math-php) - Features descriptive statistics and regressions; Continuous and discrete probability distributions; Linear algebra with matrices and vectors, Numerical analysis; special mathematical functions; Algebra (MIT)
- [DecimalObject](https://github.com/php-collective/decimal-object) - Decimal handling as value object instead of plain strings or floats (MIT)

#### Middleware

- [PSR-15 Middlewares](https://github.com/middlewares/psr15-middlewares) - Collection of PSR-15 middlewares officially developed by Middlewares organization (MIT)
- [Relay](https://github.com/relayphp/Relay.Relay) - PSR-15 server request handler (MIT)
- [Laminas Stratigility](https://github.com/laminas/laminas-stratigility) - PSR-7 middleware foundation for building and dispatching middleware pipelines (BSDv3)

#### Multi-Proccesses

- [amphp/process](https://github.com/amphp/process) - An async process dispatcher for Amp (MIT)
- [console-parallelization](https://github.com/webmozarts/console-parallelization) - Enables the parallelization of Symfony Console commands (MIT)

#### Multi-Threads

- [amphp/parallel](https://github.com/amphp/parallel) - An advanced parallelization library for PHP, enabling efficient multitasking, optimizing resource use, and application responsiveness through multiple CPU threads (MIT)
- [ext-pmmpthread](https://github.com/pmmp/ext-pmmpthread) - Fork of https://github.com/krakjoe/pthreads with a revamped API and PHP 8.1+ support (PHP)


#### Navigation

- [KnpMenu](https://github.com/KnpLabs/KnpMenu) - Menu Library for PHP (MIT)
- [Menu](https://github.com/spatie/menu) - Html menu generator (MIT)

#### Notifications

- [JoliNotif](https://github.com/jolicode/JoliNotif) - Send notifications to your desktop directly from your PHP script (MIT)
- [Notification Pusher](https://github.com/Ph3nol/NotificationPusher) - Standalone PHP library for easy devices notifications push (MIT)
- [Notificato](https://github.com/mac-cain13/notificato) - Takes care of Apple push notifications (APNS) in your PHP projects (MIT)
- [Notificator](https://github.com/namshi/notificator) - very lightweight library to handle notifications the smart way (unknown)
- [Php-pushwoosh](https://github.com/gomoob/php-pushwoosh) - easily send push notifications with the Pushwoosh REST Web Services (MIT)

#### Network

- [IP](https://github.com/darsyn/ip) - Immutable value object for IPv4 and IPv6 addresses, including helper methods and Doctrine support (MIT)
- [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) - PHP version of Google's phone number handling library (Apachev2)

#### Office

- [lowrapper](https://github.com/mnvx/lowrapper) - PHP wrapper over LibreOffice converter (MIT)
- [PHPPresentation](https://github.com/PHPOffice/PHPPresentation) - A pure PHP library for reading and writing presentations documents (LGPLv3)
- [PHPWord](https://github.com/PHPOffice/PHPWord) - A pure PHP library for reading and writing word processing documents (LGPLv3)
- [PhpSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet) - A pure PHP library for reading and writing spreadsheet files (MIT)
- [Office Convertor](https://github.com/ncjoes/office-converter) - PHP Wrapper for LibreOffice (MIT)
- [OpenSpout](https://github.com/openspout/openspout) - Read and write spreadsheet files (CSV, XLSX and ODS), in a fast and scalable way (MIT,Apachv2)

#### Parser

Parser and renderer for HTML, CSS, Markdown, YAML, TOML

- [Cebe Markdown](https://github.com/cebe/markdown) - super fast, highly extensible markdown parser for PHP (MIT)
- [CommonMark PHP](https://github.com/thephpleague/commonmark) - Highly-extensible PHP Markdown parser which fully supports the CommonMark and GFM specs (BSDv3)
- [Decoda](https://github.com/milesj/decoda) - lightweight lexical string parser for BBCode styled markup (MIT)
- [Essence](https://github.com/essence/essence) - Extracts information about web pages, like youtube videos, twitter statuses or blog articles (BSDv2)
- [Embera](https://github.com/mpratt/Embera) - Oembed consumer library, that gives you information about urls. It helps you replace urls to youtube or vimeo (MIT)
- [HTML to Markdown](https://github.com/thephpleague/html-to-markdown) - Convert HTML to Markdown with PHP (MIT)
- [HTML5 PHP](https://github.com/Masterminds/html5-php) - HTML5 parser and serializer for PHP (HTML5-PHP)
- [JSON Schema](https://github.com/jsonrainbow/json-schema) - JSON Schema for PHP (MIT)
- [MetaYaml](https://github.com/romaricdrigon/MetaYaml) - powerful schema validator (MIT)
- [Parsedown](https://github.com/erusev/parsedown) - Better Markdown Parser (MIT)
- [PHP CSS Parser](https://github.com/MyIntervals/PHP-CSS-Parser) - Parser for CSS Files written in PHP. Allows extraction of CSS files into a data structure, manipulation of said structure and output as (optimized) CSS (MIT)
- [PHP Markdown](https://github.com/michelf/php-markdown) - Parser for Markdown and Markdown Extra derived from the original Markdown.pl by John Gruber (BSDv3)
- [Shiki PHP](https://github.com/spatie/shiki-php) - Code highlighting with Shiki in PHP (MIT)
- [VObject](https://github.com/sabre-io/vobject) - allows you to easily parse and manipulate iCalendar and vCard objects (BSDv3)
- [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - library for parsing user agent strings for [ua-parser](https://github.com/tobie/ua-parser) project (MIT)
- [Stringy](https://github.com/voku/Stringy) - string manipulation library with multibyte support, performance optimized (MIT)
- [Agent](https://github.com/jenssegers/agent) - desktop/mobile user agent parser with support for Laravel, based on Mobiledetect (MIT)
- [HTML Purifier](https://github.com/ezyang/htmlpurifier) - Standards compliant HTML filter (LGPL)
- [Symfony HTML Sanitizer](https://github.com/symfony/html-sanitizer) - Provides an object-oriented API to sanitize untrusted HTML input for safe insertion into a document's DOM (MIT)
- [Negotiation](https://github.com/willdurand/Negotiation) - Content Negotiation tools (MIT)
- [vanodevium/toml](https://github.com/vanodevium/toml) - library for encoding and decoding TOML (MIT)

#### PDF

- [Browsershot](https://github.com/spatie/browsershot) - Convert HTML to an image, PDF or string (MIT)
- [Dompdf](https://github.com/dompdf/dompdf) - HTML to PDF converter for PHP(LGPL)
- [Snappy](https://github.com/KnpLabs/snappy) - library allowing thumbnail, snapshot or PDF generation from a url or a html page (MIT)
- [TCPDF](https://github.com/tecnickcom/tcpdf) - Official clone of PHP library to generate PDF documents and barcodes (LGPLv3)

#### Profiling

- [Barbushin PHP Console](https://github.com/barbushin/php-console) - Handle PHP errors, dump variables, execute PHP code remotely in Google Chromew (MIT)
- [Kint](https://github.com/kint-php/kint) - Advanced PHP dumper (MIT)
- [Metrics](https://github.com/beberlei/metrics) - Simple library that abstracts different metrics collectors (unknown)
- [PCOV](https://github.com/krakjoe/pcov) - CodeCoverage compatible driver (PHP)
- [PHP Console](https://github.com/Seldaek/php-console) - PHP debug console (BSDv3)
- [php-debugbar](https://github.com/php-debugbar/php-debugbar) - Debug bar for PHP (MIT)
- [PHPBench](https://github.com/phpbench/phpbench) - benchmarking Framework (MIT)
- [PHPSpy](https://github.com/adsr/phpspy) - low-overhead sampling profiler for PHP 7+ (MIT)
- [Tracy](https://github.com/nette/tracy) - addictive tool to ease debugging PHP code for cool developers (dual Licensing: BSD or GPL)
- [Whoops](https://github.com/filp/whoops) - PHP errors for cool kids (MIT)
- [Xdebug](https://github.com/xdebug/xdebug) - Step Debugger and Debugging Aid for PHP (PHP liked)
- [XHProf](https://github.com/phacility/xhprof) - function-level hierarchical profiler for PHP and has a simple HTML based user interface (Apachev2)
- [Z-Ray](https://www.zend.com/products/z-ray) - enterprise-level PHP debugger that comes with Zend Server (commercial)
- [Blackfire](https://www.blackfire.io) - fastest way to spot bottlenecks in your PHP & Python code (commercial)

#### Queue

- [Bernard](https://github.com/bernardphp/bernard) - multi-backend PHP library for creating background jobs for later processing (MIT)
- [BunnyPHP](https://github.com/jakubkulhan/bunny) - A performant pure-PHP AMQP (RabbitMQ) sync and also async (ReactPHP) library (MIT)
- [Thumper](https://github.com/php-amqplib/Thumper) - implements several messaging patterns for RabbitMQ (MIT)
- [Enqueue](https://github.com/php-enqueue/enqueue-dev) - Message Queue, Job Queue, Broadcasting, WebSockets packages for PHP, Symfony, Laravel, Magento (MIT)

#### Router

- [Aura.Router](https://github.com/auraphp/Aura.Router) - web router implementation for PHP (MIT)
- [Fast Route](https://github.com/nikic/FastRoute) - Fast request router for PHP (BSDv3)
- [klein.php](https://github.com/klein/klein.php) - fast & flexible router (MIT)
- [Pux](https://github.com/c9s/Pux) - fast PHP router with out-of-box controller helpers (MIT)
- [Route](https://github.com/thephpleague/route) - fast PSR-7 based routing and dispatch component, with PSR-15 middleware support, built on top of FastRoute (MIT)

#### Security

- [AntiXSS](https://github.com/voku/anti-xss) - Protection against Cross-site scripting (XSS) via PHP (MIT)
- [Halite](https://github.com/paragonie/halite) - High-level cryptography interface powered by libsodium (MPL-2.0)
- [Optimus](https://github.com/jenssegers/optimus) - Id obfuscation based on Knuth's multiplicative hashing method for PHP (MIT)
- [PHPGGC](https://github.com/ambionics/phpggc) - Library of PHP unserialize() payloads along with a tool to generate them, from command line or programmatically (Apachev2)
- [PHP Encryption](https://github.com/defuse/php-encryption) - Simple Encryption in PHP (MIT)
- [PHPSecLib](https://github.com/phpseclib/phpseclib) - PHP Secure Communications Library (MIT)
- [random_compat](https://github.com/paragonie/random_compat) - PHP 5.x support for `random_bytes()` and `random_int()` (MIT)
- [Roave Security Advisories](https://github.com/Roave/SecurityAdvisories) - Security advisories as a simple composer exclusion list, updated daily (MIT)
- [Secure Headers](https://github.com/BePsvPT/secure-headers) - PHP Secure Headers (MIT)
- [Zap](https://github.com/zaproxy/zaproxy) - ZAP by Checkmarx Core project (Apachev2)
- [GenPhrase](https://github.com/timoh6/GenPhrase) - Secure passphrase generator for PHP applications (MIT)
- [Password Compat](https://github.com/ircmaxell/password_compat) - Compatibility with the password_* functions that ship with PHP 5.5 (MIT)
- [Password Policy](https://github.com/ircmaxell/password-policy) - Password policy enforcer for PHP and JavaScript (MIT)
- [Password Validator](https://github.com/jeremykendall/password-validator) - Validates passwords against PHP's password_hash function using PASSWORD_DEFAULT (MIT)
- [Password-Generator](https://github.com/hackzilla/password-generator) - PHP Library to generate random passwords (MIT)
- [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) - Library for generating and validating passwords (MIT)
- [phpass](https://github.com/openwall/phpass) - Legacy password hashing framework for PHP applications needing to support or having previously supported PHP below 5.5 (CC-PDDC)
- [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) - Realistic PHP password strength estimate library based on Zxcvbn JS (MIT)
- [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's new noCAPTCHA (reCAPTCHA v2 & v3) (MIT)
- [Safe](https://github.com/thecodingmachine/safe) - All PHP functions, rewritten to throw exceptions instead of returning false (MIT)
- [RobThree/TwoFactorAuth](https://github.com/RobThree/TwoFactorAuth) - PHP library for Two Factor Authentication (TFA / 2FA) (MIT)
- [Laragear/WebAuthn](https://github.com/Laragear/WebAuthn) - Authenticate users with Passkeys: fingerprints, patterns and biometric data (MIT)

#### Static Analysis

- [Exakat](https://github.com/exakat/exakat) - Automated code reviewing engine for PHP (AGPL)
- [Deptrac](https://github.com/qossmic/deptrac) - Static code analysis to find violations in a dependency graph (MIT)
- [Mondrian](https://github.com/Trismegiste/Mondrian) - Static PHP code analysis tool using Graph Theory (MIT)
- [phan](https://github.com/phan/phan) - Static analyzer for PHP that prefers to avoid false-positives and attempts to prove incorrectness rather than correctness (MIT)
- [PHP Architecture Tester](https://github.com/carlosas/phpat) - Easy architecture testing tool for PHP (MIT)
- [PHPCompatibility](https://github.com/PHPCompatibility/PHPCompatibility) - PHP Compatibility check for PHP_CodeSniffer (LGPLv3)
- [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - Static code analysis to find violations in a dependency graph (MIT)
- [PHPDoc Parser](https://github.com/phpstan/phpdoc-parser) - Next-gen phpDoc parser with support for intersection types and generics (MIT)
- [PHP Metrics](https://github.com/phpmetrics/PhpMetrics) - Beautiful and understandable static analysis tool for PHP (MIT)
- [PHP Migration](https://github.com/monque/PHP-Migration) - Static analyzer for PHP version migration and compatibility checking that detects changes introduced in PHP 5.3-7.0 (MIT)
- [PHPStan](https://github.com/phpstan/phpstan) - PHP Static Analysis Tool - discover bugs in your code without running it! (MIT)
- [Psalm](https://github.com/vimeo/psalm) - Static analysis tool for finding errors and security vulnerabilities in PHP applications (MIT)

#### Task Runner and Scheduler

- [Jobby](https://github.com/jobbyphp/jobby) - Manage all your cron jobs without modifying crontab. Handles locking, logging, error emails, and more (MIT)
- [Robo](https://github.com/consolidation/Robo) - Modern task runner (MIT)
- [Task](https://github.com/taskphp/task) - Pure PHP task runner (MIT)
- [Envoy](https://github.com/laravel/envoy) - Elegant SSH tasks for PHP (MIT)

#### Template

- [Latte](https://github.com/nette/latte) - safest & truly intuitive templates for PHP (GPL, BSD)
- [MtHaml](https://github.com/arnaud-lb/MtHaml) - A PHP implementation of the HAML template language (MIT)
- [Mustache](https://github.com/bobthecow/mustache.php) - A PHP implementation of the Mustache template language (MIT)
- [PHPTAL](https://github.com/phptal/PHPTAL) - template engine for XSS-proof well-formed XHTML and HTML5 pages (LGPLv2)
- [Plates](https://github.com/thephpleague/plates) - Native PHP template system (MIT)
- [Smarty](https://github.com/smarty-php/smarty) - template engine for PHP, facilitating the separation of presentation (HTML/CSS) from application logic (LGPLv3)
- [Twig](https://github.com/twigphp/Twig) - flexible, fast, and secure template language for PHP (BSDv3)
- [Laravel Mix](https://github.com/laravel-mix/laravel-mix ) - power of webpack, distilled for the rest of us (MIT)
- [Symfony Asset](https://github.com/symfony/asset) - Manages URL generation and versioning of web assets (MIT)
- [Symfony Encore](https://github.com/symfony/webpack-encore) - simple but powerful API for processing & compiling assets built around Webpack (MIT)

#### Testing

- [Alice](https://github.com/nelmio/alice) - Expressive fixtures generator (MIT)
- [AspectMock](https://github.com/Codeception/AspectMock) - most powerful and flexible mocking framework for PHPUnit / Codeception (MIT)
- [Atoum](https://github.com/atoum/atoum) - modern, simple and intuitive PHP unit testing framework (BSDv3)
- [Behat](https://github.com/Behat/Behat) - BDD framework for PHP to help you test business expectations (MIT)
- [Codeception](https://github.com/Codeception/Codeception) - Full-stack testing PHP framework (MIT)
- [Faker](https://github.com/fakerphp/faker) - PHP library that generates fake data for you (MIT)
- [Foundry](https://github.com/zenstruck/foundry) - model factory library for creating expressive, auto-completable, on-demand dev/test fixtures with Symfony and Doctrine (MIT)
- [Infection](https://github.com/infection/infection) - PHP Mutation Testing library (BSDv3)
- [Kahlan](https://github.com/kahlan/kahlan) - PHP Test Framework for Freedom, Truth, and Justice (MIT)
- [Mockery](https://github.com/mockery/mockery) - simple yet flexible PHP mock object framework for use in unit testing with PHPUnit, PHPSpec or any other testing framework (BSDv3)
- [Nette Tester](https://github.com/nette/tester) - enjoyable unit testing in PHP with code coverage reporter (BSD or GPL)
- [ParaTest](https://github.com/paratestphp/paratest) - Parallel testing for PHPUnit (MIT)
- [Pest](https://github.com/pestphp/pest) - elegant PHP testing Framework with a focus on simplicity, meticulously designed to bring back the joy of testing in PHP (MIT)
- [Phake](https://github.com/phake/phake) - PHP Mocking Framework (BSDv3)
- [PHP-Mock](https://github.com/php-mock/php-mock) - Mock built-in PHP functions (e.g. time(), exec() or rand()) (WTFPL)
- [PHP MySQL Engine](https://github.com/vimeo/php-mysql-engine) - MySQL engine written in pure PHP (MIT)
- [PHPSpec](https://github.com/phpspec/phpspec) - toolset to drive emergent design by specification (MIT)
- [PHPT](https://github.com/php/php-src) - test tool used by PHP itself (BSDv3)
- [PHPUnit](https://github.com/sebastianbergmann/phpunit) - PHP Unit Testing framework (BSD-3-Clause)
- [PHPUnit Polyfills](https://github.com/Yoast/PHPUnit-Polyfills/) - Set of polyfills for changed PHPUnit functionality to allow for creating PHPUnit cross-version compatible tests (BSDv3)
- [Prophecy](https://github.com/phpspec/prophecy) - Highly opinionated mocking framework (MIT)
- [VFS Stream](https://github.com/bovigo/vfsStream) - stream wrapper for a virtual file system that may be helpful in unit tests to mock the real file system. It can be used with any unit test framework, like PHPUnit or SimpleTest (BSDv3)
- [Better Reflection](https://github.com/Roave/BetterReflection) - reflection API that aims to improve and provide more features than PHP's built-in reflection API (MIT)
- [Assert](https://github.com/beberlei/assert) - Thin assertion library for use in libraries and business-model

#### URL

- [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - public suffix list based domain parsing (MIT)
- [Purl](https://github.com/jwage/purl) - simple object oriented URL manipulation library for PHP 7.2+ (MIT)
- [sabre/uri](https://github.com/sabre-io/uri) - Functions for making sense out of URIs (BSDv3)
- [Uri](https://github.com/thephpleague/uri) - URI manipulation library (MIT)
- [glenscott/url-normalizer](https://github.com/glenscott/url-normalizer) - syntax based normalization of URI's (MIT)

#### Validator

- [Filterus](https://github.com/ircmaxell/filterus) - simple filtering library for PHP
- [Aura.Filter](https://github.com/auraphp/Aura.Filter) - validate and sanitize arrays and objects (MIT)
- [CakePHP Validation](https://github.com/cakephp/validation) - validation library from CakePHP (MIT)
- [Upload](https://github.com/brandonsavage/Upload) - file uploads with validation and storage strategies (MIT)
- [Valitron](https://github.com/vlucas/valitron) - simple, elegant, stand-alone validation library with NO dependencies (BSDv3)
- [Volan](https://github.com/serkin/Volan) - light and extendable schema validation library (MIT)
- [Respect Validation](https://github.com/Respect/Validation) - the most awesome validation engine ever created for PHP (MIT)
- [Valinor](https://github.com/CuyZ/Valinor) - Dependency free PHP library that helps to map any input into a strongly-typed structure (MIT)

#### Video

- [PHP FFmpeg](https://github.com/PHP-FFmpeg/PHP-FFmpeg/) - object oriented PHP driver for FFMpeg binary (MIT)

#### Misc

- [Finite](https://github.com/yohang/Finite) - simple PHP finite state machine (MIT)
- [Functional PHP](https://github.com/lstrojny/functional-php) - primitives for functional programming in PHP (MIT)
- [Iter](https://github.com/nikic/iter) - iteration primitives using generators (BSDv3)
- [IterTools PHP](https://github.com/markrogoyski/itertools-php) - PHP iteration tools library (MIT)
- [Pipeline](https://github.com/thephpleague/pipeline) - pipeline pattern implementation (MIT)
- [Porter](https://github.com/ScriptFUSION/Porter) - durable and asynchronous data imports for consuming data at scale and publishing testable SDKs (LGPLv3, GPLv3)
- [RulerZ](https://github.com/K-Phoen/rulerz) - powerful implementation of the Specification pattern in PHP (MIT)
- [UUID](https://github.com/ramsey/uuid) - PHP library for generating universally unique identifiers (UUIDs) (MIT)
- [Url highlight](https://github.com/vstelmakh/url-highlight) - parse URLs from string input (MIT)
- [URLify](https://github.com/jbroadway/urlify) - fast PHP slug generator and transliteration library that converts non-ascii characters for use in URLs (BSDv3)
- [Device Detector](https://github.com/matomo-org/device-detector) - universal device detection library that parses User Agents and Browser Client Hints to detect devices (LGPLv3)
- [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - lightweight PHP class for detecting mobile devices (including tablets) (MIT)
- [ISO-codes](https://github.com/ronanguilloux/IsoCodes) - validators for standards from ISO, International Finance, Public Administrations, GS1, Manufacturing Industry, Phone numbers & Zipcodes for many countries (GPLv3)
- [Lock](https://github.com/php-lock/lock) - serialized execution of critical code in concurrent situations (MIT)
- [Hprose-PHP](https://github.com/hprose/hprose-php) - cross-language RPC (MIT)
- [Laravel Serializable Closure](https://github.com/laravel/serializable-closure) - easy and secure way to serialize closures in PHP (MIT)
- [Pagerfanta](https://github.com/whiteoctober/Pagerfanta) - pagination for PHP (MIT)
- [ProxyManager](https://github.com/Ocramius/ProxyManager) - OOP proxy wrappers/utilities - generates and manages proxies of your objects (MIT)

### Framework

- [AMP](https://github.com/amphp/amp) - non-blocking concurrency framework for PHP applications (MIT)
- [BotMan](https://github.com/botman/botman) - framework agnostic PHP library to build chat bots (MIT)
- [CakePHP](https://github.com/cakephp/cakephp) - rapid application development framework (MIT)
- [CakePHP CRUD](https://github.com/friendsofcake/crud) - production-grade rapid controller development with built in love for API and Search (MIT)
- [CodeIgniter](https://github.com/codeigniter4/CodeIgniter4) - Open Source PHP Framework (originally from EllisLab) (MIT)
- [FuelPHP](https://github.com/fuel/fuel) - simple, flexible, community driven PHP 5.3+ (MIT)
- [Laminas](https://github.com/laminas) - enterprise-ready PHP Framework and components (BSDv3)
- [Laravel](https://github.com/laravel/laravel) - web application framework with expressive, elegant syntax (MIT)
- [Laravel Zero](https://github.com/laravel-zero/laravel-zero) -  micro-framework that provides an elegant starting point for your console application (MIT)
- [LaravelS](https://github.com/hhxsv5/laravel-s) - out-of-the-box adapter between Laravel/Lumen and Swoole (MIT)
- [Livewire](https://github.com/livewire/livewire) - full-stack framework for Laravel that takes the pain out of building dynamic UIs (MIT)
- [LLPhant](https://github.com/LLPhant/LLPhant) - comprehensive PHP Generative AI Framework using OpenAI GPT 4, inspired by Langchain (MIT)
- [Mezzio](https://github.com/mezzio/mezzio) - PSR-15 Middleware Microframework (BSDv3)
- [Minicli](https://github.com/minicli/minicli) - minimal framework for command-line applications in PHP (MIT)
- [Nette](https://github.com/nette/nette) - framework speaks your language and helps you to easily build better websites (GPL, BSD)
- [Phalcon](https://github.com/phalcon/cphalcon) - High performance, full-stack PHP framework delivered as a C extension (BSDv3)
- [ReactPHP](https://github.com/reactphp/reactphp) - event-driven, non-blocking I/O with PHP (MIT)
- [Silly](https://github.com/mnapoli/silly) - CLI micro-framework based on Symfony Console (MIT)
- [Slim](https://github.com/slimphp/Slim) - micro framework that helps you quickly write simple yet powerful web applications and APIs (MIT)
- [Spiral](https://github.com/spiral/framework) - high-performance PHP framework (MIT)
- [Swoole](https://github.com/swoole/swoole-src) - coroutine-based concurrency library for PHP (Apache)
- [Symfony](https://github.com/symfony/symfony) - framework for web and console applications and a set of reusable PHP components (MIT)
- [TinnkPHP](https://github.com/top-think/framework) - simple, lightweight framework (Apache2)
- [Workerman](https://github.com/walkor/Workerman) - asynchronous event driven PHP socket framework (MIT)
- [Yii2](https://github.com/yiisoft/yii2/) - modern framework designed to be a solid foundation for your PHP application (BSDv3)

### Extensions

- [PHP APM](https://pecl.php.net/package/APM) - Monitoring extension collecting errors and statistics into SQLite/MySQL/StatsD.
- [PHP CPP](https://www.php-cpp.com/) - monitoring extension enabling native Application Performance Management (APM) for PHP (PHPv3)
- [Phalcon](https://phalcon.io/en-us) - A framework implemented as a C extension. (MIT)
- [Zephir](https://github.com/zephir-lang/zephir ) - A compiled language between PHP and C++ for developing PHP extensions.
- [Swoole](https://github.com/swoole/swoole-src) - Coroutine-based concurrency library for PHP (Apache)
- [ext-php-rs](https://github.com/davidcole1340/ext-php-rs) - Bindings for the Zend API to build PHP extensions natively in Rust (Apache / MIT)

### Platforms

#### Analytics

- [Matomo](https://github.com/matomo-org/matomo) - leading open-source alternative to Google Analytics (GPLv3)

#### Content Management Systems (CMS)

- [Backdrop](https://backdropcms.org) - A CMS targeting small-to-medium-sized business and non-profits (a fork of Drupal).
- [Concrete5](https://www.concretecms.com/) - A CMS targeting users with a minimum of technical skills.
- [CraftCMS](https://github.com/craftcms/cms) - A flexible, user-friendly CMS for creating custom digital experiences on the web and beyond.
- [DigiDocu](https://github.com/harish81/digidocu) - Open Source Documents Management System Built with Laravel 10 (GPL)
- [Drupal](https://new.drupal.org/home) - An enterprise level CMS.
- [Grav](https://github.com/getgrav/grav) - A modern flat-file CMS.
- [Joomla](https://www.joomla.org/) - Another leading CMS.
- [Kirby](https://getkirby.com/) - A flat-file CMS that adapts to any project.
- [Magento](https://github.com/magento/magento2) - The most popular e-commerce platform.
- [Moodle](https://moodle.org/) - An open-source learning platform.
- [OpenMage](https://github.com/OpenMage/magento-lts) - Fork of EoL Magento 1 e-commerce platform.
- [Pico CMS](https://picocms.org/) - A stupidly simple, blazing fast, flat file CMS.
- [Statamic](https://statamic.com/) - Build beautiful, easy-to-manage websites.
- [Sulu](https://sulu.io/) - A user and developer friendly focused CMS and Platform based on the Symfony Framework.
- [TYPO3](https://typo3.org) - An enterprise level CMS.
- [WordPress](https://github.com/WordPress/WordPress) - A blogging platform and CMS.
- [MediaWiki](https://github.com/wikimedia/mediawiki) - collaborative editing software that runs Wikipedia (GPLv2)

#### E-commerce

- [Money](https://github.com/moneyphp/money) - A PHP implementation of Fowler's money pattern.
- [Brick Money](https://github.com/brick/money) - A money library for PHP, with support for contexts, cash roundings, currency conversion.
- [OmniPay](https://github.com/thephpleague/omnipay) - A framework agnostic multi-gateway payment processing library.
- [Payum](https://github.com/payum/payum) - A payment abstraction library.
- [Shopsys Framework](https://github.com/shopsys/shopsys/) - An open source e-commerce platform for in-house development teams.
- [Shopware](https://github.com/shopware/shopware) - Highly customizable e-commerce software
- [Swap](https://github.com/florianv/swap) - An exchange rates library.
- [Sylius](https://sylius.com/) - An open source e-commerce solution.

#### ERP / CRM

- [Dolibarr](https://github.com/Dolibarr/dolibarr) - a modern software package to manage your company or foundation's activity (GPLv3)
- [Monica](https://github.com/monicahq/monica) - personal CRM. Remember everything about your friends, family and business relationships (AGPLv3)

#### File Server

- [NextCloud](https://github.com/nextcloud/server) - safe home for all your data (AGPLv3)

#### Forum

- [Flarum](https://github.com/flarum/flarum) - Simple forum software for building great communities (MIT)
- [MyBB](https://github.com/mybb/mybb) - free and open source forum software (LGPLv3)
- [phpBB](https://github.com/phpbb/phpbb) - a popular open-source bulletin board (GPLv2)
- [Vanilla](https://github.com/vanilla/vanilla) - powerfully simple discussion forum you can easily customize to make as unique as your community (GPLv2)

### Static Site Generators

- [Couscous](http://couscous.io) - Couscous turns Markdown documentation into beautiful websites. It's GitHub Pages on steroids.
- [Jigsaw](https://jigsaw.tighten.com/) - Simple static sites with Laravel's Blade.
- [Sculpin](https://sculpin.io) - A tool that converts Markdown and Twig into static HTML.

## Ecosystem

### Build Tool

- [Box](https://github.com/box-project/box) - A utility to build PHAR files.
- [Construct](https://github.com/jonathantorres/construct) - A PHP project/micro-package generator.
- [Phing](https://www.phing.info/) - A PHP project build system inspired by Apache Ant.
- [RMT](https://github.com/liip/RMT) - A library for versioning and releasing software.

### Development tool / environment

- [Ansible](https://www.redhat.com/en/ansible-collaborative) - A radically simple orchestration framework.
- [CaptainHook](https://github.com/captainhook-git/captainhook) - very flexible git hook manager for software developers that makes sharing git hooks with your team a breeze (MIT)
- [DDEV](https://github.com/ddev/ddev) - a local web development environment system for PHP.
- [Deployer](https://github.com/deployphp/deployer) - deployment tool with support for popular frameworks out of the box (MIT)
- [Docker](https://www.docker.com/) - A containerization platform.
- [Docker PHP Extension Installer](https://github.com/mlocati/docker-php-extension-installer) - Easily install PHP extensions in Docker containers.
- [Docksal](https://github.com/docksal/docksal) - Unified, Docker :whale: powered web development environments for macOS, Windows, and Linux.
- [Expose](https://github.com/exposedev/expose) - An open-source PHP tunneling service.
- [Lando](https://lando.dev/) - Push-button development environments.
- [Laravel Homestead](https://laravel.com/docs/master/homestead) - A local development environment for Laravel.
- [Laravel Herd](https://herd.laravel.com/windows) - A one click PHP development environment for macOS and Windows.
- [Laradock](http://laradock.io/) - A full PHP development environment based on Docker.
- [PHPMon](https://phpmon.app/) - A macOS menu bar app for managing PHP installations (works with [Laravel Valet](https://laravel.com/docs/master/valet)).
- [Puppet](https://www.puppet.com) - A server automation framework and application.
- [Rocketeer](https://github.com/rocketeers/rocketeer) - Send your projects up in the clouds (MIT)
- [Laravel Sail](https://github.com/laravel/sail) - Docker files for running a basic Laravel application (MIT)
- [Takeout](https://github.com/tighten/takeout) - A Docker-based development-only dependency manager.
- [Vagrant](https://www.vagrantup.com/) - A portable development environment utility.
- [ClassPreloader](https://github.com/ClassPreloader/ClassPreloader) - A library for optimizing autoloading.

### Dependency Management

- [Composer Installers](https://github.com/composer/installers) - A  multi-framework Composer library installer.
- [Composer](https://getcomposer.org/) - A package and dependency manager.
- [Pie](https://github.com/php/pie) - The official PHP installer for extensions.
- [Phive](https://phar.io/) - A PHAR manager.
- [Pickle](https://github.com/FriendsOfPHP/pickle) - A PHP extension installer.* [Composed](https://github.com/joshdifabio/composed) - A library to parse your project's Composer environment at runtime.
- [Composer Merge Plugin](https://github.com/wikimedia/composer-merge-plugin) - A composer plugin to merge several `composer.json` files.
- [Composer Normalize](https://github.com/ergebnis/composer-normalize) - A plugin for normalizing `composer.json` files.
- [Composer Patches](https://github.com/cweagans/composer-patches) - A plugin for Composer to apply patches.
- [Composer Prefer Lowest Validator](https://github.com/dereuromark/composer-prefer-lowest) - A plugin to check if minimum dependencies can be installed and tested.
- [Composer Require Checker](https://github.com/maglnet/ComposerRequireChecker) - CLI tool to analyze composer dependencies and verify that no unknown symbols are used in the sources of a package.
- [Composer Unused](https://github.com/composer-unused/composer-unused) - A CLI Tool to scan for unused composer packages.
- [Repman](https://repman.io) - A private PHP package repository manager and Packagist proxy.
- [Satis](https://github.com/composer/satis) - A static Composer repository generator.
- [Tooly](https://github.com/tommy-muehle/tooly-composer-script) - A library to manage PHAR files in a project using Composer.
- [Toran Proxy](https://toranproxy.com) - A Composer proxy for speed and reliability. (:warning: Toran Proxy is being phased out.)

### PHP Installation

- [Brew PHP Switcher](https://github.com/philcook/brew-php-switcher) - Brew PHP switcher.
- [HomeBrew](https://brew.sh/) - A package manager for OSX.
- [PHP Brew](https://github.com/phpbrew/phpbrew) - A PHP version manager and installer.
- [PHP Build](https://github.com/php-build/php-build) - Another PHP version installer.
- [Static PHP CLI](https://github.com/crazywhalecc/static-php-cli) - Build or [download](https://dl.static-php.dev/static-php-cli/) static versions of PHP CLI and FPM.
- [PCEL](https://pecl.php.net/) - repository for PHP Extensions, providing a directory of all known extensions

### Server

- [amphp/http-server](https://github.com/amphp/http-server) - An advanced async HTTP server library for PHP, perfect for real-time apps and APIs with high concurrency demands (MIT)
- [appserver.io](https://github.com/appserver-io/appserver) - A multithreaded application server for PHP, written in PHP.
- [php-pm](https://github.com/php-pm/php-pm) - A process manager, supercharger and load balancer for PHP applications.
- [RoadRunner](https://github.com/roadrunner-server/roadrunner) - High-performance PHP application server, load-balancer and process manager.
- [FrankenPHP](https://github.com/php/frankenphp) - The modern PHP app server written in Golang (MIT)
- [Ratchet](https://github.com/ratchetphp/Ratchet) - Asynchronous WebSocket server (MIT)
- [Restler](https://github.com/Luracast/Restler) - A lightweight framework to expose PHP methods as RESTful web API.

### Editor and IDE

- [Eclipse for PHP Developers](https://www.eclipse.org/downloads/) - A PHP IDE based on the Eclipse platform.
- [Apache NetBeans](https://netbeans.apache.org/front/main/index.html) - An IDE with support for PHP and HTML5.
- [PhpEd](https://www.nusphere.com/products/phped.htm) - An IDE with professional commercial debugger.
- [PhpStorm](https://www.jetbrains.com/phpstorm/) - A commercial PHP IDE.
- [VS Code](https://code.visualstudio.com/) - An open source code editor.
- [Laminas API Tool Skeleton](https://github.com/laminas-api-tools/api-tools-skeleton) - An API builder built with the Laminas Framework.

### Virtual Machines

- [Hack](https://hacklang.org/) - A programming language for HHVM.
- [HHVM](https://github.com/facebook/hhvm) - A Virtual Machine, Runtime and JIT for PHP by Facebook.
- [PeachPie](https://github.com/peachpiecompiler/peachpie) - PHP compiler and runtime for .NET and .NET Core.

### Web Application

- [3V4L](https://3v4l.org/) - An online PHP & HHVM shell.
- [Adminer](https://www.adminer.org/en/) - Database management in a single PHP file.
- [Cachet](https://github.com/cachethq/cachet) - The open source status page system.
- [DBV](https://github.com/victorstanciu/dbv) - A database version control application.
- [Lychee](https://github.com/electerious/Lychee) - An easy to use and great looking photo-management-system.
- [MailCatcher](https://github.com/sj26/mailcatcher) - A web tool for capturing and viewing emails.
- [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) - A web interface for MySQL/MariaDB.
- [PHP Queue](https://github.com/CoderKungfu/php-queue) - An application for managing queueing backends.
- [phpRedisAdmin](https://github.com/ErikDubbelboer/phpRedisAdmin) - A simple web interface to manage [Redis](https://redis.io/) databases.
- [PHPSandbox](https://phpsandbox.io) - An online IDE for PHP in the browser.

### Utility

- [PackageGenerator](https://github.com/WsdlToPhp/PackageGenerator) - Package Generator generates a PHP SDK from any WSDL.

## Resources

### Web Service

- [Code Climate](https://codeclimate.com) - An automated code review.
- [CircleCI](https://circleci.com)
- [Gitlab CI/CD](https://about.gitlab.com/solutions/continuous-integration/)
- [Jenkins](https://www.jenkins.io/)
- [Laravel Vapor](https://vapor.laravel.com/) - serverless deployment platform for Laravel, powered by AWS
- [SemaphoreCI](https://semaphore.io/)
- [Travis CI](https://www.travis-ci.com)
- [BugSnag](https://www.bugsnag.com/) - Error and Real User Monitoring.
- [Honeybadger](https://www.honeybadger.io/) - Error Tracking & Application Monitoring for Developers.
- [Rollbar](https://rollbar.com/) - Error Logging & Tracking Service for Software Teams.
- [Sentry](https://sentry.io/welcome/) - Application Performance Monitoring & Error Tracking Software.
- [Tideways](https://tideways.com/) - Monitoring and profiling tool.
- [Bldr](https://bldr.io/) - A PHP Task runner built on Symfony components.
- [API Platform](https://api-platform.com ) - Expose in minutes a hypermedia REST API that embraces JSON-LD, Hydra format.

### Tutorial / Learning

- [Design Patterns PHP](https://github.com/DesignPatternsPHP/DesignPatternsPHP ) - A repository of software patterns implemented in PHP.
- [Nomad PHP](https://nomadphp.com/) - A online PHP learning resource.
- [Laravel News](https://laravel-news.com/) - The official Laravel blog.
- [PHP Annotated Monthly](https://blog.jetbrains.com/phpstorm/tag/php-annotated-monthly/) - A monthly digest of PHP news.
- [PHP FIG](https://www.php-fig.org/) - The PHP Framework Interoperability Group.
- [PHP Package Development Standards](http://php-pds.com) - Package development standards for PHP.
- [PHP School](https://www.phpschool.io/) - Open Source Learning for PHP.
- [PHP The Right Way](https://phptherightway.com/) - A PHP best practice quick reference guide.
- [PHP UG](https://php.ug) - A website to help people locate their nearest PHP user group (UG).
- [PHP Watch](https://php.watch/) - PHP articles, news, upcoming changes, RFCs and more.
- [Unit Testing Tips](https://testing-tips.sarvendev.com/) - Unit Testing Tips by examples in PHP.
- [PHP Internals Book](https://www.phpinternalsbook.com/) - An online book about PHP internals, written by three core developers.
- [Mastering PHP](https://linu.us/series/mastering-php)

### Books

- [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles.
- [Functional Programming in PHP](https://www.functionalphp.com/) - This book will show you how to leverage these new PHP5.3+ features by understanding functional programming principles
- [Grumpy PHPUnit](https://leanpub.com/grumpy-phpunit) - A book about unit testing with PHPUnit by Chris Hartjes.
- [Mastering Object-Orientated PHP](https://masteringobjectorientedphp.com/) - A book about object-orientated PHP by Brandon Savage.
- [PHP Cookbook](https://www.oreilly.com/library/view/php-cookbook/9781098121310/) - This cookbook provides code recipes to help you resolve a variety of coding issues.
- [Modernizing Legacy Applications in PHP](https://leanpub.com/mlaphp) - A book about modernizing legacy PHP applications by Paul M. Jones.
- [Scaling PHP Applications](https://www.scalingphpbook.com) - An ebook about scaling PHP applications by Steve Corona.
- [Securing PHP: Core Concepts](https://leanpub.com/securingphp-coreconcepts) - A book about common security terms and practices for PHP by Chris Cornutt.
- [Signaling PHP](https://leanpub.com/signalingphp) - A book about catching PCNTL signals in CLI scripts by Cal Evans.
- [XML Parsing with PHP](https://www.phparch.com/books/xml-parsing-with-php/) - This book covers parsing and validating XML documents, leveraging XPath expressions, and working with namespaces as well as how to create and modify XML files programmatically.

### Videos

- [Laracasts](https://laracasts.com) - Screencasts about Laravel, Vue JS and more.
- [Laravel YouTube Channel](https://www.youtube.com/channel/UCfO2GiQwb-cwJTb1CuRSkwg) - The official Laravel YouTube channel.
- [Program With Gio](https://www.youtube.com/playlist?list=PLr3d3QYzkw2xabQRUpcZ_IBk9W50M9pe-) - PHP 8 course by Gio.
- [Programming with Anthony](https://www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - A video series by Anthony Ferrara.
- [SymfonyCasts](https://symfonycasts.com/) - Screencasts and tutorials about PHP and Symfony.

### Conferences

- [Laracon EU](https://www.youtube.com/@LaraconEU) - Laracon EU is a 2-day event for people who are interested in learning Laravel and related technologies, or who want to share their knowledge with others.
- [PHP[TEK]](https://phptek.io/) - The longest-running web developer conference in the United States that has a focus on the PHP programming language.
- [PHP UK Conference](https://www.youtube.com/user/phpukconference/videos) - A collection of videos from the PHP UK Conference.

### Podcasts

- [Laravel News Podcast](https://podcast.laravel-news.com/) - The Laravel News Podcast brings you all the latest news and events related to the Laravel PHP Framework.
- [Mostly Technical](https://mostlytechnical.com/) - Hosted by Ian Landsman and Aaron Francis, Mostly Technical is a lively discussion on Laravel, business, and an eclectic mix of related topics.
- [No Compromises](https://show.nocompromises.io/) - Two seasoned salty programming veterans talk best practices based on years of working with Laravel SaaS teams.
- [North Meets South Web Podcast](https://www.northmeetssouth.audio/) - Jacob Bennett and Michael Dyrynda conquer a 14.5 hour time difference to talk about life as web developers.
- [Over Engineered](https://overengineered.fm/) - A podcast in mini-series where we explore unimportant programming questions in extreme detail.
- [PHP Internals News](https://phpinternals.news) - A podcast about PHP internals.
- [PHP Town Hall](https://phptownhall.com/) - A casual PHP podcast by Ben Edmunds and Phil Sturgeon.
- [php[podcast] episodes from php[architect]](https://www.phparch.com/podcast/) - The official podcast of php[architect] the industry's leading tech magazine and publisher focused on PHP and web development.
- [PHPUgly](https://www.phpugly.com/) - The ramblings of a few overworked PHP Developers.
- [The Laracasts Snippet](https://laracasts.simplecast.com) - The Laracasts snippet, each episode, offers a single thought on some aspect of web development.
- [The Laravel Podcast](https://laravelpodcast.com/) - Laravel and PHP development news and discussion.
- [The PHP Roundtable](https://phproundtable.com/) - The PHP Roundtable is a casual gathering of developers discussing topics that PHP nerds care about.

### Newsletters

- [PHP Weekly](https://www.phpweekly.com/) - A weekly newsletter about PHP.

### Reading

- [php[architect]](https://www.phparch.com/magazine/) - A monthly magazine dedicated to PHP.

### Internals Reading

- [PHP RFCs](https://wiki.php.net/rfc) - The home of PHP RFCs (Request for Comments).
- [Externals](https://externals.io/) - PHP internal discussions.
- [PHP RFC Watch](https://github.com/beberlei/php-rfc-watch) - Watch the latest PHP [RFCs](https://wiki.php.net/rfc).



### Package Repository

- [Firegento](https://packages.firegento.com/) - Magento Module Composer Repository.
- [Packagist](https://packagist.org/) - The PHP Package Repository.
- [Packalyst](https://packalyst.com/) - The Laravel Package Repository
- [Private Packagist](https://packagist.com/) - Composer package archive as a service for PHP.
- [WordPress Packagist](https://wpackagist.org/) - Manage your plugins with Composer.

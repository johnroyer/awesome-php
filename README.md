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
- [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - An email reply parser library.
- [Email Validator](https://github.com/nojacko/email-validator) - A small email address validation library.
- [Fetch](https://github.com/tedious/Fetch) - An IMAP library.
- [Mautic](https://github.com/mautic/mautic) - Email marketing automation
- [PHPMailer](https://github.com/PHPMailer/PHPMailer) - Another mailer solution.
- [PHP IMAP](https://github.com/barbushin/php-imap) - A library to access mailboxes via POP3, IMAP and NNTP.
- [Stampie](https://github.com/Stampie/Stampie) - A library for email services such as [SendGrid](https://sendgrid.com/en-us), [PostMark](https://postmarkapp.com), [MailGun](https://www.mailgun.com/) and [MailChimp](https://mailchimp.com/features/transactional-email/).
- [SwiftMailer](https://github.com/swiftmailer/swiftmailer) - Comprehensive mailing tools (MIT)
- [Symfony Mailer](https://github.com/symfony/mailer) - A powerful library for creating and sending emails.

#### Encode Decode

- [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - A portable library for working with UTF-8 strings.
- [Portable ASCII](https://github.com/voku/portable-ascii) - A library to convert strings to ASCII.
- [Portable UTF-8](https://github.com/voku/portable-utf8) - A string manipulation library with UTF-8 safe replacement methods.

#### Event

- [Broadway](https://github.com/broadway/broadway) - An event source and CQRS library.
- [CakePHP Event](https://github.com/cakephp/event) - An event dispatcher library.
- [Elephant.io](https://github.com/ElephantIO/elephant.io) - Yet another web socket library.
- [Evenement](https://github.com/igorw/evenement) - An event dispatcher library.
- [Event](https://github.com/thephpleague/event) - An event library with a focus on domain events.
- [Fast CGI Client](https://github.com/hollodotme/fast-cgi-client) - A client to make synchronous/asynchronous requests through php-fpm socket.
- [Pawl](https://github.com/ratchetphp/Pawl) - An asynchronous web socket client.
- [Prooph Event Store](https://github.com/prooph/event-store) - An event source component to persist event messages
- [PHP Defer](https://github.com/php-defer/php-defer) - Golang's defer statement for PHP.
- [RxPHP](https://github.com/ReactiveX/RxPHP) - A reactive extension library.

#### File

- [CSV](https://github.com/thephpleague/csv) - A CSV data manipulation library.
- [Flysystem](https://github.com/thephpleague/Flysystem) - Abstraction for local and remote filesystems.
- [Gaufrette](https://github.com/KnpLabs/Gaufrette) - A filesystem abstraction layer.
- [UnifiedArchive](https://github.com/wapmorgan/UnifiedArchive) - A unified reader and writer of compressed archives.
- [Parquet](https://github.com/flow-php/parquet) - PHP implementation of Parquet file format

### Geolocation

- [Country List](https://github.com/umpirsky/country-list) - A list of all countries with names and ISO 3166-1 codes.
- [GeoCoder](https://github.com/geocoder-php/Geocoder) - The most featured Geocoder library written in PHP (MIT)
- [GeoJSON](https://github.com/jmikola/geojson) - A GeoJSON implementation.
- [GeoTools](https://github.com/thephpleague/geotools) - A library of geo-related tools.
- [PHPGeo](https://github.com/mjaschen/phpgeo) - A simple geo library.

### Globalization

Include internationalization (I18n), localization (L10n) and translation

- [Aura.Intl](https://github.com/auraphp/Aura.Intl) - Internationalization tools, particularly message translation (MIT)
- [CakePHP I18n](https://github.com/cakephp/i18n) - Message translation and localization for dates and numbers.

#### HTTP

- [Buzz](https://github.com/kriswallsmith/Buzz) - Another HTTP client.
- [Guzzle]( https://github.com/guzzle/guzzle) - A comprehensive HTTP client.
- [HTTPlug](https://github.com/php-http/httplug) - HTTPlug, the HTTP client abstraction for PHP (MIT)
- [Nyholm PSR-7](https://github.com/Nyholm/psr7) - A super lightweight PSR-7 implementation (MIT)
- [PHP VCR](https://github.com/php-vcr/php-vcr) - Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests (MIT)
- [Requests](https://github.com/WordPress/Requests) - Requests for PHP is a humble HTTP request library. It simplifies how you interact with other sites and takes away all your worries (BSD liked)
- [Retrofit](https://github.com/tebru/retrofit-php) - Retrofit implementation in PHP. A REST client for PHP (MIT)
- [Symfony HTTP Client](https://github.com/symfony/http-client) - A component to fetch HTTP resources synchronously or asynchronously.
- [Laminas Diactoros](https://github.com/laminas/laminas-diactoros) - PSR-7 HTTP Message implementation.

#### Intergration

SDK, client API

- [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php) - The official PHP AWS SDK library.
- [AsyncAWS](https://async-aws.com/) - An unofficial asynchronous PHP AWS SDK.
- [Bref](https://bref.sh/) - helps you go serverless on AWS with PHP (MIT)
- [Campaign Monitor](https://campaignmonitor.github.io/createsend-php/) - The official Campaign Monitor PHP library.
- [Elastica](https://github.com/ruflin/Elastica) - A client library for ElasticSearch.- [Ganesha](https://github.com/ackintosh/ganesha) - A PHP implementation of Circuit Breaker pattern.
- [ElasticSearch PHP](https://github.com/elastic/elasticsearch-php) - The official client library for [ElasticSearch](https://www.elastic.co/).
- [Github](https://github.com/KnpLabs/php-github-api) - A library to interface with the Github API.
- [Instructor for PHP](https://github.com/cognesy/instructor-php) - Structured data outputs with LLMs, in PHP.
- [Jieba-PHP](https://github.com/fukuball/jieba-php) - A PHP port of Python's jieba. Chinese text segmentation for natural language processing.
- [LLPhant](https://github.com/LLPhant/LLPhant) - A comprehensive PHP Generative AI Framework using OpenAI GPT 4. Inspired by Langchain.
- [Mailgun](https://github.com/mailgun/mailgun-php) The official Mailgun PHP API.
- [meilisearch-php](https://github.com/meilisearch/meilisearch-php) - PHP client for Meilisearch (MIT)
- [OpenAI Client](https://github.com/openai-php/client) - OpenAI PHP is a supercharged community-maintained PHP API client that allows you to interact with OpenAI API.
- [OpenAI Client for Laravel](https://github.com/openai-php/laravel) - OpenAI PHP for Laravel is a supercharged PHP API client that allows you to interact with OpenAI API.
- [PHP Mistral AI SDK](https://github.com/SoftCreatR/php-mistral-ai-sdk) - A powerful and easy-to-use PHP SDK for the Mistral AI API, allowing seamless integration of advanced AI-powered features into your PHP projects.
- [Square](https://github.com/square/connect-php-sdk) - The official Square PHP SDK for payments and other Square APIs.
- [Stripe](https://github.com/stripe/stripe-php) - The official Stripe PHP library.
- [Solarium](https://www.solarium-project.org/) - A client library for [Solr](https://solr.apache.org/).
- [SphinxQL Query Builder](https://foolcode.github.io/SphinxQL-Query-Builder/) - A query library for the [Sphinx](https://sphinxsearch.com/) and [Manticore](https://manticoresearch.com/) search engines.
- [Twilio](https://github.com/twilio/twilio-php) - The official Twilio PHP REST API.


#### Image

- [Color Extractor](https://github.com/thephpleague/color-extractor) - A library for extracting colours from images.
- [Glide](https://github.com/thephpleague/glide) - An on-demand image manipulation library.
- [Image Hash](https://github.com/jenssegers/imagehash) - A library for generating perceptual image hashes.
- [Image Optimizer](https://github.com/psliwa/image-optimizer) - A library for optimizing images.
- [Imagine](https://imagine.readthedocs.io/en/latest/index.html) - An image manipulation library.
- [Intervention Image](https://github.com/Intervention/image) - Another image manipulation library.
- [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) - Another image manipulation library.
- [PHP QR Code](https://github.com/chillerlan/php-qrcode/) - QR Code generator and reader.

#### JSON

- [JSON Lint](https://github.com/Seldaek/jsonlint) - A JSON lint utility.
- [JSONMapper](https://github.com/JsonMapper/JsonMapper) - A library for mapping JSON to PHP objects.
- [HAL](https://github.com/blongden/hal) - A Hypertext Application Language (HAL) builder library.

#### Logging

- [Monolog](https://github.com/Seldaek/monolog) - A comprehensive logger.

#### Math

- [Brick Math](https://github.com/brick/math) - A library providing large number support: `BigInteger`, `BigDecimal` and `BigRational`.
- [MathPHP](https://github.com/markrogoyski/math-php) - A math library for PHP.
- [DecimalObject](https://github.com/php-collective/decimal-object) - A value object to handle decimals/floats easily and more precisely.

#### Middleware

- [PSR-15 Middlewares](https://github.com/middlewares/psr15-middlewares) - Inspiring collection of handy middlewares.
- [Relay](https://github.com/relayphp/Relay.Relay) - A PHP 5.5 PSR-7 middleware dispatcher.
- [Laminas Stratigility](https://github.com/laminas/laminas-stratigility) - Middleware for PHP built on top of PSR-7.

#### Multi-Proccesses

- [amphp/process](https://github.com/amphp/process) - An async process dispatcher for Amp (MIT)
- [console-parallelization](https://github.com/webmozarts/console-parallelization) - Enables the parallelization of Symfony Console commands (MIT)

#### Multi-Threads

- [amphp/parallel](https://github.com/amphp/parallel) - An advanced parallelization library for PHP, enabling efficient multitasking, optimizing resource use, and application responsiveness through multiple CPU threads (MIT)
- [ext-pmmpthread](https://github.com/pmmp/ext-pmmpthread) - Fork of https://github.com/krakjoe/pthreads with a revamped API and PHP 8.1+ support (PHP)


#### Navigation

- [KnpMenu](https://github.com/KnpLabs/KnpMenu) - A menu library.
- [Menu](https://github.com/spatie/menu) - A flexible menu library with a fluent interface.

#### Notifications

- [JoliNotif](https://github.com/jolicode/JoliNotif) - A cross-platform library for desktop notification (support for Growl, notify-send, toaster, etc)
- [Notification Pusher](https://github.com/Ph3nol/NotificationPusher) - A standalone library for device push notifications.
- [Notificato](https://github.com/mac-cain13/notificato) - A library for handling push notifications.
- [Notificator](https://github.com/namshi/notificator) - A lightweight notification library.
- [Php-pushwoosh](https://github.com/gomoob/php-pushwoosh) - A PHP Library to easily send push notifications with the Pushwoosh REST Web Services.

#### Network

- [IP](https://github.com/darsyn/ip) - An immutable value object for working with IPv4 and IPv6 addresses.
- [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) - A PHP implementation of Google's phone number handling library.

#### Office

- [lowrapper](https://github.com/mnvx/lowrapper) - PHP wrapper over LibreOffice converter (MIT)
- [PHPPresentation](https://github.com/PHPOffice/PHPPresentation) - A pure PHP library for reading and writing presentations documents (LGPLv3)
- [PHPWord](https://github.com/PHPOffice/PHPWord) - A pure PHP library for reading and writing word processing documents (LGPLv3)
- [PhpSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet) - A pure PHP library for reading and writing spreadsheet files (MIT)
- [Office Convertor](https://github.com/ncjoes/office-converter) - PHP Wrapper for LibreOffice (MIT)
- [OpenSpout](https://github.com/openspout/openspout) - A community driven fork of `box/spout`, a PHP library to read and write spreadsheet files (CSV, XLSX and ODS), in a fast and scalable way.

#### Parser

Parser and renderer for HTML, CSS, Markdown, YAML, TOML

- [Cebe Markdown](https://github.com/cebe/markdown) - A fast and extensible Markdown parser.
- [CommonMark PHP](https://github.com/thephpleague/commonmark) - Highly-extensible Markdown parser which fully supports the [CommonMark spec](https://spec.commonmark.org/).
- [Decoda](https://github.com/milesj/decoda) - A lightweight markup parser library.
- [Essence](https://github.com/essence/essence) - A library for extracting web media.
- [Embera](https://github.com/mpratt/Embera) - An Oembed consumer library.
- [HTML to Markdown](https://github.com/thephpleague/html-to-markdown) - Converts HTML into Markdown.
- [HTML5 PHP](https://github.com/Masterminds/html5-php) - An HTML5 parser and serializer library.
- [JSON Schema](https://github.com/jsonrainbow/json-schema) - A [JSON Schema](https://json-schema.org/) validation library.
- [MetaYaml](https://github.com/romaricdrigon/MetaYaml) - A schema validation library that supports YAML, JSON and XML.
- [Parsedown](https://github.com/erusev/parsedown) - Another Markdown parser.
- [PHP CSS Parser](https://github.com/MyIntervals/PHP-CSS-Parser) - A Parser for CSS Files written in PHP.
- [PHP Markdown](https://github.com/michelf/php-markdown) - A Markdown parser.
- [Shiki PHP](https://github.com/spatie/shiki-php) - A [Shiki](https://github.com/shikijs/shiki) code highlighting package in PHP.
- [VObject](https://github.com/sabre-io/vobject) - A library for parsing VCard and iCalendar objects.
- [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - A library for parsing user agent strings.
- [Stringy](https://github.com/voku/Stringy) - A string manipulation library with multibyte support.
- [Agent](https://github.com/jenssegers/agent) - A PHP desktop/mobile user agent parser, based on Mobiledetect.
- [HTML Purifier](https://github.com/ezyang/htmlpurifier) - A standards compliant HTML filter.
- [Symfony HTML Sanitizer](https://github.com/symfony/html-sanitizer) - An HTML sanitizer library.
- [Negotiation](https://github.com/willdurand/Negotiation) - A content negotiation library.
- [vanodevium/toml](https://github.com/vanodevium/toml) - library for encoding and decoding TOML (MIT)

#### PDF

- [Browsershot](https://github.com/spatie/browsershot) - Convert HTML to an image, PDF or string.
- [Dompdf](https://github.com/dompdf/dompdf) - A HTML to PDF converter.
- [Gotenberg](https://github.com/gotenberg/gotenberg-php) - A PHP client for interacting with Gotenberg.
- [Snappy](https://github.com/KnpLabs/snappy) - A PDF and image generation library.
- [TCPDF](https://github.com/tecnickcom/tcpdf) - Official clone of PHP library to generate PDF documents and barcodes (LGPLv3)

#### Profiling

- [Barbushin PHP Console](https://github.com/barbushin/php-console) - Another web debugging console using Google Chrome.
- [Kint](https://github.com/kint-php/kint) - A debugging and profiling tool.
- [Metrics](https://github.com/beberlei/metrics) - A simple metrics API library.
- [PCOV](https://github.com/krakjoe/pcov) - A self-contained code coverage compatible driver.
- [PHP Console](https://github.com/Seldaek/php-console) - A web debugging console.
- [php-debugbar](https://github.com/php-debugbar/php-debugbar) - Debug bar for PHP (MIT)
- [PHPBench](https://github.com/phpbench/phpbench) - A benchmarking Framework.
- [PHPSpy](https://github.com/adsr/phpspy) - A low-overhead sampling profiler.
- [Tracy](https://github.com/nette/tracy) - A simple error detection, logging and time measuring library.
- [Whoops](https://github.com/filp/whoops) - A pretty error-handling library.
- [Xdebug](https://github.com/xdebug/xdebug) - Step Debugger and Debugging Aid for PHP (PHP liked)
- [XHProf](https://github.com/phacility/xhprof) - A profiling tool originally developed by Facebook.
- [Z-Ray](https://www.zend.com/products/z-ray) - enterprise-level PHP debugger that comes with Zend Server (commercial)
- [Blackfire](https://www.blackfire.io) - fastest way to spot bottlenecks in your PHP & Python code (commercial)

#### Queue

- [Bernard](https://github.com/bernardphp/bernard) - A multibackend abstraction library.
- [BunnyPHP](https://github.com/jakubkulhan/bunny) - A performant pure-PHP AMQP (RabbitMQ) sync and also async (ReactPHP) library.
- [Pheanstalk](https://github.com/pheanstalk/pheanstalk) - A Beanstalkd client library.
- [PHP AMQP](https://github.com/php-amqplib/php-amqplib) - A pure PHP AMQP library.
- [Tarantool Queue](https://github.com/tarantool-php/queue) - PHP bindings for Tarantool Queue.
- [Thumper](https://github.com/php-amqplib/Thumper) - A RabbitMQ pattern library.
- [Enqueue](https://github.com/php-enqueue/enqueue-dev) - A message queue packages for PHP that supports RabbitMQ, AMQP, STOMP, Amazon SQS, Redis and Doctrine transports.

#### Router

- [Aura.Router](https://github.com/auraphp/Aura.Router) - A full-featured routing library.
- [Fast Route](https://github.com/nikic/FastRoute) - A fast routing library.
- [Klein](https://github.com/klein/klein.php) - A flexible router.
- [Pux](https://github.com/c9s/Pux) - Another fast routing library.
- [Route](https://github.com/thephpleague/route) - A routing library built on top of Fast Route.

#### Security

- [AntiXSS](https://github.com/voku/anti-xss) - A library that tries to preventing Cross-Site Scripting (XSS) attacks by blacklisting.
- [Halite](https://github.com/paragonie/halite) - High-level cryptography interface powered by [libsodium](https://github.com/jedisct1/libsodium) (MIT)
- [Optimus](https://github.com/jenssegers/optimus) - Id obfuscation based on Knuth's multiplicative hashing method.
- [PHPGGC](https://github.com/ambionics/phpggc) - A library of PHP unserializable payloads along with a tool to generate them.
- [PHP Encryption](https://github.com/defuse/php-encryption) - Secure PHP Encryption Library.
- [PHPSecLib](https://github.com/phpseclib/phpseclib) - PHP Secure Communications Library (MIT)
- [random_compat](https://github.com/paragonie/random_compat) - PHP 5.x support for `random_bytes()` and `random_int()`
- [Roave Security Advisories](https://github.com/Roave/SecurityAdvisories) - This package ensures that your application doesn't have installed dependencies with known security vulnerabilities.
- [Secure Headers](https://github.com/BePsvPT/secure-headers) - A package that adds security related headers to HTTP response.
- [Zap](https://github.com/zaproxy/zaproxy) - An integrated penetration testing tool for web applications.
- [GenPhrase](https://github.com/timoh6/GenPhrase) - A library for generating secure random passphrases.
- [Password Compat](https://github.com/ircmaxell/password_compat) - A compatibility library for the new PHP 5.5 password functions.
- [Password Policy](https://github.com/ircmaxell/password-policy) - A password policy library for PHP and JavaScript.
- [Password Validator](https://github.com/jeremykendall/password-validator) - A library for validating and upgrading password hashes.
- [Password-Generator](https://github.com/hackzilla/password-generator) - PHP library to generate random passwords.
- [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) - A library for generating and validating passwords.
- [phpass](https://github.com/openwall/phpass) - Legacy password hashing framework for PHP applications needing to support or having previously supported PHP below 5.5 (Public Domain)
- [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) - A realistic PHP password strength estimate library based on Zxcvbn JS.
- [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's noCAPTCHA (reCAPTCHA).
- [Safe](https://github.com/thecodingmachine/safe) - All PHP functions, rewritten to throw exceptions instead of returning false.
- [RobThree/TwoFactorAuth](https://github.com/RobThree/TwoFactorAuth) - Two Factor Authentication (TFA / 2FA) (MIT)
- [Laragear/WebAuthn](https://github.com/Laragear/WebAuthn) - Authenticate users with Passkeys: fingerprints, patterns and biometric data (MIT)

#### Static Analysis

- [Exakat](https://github.com/exakat/exakat) - A static analysis engine for PHP.
- [Deptrac](https://github.com/qossmic/deptrac) - A static code analysis tool that helps to enforce rules for dependencies between software layers.
- [Mondrian](https://github.com/Trismegiste/Mondrian) - A code analysis tool using Graph Theory.
- [phan](https://github.com/phan/phan) - A static analyzer based on PHP 7+ and the php-ast extension.
- [PHP Architecture Tester](https://github.com/carlosas/phpat) - Easy-to-use architecture testing tool for PHP.
- [PHPCompatibility](https://github.com/PHPCompatibility/PHPCompatibility) - A PHP compatibility checker for PHP CodeSniffer.
- [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - A tool to create customizable dependency graphs.
- [PHPDoc Parser](https://github.com/phpstan/phpdoc-parser) - Next-gen phpDoc parser with support for intersection types and generics
- [PHP Metrics](https://github.com/phpmetrics/PhpMetrics) - A static metric library.
- [PHP Migration](https://github.com/monque/PHP-Migration) - A static analyzer for PHP version migration.
- [PHPStan](https://github.com/phpstan/phpstan) - A PHP Static Analysis Tool.
- [Psalm](https://github.com/vimeo/psalm) - A static analysis tool for finding errors in PHP applications.

#### Stream

- [Streamer](https://github.com/fzaninotto/Streamer) - A simple object-orientated stream wrapper library.

#### Task Runner and Scheduler

- [Jobby](https://github.com/jobbyphp/jobby) - A PHP cron job manager without modifying crontab.
- [Robo](https://github.com/consolidation/Robo) - A PHP Task runner with object-orientated configurations.
- [Task](https://github.com/taskphp/task) - A pure PHP task runner inspired by Grunt and Gulp.
- [Envoy](https://github.com/laravel/envoy) - A tool to run SSH tasks with PHP.

#### Template

- [Latte](https://github.com/nette/latte) - safest & truly intuitive templates for PHP (GPL, BSD)
- [MtHaml](https://github.com/arnaud-lb/MtHaml) - A PHP implementation of the HAML template language.
- [Mustache](https://github.com/bobthecow/mustache.php) - A PHP implementation of the Mustache template language.
- [PHPTAL](https://github.com/phptal/PHPTAL) - template engine for XSS-proof well-formed XHTML and HTML5 pages (LGPLv2)
- [Plates](http://platesphp.com/) - A native PHP templating library.
- [Smarty](https://github.com/smarty-php/smarty) - template engine for PHP, facilitating the separation of presentation (HTML/CSS) from application logic (LGPLv3)
- [Twig](https://github.com/twigphp/Twig) - flexible, fast, and secure template language for PHP (BSDv3)
- [Laravel Mix](https://github.com/laravel-mix/laravel-mix ) - An elegant wrapper around Webpack for the 80% use case.
- [Symfony Asset](https://github.com/symfony/asset) - Manages URL generation and versioning of web assets.
- [Symfony Encore](https://github.com/symfony/webpack-encore) - A simple but powerful API for processing and compiling assets built around Webpack.

#### Testing

- [Alice](https://github.com/nelmio/alice) - An expressive fixture generation library.
- [AspectMock](https://github.com/Codeception/AspectMock) - The most powerful and flexible mocking framework for PHPUnit / Codeception (MIT)
- [Atoum](https://github.com/atoum/atoum) - A simple testing library.
- [Behat](https://docs.behat.org/en/latest/) - A behaviour driven development (BDD) testing framework.
- [Codeception](https://github.com/Codeception/Codeception) - A full stack testing framework.
- [Faker](https://github.com/fakerphp/faker) - A fake data generator library.
- [Foundry](https://github.com/zenstruck/foundry) - A fixture factory generation library for Doctrine.
- [Infection](https://github.com/infection/infection) - An AST-based PHP Mutation testing framework.
- [Kahlan](https://github.com/kahlan/kahlan) - Full stack Unit/BDD testing framework with built-in stub, mock and code-coverage support.
- [Mockery](https://github.com/mockery/mockery) - A mock object library for testing.
- [Nette Tester](https://github.com/nette/tester) - A productive and enjoyable parallel unit testing framework.
- [ParaTest](https://github.com/paratestphp/paratest) - A parallel testing library for PHPUnit.
- [Pest](https://github.com/pestphp/pest) - an elegant PHP testing Framework with a focus on simplicity, meticulously designed to bring back the joy of testing (MIT)
- [Phake](https://github.com/phake/phake) - Another mock object library for testing.
- [PHP-Mock](https://github.com/php-mock/php-mock) - A mock library for built-in PHP functions (e.g. time()).
- [PHP MySQL Engine](https://github.com/vimeo/php-mysql-engine) -  A MySQL engine written in pure PHP.
- [PHPSpec](https://github.com/phpspec/phpspec) - A design by specification unit testing library.
- [PHPT](https://qa.php.net/write-test.php) - A test tool used by PHP itself.
- [PHPUnit](https://github.com/sebastianbergmann/phpunit) - A unit testing framework.
- [PHPUnit Polyfills](https://github.com/Yoast/PHPUnit-Polyfills/) - Simplifies running PHPUnit tests on multiple PHPUnit versions.
- [Prophecy](https://github.com/phpspec/prophecy) - A highly opinionated mocking framework.
- [VFS Stream](https://github.com/bovigo/vfsStream) - A virtual filesystem stream wrapper for testing.
- [Better Reflection](https://github.com/Roave/BetterReflection) - AST-based reflection library that allows analysis and manipulation of code
- [Assert](https://github.com/beberlei/assert) - A validation library with a rich set of assertions. Supports assertion chaining and lazy assertions.

#### URL

- [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - A domain suffix parser library.
- [Purl](https://github.com/jwage/purl) - A URL manipulation library.
- [sabre/uri](https://github.com/sabre-io/uri) - A functional URI manipulation library.
- [Uri](https://github.com/thephpleague/uri) - Another URL manipulation library.
- [glenscott/url-normalizer](https://github.com/glenscott/url-normalizer) - Syntax based normalization of URI's (MIT)

#### Validator

- [Filterus](https://github.com/ircmaxell/filterus) - A simple PHP filtering library.
- [Aura.Filter](https://github.com/auraphp/Aura.Filter) - Provides tools to validate and sanitize objects and arrays.
- [CakePHP Validation](https://github.com/cakephp/validation) - Another validation library.
- [Upload](https://github.com/brandonsavage/Upload) - A library for handling file uploads and validation.
- [Valitron](https://github.com/vlucas/valitron) - Another validation library.
- [Volan](https://github.com/serkin/Volan) - Another simplified validation library.
- [Respect Validation](https://github.com/Respect/Validation) - A simple validation library.
- [Valinor](https://github.com/CuyZ/Valinor) - A library for mapping to strongly typed value objects.

#### Video

- [PHP FFmpeg](https://github.com/PHP-FFmpeg/PHP-FFmpeg/) - A wrapper for the [FFmpeg](https://www.ffmpeg.org/) video library.

#### Misc

- [Finite](https://github.com/yohang/Finite) - A simple PHP finite state machine.
- [Functional PHP](https://github.com/lstrojny/functional-php) - A functional programming library.
- [Iter](https://github.com/nikic/iter) - A library that provides iteration primitives using generators.
- [IterTools PHP](https://github.com/markrogoyski/itertools-php) - A library that provides functionality for working with iterable entities (similar to itertools library in Python).
- [Pipeline](https://github.com/thephpleague/pipeline) - A pipeline pattern implementation.
- [Porter](https://github.com/ScriptFUSION/Porter) - Data import abstraction library for consuming Web APIs and other data sources.
- [RulerZ](https://github.com/K-Phoen/rulerz) - A powerful rule engine and implementation of the Specification pattern.
- [UUID](https://github.com/ramsey/uuid) - A library for generating UUIDs.
- [Url highlight](https://github.com/vstelmakh/url-highlight) - A library for parsing URLs from text and converting them into clickable links.
- [URLify](https://github.com/jbroadway/urlify) - A PHP port of Django's URLify.js.
- [Device Detector](https://github.com/matomo-org/device-detector) - Another library for parsing user agent strings.
- [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - A lightweight PHP class for detecting mobile devices (including tablets).
- [ISO-codes](https://github.com/ronanguilloux/IsoCodes) - A library for validating inputs according to standards from ISO, International Finance, Public Administrations, GS1, Book Industry, Phone numbers & Zipcodes for many countries.
- [Lock](https://github.com/php-lock/lock) - A lock library to provide exclusive execution.
- [Hprose-PHP](https://github.com/hprose/hprose-php) - A cross-language RPC.
- [Laravel Serializable Closure](https://github.com/laravel/serializable-closure) - A library that allows Closures to be serialized.
- [Pagerfanta](https://github.com/whiteoctober/Pagerfanta) - A pagination library.
- [ProxyManager](https://github.com/Ocramius/ProxyManager) - A set of utilities to generate proxy objects for data mappers.

### Framework

- [AMP](https://github.com/amphp/amp) - non-blocking concurrency framework for PHP applications (MIT)
- [CakePHP](https://cakephp.org/) - A rapid application development framework.
- [CodeIgniter](https://codeigniter.com/) - A powerful PHP framework with a very small footprint.
- [FuelPHP](https://github.com/fuel/fuel) - simple, flexible, community driven PHP 5.3+ (MIT)
- [Laminas](https://getlaminas.org/) - A framework comprised of individual components (previously Zend Framework).
- [Laravel](https://laravel.com/) - A web application framework with expressive, elegant syntax.
- [Nette](https://nette.org) - A web framework comprised of mature components.
- [Phalcon](https://phalcon.io/en-us) - A framework implemented as a C extension.
- [Spiral](https://spiral.dev/) - A high-performance PHP/Go framework.
- [Symfony](https://symfony.com/) - A set of reusable components and a web framework.
- [ReactPHP](https://github.com/reactphp/reactphp) - Event-driven, non-blocking I/O with PHP (MIT)
- [Yii2](https://github.com/yiisoft/yii2/) - A fast, secure, and efficient web framework.
- [Laravel Zero](https://laravel-zero.com) - A micro-framework for console applications.
- [Mezzio](https://getexpressive.org/) - A micro-framework by Laminas.
- [Minicli](https://github.com/minicli/minicli) - Minimalist, dependency-free framework for building CLI-centric PHP applications.
- [Silly](https://github.com/mnapoli/silly) - A micro-framework for CLI applications.
- [Slim](https://www.slimframework.com/) - Another simple micro framework.
- [Slim Skeleton](https://github.com/slimphp/Slim-Skeleton) - A skeleton for Slim.
- [Slim Twig View](https://github.com/slimphp/Slim-Views) - Integrate Twig into Slim.
- [Slim PHP View](https://github.com/slimphp/PHP-View) - A simple PHP renderer for Slim.
- [Symfony](https://github.com/symfony/symfony) - for web and console applications and a set of reusable PHP components (MIT)
- [CakePHP CRUD](https://github.com/friendsofcake/crud) - A Rapid Application Development (RAD) plugin for CakePHP.
- [LaravelS](https://github.com/hhxsv5/laravel-s) - An out-of-the-box adapter between Laravel/Lumen and Swoole.
- [Livewire](https://livewire.laravel.com/) - Powerful, dynamic, front-end UIs without leaving PHP.
- [Swoole](https://github.com/swoole/swoole-src) - Coroutine-based concurrency library for PHP (Apache)
- [BotMan](https://github.com/botman/botman) - A framework agnostic PHP library to build cross-platform chatbots.
- [TinnkPHP](https://github.com/top-think/framework) - simple, lightweight framework (Apache2)
- [Workerman](https://github.com/walkor/Workerman) - An asynchronous event driven PHP socket framework (MIT)

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

#### Photo and Video

- [Lychee](https://github.com/LycheeOrg/Lychee) - Great looking and easy-to-use photo-management-system (MIT)

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

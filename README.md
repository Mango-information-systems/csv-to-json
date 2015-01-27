csv-to-json
=============

Online CSV to JSON converter

Easy, privacy-friendly and offline-first online csv to json converter

##Features

* Offline-first: once the page is loaded, you should be able to use the app without an Internet connection.
* Privacy friendly: all the processing is done in the browser.
* Easy to use: Minimalist and straightforward UI (hopefully).

##How to use

This app is a static site built with [jekyll](http://jekyllrb.com/). Tested with jekyll v1.2.1

1. First, you need to setup the `_config.yml` file. You may use the sample file `sample-_config.yml` as a base.
2. Build with this command: `jekyll build`. The converter is saved at `{{base-url}}/csv-to-json.html`.
3. Host wherever you want or use locally.

##Featuring

* mozilla's [localforage](https://github.com/mozilla/localForage)
* [papaParse](https://github.com/mholt/PapaParse) javascript CSV parser

##Fork

If you fork, please remove our branding (logo and company name) from your interface in order to avoid confusion.

##About

Here is some background about the project.

This converter was built with two purpose:

* be used internally,
* experiment with the development of an offline-friendly HTML5 web app.

At time of creation of the app the website of Mango Information Systems was about to be fully rebuild from scratch using another technology architecture, meaning this tool would probably be re-written soon.

With this in mind, priority has been put on **getting things done** rather than elegance of the architecture.

The CSV parser used is however cleaner and includes test, cf. [papaParse](https://github.com/mholt/PapaParse).

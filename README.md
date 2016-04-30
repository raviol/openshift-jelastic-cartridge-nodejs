# Jelastic NodeJS Cartridge
This cartridge provides [Node.js](http://nodejs.org/) on Jelastic Platform.

**Node.js** is a cross-platform environment for server-side and networking applications. Node.js applications are written in JavaScript and can be run on different platforms with no changes. Source code is compiled with the help of Google V8 engine, what gives a possibility to connect external libraries, even that are written in different language, and allows JavaScript to interact with input/output devices through Node.js API. 

The goal of Node.js is to offer an easy and safe way to build high performance and scalable network applications. It uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, and is able to handle many client connections at the same time.

For more details refer to the [Jelastic documentation](http://docs.jelastic.com/deploy-nodejs-archive-url).

Follow the [link](http://ops-docs.jelastic.com/private-add-cartridge) in order to find out how to enable the current cartridge at Jelastic dashboard.

### What Jelastic cartridge is?

Jelastic [Platform-as-Infrastructure](http://docs.jelastic.com/what-is-platform-as-infrastructure) supports **OpenShift’s cartridge model** to make it easier for independent software vendors (ISVs) offering core services in multiple platforms and for a wider array of cloud ecosystems and marketplaces. This open standard for technology packaging and deployment enables ISVs and end-users to integrate their own middleware, databases, and services into the platform and make them available to PaaS developers building applications.

A **cartridge** is an advanced packaging format. In our case, it is represented with existing OpenShift cartridge specifications, extended with Jelastic configurations, to provide more complex functionality and the ability to make adjustments in Jelastic. This additional tuning is required based on the difference between the architectures of the two platforms (Jelastic and OpenShift).

Such configuration is quite easy - you just need to fork a basic cartridge and add custom settings. Detailed instruction on how to create your own cartridge can be seen [here](http://ops-docs.jelastic.com/create-cartridge).


### How to add a cartridge to Jelastic Cloud?

Ready cartridge (your own or one of those we’ve already prepared for you) can be added to the Jelastic PaI via JCA. After that it should be tested and published in order to become available through the dashboard. Find out the details in [this](http://ops-docs.jelastic.com/private-add-cartridge) instruction.

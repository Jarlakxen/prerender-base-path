prerender-base-path
===================

Prerender plugin for set a base path, to be used with the prerender node application from https://github.com/prerender/prerender.

How to use
----------

In your local prerender project run:

    $ npm install prerender-base-path --save
    
Then in the server.js that initializes the prerender:

    server.use(require('prerender-base-path'));

Configuration
-------------

You need to set `SERVER_BASE_PATH` environment variables to specify the base path of the server.
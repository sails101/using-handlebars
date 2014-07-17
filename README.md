# Sails with Handlebars

This repository is a demo using Handlebars templating engine on Sails with views and layout.
Feel free to download, clone or fork it as you want.

If you already are working on a Sails project using an other templating engine, here are the steps:
* Install Handlebars dependency with ```npm install handlebars [--save]```.
* In ```config/views.js``` change ```ejs``` to ```handlebars``` for the templating engine.
* Change extension name of your files to ```.handlebars```.
* In your ```layout.handlebars``` change ```<%- body %>``` to ```{{{ body }}}```.
* You are now able to lift your server with Handlebars as templating engine.

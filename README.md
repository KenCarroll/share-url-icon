# share-url-icon

This is a demo of how to create reusable web components using polymer
It is based on the following Polymer 2.0 tutorial(https://www.polymer-project.org/2.0/start/first-element/intro).

## Data Down, Events Up

This webcomponent provides propertites to allow the user to configure certain aspects of the icon

When the share is complete the component generates an event.

## Running the tutorial code

You'll need to install some command-line tools to manage dependencies and to run the demo.

1.  Download and install Node version 6.x or 7.x from [https://nodejs.org/](https://nodejs.org/). Node includes the node package manager command, `npm`.

2.  Install `bower` and the Polymer CLI:

        npm install -g bower polymer-cli

3.  Clone this repo:

        https://github.com/KenCarroll/share-url-icon
        
4.  Change directory to your local repo and install dependencies with `bower`:

        cd share-url-icon
        bower install
        
5.  To preview your element, run the Polymer development server from the repo directory:

        polymer serve --open
        

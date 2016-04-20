# Google App Engine Flexible Environment Servlet API Hello World

This sample demonstrates how to deploy an application on Google App Engine.

It includes an example web.xml that redirects unknown URLs to a custom 404 page.

## Setup
1. Update the `<application>` tag in `src/main/webapp/WEB-INF/appengine-web.xml`
   with your project name.
1. Update the `<version>` tag in `src/main/webapp/WEB-INF/appengine-web.xml`
   with your version name.

## Running locally
    $ mvn gcloud:run

## Deploying
    $ mvn gcloud:deploy

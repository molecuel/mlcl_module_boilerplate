# molecuel module Boilerplate

This is a boilerplate for the module development for the molecuel Framework. We are using typescript and compile the code to es6. The code is compatible to node versions > 4.X.

## Starting the development

First you need to initialize the typings. Execute typings install in the the project directory. Typings need to be installed globally with npm install -g typings.

Execute gulp in the module project directory. The default gulp task watches for changes in the code. We are using typescript compilation with gulp to be independent from any development environments.

## What is missing?

Currently the unit tests implementation from older framework versions has not been yet upgraded to fit into the gulp workflow. This is coming soon. Until then the unit tests need to be run manually.

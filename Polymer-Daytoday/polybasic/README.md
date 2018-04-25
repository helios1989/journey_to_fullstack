To install bower
npm install -g bower
npm install -g polymer-cli
bower install Polymer/polymer#^2.0.0
1.Create a test index.html file, and add the following in the <head> tag:
2.
<script src="/bower_components/webcomponentsjs/webcomponents-loader.js"></script> to load the polyfills
<link rel="import" href="/bower_components/polymer/polymer.html"> to import Polymer
Import and use whichever elements you’d like.

Serve your project.

3. polymer serve
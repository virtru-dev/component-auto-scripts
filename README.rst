component-auto-scripts - Automatically find scripts for component.json
======================================================================

A simple script that automatically finds scripts for component.json.

Usage
-----

To match `*.js` and `lib/*.js`, just do::
    
    $ component auto-scripts *.js,lib/*.js

If you are using component-test-build then you can also specify testScripts::
    
    $ component auto-scripts *.js,lib/*.js --test-scripts tests/*.js,tests/**.js

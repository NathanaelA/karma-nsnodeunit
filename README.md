# karma-nsnodeunit
Adapter for the Nodeunit testing framework for NativeScript. 

This is based on both the Karma-NodeUnit located at https://github.com/karma-runner/karma-nodeunit
And the actual nodeunit from https://github.com/caolan/nodeunit 
They have both been modified to work inside the NativeScript test runner environment.

## Usage
1. `tns test init`  To initialize the testing system, Choose Mocha.
1. `npm install karma-nsnodeunit --save-dev`
2. Update the `karma.conf.js` file and set the `frameworks: ['nsnodeunit']`
3. Write your nodeunit tests inside the app/tests folder.

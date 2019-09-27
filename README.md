# etherlime_es6

Small example of repo that would work with truffle but not etherlime due to use of es6 syntax in the test scripts.

Based off "metacoin" truffle example. 

Offending line is: `import expectThrow from './helpers/expectThrow';` in metacoin.js


Master branch is working truffle version.
Etherlime branch is the setup for etherlime after conversion from working truffle version (compiles but test fails).
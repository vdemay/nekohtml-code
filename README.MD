# NekoHTML 
This is a fork of official svn Neko repository: https://sourceforge.net/p/nekohtml

## Fixes since Fork

##### 1.9.22.p1
 - Allow NOSCRIPT tag in HEAD tag (HTML5 compliance)

## Building

You can build NekoHTML by typing the following command:

  > ant (target ...)

The default target will build the entire package.

To build NekoHTML, you need Ant and Xerces2. Place the Xerces jar 
files in the lib/ directory.

## Deploy for Maven
  > ant deploy-mvn-local 
  
will generate maven directory in ./mvn/...
With a dependency to xerces

## Documentation

The documentation for NekoHTML is located at the following URL: doc/index.html

## Contact Information

Original maintainer: Andy Clark <andyc@apache.org>

Patches: Vincent Demay 

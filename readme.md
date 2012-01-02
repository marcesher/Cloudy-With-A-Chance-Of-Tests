# readme

## What is Cloudy With A Chance Of Tests?

Cloudy With A Chance Of Tests is a pared down ant build.xml. Some targets in the build.xml are purposely left blank for place holders. You may eventually add more to the build.xml for your process by completing them but it isn't necessary. Who knows maybe you'll start using MXUnit and refactoring your code so it is more testable but it isn't needed in this first step :-) 

The build.xml should be able to be used without any CFML code changes to your code base and only a few changes to build.properties that match your environment. 

This build.xml can be used for Continuous Integration with ColdFusion (without or with more tests). A syntax and other specific CFML checks will occur setting the stage for more testing and other progressions in the build.xml and your code base.

Have fun, this is a journey not a sprint. Introduce this easy step, sit back and wait till your chance to do more.

## Installation

This build script is decoupled from the environment you can execute it in the command prompt, Eclipse IDE, or Jenkins with just a few changes to build.properties. 

Please add the build.xml to your source control system in your top level folder and ignore the build.properties. You will have to change some build.properties settings to match the environment it will run on. 

Add the lib folder with the jar at the top level of the project. 

To run the VarScope, QueryParam, and ColdDoc, you will need to download and place them in the top level of the web server (not just the project top level). I would recommend excluding them from your source control system.

* http://varscoper.riaforge.org/

* http://qpscanner.riaforge.org/

* http://colddoc.riaforge.org/

## License

This is licensed under [Creative CommonsAttribution-Noncommercial-Share Alike 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) except for third party software which retains their licenses. 

## Contributors / Originators

Please add yourself if you help:

* @denstar

* @vitrix

* @lmajano

## Git Workflow for Contributors

This project uses the excellent [Git Workflow series](http://www.silverwareconsulting.com/index.cfm/Git-Workflow) by [Bob Silverburg](https://github.com/bobsilverberg/) for contributions.

## Dealing with line endings

Before contributing, please read this [http://help.github.com/dealing-with-lineendings/](http://help.github.com/dealing-with-lineendings/)
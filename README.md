# dr.build
Build magic to fix everything

Checks out and composite-builds a "virtual mono-repo"  
of various [We The Internet](https://github.com/WeTheInternet) projects.

To add your own projects (gradle, maven or sh), see [settings.gradle].

`./gradlew build` will initialize a `"$rootDir/repo"` directory,  
suitable to be consumed by other builds.

You may wish to add your own code to a fork of this repository,  
or simply check-out-and-build the project,  
so you can add our tools to your classpath  
and build solutions directly into your build.

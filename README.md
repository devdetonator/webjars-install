##Install Chance.js and URI.js webjars to your local Maven repository
* Clone this GIT repository
`git clone https://github.com/devdetonator/webjars-install.git`

* Install chance.js 0.5.4
`mvn install:install-file -Dfile=chancejs-0.5.4.jar -DgroupId=org.webjars -DartifactId=chancejs -Dversion=0.5.4 -Dpackaging=jar`

* Install URI.js 1.12.0
`mvn install:install-file -Dfile=urijs-1.12.0.jar -DgroupId=org.webjars -DartifactId=urijs -Dversion=1.12.0 -Dpackaging=jar`

* Enjoy boobs
![alt tag](https://raw.github.com/devdetonator/webjars-install/master/logo.jpg)

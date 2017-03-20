# maven-repo

## repo url

* https://raw.githubusercontent.com/zoowii/maven-repo/master
* https://coding.net/u/zoowii/p/maven-repo/git/raw/master


## artifact url

* https://raw.githubusercontent.com/zoowii/maven-repo/master/path/of/group/artifactName/version/pomName.pom

## Add jars

* `mvn install:install-file  -Dfile=path-to-your-artifact-jar  -DgroupId=your.groupId  -DartifactId=your-artifactId   -Dversion=version     -Dpackaging=jar  -DlocalRepositoryPath=path-to-specific-local-repo`

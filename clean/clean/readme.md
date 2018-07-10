# Maven Clean

## Clean the Project

Maven clean attempts to clean a project's working directory of the files that we're generated at build-time generated inside the target directoryBy default, it discovers and deletes the directories configured in project.build.directory, project.build.outputDirectory, project.build.testOutputDirectory, and project.reporting.outputDirectory.


Navigate to the folder which has the Project Object Model.

```terminal
$ mvn package
```

```terminal
$ ls
```

### Project Directory before maven clean after package
.
├── target                  # Build Time Generated Folder
├── pom.xml                 # Project Object Model
└── readme.md


```terminal
$ mvn clean
```


```terminal
$ ls
```
### Project Directory after maven clean
.
├── pom.xml                 # Project Object Model
└── readme.md

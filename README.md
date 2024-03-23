# WARNINGS

* Will cherry pick code changes only for the archiver appliance codes, **NOT** tests, styles, and so on
* Will test it within a local environment accordingly
* Will not Release and Tag within history


# THOUGHTS

This repository uses a legacy build system that is different from the community EPICS archiver appliance repository, which recently became inoperable due to the removal of the Ant build system.

Migrating to the community's Gradle build system is challenging. Our resource constraints and lack of familiarity with Gradle make adoption difficult. There's no clear benefit to learning Gradle for our specific needs (accelerator control system) at this time.

In addition, the current build system has significant drawbacks:

    Requires a specific and recent version of Gradle.
    Uses a mix of Gradle styles, making it difficult to understand and maintain.
    Relies on the Gradle wrapper, which prevents standard Gradle build commands from using the system's default version of Gradle.

Given these factors and the wider adoption of Maven in EPICS Java applications, migrating to Maven may be a more strategic choice.


In my opinion, migrating to Tomcat 10 should be a higher priority than building the system.


# Cherry-picking, Merging, and manually selected files

Thanks Git for diverting our works easily every before.
The baseline of this repository from `835061f` and the following individual commits are selected due to my own reviews

- Commit `dea7acb`
- Commit `8b4f22e`



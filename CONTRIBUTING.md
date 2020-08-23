## Getting started 

- To learn about forking the project, read the instructions on the following page: https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/

## Release checklist

- Cleanup change notes for the new version in `src/main/resources/META-INF/plugin.xml`
- Make sure `sinceBuild` and `untilBuild` are updated in `build.gradle` and support the latest released version of IntelliJ (optimally also the next EAP).
- Ensure that the plugin is checked in CI together with the `untilBuild` IntelliJ version.
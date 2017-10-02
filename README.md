1. Create a `sonar-project.properties` files to store your configuration - like `sonar.projectKey` or `sonar.sources`
  2. In your `.travis.yml` file:
 -  1. Activate the [Travis Add-on](https://docs.travis-ci.com/user/sonarqube/)
 -  2. Run `sonar-scanner` at some point of time in the `script` section
 +   1. Activate the [Travis Add-on](https://docs.travis-ci.com/user/sonarcloud/)
 +   2. Run `sonar-scanner` at some point of time in the `script` section
  
  You can take a look at the
  [sonar-project.properties](https://github.com/SonarSource/sq-com_example_standard-sqscanner-travis/blob/master/sonar-project.properties)

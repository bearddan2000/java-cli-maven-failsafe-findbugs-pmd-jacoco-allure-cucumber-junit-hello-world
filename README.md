# java-cli-maven-failsafe-findbugs-pmd-jacoco-allure-cucumber-junit-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using junit5
and cucumber framework with jacoco,
pmd, allure, failsafe and surefire plugins.

Serves allure report from link given
after the build.

## Tech stack
- java
- maven
	- findbugs
  - junit5
	- failsafe
  - surefire
  - jacoco
  - cucumber
  - pmd
	- allure

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco
- pmd report found at bin/target/site
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Jacoco config](https://www.baeldung.com/jacoco)

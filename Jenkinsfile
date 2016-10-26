#!groovy

@Library('github.com/toyoyo7/multibranch-demo-lib') _

/*** Build the eboutique project components ***/

stage concurrency: 1, name: 'Build'
master {
 helloWorld("Joe")
 acme.foo = "5";
 echo acme.foo;
 acme.say "Joe";
 /*jenkinsPlugin {
    name = 'git'
 }*/ 
}

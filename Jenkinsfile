#!/usr/bin/env groovy

node {
  tool 'M3'
  echo 'kubrix-platform build started...' 
  
  stage('Build') {
    withMaven(maven: 'M3') {
      sh "ls"
      sh "mvn clean deploy"
    }
  }
}

pipeline {
  agent any
  stages {
    stage ('Build DOcker image'){
      steps {
         sh "docker build -t jenkinstraining.azurccr.io/sample-docker-image-66557:$BUILD_NUMBER ." 
      }
    }
    stage ('Push image'){
      environment {
          DOCKER_CONFIG = credentials('
  } 
}

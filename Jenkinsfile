pipeline {
  agent any
  stages {
    stage('Build todo api') {
      agent {
        docker {
          image 'maven:3.6.3-adoptopenjdk-8'
        }

      }
      steps {
        sh 'mvn package'
      }
    }

  }
}
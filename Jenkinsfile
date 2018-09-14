pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh './jenkins/build.sh'
        archiveArtifacts 'target/*.jar'
      }
    }
  }
}
pipeline {
  agent { docker { image 'maven:3.9.3' } }
  stages {
    stage('build') {
      steps {
        sh 'mvn --version'
      }
    }
  }
}

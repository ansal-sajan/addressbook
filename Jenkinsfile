pipeline {
  agent any
  tools {
    maven 'local-maven'
  }
  stages {
    stage('Build') {
      steps {
        echo "Building"
        sh 'mvn compile'
      }
    }
    stage('Package') {
      steps {
        echo "Packaging"
        sh 'mvn package'
      }
    }
  }
}

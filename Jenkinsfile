pipeline {
  agent any
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

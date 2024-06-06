pipeline {
  agent {
    docker { image 'python:3.9-alpine' }
  }
  stages {
    stage('Checkout') {
      steps {
        // Checkout the source code from the Git repository
        git 'https://your-repo-url.git'
      }
    }
    stage('Run') {
      steps {
        // Run the Python script
        sh 'python hello.py'
      }
    }
  }
}

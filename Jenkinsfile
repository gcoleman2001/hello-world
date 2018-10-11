pipeline {
  agent any
  stages {
    stage('Review') {
      steps {
        fileExists 'Casting.py'
      }
    }
    stage('Run the file') {
      steps {
        sh 'python Casting.cy'
      }
    }
  }
}
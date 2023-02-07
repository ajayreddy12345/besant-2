pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        nodejs('my-node') {
          sh 'npm install'
        }

      }
    }

    stage('') {
      steps {
        nodejs('my-node') {
          sh 'ng build '
        }

      }
    }

  }
}
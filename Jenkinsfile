pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        parallel(
          "Build X": {
            echo '1'
            
          },
          "What?": {
            echo '2'
            
          }
        )
      }
    }
    stage('Test') {
      steps {
        echo '3'
        waitUntil() {
          echo '4'
        }
        
      }
    }
  }
}
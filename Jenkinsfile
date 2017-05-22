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
    stage('') {
      steps {
        echo '3'
      }
    }
  }
}
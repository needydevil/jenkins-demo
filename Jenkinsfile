pipeline {
  agent any
  
  stages {
    stage('Build') {
      steps {
        echo 'Building from Jenkinsfile...'
      }
    }

    stage('Test') {
      steps {
        echo 'Running tests from Jenkinsfile...'
      }
    }
  }

  post {
    always {
      echo 'Pipeline completed.'
    }
  }
}

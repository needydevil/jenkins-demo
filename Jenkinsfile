pipeline {
  agent any
  
  stages {
    stage('Build') {
      steps {
        echo 'New version build at ${new Date()}'
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

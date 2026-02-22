pipeline {
  agent any

  environment {
    APP_NAME = "MyApp"
    VERSION = "1.0.0"
  }
  
  stages {
    stage('Build') {
      steps {
        echo "Building ${APP_NAME} version ${VERSION}"
        echo "Build number: ${env.BUILD_NUMBER}"
        echo "Job name: ${env.JOB_NAME}"
      }
    }

    stage('Test') {
      steps {
        echo "Running tests for ${APP_NAME}"
      }
    }
  }

  post {
    always {
      echo 'Pipeline completed.'
    }
  }
}

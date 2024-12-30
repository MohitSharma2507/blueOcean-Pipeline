pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
date
'''
      }
    }

    stage('test') {
      steps {
        echo 'testingStage'
      }
    }

    stage('deploy') {
      steps {
        echo 'DeplyingStage'
      }
    }

  }
}
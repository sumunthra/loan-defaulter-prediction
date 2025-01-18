pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'pip install -r requirements.txt'
      }
    }

    stage('run python ') {
      steps {
        sh 'python app.py'
      }
    }

  }
}
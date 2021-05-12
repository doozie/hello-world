pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo '"Hello"'
      }
    }

    stage('Email') {
      steps {
        emailext(subject: 'Hi', body: 'me', to: 'martin@thedowies.com')
      }
    }

  }
}
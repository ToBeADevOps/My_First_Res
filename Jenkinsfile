pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        withMaven(jdk: 'C:\\Program Files\\Java\\jdk1.8.0_261', maven: 'C:\\Program Files\\apache-maven-3.6.3', publisherStrategy: 'IMPLICIT')
      }
    }

    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }

  }
}
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        withMaven(publisherStrategy: 'IMPLICIT', globalMavenSettingsConfig: 'C:\\Program Files\\apache-maven-3.6.3', globalMavenSettingsFilePath: 'C:\\Program Files\\apache-maven-3.6.3')
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
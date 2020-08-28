pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        withMaven(publisherStrategy: 'IMPLICIT', globalMavenSettingsFilePath: 'C:\\Program Files\\apache-maven-3.6.3', mavenSettingsFilePath: 'C:\\Program Files\\apache-maven-3.6.3\\conf\\settings.xml')
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
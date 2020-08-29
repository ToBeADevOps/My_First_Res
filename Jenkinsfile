pipeline {
  agent any
  stages {
    stage('SVN Checkout') {
      steps {
        bat 'C:\\Users\\hell\\Desktop\\Project\\BAT\\checkout.bat'
      }
    }

    stage('Build') {
      steps {
        echo 'Building..'
      }
    }

    stage('Test') {
      steps {
        echo 'Test....'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy start...'
      }
    }

  }
}
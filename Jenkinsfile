pipeline {
  agent any
  stages {
    stage('SVN Checkout') {
      steps {
        bat 'svn co "https://192.168.1.20/svn/haru/trunk/Doc/TranslateData" "C:/Users/hell/Desktop/trunk/Doc/TranslateData" --username "zhaohui" --password "Chengxu,Zh0.0"'
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
pipeline {
  agent any
  stages 
    {
    stage('Clean') {
      steps {
        echo 'Cleaning stage'
      }
    }
    stage('Install') {
      steps {
        bat 'mvn install'
      }
    }
    stage('Deploy') {
      steps {
        bat 'mvn deploy'
      }
    }
  }
}

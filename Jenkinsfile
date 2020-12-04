pipeline {
  agent any
  stages 
    {
    stage('Clean') {
      steps {
        echo 'Cleaning stage'
        bat 'mvn clean'
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

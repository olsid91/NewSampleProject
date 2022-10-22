pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
              git "https://github.com/olsid91/NewSampleProject.git"
    }
   }
        stage('compile') {
            steps {
                sh "mvn compile"
            }
        }
      stage('test') {
            steps {
               sh "mvn test"
    }
   }
  }
}

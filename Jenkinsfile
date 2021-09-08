pipeline {
    agent none
            stages {
                stage('Checkout') {
                        checkout scm
                      }
                stage('Run Tests') {
                                steps {
                                        sh 'mvn test'
                                 }
                      }
            }

  }
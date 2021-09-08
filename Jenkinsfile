pipeline {
    agent none
            stages {
                stage('Checkout') {
                         steps {
                                    checkout scm
                                }
                      }
                stage('Run Tests') {
                                steps {
                                        sh 'mvn test'
                                 }
                      }
            }

  }
pipeline {
    agent any
            stages {

                def mvnHome = tool 'MAVEN_HOME'
                stage('Run Tests') {
                                steps {
                                        echo "${mvnHome}"
                                        sh "${mvnHome}/bin/mvn test"
                                 }
                      }
            }

  }
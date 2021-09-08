pipeline {
    agent any
            def mvnHome = tool 'MAVEN_HOME'
            stages {
                stage('Run Tests') {
                                steps {
                                        echo "${mvnHome}"
                                        sh "${mvnHome}/bin/mvn test"
                                 }
                      }
            }

  }
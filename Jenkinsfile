pipeline {
    agent any
            stages {
                stage('Run Tests') {
                                steps {
                                        echo "${MAVEN_HOME}"
                                        sh "${MAVEN_HOME}/bin/mvn test"
                                 }
                      }
            }

  }
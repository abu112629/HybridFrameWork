pipeline {
    agent any{

        withEnv(["JAVA_HOME=${tool 'jdk8'}", "PATH+MAVEN=${tool 'maven'}/bin:${env.JAVA_HOME}/bin"])

         stages {

                        stage('Run Tests') {
                                        steps {

                                                sh 'mvn test'
                                         }
                              }
                    }
    }


  }
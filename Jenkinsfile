pipeline {

          agent any

          environment {

              //JAVA_HOME = '/usr/bin/java' //'C:\\Program Files\\Java\\jdk1.8.0_202'

              PYTHON_HOME = '/usr/bin/python3' //'C:\\Users\\rehou\\AppData\\Local\\Programs\\Python\\Python39'

              PATH = "${env.PATH}:${JAVA_HOME}/bin:/usr/bin" //'${env.PATH};${JAVA_HOME}\\bin;${PYTHON_HOME}'

          stages {

              stage('Build') {

                  steps {

                      script {

                          // Choisissez la commande en fonction de votre script

                          sh 'python hello.py' // Pour Python

                          // sh 'javac HelloWorld.java && java HelloWorld' // Pour Java

                      }

                  }

              }

          }

      }
 

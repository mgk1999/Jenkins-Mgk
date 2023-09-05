pipeline{
    agent any{
    stages{
        stage('built'){
        steps{
           echo "Compiling java source code!!"
           sh "java mgk.java"
            }
          }
          stage('run'){
            steps{
                echo "Running code"
                sh "java mgk"
            }
          }
        }
      }
    }
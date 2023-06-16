pipeline{
  agent any

  stages{
    stage('Hello'){
      steps{
        sh 'echo Hello'
        sh 'echo Bye'
        print 'hello'
        script{
          println "Hello World"
        }
       }
      }
    }
  post{
    always{
      println 'post step'
      }
    }
}
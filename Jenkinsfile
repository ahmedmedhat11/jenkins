pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        script{
          sh "mvn clean pasckage"
        }
      }
    }
    stage('test'){
      steps{
        script{
          sh "mvn test"
        }
      }
    }
  }
}

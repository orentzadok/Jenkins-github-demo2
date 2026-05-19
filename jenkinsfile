pipeline{
  agent any
  stages{
    stage('hello'){
      steps{
        sh 'echo hello'
      }
    }
    stage('files'){
      steps{
        sh 'ls -l'
      }
    }
    stage('memory'){
      steps{
        sh 'free -h'
      }
    }
  }
}

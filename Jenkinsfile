pipeline{
  agent any
  stages{
    stage('Clone repo'){
      steps{
        git url:'',branch:'main'
      }
    }
    stage('Install Python'){
      steps{
        sh 'python3 --version'
      }      
    }
    stage('Run'){
      steps{
        sh 'python3 app.py'
      }
    }
  }
}

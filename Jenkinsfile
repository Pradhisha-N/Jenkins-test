pipeline{
  agent any
  stages{
    stage('Clone repo'){
      steps{
        git url:'https://github.com/Pradhisha-N/Jenkins-test',branch:'main'
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

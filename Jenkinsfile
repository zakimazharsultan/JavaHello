pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh 'sudo docker build -t myjavaimg .'
      }
    }
    
    stage('Run'){
      steps{
        sh 'sudo docker run myjavaimg'
      }
    }
  }
}

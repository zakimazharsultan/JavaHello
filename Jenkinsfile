pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh 'docker build -t myjavaimg .'
      }
    }
    
    stage('Run'){
      steps{
        sh 'docker run myjavaimg'
      }
    }
  }
}

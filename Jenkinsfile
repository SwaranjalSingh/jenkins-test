  pipeline{
    agent{
      docker { image 'node:16-alpine' }
    }
    stages{
      stage('Test'){
        steps{
          sh 'node -v' 
        }
      }
      stage('deploy'){
        steps{
          sh 'node --version' 
        }
      }
    }
  }

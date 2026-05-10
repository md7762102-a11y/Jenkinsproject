pipeline{
  parameters{
    string(name: 'username', defaultValue: 'Mamta', description: 'enter your name')
  }
  stages{
    stage('build'){
      steps{
        sh 'echo "build step"'
      }
    }
    stage('test'){
      steps{
        sh 'echo "test steps"'
      }
    }
    stage('deploy'){
    steps{
      sh 'echo "deploy ${name}"'
    }
    }
  }
}  

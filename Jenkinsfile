pipeline {
  agent any
  stages {
    stage('Preparation') 
    {
      steps{
         echo "Successfully cloned repository..."
         echo "current branch BRANCH_NAME"
      }
    }
    stage('Build') {
      steps{
          echo "changing into directory src"
      }
    }
    stage('Results') {
      steps{
        echo "Ending job ..."
      }
    }
  }
}

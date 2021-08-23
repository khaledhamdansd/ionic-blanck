pipeline {
   agent any
      environment {
         Path='\\usr\\local\\bin:\\usr\\bin:\\bin'
      }

   stages {
      stage('NPM Setup') {
      steps {
      echo "Publish NPM Setup "
      sh 'npm install'
      }
   }


   stage('Android Build') {
   steps {
    echo "Publish Android API Action"
   }
  }

   stage('Publish Android') {
     steps {
    echo "Publish Android API Action"
   }
  }
 }
}


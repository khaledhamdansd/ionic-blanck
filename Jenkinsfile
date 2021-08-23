pipeline {
   agent any
      environment {
         Path='/usr/local/bin:/usr/bin:/bin'
      }

   stages {
      stage('NPM Setup') {
      steps {
         bat 'npm install'
      }
   }


   stage('Android Build') {
   steps {
      bat 'ionic cordova build android --release'
   }
  }

   stage('Publish Android') {
     steps {
    echo "Publish Android API Action"
   }
  }
 }
}


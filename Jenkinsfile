node {
   stage('Preparation') {
      git 'https://github.com/ak-hacks/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}
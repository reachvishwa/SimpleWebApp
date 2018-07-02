node {
   stage('Preparation') {
      git 'https://github.com/reachvishwa/SimpleWebApp'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}
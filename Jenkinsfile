pipeline {
  agent {label "agent1"}
  options {
    buildDiscarder logRator(artifactDaysToKeepStr: ", artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')
      disableConcurrentBuilds()
   }
   stages {
     stage('Hello') {
       steps {
         echo "hello"
       }
     }
   }
 }


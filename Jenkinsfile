pipeline {
  agent any
  
  stages {
    stage ('Build') {
      steps {
        echo 'Hi How are you doing? I am runnning build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}

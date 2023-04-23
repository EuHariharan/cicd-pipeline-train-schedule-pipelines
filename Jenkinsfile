pipeline {
  agent any
  stages {
    stage ('Build'){
      steps{
        echo 'Automation ran successfully'
        sh './gradlew build --no-daemon'
        archieveArtificats artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}

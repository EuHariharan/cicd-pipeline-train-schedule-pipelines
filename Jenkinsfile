pipeline {
  agent any
  stages {
    stage ('Build'){
      steps {
        echo 'Automation ran successfully'
        sh './gradlew build --no-daemon'
        archiveArtificats artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}

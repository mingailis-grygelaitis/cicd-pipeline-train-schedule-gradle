pipeline {
 agent any
  stages {
    stage ('Building') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifcats: 'dist/trainSchedule.zip'
      }
    }
  }
}

pipeline {
  agent any
  atages {
    stage ('build') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacs artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}

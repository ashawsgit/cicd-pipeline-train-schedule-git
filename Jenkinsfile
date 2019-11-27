pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation 51'
        sh 'gradle build --no-daemon'
        archiveArtifacts artifacts: 'routes/'
      }
    }
  }
}

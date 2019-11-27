pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation 1'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'routes/'
            }
        }
    }
}

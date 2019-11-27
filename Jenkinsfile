pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation 2'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'routes/'
            }
        }
    }
}

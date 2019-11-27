pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation 3'
                sh './gradlew build --stacktrace'
                archiveArtifacts artifacts: 'routes/'
            }
        }
    }
}

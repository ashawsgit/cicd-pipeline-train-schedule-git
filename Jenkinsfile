pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation 2'
                sh './gradlew build --stacktrace'
                archiveArtifacts artifacts: 'routes/'
            }
        }
    }
}

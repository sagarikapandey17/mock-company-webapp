pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh './gradlew assemble' // TODO: Add your build steps here
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh './gradlew test' // TODO: Add your test steps here
            }
        }
    }
}

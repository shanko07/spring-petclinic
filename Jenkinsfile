pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                ./mvnw clean compile -Dmaven.skip.test=true
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

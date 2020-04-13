pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'First time Build using jenkins file.'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing after building..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying after building and testing....'
            }
        }
    }
}

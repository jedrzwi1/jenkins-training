pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
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
        stage('Scripting') {
            steps {
                script {
                    if (2 + 2 != 4) {
                        println("Nigdy tu nie wejde")
                    }
                    else {
                        println("Brawo")
                    }
                }
            }
        }
    }
}

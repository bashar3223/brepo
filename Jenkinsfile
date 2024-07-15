pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    writeFile file: 'build.txt', text: 'Building..'
                    echo 'Building..'
                }
            }
        }
        stage('Test'){
            steps {
                script {
                    writeFile file: 'test.txt', text: 'Testing..'
                    echo 'Testing..'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    writeFile file: 'deploy.txt', text: 'Deploying....'
                    echo 'Deploying....'
                }
            }
        }
    }
}

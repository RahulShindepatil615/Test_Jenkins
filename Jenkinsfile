pipeline {
    agent {label 'linux'}

    stages {
        stage('Build') {
            steps {
                echo 'This is build stage Building..'
                mkdir /rahul/home/newfolder
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

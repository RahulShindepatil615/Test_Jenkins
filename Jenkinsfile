pipeline {
    agent {label 'linux'}

    stages {
        stage('Build') {
            steps {
                echo 'This is build stage Building..'
                //sh 'mkdir /home/rahul/new_folder1'
            }
        }
        stage('Test') {
            steps {
                echo 'This is Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

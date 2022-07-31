pipeline {
    agent any

    stages {
        stage('Checkout'){
            steps {
                checkout scm 
            }
         
        }
        stage('Static Code Analysis') {
            steps {
                echo 'Code Analysis calisti'
            }
        }
        stage('Test') {
            steps {
                echo 'testler calisti'
            }
        }
        stage('Build') {
            steps {
                echo 'build calisti'
            }
        }
    }
}

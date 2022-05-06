pipeline {
    agent any

    stages {
        stage('Hello') {
            
            steps {
                sh '''echo Hello World'''
                sh '''sleep 5'''
            }
            
        }
        stage('Bye') {
            
            steps {
                sh '''echo Bye World'''
                sh '''sleep 5'''
            }
        }
    }
}

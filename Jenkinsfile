pipeline {
    
    agent any
    
    stages {
        stage('SCM') {
            steps {
                echo 'i m SCM'
                sh  'date'
                git 'https://github.com/vimallinuxworld13/jenkins_training_2024_docker.git'
            }
        }
        
        stage('Build') {
            steps {
                echo 'i m BUILD'
                sh 'date'
            }
        }
        
        stage('Test') {
            steps {
                echo 'i m Test'
            }
        }
        stage('QA') {
            steps {
                echo 'i m QAT'
            }
        stage('Deploy') {
            steps {
                echo 'i m Deploy'
            }
        }
    }
    
    
}

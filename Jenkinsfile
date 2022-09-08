pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello'
            }
        }
        stage('Build buildjob') {
            steps {
                build 'buildjob'
            }
        }
        stage('Build devjob') {
            steps {
                build 'devjob'
            }
        }
        stage('Build testjob') {
            steps {
                build 'testjob'
            }
        }       
        stage('Bye') {
            steps {
                echo 'Bye'
            }
        }
    }
}

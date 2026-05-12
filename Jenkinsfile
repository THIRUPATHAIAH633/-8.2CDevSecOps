pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application using Maven build tool'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit and integration tests using JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Performing code analysis using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Performing security scan using OWASP Dependency Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying application to AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running Selenium tests on staging environment'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying application to AWS EC2 production server'
            }
        }
    }
}

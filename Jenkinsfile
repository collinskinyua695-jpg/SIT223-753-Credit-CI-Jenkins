pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build and package the application using Maven.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Run unit and integration tests using JUnit.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyse the code using SonarQube.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Perform a security scan using OWASP ZAP.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy the application to the staging server using AWS EC2.'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Run integration tests on the staging environment using JUnit.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy the application to the production server using AWS EC2.'
            }
        }

        // Updated for CI pipeline test
    }
}

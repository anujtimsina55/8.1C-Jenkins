pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Building code with Maven'
            }
        }
        stage('Unit & Integration Tests') {
            steps {
                echo 'Stage 2: Running unit & integration tests with JUnit'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Code analysis with SonarQube'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security scan with OWASP Dependency-Check'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploying to staging server'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Running integration tests on staging'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploying to production server'
            }
        }
    }
}

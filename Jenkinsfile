pipeline {
    agent any

    stages {
        stage('Stage 1: Build') {
            steps {
                echo 'Compile and package code'
                echo 'Tool used: Gradle'
            }
        }

        stage('Stage 2: Unit and Integration Tests') {
            steps {
                echo 'Validate functionality and component interaction'
                echo 'Tools used: Pytest and Spock'
            }
        }

        stage('Stage 3: Code Analysis') {
            steps {
                echo 'Static code analysis and quality checks'
                echo 'Tools used: ESLint and mypy'
            }
        }

        stage('Stage 4: Security Scan') {
            steps {
                echo 'Identify vulnerabilities and secrets'
                echo 'Tool Used: SpectralOps'
            }
        }

        stage('Stage 5: Deploy to Staging') {
            steps {
                echo 'Push to pre-production environment'
                echo 'Tools used: AWS CLI, Ansible'
            }
        }

        stage('Stage 6: Integration Tests on Staging') {
            steps {
                echo 'Validate production-like behavior'
                echo 'Tools used: Cypress, Robot Framework'
            }
        }

        stage('Stage 7: Deploy to Production') {
            steps {
                echo 'Final deployment to live environment'
                echo 'Tools used: Azure DevOps Pipelines'
            }
        }
    }
}

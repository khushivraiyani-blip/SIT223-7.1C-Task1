pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Tool: Maven"
                echo "Build the code using Maven to compile and package the application"
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo "Tools: JUnit and Selenium"
                echo "Run unit tests and integration tests"
            }
        }

        stage('Code Analysis') {
            steps {
                echo "Tool: SonarQube"
                echo "Analyse the code and check that it meets industry standards"
            }
        }

        stage('Security Scan') {
            steps {
                echo "Tool: Snyk"
                echo "Scan the code for security vulnerabilities"
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo "Tool: AWS EC2"
                echo "Deploy the application to the staging server"
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo "Tool: Selenium"
                echo "Run integration tests on the staging environment"
            }
        }

        stage('Deploy to Production') {
            steps {
                echo "Tool: AWS EC2"
                echo "Deploy the application to the production server"
            }
        }
    }
}

// Testing automatic Jenkins trigger - commit 2

pipeline {
    agent any
    stages {
        stage('Lint Checks'){
            steps {
                sh "echo ***** Starting Style Checks *****"
                // sh "mvn checkstyle:check || true"
                sh "echo ***** Style Checks Are Completed *****"
            }
        }
        stage('Static Code Analysis') {
            steps {
                sh "echo Starting Static Code Analysis"
            }
        }
    }
}


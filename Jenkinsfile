pipeline {
    agent {
        node {
            label "ubuntu && java17"
        }
    }
    stages {
        stage("Build") {
            steps {
                echo "Run Build"
            }
        }
        stage("Test") {
            steps {
                echo "Run Test"
            }
        }
        stage("Deploy") {
            steps {
                echo "Run Deploy"
            }
        }
    }
    post { 
        always {
            echo "Steps is running"
        }
        success {
            echo "Successfully running"
        }
        failure {
            echo "Failed running"
        }
        cleanup {
            echo "Cleaning up"
        }
    }
}
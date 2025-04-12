pipeline {
    agent {
        node {
            label "linux && java17"
        }
    }
    stages {
        stage("Build") {
            steps {
                echo("Run Build")
            }
        }
        stage("Test") {
            steps {
                echo("Run Test")
                sh("error")
            }
        }
        stage("Deploy") {
            steps {
                echo("Run Deploy")
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
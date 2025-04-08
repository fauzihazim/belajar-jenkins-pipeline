pipeline {
    agent {
        node {
            label "linux && java17"
        }
    }
    stages {
        stage("Hello") {
            steps {
                echo "run stages Hello"
                echo "Hello World"
                echo "Hello Pipeline"
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